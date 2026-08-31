
---
name: call-sheet
description: Create and manage Call Sheet records in the Fresa Sales Module. Use this skill when the user wants to create a new call sheet, search existing call sheets, or view call sheet status.
---

================================================================================
SKILL DOCUMENT: CALL SHEET
Module: Sales | Freight Forwarding Software
================================================================================

OVERVIEW
--------
The Call Sheet module is used by sales persons to record and manage customer
calls, follow-ups, and visit activities.

NAVIGATION
----------
1. Click the Hamburger menu and select "Show All Menu".
2. Type "Call Sheet" in the search bar and click Search.
3. Click "Call Sheet" from the results.

FILTER OPTIONS
--------------
- Date Type     : LOV — Options: Call Date | Created Date | Followup Date
- Date Range    : LOV — Options: Today, This Week, This Month, Yesterday, Last Week, Last 7 Days, Last 14 Days, Last Month
- From Date     : Date Picker — DO NOT type manually.
- To Date       : Date Picker — DO NOT type manually.
- Client        : Search LOV — Type → Search → Select.
- Status        : LOV — Options: Prospect | Call Planned | Booked | Active | In Progress | Cancelled

CREATING A NEW CALL SHEET
--------------------------
Click "Create" button. Allow location permission when prompted.

Mandatory fields (**):
- ** Branch          : LOV
- ** Sales Person    : LOV Search
- ** Call Date       : Date Picker
- ** Contact Name    : Auto-fill or ask user
- ** Followup Status : LOV
- ** Salesperson Remarks : Text

Other fields:
- Client Priority, Current Forwarder, Grade, Client Profile
- Followup Toggle, Call Activity, Client, Client Name
- Client Category, Customer Type, Dial Code, Contact Dial
- Territory Area, Services (checkboxes: Sea-FCL, AIR, LAND, Sea-Groupage, RORO, Others)
- Address, Email To, Commodity, Email CC, Remarks
- Import From (POL), POD

After filling: Click "Save and Close".

RULES
-----
- Never type dates as plain text — always use date picker.
- Never fill LOV fields by typing — always search and select.
- If client not found: notify user "This client is not yet created in the Organization."
