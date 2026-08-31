
================================================================================
SKILL DOCUMENT: SALES MODULE — OVERVIEW & INDEX
Module: Sales | Freight Forwarding Software
================================================================================

OVERVIEW
--------
The Sales Module is designed for sales persons in freight forwarding companies.
Sales persons play a vital role in quotation providing/gathering, enquiry
providing/gathering, and getting leads for new customers. This module offers
dedicated menus to support these sales activities.

--------------------------------------------------------------------------------
HOW TO NAVIGATE TO ANY MENU
--------------------------------------------------------------------------------
All menus in this system are accessed the same way:

  1. Click the Hamburger (☰) menu icon.
  2. Select "Show All Menu" — this is the FIRST item in the hamburger menu.
  3. In the search bar on the "Show All Menu" page, type the name of the menu.
  4. Click the Search button.
  5. Click on the menu name from the search results to open it.

This navigation method applies to ALL menus listed below.

--------------------------------------------------------------------------------
SALES MODULE MENUS
--------------------------------------------------------------------------------

The Sales module contains the following 10 menus:

  1.  Call Sheet
  2.  Sales Lead
  3.  All Quotations
  4.  All Enquiries
  5.  Sales Report
  6.  Shipment Restricted
  7.  Personal Followup Calendar
  8.  Follow Up List
  9.  Quotation Approval List
  10. Visiting Card List

Skill documents (with full workflows and field details) are currently available
for the following menus only:

  File No. | Menu Name       | Skill File
  ---------|-----------------|-----------------------------
  01       | Call Sheet      | 01_Call_Sheet.txt
  02       | Sales Lead      | 02_Sales_Lead.txt
  03       | All Quotations  | 03_All_Quotations.txt

Skill documents for the remaining 7 menus will be created once their
workflows and field details are provided.

--------------------------------------------------------------------------------
COMMON RULES FOR AI AGENT (Apply across all Sales Menus)
--------------------------------------------------------------------------------

  1. NAVIGATION       : Always use "Show All Menu" → Search → Click to open.

  2. DATE FIELDS      : NEVER type dates as plain text.
                        Always use the date picker: Select Year → Month → Date.

  3. LOV FIELDS       : NEVER type values directly into LOV (List of Values) fields.
                        Always: type in search box → Click Search → Select from results.

  4. FILTERS          : Apply ONLY the filters the user specifies.
                        Do not fill extra fields the user did not mention.

  5. MANDATORY FIELDS : Fields marked ** must not be left blank.
                        If user has not provided a mandatory field value, ASK before saving.

  6. CLIENT NOT FOUND : If a client search returns no results, notify the user:
                        "This client is not yet created in the Organization."

  7. SAVE ERRORS      : If an error occurs after saving, display the error message
                        clearly to the user.

  8. SEARCH BUTTON    : Always click Search after setting filters.
                        Lists do not auto-refresh without clicking Search.

  9. CLEAR BUTTON     : Use when user asks to reset/clear all filter fields.

================================================================================
END OF SKILL DOCUMENT: SALES MODULE OVERVIEW & INDEX
================================================================================
