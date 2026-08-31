

================================================================================
SKILL DOCUMENT: ALL QUOTATIONS
Module: Sales | Freight Forwarding Software
================================================================================

OVERVIEW
--------
The All Quotations module allows users to view and search quotations created
within the system. Sales persons use this to track and review quotations sent
to clients for freight forwarding services.

--------------------------------------------------------------------------------
NAVIGATION
--------------------------------------------------------------------------------
1. Click the Hamburger menu and select "Show All Menu" (first item in the list).
2. In the search bar, type "All Quotations" and click the Search button.
3. Click on "All Quotations" from the results to open the module.

--------------------------------------------------------------------------------
FILTER OPTIONS (For viewing existing Quotations)
--------------------------------------------------------------------------------
The following filters help search and narrow down quotation records.
Fields marked with ** are required before clicking Search.

  No. | Field Name   | Type         | Instructions
  ----|---------------|--------------|--------------------------------------------
  1.  | **Date Type  | LOV          | Select the date type from dropdown
      |               |              | (mandatory before searching)
  2.  | **Date Range | LOV          | Select the range from dropdown
      |               |              | Options: Today, This Week, This Month,
      |               |              | Yesterday, Last Week, Last 7 Days,
      |               |              | Last 14 Days, Last Month, etc.
      |               |              | (mandatory before searching)
  3.  | From Date     | Date Picker  | DO NOT type manually.
      |               |              | Select Year → Month → Date from picker.
  4.  | To Date       | Date Picker  | DO NOT type manually.
      |               |              | Select Year → Month → Date from picker.
  5.  | Quote No.     | Text         | Type the quotation number if user provides
  6.  | Client        | LOV (Search) | Type client name → Click Search →
      |               |              | Select from results.

⚠️ The page will NOT refresh/load results until you click the Search button.
   Always click Search after setting the filter values.

--------------------------------------------------------------------------------
ACTION BUTTONS
--------------------------------------------------------------------------------

1. SEARCH
   - After entering filter values, click the "Search" button to load results.
   - The page refreshes and displays matching quotations.

2. CLEAR
   - Use when user wants to reset/clear all entered filter values.
   - Click the "Clear" button to reset the form.

--------------------------------------------------------------------------------
NOTES FOR AI AGENT
--------------------------------------------------------------------------------
- Date Type and Date Range are required — always select these before searching.
- Never type dates as plain text — always use the date picker.
- Never fill the Client field by typing directly — always use search + select.
- Apply only the filters the user specifies; do not fill extra filter fields.
- This module is for VIEWING quotations only — quotation creation may be
  handled from a different module or workflow.
- Always click Search after setting filters — the list does not auto-refresh.

================================================================================
END OF SKILL DOCUMENT: ALL QUOTATIONS
================================================================================
