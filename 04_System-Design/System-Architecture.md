# System Architecture

## Overview

Rentify follows a modular architecture designed around four primary user roles:

- Customer / Renter
- Vendor / Property Owner
- Admin
- Verification Partner

The architecture connects rental discovery, property verification, contextual information and rental assistance within a unified workflow.

## High-Level Architecture

The proposed production architecture consists of:

1. **Presentation Layer**
   - React-based web interface
   - Role-specific dashboards and workflows

2. **Application Layer**
   - Authentication and role management
   - Property listing management
   - Verification management
   - Recommendation / decision support
   - Rental assistance
   - Feedback and credibility

3. **Data Layer**
   - User records
   - Property listings
   - Verification records
   - Feedback
   - Assistance content

4. **External Services**
   - Location and mapping services
   - Notification services
   - Potential government/registry integrations

## Core Workflow

Vendor submits property  
→ Admin reviews listing  
→ Verification Partner performs field verification  
→ Listing becomes Verified or Flagged  
→ Customer discovers and evaluates the listing  
→ Customer accesses contextual assistance  
→ Customer makes an informed decision

## Current Prototype Architecture

The current prototype is a frontend-based implementation using React and browser local storage.

It demonstrates the role-based workflows and verification lifecycle using simulated data.

## Proposed Production Architecture

The production version can extend the prototype with:

- Backend REST APIs
- Persistent database
- Authentication and authorization
- Secure document storage
- External location services
- Advanced recommendation
- External verification/registry services

These components are proposed and are not part of the current prototype.
