
---
name: sales-lead
description: Create and manage Sales Lead records in the Fresa Sales Module. Use this skill when the user wants to create a new sales lead, search existing leads, or filter leads by status or service.
---

================================================================================
SKILL DOCUMENT: SALES LEAD
Module: Sales | Freight Forwarding Software
================================================================================

OVERVIEW
--------
The Sales Lead module captures and manages potential new customers or business opportunities.

NAVIGATION
----------
1. Click the Hamburger menu and select "Show All Menu".
2. Type "Sales Lead" in the search bar and click Search.
3. Click "Sales Lead" from the results.

FILTER OPTIONS
--------------
- Date Type     : LOV — Options: Created Date | Followup Date
- Date Range    : LOV — Options: Today, This Week, This Month, Yesterday, Last Week, Last 7 Days, Last 14 Days, Last Month
- From Date     : Date Picker — DO NOT type manually.
- To Date       : Date Picker — DO NOT type manually.
- Client        : Search LOV — Type → Search → Select.
- Services      : LOV — Options: AIR IMPORT | FCL EXPORT | FCL IMPORT | LCL EXPORT | LCL IMPORT | SALES

CREATING A NEW SALES LEAD
--------------------------
Click "Create" button.

Mandatory fields (**):
- ** Client                  : Text
- ** Email To                : Text
- ** Assigned Sales Person   : LOV Search
- ** Status                  : LOV
- ** Followup Date           : Date Picker
- ** Services                : Dual Listbox — click service in LEFT box → click RIGHT ARROW → moves to RIGHT box

Other fields:
- Address, Dial Code, Contact No., Contact Person Name
- Email CC, Website, Country (LOV Search)
- Lead Source, Action, Remark

After filling: Click "Save".

RULES
-----
- Never type dates as plain text — always use date picker.
- Never fill LOV Search fields by typing — always search and select.
- Services uses dual listbox — use arrow button to move selections.
- If client not found: notify user "This client is not yet created in the Organization."
