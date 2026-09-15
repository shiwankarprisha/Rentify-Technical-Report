# Customer Module

The Customer Module provides the primary renter-facing experience.

## Property Discovery

Customers can browse available rental properties from the main discovery interface.

Each listing provides information such as:

- Property title
- City
- Locality
- Property type
- Rent
- Deposit
- Carpet area
- Lister
- Transit information
- Safety score
- Trust score
- Verification status

## Search and Filtering

Customers can filter listings using:

- Locality / title / owner search
- City
- Property type / BHK
- Maximum rent
- Verified Only

A reset option is also available to clear the applied filters.

## Listing Ranking

The current prototype uses deterministic ranking.

The ranking prioritizes:

1. Verified listings
2. Higher credibility score
3. Lower rent

This is a rule-based ranking mechanism and is not a machine-learning recommendation model.

## Property Details

Customers can open a listing using:

**View Full Details**

The property details page displays:

- Monthly rent
- Security deposit
- Brokerage
- Carpet area
- Floor
- Owner/lister
- Contact information
- Amenities
- Safety information
- Verification status
- Ownership and field-audit information
- Tenant feedback

## Verification Information

Verified properties display verification-related information.

Flagged properties display warnings and advise customers not to proceed with risky upfront transactions.

## Decision Guidance Hub

The property details interface provides access to:

- Scam Awareness
- Legal & Tenancy Rights
- Government Housing Schemes

## Feedback

Customers can submit:

- Star rating
- Written feedback

The feedback contributes to the property's displayed credibility information.

## Implementation Status

The Customer Module is implemented in the current prototype using simulated data and browser local storage.
