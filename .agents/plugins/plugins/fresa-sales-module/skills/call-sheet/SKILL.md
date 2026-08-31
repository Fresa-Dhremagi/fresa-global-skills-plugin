
================================================================================
SKILL DOCUMENT: CALL SHEET
Module: Sales | Freight Forwarding Software
================================================================================

OVERVIEW
--------
The Call Sheet module is used by sales persons to record and manage customer
calls, follow-ups, and visit activities. It helps track interactions with
clients and plan future follow-up actions.

--------------------------------------------------------------------------------
NAVIGATION
--------------------------------------------------------------------------------
1. Click the Hamburger menu and select "Show All Menu" (first item in the list).
2. In the search bar, type "Call Sheet" and click the Search button.
3. Click on "Call Sheet" from the results to open the module.

--------------------------------------------------------------------------------
FILTER OPTIONS (For viewing existing Call Sheets)
--------------------------------------------------------------------------------
The following filters help narrow down and search existing call sheet records.
Users may provide one or more filter values — apply only what the user specifies.

  - Date Type     : LOV — Options: Call Date | Created Date | Followup Date
  - Date Range    : LOV — Options: Today, This Week, This Month, Yesterday,
                    Last Week, Last 7 Days, Last 14 Days, Last Month, etc.
  - From Date     : Date Picker — DO NOT type manually. Select Year → Month → Date.
  - To Date       : Date Picker — DO NOT type manually. Select Year → Month → Date.
  - Client        : Search LOV — Type client name in search box → Click Search →
                    Select from results.
                    ⚠️ If no results appear: notify user that this client is not
                    yet created in the Organization.
  - Status        : LOV — Options: Prospect | Call Planned | Booked | Active |
                    In Progress | Cancelled

After setting filters, click the Search button to load results.

--------------------------------------------------------------------------------
ACTION BUTTONS
--------------------------------------------------------------------------------

1. CALENDAR VIEW
   - Use when user wants to view call sheet follow-ups in a calendar format.
   - Click "Calendar View" button.
   - Select Date Type from LOV: Call Date or Followup Date.
   - Click Submit button.
   - Once calendar loads, select view mode: Month or List (based on user preference).

2. CLEAR
   - Use when user wants to reset/clear all entered filter values.
   - Click the "Clear" button.

3. STATUS FUNNEL
   - Use when user wants to view call sheets in chart/funnel format.
   - Click "Status Funnel" button.
   - The call sheet status chart will be displayed.

4. CREATE (New Call Sheet)
   - Use when user wants to create a new call sheet record.
   - Click the "Create" button.

--------------------------------------------------------------------------------
CREATING A NEW CALL SHEET
--------------------------------------------------------------------------------

⚠️ IMPORTANT — LOCATION PERMISSION:
When the Create page opens, a browser prompt will ask for location access
(to capture latitude and longitude). Click "Allow for this time" before
proceeding. This step is mandatory.

Fields marked with ** are MANDATORY and must not be left blank.

  No. | Field Name            | Type         | Instructions
  ----|------------------------|--------------|-----------------------------------
  1.  | **Branch              | LOV          | Select from dropdown
  2.  | Client Priority        | LOV          | Select from dropdown
  3.  | Current Forwarder      | Text         | Type value
  4.  | Grade                  | Text         | Type value
  5.  | **Sales Person        | LOV (Search) | Type name → Click Search → Select.
      |                        |              | Do NOT type name as plain text.
  6.  | **Call Date           | Date Picker  | Must pick from date picker.
      |                        |              | Do NOT type as plain text.
  7.  | Client Profile/Business| Text         | Type value
  8.  | Followup?              | Toggle       | Ask user — if follow-up needed,
      |                        |              | enable toggle; else leave as-is.
  9.  | Call Activity          | LOV (Search) | Type activity → Click Search →
      |                        |              | Select from results.
  10. | Client                 | LOV (Search) | Type client name → Click Search →
      |                        |              | Select from results.
      |                        |              | Note: Selecting client may auto-fill
      |                        |              | Contact Name, Dial Code, Contact Dial.
  11. | Client Name            | Text         | Type value (if not auto-filled)
  12. | Client Category        | LOV          | Select from dropdown
  13. | **Contact Name        | Auto-fill    | Auto-fills on client select.
      |                        |              | If blank, ask user for value.
  14. | Customer Type          | LOV          | Select from dropdown
  15. | **Followup Status     | LOV          | Select from dropdown
  16. | Dial Code              | LOV          | Auto-fills on client select.
      |                        |              | If blank, ask user for value.
  17. | Contact Dial           | Text         | Auto-fills on client select.
      |                        |              | If blank, ask user for value.
  18. | **Salesperson Remarks | Text         | Type remarks — mandatory
  19. | Territory Area         | Text         | Type value
  20. | Services               | Checkboxes   | Select one or more:
      |                        |              | ☐ Sea-FCL  ☐ AIR  ☐ LAND
      |                        |              | ☐ Sea-Groupage  ☐ RORO  ☐ Others
  21. | Address                | Text         | Type value
  22. | Email To               | Text         | Type email address
  23. | Commodity              | Text         | Type value
  24. | Email CC               | Text         | Type email address
  25. | Remarks                | Text         | Type value
  26. | Import From (POL)      | LOV          | Select from dropdown
  27. | POD                    | LOV          | Select from dropdown

After filling all required fields:
→ Click "Save and Close" button.
→ If any error occurs, display the error message to the user on the interface.

--------------------------------------------------------------------------------
NOTES FOR AI AGENT
--------------------------------------------------------------------------------
- Never type dates as plain text — always use the date picker.
- Never fill LOV (Search) fields by typing directly — always use search + select.
- Apply only the filters the user specifies; do not fill extra filter fields.
- When client is selected, check for auto-filled fields before asking the user.
- If a mandatory field (**) is missing from user input, ask the user before saving.

================================================================================
END OF SKILL DOCUMENT: CALL SHEET
================================================================================
