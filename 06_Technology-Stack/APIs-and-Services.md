# APIs and Services

## Current Prototype

The current prototype does not depend on live external APIs for its core workflow.

Property, verification and assistance information is represented using simulated application data.

## Proposed External Services

A production implementation may integrate external services for additional functionality.

### Location and Mapping Services

Location APIs can provide:

- Map visualization
- Geolocation
- Nearby amenities
- Distance calculations
- Locality information

Possible technologies include Google Maps Platform or OpenStreetMap-based services.

### Government / Registry Services

Where technically and legally available, appropriate government or registry services could be integrated to support property-related verification.

Such integrations would require suitable access, authorization and compliance requirements.

### Notification Services

Notification services could be used for:

- Verification-status updates
- Partner assignments
- Listing-status changes
- User notifications

## API Architecture

The proposed architecture follows:

**Frontend → Backend REST API → External Service**

The backend should act as the controlled integration layer rather than exposing sensitive service credentials directly to the frontend.

## Current Status

Live government-registry APIs, live mapping APIs and production notification services are not implemented in the current prototype.

They are proposed extensions of the production system.
