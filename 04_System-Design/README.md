# 04 — System Design

This section documents the architecture, modules, data flow and verification workflow of the Rentify system.

## Contents

- `System-Architecture.md` — High-level architecture of the proposed system
- `Module-Design.md` — Major system modules and their responsibilities
- `Data-Flow.md` — Movement of information through the system
- `Verification-Workflow.md` — Property verification lifecycle and workflow

## Core Architecture

Rentify is organized around role-specific modules connected through the rental decision-support workflow.

The primary conceptual flow is:

**DISCOVER → VERIFY → UNDERSTAND → DECIDE**

## Major Modules

- Customer Module
- Vendor Module
- Admin Module
- Verification Partner Module
- Property Management
- Verification Management
- Rental Assistance
- Feedback and Credibility

## Verification Lifecycle

The proposed verification workflow is:

**Pending → In-Review → Verified / Flagged**

The primary interaction is:

**Vendor → Admin → Verification Partner → Verified / Flagged**

## Current vs Proposed Architecture

The current implementation is a frontend prototype using React, React Router, Tailwind CSS, React Context and browser local storage.

The proposed production architecture can introduce:

- Backend REST APIs
- Authentication and authorization
- Persistent database
- Secure document storage
- External location and notification services
- Appropriate verification or registry integrations

The production architecture is therefore an extension of the demonstrated prototype workflow.
