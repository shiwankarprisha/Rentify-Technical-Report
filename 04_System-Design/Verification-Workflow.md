# Verification Workflow

Property verification is a central component of Rentify's trust-oriented workflow.

## Step 1 — Property Submission

The Vendor submits:

- Property details
- Ownership-proof information
- Document type
- Deed registration information
- Government ID information

The listing initially enters the **Pending** state.

## Step 2 — Administrative Review

The Admin reviews the submitted information.

The administrator can:

- Continue the verification process
- Assign a Verification Partner
- Flag the listing when a discrepancy is identified

## Step 3 — Field Verification

An assigned Verification Partner performs an on-site inspection.

The prototype checklist includes:

- GPS/location confirmation
- Original ownership document inspection
- Physical keys testing
- Vacancy confirmation
- Available ownership confirmation through local/society verification

The listing enters the **In-Review** state during this stage.

## Step 4 — Verification Decision

### Successful Verification

If the required checks are satisfactory:

**Verification Partner → Confirm → Verified Listing**

The listing receives verification information/seal data in the prototype.

### Discrepancy

If a significant discrepancy is identified:

**Verification Partner → Flag Discrepancy → Flagged Listing**

A reason/note is recorded.

## Listing Lifecycle

```text
PENDING
   ↓
IN-REVIEW
   ↓
 ┌─────────────┐
 ↓             ↓
VERIFIED     FLAGGED
