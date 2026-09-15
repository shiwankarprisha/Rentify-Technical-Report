# Functional Requirements

The Rentify system shall provide the following functional capabilities.

## FR-01: Property Discovery

The system shall allow customers/renters to browse available rental properties.

## FR-02: Property Search and Filtering

The system shall allow renters to filter properties based on parameters such as:

- City
- Property type / BHK
- Maximum rent
- Verification status

## FR-03: Property Details

The system shall display relevant property information including:

- Rent
- Security deposit
- Property type
- Location/locality
- Carpet area
- Owner/lister information
- Amenities
- Safety information
- Verification status

## FR-04: Property Submission

The system shall allow vendors/property owners to submit new rental properties with relevant property and ownership information.

## FR-05: Ownership Information

The system shall capture ownership-document details such as document type and registration information.

## FR-06: Administrative Review

The system shall provide administrators with a review queue for submitted listings.

## FR-07: Verification Assignment

The system shall allow administrators to assign eligible listings to verification partners for physical verification.

## FR-08: Physical Verification

The system shall support a verification checklist covering location, ownership documentation, physical access/vacancy and available ownership confirmation.

## FR-09: Verification Status

The system shall maintain listing states such as:

**Pending → In-Review → Verified / Flagged**

## FR-10: Discrepancy Reporting

The system shall allow verification personnel or administrators to record discrepancies and flag listings.

## FR-11: Rental Assistance

The system shall provide structured information related to:

- Scam awareness
- Legal and tenancy rights
- Government housing schemes

## FR-12: Feedback

The system shall allow customers/tenants to submit ratings and feedback for properties.

## FR-13: Decision Support

The system shall present property information and verification/credibility indicators to support informed rental decisions.

## FR-14: Role-Based Workflows

The system shall provide separate workflows for:

- Customer / Renter
- Vendor / Property Owner
- Admin
- Verification Partner

## Current Prototype

The current prototype demonstrates property discovery, filtering, property details, vendor submission, administrative review, verification-partner workflow, verification states, assistance content and feedback using simulated data and browser local storage.

## Proposed Production Features

Authentication, persistent database storage, actual document uploads, external verification integrations and advanced recommendation capabilities are proposed for the production system.
