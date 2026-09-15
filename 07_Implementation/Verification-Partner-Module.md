# Verification Partner Module

The Verification Partner Module supports field-level verification of rental properties.

## Assigned Visits

The verification partner can view properties assigned for physical verification.

The interface displays relevant property information before the inspection.

## On-Site Protocol Checklist

The prototype provides a checklist covering:

- GPS geotag confirmed matching locality
- Original Index II paper deed inspected face-to-face
- Physical keys tested and vacant unit confirmed
- Society secretary / guard confirmation of ownership

## Verification Actions

After completing the inspection, the verification partner can choose:

**Confirm (Issue Official Stamp)**

or

**Flag Discrepancy**

## Successful Verification

When the required checks are confirmed, the property status changes to:

**Verified**

The prototype generates verification seal information and a field report.

## Discrepancy

If an issue is identified, the verification partner records a note and flags the property.

The property status becomes:

**Flagged**

## Field Audit Information

The prototype records field-verification information such as:

- Verification officer
- GPS information
- Key/access confirmation
- Vacancy status
- Field observations

## Implementation Boundary

The prototype simulates the field-verification process.

It does not independently authenticate government records or guarantee the legal ownership of a property.

Production implementation would require authenticated verification personnel, secure records and appropriate verification mechanisms.
