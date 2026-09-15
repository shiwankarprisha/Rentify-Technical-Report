# Testing Strategy

The Rentify prototype is validated primarily through functional and workflow-based testing.

## Testing Objectives

Testing aims to verify that:

- Major user workflows are accessible.
- Search and filtering behave as expected.
- Listing states transition correctly.
- Verification workflows operate correctly.
- Role-specific interfaces provide the intended actions.
- Rental assistance content is accessible.
- Feedback can be submitted.
- Prototype state persists during the demonstration.

## Testing Levels

### 1. Functional Testing

Individual features are checked against their expected behaviour.

Examples:

- Search listings
- Apply filters
- Submit a property
- Assign a verification partner
- Verify a property
- Flag a discrepancy
- Submit feedback

### 2. Workflow Testing

Complete user journeys are tested across multiple modules.

Example:

**Vendor → Admin → Verification Partner → Verified / Flagged → Customer**

### 3. UI Testing

The interface is checked for:

- Navigation
- Buttons
- Forms
- Status indicators
- Responsive layout
- Readability

### 4. State and Persistence Testing

Prototype state changes are checked using the application's shared state and browser local storage.

## Testing Approach

Testing is primarily scenario-based because the current implementation is an interactive prototype rather than a production system.

The test cases focus on validating the intended user workflows and system responses.

## Future Testing

A production implementation should additionally include:

- Unit testing
- API testing
- Integration testing
- Database testing
- Authentication testing
- Security testing
- Performance testing
- Accessibility testing
- Automated regression testing
