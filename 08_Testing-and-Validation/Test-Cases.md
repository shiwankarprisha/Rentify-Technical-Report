# Test Cases

The following test cases cover the major workflows implemented in the Rentify prototype.

| ID | Test Scenario | Expected Result |
|---|---|---|
| TC-01 | Open Rentify landing page | Landing page loads with role options |
| TC-02 | Select Customer role | Customer interface opens |
| TC-03 | Search using locality/title/owner | Matching listings are displayed |
| TC-04 | Apply city filter | Listings are filtered by selected city |
| TC-05 | Apply BHK/property-type filter | Matching property types are displayed |
| TC-06 | Apply maximum-rent filter | Listings above the selected rent are excluded |
| TC-07 | Enable Verified Only | Only verified listings are displayed |
| TC-08 | Open property details | Complete property information is displayed |
| TC-09 | Open verified property | Verification information/seal is displayed |
| TC-10 | Open flagged property | Warning and discrepancy information are displayed |
| TC-11 | Open rental assistance | Assistance portal is displayed |
| TC-12 | Submit a new property as Vendor | Listing enters the verification workflow |
| TC-13 | View vendor listing status | Current listing state is displayed |
| TC-14 | Review pending listing as Admin | Listing information and review actions are available |
| TC-15 | Assign Verification Partner | Listing moves to In-Review |
| TC-16 | Flag listing as Admin | Listing becomes Flagged with a recorded reason |
| TC-17 | View assigned visit as Verification Partner | Assigned property and checklist are displayed |
| TC-18 | Complete verification checklist | Verification action becomes available |
| TC-19 | Confirm successful field verification | Listing becomes Verified |
| TC-20 | Report field discrepancy | Listing becomes Flagged with a note |
| TC-21 | Submit tenant feedback | Feedback is added to the property information |
| TC-22 | Reset Demo | Prototype returns to its initial demonstration state |
| TC-23 | Refresh after state change | Relevant prototype state remains available through local storage |
| TC-24 | Navigate between major modules | Correct module/page opens |

## Test Data

The prototype contains seeded demonstration listings representing:

- Verified properties
- Properties under review
- Pending properties
- Flagged properties

These states allow the major workflows to be demonstrated without requiring a production backend.

## Test Result Recording

Actual pass/fail results should be recorded after executing each test case during the final prototype testing cycle.
