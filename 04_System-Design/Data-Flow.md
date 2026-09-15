# Data Flow

The Rentify data flow describes how information moves between users, system processes and data stores.

## Property Submission Flow

Vendor
→ Property Details
→ Ownership Information
→ Listing Management
→ Verification Queue

## Verification Flow

Admin
→ Listing Review
→ Verification Partner Assignment
→ Field Verification
→ Verification Result
→ Listing Status

Possible statuses:

**Pending → In-Review → Verified / Flagged**

## Customer Discovery Flow

Customer
→ Search / Filter Criteria
→ Property Discovery
→ Property Listing Data
→ Property Details
→ Verification & Context Information
→ Rental Decision

## Assistance Flow

Customer
→ Assistance Portal
→ Scam Awareness / Legal Guidance / Government Schemes
→ Guidance Information

## Feedback Flow

Customer
→ Property Feedback
→ Feedback & Credibility Data
→ Property Information

## Main Data Entities

The proposed system maintains:

- User Data
- Property Listings
- Ownership / Verification Records
- Field Audit Records
- Feedback and Reviews
- Rental Assistance Content

## Current Prototype

The current prototype uses simulated data and browser local storage to maintain listing state, user role state, audit information and feedback during demonstration.

## Proposed Production System

A production implementation would use a persistent database and backend APIs to manage these data flows securely and consistently.
