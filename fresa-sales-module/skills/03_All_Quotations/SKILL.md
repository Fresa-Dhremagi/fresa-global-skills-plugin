
---
name: all-quotations
description: Search and view quotations in the Fresa Sales Module. Use this skill when the user wants to find, filter, or view existing quotations.
---

================================================================================
SKILL DOCUMENT: ALL QUOTATIONS
Module: Sales | Freight Forwarding Software
================================================================================

OVERVIEW
--------
The All Quotations module allows users to view and search quotations created within the system.

NAVIGATION
----------
1. Click the Hamburger menu and select "Show All Menu".
2. Type "All Quotations" in the search bar and click Search.
3. Click "All Quotations" from the results.

FILTER OPTIONS
--------------
Mandatory before searching (**):
- ** Date Type   : LOV — select date type from dropdown
- ** Date Range  : LOV — Options: Today, This Week, This Month, Yesterday, Last Week, Last 7 Days, Last 14 Days, Last Month

Optional filters:
- From Date  : Date Picker — DO NOT type manually.
- To Date    : Date Picker — DO NOT type manually.
- Quote No.  : Text — type quotation number if provided
- Client     : Search LOV — Type → Search → Select.

ACTION BUTTONS
--------------
- SEARCH : Click after setting filters to load results.
- CLEAR  : Resets all filter values.

RULES
-----
- Date Type and Date Range are mandatory before searching.
- Never type dates as plain text — always use date picker.
- Never fill Client field by typing — always search and select.
- Always click Search after setting filters — list does not auto-refresh.
- This module is for VIEWING only — not for creating quotations.
