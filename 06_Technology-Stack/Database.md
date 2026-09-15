# Database

## Current Prototype

The current Rentify prototype does not use MongoDB or PostgreSQL.

Instead, demonstration data is maintained in the browser using local storage.

The prototype stores information related to:

- Property listings
- Current role
- Audit logs
- Feedback
- Listing status changes

This approach allows the complete workflow to be demonstrated without a server-side database.

## Proposed Production Database

A production implementation can use either:

- MongoDB
- PostgreSQL

### MongoDB

MongoDB can be used for flexible document-oriented storage of property, user and verification-related information.

### PostgreSQL

PostgreSQL can be used when strongly structured relational data and transactional consistency are preferred.

## Proposed Data Entities

The production database may contain entities such as:

- Users
- Properties
- Ownership Documents
- Verification Records
- Field Audit Records
- Feedback
- Assistance Content
- Audit Logs

## Data Relationships

A simplified relationship is:

**User → Property → Verification Record → Field Audit**

and:

**Customer → Feedback → Property**

## Security

Sensitive ownership and identity information should be protected using appropriate:

- Access controls
- Encryption
- Data-retention policies
- Audit mechanisms

## Implementation Status

A persistent database is proposed for the production system and is not part of the current prototype.
