================================================================================
SKILL DOCUMENT: SALES LEAD
Module: Sales | Freight Forwarding Software
================================================================================

OVERVIEW
--------
The Sales Lead module is used by sales persons to capture, manage, and follow up
on potential new customers or business opportunities. It tracks lead source,
assigned sales person, services of interest, and follow-up status.

--------------------------------------------------------------------------------
NAVIGATION
--------------------------------------------------------------------------------
1. Click the Hamburger menu and select "Show All Menu" (first item in the list).
2. In the search bar, type "Sales Lead" and click the Search button.
3. Click on "Sales Lead" from the results to open the module.

--------------------------------------------------------------------------------
FILTER OPTIONS (For viewing existing Sales Leads)
--------------------------------------------------------------------------------
The following filters help narrow down and search existing sales lead records.
Users may provide one or more filter values — apply only what the user specifies.

  - Date Type     : LOV — Options: Created Date | Followup Date
  - Date Range    : LOV — Options: Today, This Week, This Month, Yesterday,
                    Last Week, Last 7 Days, Last 14 Days, Last Month, etc.
  - From Date     : Date Picker — DO NOT type manually. Select Year → Month → Date.
  - To Date       : Date Picker — DO NOT type manually. Select Year → Month → Date.
  - Client        : Search LOV — Type client name in search box → Click Search →
                    Select from results.
                    ⚠️ If no results appear: notify user that this client is not
                    yet created in the Organization.
  - Services      : LOV — Options: AIR IMPORT | FCL EXPORT | FCL IMPORT |
                    LCL EXPORT | LCL IMPORT | SALES

After setting filters, click the Search button to load results.

--------------------------------------------------------------------------------
ACTION BUTTONS
--------------------------------------------------------------------------------

1. CLEAR
   - Use when user wants to reset/clear all entered filter values.
   - Click the "Clear" button.

2. CREATE (New Sales Lead)
   - Use when user wants to create a new sales lead record.
   - Click the "Create" button.

--------------------------------------------------------------------------------
CREATING A NEW SALES LEAD
--------------------------------------------------------------------------------

Fields marked with ** are MANDATORY and must not be left blank.

  No. | Field Name              | Type         | Instructions
  ----|--------------------------|--------------|----------------------------------
  1.  | **Client                | Text         | Type client name — mandatory
  2.  | Address                  | Text         | Type value
  3.  | Dial Code                | LOV          | Select from dropdown
  4.  | Contact No.              | Text         | Type contact number
  5.  | Contact Person Name      | Text         | Type contact person name
  6.  | **Email To              | Text         | Type email address — mandatory
  7.  | Email CC                 | Text         | Type email address
  8.  | **Assigned Sales Person | LOV (Search) | Type name → Click Search →
      |                          |              | Select from results.
      |                          |              | Do NOT type name as plain text.
  9.  | **Status                | LOV          | Select from dropdown — mandatory
  10. | Website                  | Text         | Type website URL
  11. | **Followup Date         | Date Picker  | Must pick from date picker.
      |                          |              | Do NOT type as plain text.
  12. | Country                  | LOV (Search) | Type country name in search bar →
      |                          |              | Select from results.
  13. | Lead Source              | LOV          | Select from dropdown
  14. | **Services              | Dual Listbox | ⚠️ Special Selection Method:
      |                          |              | - From LEFT box, click desired service
      |                          |              | - Click the RIGHT ARROW button (→)
      |                          |              | - Selected service moves to RIGHT box
      |                          |              | - Repeat for each additional service
      |                          |              | This is mandatory — at least one
      |                          |              | service must be selected.
  15. | Action                   | Text         | Type action description
  16. | Remark                   | Text         | Type remarks

After filling all required fields:
→ Click "Save" button.
→ If any error occurs, display the error message to the user on the interface.

--------------------------------------------------------------------------------
NOTES FOR AI AGENT
--------------------------------------------------------------------------------
- Never type dates as plain text — always use the date picker.
- Never fill LOV (Search) fields by typing directly — always use search + select.
- Services field uses a dual listbox — use the arrow button to move selections,
  do not try to type or drag items.
- Apply only the filters the user specifies; do not fill extra filter fields.
- If a mandatory field (**) is missing from user input, ask the user before saving.

================================================================================
END OF SKILL DOCUMENT: SALES LEAD
================================================================================
