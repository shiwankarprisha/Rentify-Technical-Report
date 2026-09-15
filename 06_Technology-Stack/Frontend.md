# Frontend

The current Rentify prototype is implemented as a frontend-focused React application.

## Technologies Used

### React 19

React is used to build the component-based user interface.

The application contains separate views for:

- Customer / Renter
- Vendor / Property Owner
- Admin
- Verification Partner
- Rental Assistance
- Property Details

### React Router 7

React Router is used for client-side navigation between different Rentify workflows.

Main routes include:

- `/` — Landing Page
- `/customer` — Customer Home
- `/property/:id` — Property Details
- `/vendor` — Vendor Dashboard
- `/admin` — Admin Dashboard
- `/partner` — Verification Partner Portal
- `/assistance` — Rental Assistance

### Tailwind CSS

Tailwind CSS is used for responsive styling, layouts and reusable interface styling.

### Lucide React

Lucide React is used for interface icons throughout the application.

### Vite

Vite is used as the frontend development and build tool.

## State Management

The prototype uses a shared React context for application state.

The context manages:

- Listings
- Current user role
- Audit logs
- Feedback
- Listing submission
- Verification workflow actions
- Demo reset

## Browser Storage

Browser local storage is used to persist prototype state during the demonstration.

## Prototype Limitation

The current frontend does not connect to a production backend or persistent database.
