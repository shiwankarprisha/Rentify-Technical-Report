# Recommendation Methodology

Rentify aims to support renters in identifying properties that are relevant to their requirements while also making verification and credibility information visible.

## Current Prototype Approach

The current prototype uses deterministic filtering and ranking rather than machine-learning recommendation.

Listings are ranked using the following order:

1. Verified listings are prioritized.
2. Credibility score is considered.
3. Lower rent is preferred when other factors are comparable.

Customers can also explicitly filter listings using:

- City
- Property type / BHK
- Maximum rent
- Verification status

## Decision-Support Perspective

The recommendation approach is intended to support decision-making rather than automatically make a rental decision for the customer.

The customer can inspect the complete property details and verification information before deciding.

## Proposed Future Recommendation

A production version can introduce an explainable recommendation model using factors such as:

- Budget compatibility
- Location preference
- Property type
- Amenities
- User preferences
- Verification status
- Credibility information

A possible weighted model can be developed after sufficient user and listing data becomes available.

## Advanced Future Approaches

Future work may explore:

- Content-based recommendation
- Collaborative filtering
- Hybrid recommendation
- Context-aware recommendation
- Explainable ranking

These approaches are not implemented in the current prototype.
