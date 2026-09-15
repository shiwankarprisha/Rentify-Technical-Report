# Module Design

Rentify is divided into functional modules corresponding to the major stages of the rental decision process.

## 1. Customer Module

Provides the renter-facing discovery and decision-support experience.

### Functions

- Property search
- Property filtering
- Property details
- Verification status
- Safety information
- Credibility information
- Rental assistance
- Tenant feedback

---

## 2. Vendor Module

Allows property owners to submit and manage rental listings.

### Functions

- Property submission
- Property information entry
- Ownership-document information
- Identity information
- Listing status tracking

---

## 3. Admin Module

Acts as the central verification-management interface.

### Functions

- Review queue
- Listing review
- Verification partner assignment
- Active visit monitoring
- Verification outcome management
- Listing flagging

---

## 4. Verification Partner Module

Supports field-level property verification.

### Functions

- Assigned visit management
- GPS/location confirmation
- Original document inspection
- Physical property inspection
- Vacancy/key verification
- Field observations
- Verification confirmation
- Discrepancy reporting

---

## 5. Rental Assistance Module

Provides structured guidance to renters.

### Functions

- Scam awareness
- Legal and tenancy rights
- Government housing schemes

---

## 6. Property & Verification Module

Maintains the property lifecycle and verification information.

### Listing Lifecycle

**Pending → In-Review → Verified / Flagged**

---

## 7. Feedback & Credibility Module

Collects tenant feedback and presents credibility-related information associated with properties.

## Prototype Implementation

The current prototype implements these modules as React pages/components with shared state managed through the application context and browser local storage.

## Future Extension

The modules can be separated into backend services and persistent database models in the production version.
