# Admin Module

The Admin Module provides the verification-management interface for Rentify.

## Admin Dashboard

The dashboard provides operational metrics including:

- Review Queue
- Active Visits
- Certified

## Review Queue

The administrator can review submitted properties that are awaiting verification.

The review interface provides access to listing information and verification actions.

## Verification Partner Assignment

The administrator can select an available verification partner and use:

**Assign Partner**

The listing then moves into the field-verification stage.

## Listing Flagging

The administrator can flag a listing when a discrepancy is identified.

A reason is required when recording a flag.

## Active Field Visits

The administrator can monitor listings currently assigned for field verification.

## Verification Records

The Admin interface also provides an audit-oriented view of listing statuses and verification information.

## Listing States

The system tracks:

- Pending
- In-Review
- Verified
- Flagged

## Implementation Note

The prototype includes an administrative approval option for demonstration purposes.

The primary intended verification workflow is:

**Vendor → Admin → Verification Partner → Verified / Flagged**

## Prototype Boundary

The current Admin Module operates on simulated application data.

Production implementation would require authenticated administrative access, persistent records and secure verification infrastructure.
