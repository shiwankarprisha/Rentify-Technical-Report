# Advanced Recommendation

The current prototype uses deterministic filtering and ranking.

A future version of Rentify can introduce more advanced and personalized recommendation techniques.

## Possible Recommendation Factors

The recommendation system could consider:

- Budget
- Preferred locality
- Property type
- BHK
- Amenities
- Distance from important locations
- Verification status
- Credibility information
- Previous user preferences

## Possible Approaches

### Content-Based Recommendation

Properties can be recommended based on similarity between property characteristics and user preferences.

### Collaborative Filtering

Recommendations can use patterns from interactions and preferences of multiple users when sufficient data is available.

### Hybrid Recommendation

Content-based and collaborative approaches can be combined to improve recommendation quality.

### Context-Aware Recommendation

Context such as location, time, user requirements and rental purpose could be incorporated into ranking.

## Explainability

Recommendations should provide understandable reasons for ranking properties.

For example:

- Matches preferred locality
- Within stated budget
- Preferred property type
- Verified listing

## Current Status

The current prototype does **not** implement machine-learning recommendation.

Its ranking is deterministic and prioritizes verification status, credibility score and rent.
