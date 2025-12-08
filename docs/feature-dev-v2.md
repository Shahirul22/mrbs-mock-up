# Mockup Development Roadmap

This document outlines the step-by-step plan to build the static mockup for the Meeting Room Booking System (MRBS). The goal is to create high-fidelity HTML/CSS/JS static pages that demonstrate the visual design and user flow without backend logic.

## Phase 1: Foundation & Core Layout
**Goal:** Establish the visual identity and basic navigation structure.

1.  **Project Setup & Design System**
    *   [x] Create `index.css` with CSS variables for colors, typography, spacing, and shadows (based on modern, premium aesthetics).
    *   [x] Define utility classes for common layouts (flex, grid) and components (buttons, cards, inputs).
    *   [x] Set up directory structure for `pages/`, `assets/`, `styles/`, and `scripts/`.

2.  **Global Layout Components**
    *   [x] **Navigation Bar:** Logo, user profile dropdown, notifications bell.
    *   [x] **Sidebar Navigation:** Links to Dashboard, Rooms, Bookings, Reports, Users, Settings (collapsible).
    *   [x] **Footer:** Copyright and links.
    *   [x] Create a `layout.html` template (or base structure) to be reused.

3.  **Authentication Pages**
    *   [x] **Login Page:** Email/Password form, "Remember Me", "Forgot Password" link. (Feature 3.3)
    *   [x] **Registration Page:** Registration form with validation visual cues. (Feature 3.1)
    *   [x] **Forgot Password Page:** Email input for reset link.

4.  **Dashboards**
    *   [x] **Admin Dashboard:** Overview stats (bookings today, room utilization), charts (utilization), recent activity feed. (Feature 3.6)
    *   [x] **User Dashboard:** Upcoming personal bookings, quick book action, recent notifications.

## Phase 2: Meeting Rooms Management (Subsystem 1)
**Goal:** Visualize how users find and view meeting rooms.

1.  **Room Inventory**
    *   [ ] **Room List Page:** Grid/List view of rooms with thumbnails, capacity, location, and status badges. (Feature 1.1)
    *   [ ] **Search & Filter Sidebar:** Filters for capacity, location, availability, equipment. (Feature 1.4)

2.  **Room Details**
    *   [ ] **Room Detail Page:** Large image gallery, full specifications, amenities list, location map/description. (Feature 1.2, 1.3)
    *   [ ] **Availability Calendar (Read-only):** Visual display of free/busy slots for the room. (Feature 1.5)

3.  **Room Administration (Admin Only)**
    *   [ ] **Add/Edit Room Form:** Form to input room details, upload images, set capacity and location.
    *   [ ] **Room Status Management:** Toggle for Active/Inactive/Maintenance with date pickers for maintenance periods. (Feature 1.6)

## Phase 3: Booking Management (Subsystem 2)
**Goal:** Demonstrate the booking workflow and schedule management.

1.  **Booking Calendar**
    *   [ ] **Global Calendar View:** Day/Week/Month views showing bookings across all rooms. (Feature 2.7)
    *   [ ] **Interactive Slots:** Clickable time slots to trigger booking modal/page.

2.  **Booking Process**
    *   [ ] **Create Booking Page/Modal:** Form for date, time, room selection, purpose, attendees. (Feature 2.1)
    *   [ ] **Recurring Booking Options:** UI for selecting repetition patterns (daily, weekly). (Feature 2.2)
    *   [ ] **Booking Confirmation:** Summary screen before final submission.

3.  **My Bookings**
    *   [ ] **Personal Booking History:** List of user's past and upcoming bookings with status indicators. (Feature 2.3)
    *   [ ] **Booking Management Actions:** Edit and Cancel buttons with confirmation modals. (Feature 2.5, 2.6)

4.  **Booking Administration**
    *   [ ] **All Bookings List:** Admin view of all system bookings with advanced filters. (Feature 2.4)
    *   *Note: Approval Queue removed - system uses auto-approval on first-come-first-served basis*

## Phase 4: Administrative Management (Subsystem 3)
**Goal:** Build the backend management and reporting interfaces.

1.  **User Management**
    *   [x] **User List:** Table of users with role badges, status, and actions. (Feature 3.16)
    *   [x] **User Profile/Edit:** Form to edit user details and assign roles. (Feature 3.2)

2.  **Reports & Analytics**
    *   [x] **Reports Hub:** Landing page to select report type (Daily, Monthly, Utilization).
    *   [x] **Report View:** Template showing charts (bar/line/pie) and data tables for the selected report. (Feature 3.9 - 3.12)
    *   [x] **Export Options:** Visual buttons for PDF/Excel/CSV export. (Feature 3.13)

3.  **System Control**
    *   [x] **Audit Log:** Table showing system events with timestamps and user details. (Feature 3.4)
    *   [x] **System Configuration:** Form to set booking limits, operating hours, and notification toggles. (Feature 3.17)

## Phase 5: Polish & Interaction
**Goal:** Enhance the "feel" of the mockup.

1.  **Interactive Elements**
    *   [x] Add hover effects to cards and buttons.
    *   [x] Implement simple JS for dropdowns, modal toggles, and tab switching.
    *   [x] Add "Toast" notifications to simulate success/error messages (e.g., "Booking Created", "Room Saved").

2.  **Navigation Linking**
    *   [x] Ensure all links work to navigate between the static pages.
    *   [x] Verify "Admin" vs "User" flows (even if simulated via separate links).

3.  **Final Review**
    *   [x] Cross-check against `features.md` to ensure all key visual elements are represented.

