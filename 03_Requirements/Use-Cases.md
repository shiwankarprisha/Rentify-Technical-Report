# Use Cases

## UC-01: Search Rental Property

**Actor:** Customer

**Description:**  
The customer searches for rental properties using location, property type, rent and verification filters.

**Outcome:**  
Relevant listings are displayed for evaluation.

---

## UC-02: View Property Details

**Actor:** Customer

**Description:**  
The customer opens a listing to examine property specifications, rent, deposit, amenities, safety information and verification status.

**Outcome:**  
The customer obtains contextual information required for evaluation.

---

## UC-03: Access Rental Assistance

**Actor:** Customer

**Description:**  
The customer accesses scam awareness, legal/tenancy guidance and government housing-scheme information.

**Outcome:**  
The customer receives structured rental guidance.

---

## UC-04: Submit Property

**Actor:** Vendor

**Description:**  
The vendor enters property details and ownership-document information and submits the property for review.

**Outcome:**  
The listing enters the verification workflow.

---

## UC-05: Review Listing

**Actor:** Admin

**Description:**  
The administrator reviews a submitted property and its provided information.

**Outcome:**  
The administrator can proceed with verification, assign a verification partner, or flag the listing.

---

## UC-06: Assign Verification Partner

**Actor:** Admin

**Description:**  
The administrator assigns an available verification partner to an eligible listing.

**Outcome:**  
The property enters the field-verification stage.

---

## UC-07: Perform Physical Verification

**Actor:** Verification Partner

**Description:**  
The verification partner performs the defined on-site checklist.

**Outcome:**  
The verification partner confirms the property or reports a discrepancy.

---

## UC-08: Verify or Flag Listing

**Actor:** Admin / Verification Partner

**Description:**  
Based on the verification process, a listing is assigned an appropriate status.

**Possible Outcomes:**

- Verified
- Flagged

---

## UC-09: Submit Feedback

**Actor:** Customer

**Description:**  
The customer provides a rating and written feedback for a property.

**Outcome:**  
Feedback becomes part of the property's credibility information.

---

## Overall Use-Case Flow

**Customer:**  
Discover → Filter → View Details → Verify Information → Understand Context → Decide

**Vendor:**  
Submit Property → Review → Verification → Status

**Admin:**  
Review → Assign → Monitor → Verify/Flag

**Verification Partner:**  
Assigned Visit → Physical Inspection → Confirm / Report Discrepancy
