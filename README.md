# Meeting Room Booking System (MRBS) - Mockup

A high-fidelity static mockup of a comprehensive Meeting Room Booking System, built with HTML, CSS, and JavaScript.

## 🎯 Project Overview

This mockup demonstrates the complete user interface and user experience for a Meeting Room Booking System designed for organizational use. It includes authentication, room management, booking workflows, reporting, and administrative features.

## ✨ Features

### 🔐 Authentication & User Management
- **Login/Register/Password Reset** - Complete authentication flow
- **User Profiles** - View and edit user information
- **Role-Based Access** - Admin, Director, and User roles
- **User Management** - Admin interface for managing users

### 🏢 Meeting Room Management
- **Room Inventory** - Browse all available meeting rooms
- **Room Details** - Detailed view with images, capacity, amenities
- **Room Administration** - Add, edit, and manage room status
- **Search & Filter** - Find rooms by capacity, location, equipment

### 📅 Booking Management
- **Calendar View** - Day/Week/Month views of all bookings
- **Create Bookings** - Interactive booking form with validation
- **My Bookings** - Personal booking history and management
- **Approval Queue** - Admin workflow for pending bookings
- **Booking Actions** - Edit, cancel, approve, reject bookings

### 📊 Reports & Analytics
- **Reports Hub** - Central dashboard for all reports
- **Visual Charts** - Bar charts, donut charts for data visualization
- **Multiple Report Types**:
  - Daily Bookings Report
  - Monthly Analysis
  - User Activity Report
  - Room Utilization Report
- **Export Options** - PDF, Excel, CSV export buttons
- **Date Range Filters** - Customizable reporting periods

### ⚙️ System Administration
- **System Settings** - Configure booking rules and operating hours
- **Audit Logs** - Complete activity tracking and audit trail
- **Notification Settings** - Email and reminder configurations
- **Maintenance Mode** - System-wide maintenance toggle

### 🎨 Interactive Features (Phase 5)
- **Hover Effects** - Cards and tables respond to user interaction
- **Toast Notifications** - Success, error, info, and warning messages
- **Active Menu Highlighting** - Always know your current location
- **Confirmation Dialogs** - Prevent accidental destructive actions
- **Smooth Animations** - Polished, modern user experience

## 📁 Project Structure

```
mrbs-mock-up/
├── assets/
│   ├── css/              # Core theme styles
│   ├── js/               # JavaScript files
│   │   ├── main.js       # Theme initialization
│   │   ├── interactions.js  # Custom interactions & toasts
│   │   └── dashboards-analytics.js
│   ├── vendor/           # Third-party libraries
│   └── img/              # Images and icons
├── pages/
│   ├── auth-login.html
│   ├── auth-register.html
│   ├── auth-forgot-password.html
│   ├── dashboard-admin.html
│   ├── dashboard-user.html
│   ├── rooms-list.html
│   ├── rooms-detail.html
│   ├── rooms-add.html
│   ├── rooms-edit.html
│   ├── bookings-calendar.html
│   ├── bookings-my.html
│   ├── bookings-all.html
│   ├── bookings-approval.html
│   ├── users-list.html
│   ├── users-edit.html
│   ├── reports-hub.html
│   ├── reports-view.html
│   ├── settings-system.html
│   └── system-audit-logs.html
├── styles/
│   └── index.css         # Custom styles & interactions
├── docs/
│   ├── features.md       # Feature specifications
│   ├── feature-dev-v2.md # Development roadmap
│   ├── navigation-verification.md
│   └── phase5-summary.md
└── theme/                # Original theme files
```

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- No server required - all files are static HTML

### Installation

1. **Clone or download** this repository
2. **Navigate** to the `pages/` directory
3. **Open** any HTML file in your browser

### Recommended Starting Points

- **Admin View**: `pages/dashboard-admin.html`
- **User View**: `pages/dashboard-user.html`
- **Login Page**: `pages/auth-login.html`

## 🎨 Design System

### Theme
Built on **Sneat Bootstrap Admin Template** (Free version)

### Color Palette
- **Primary**: `#696cff` (Purple)
- **Success**: `#71dd37` (Green)
- **Warning**: `#ffab00` (Orange)
- **Danger**: `#ff3e1d` (Red)
- **Info**: `#03c3ec` (Cyan)

### Typography
- **Font Family**: Public Sans
- **Weights**: 300, 400, 500, 600, 700

### Components
- Cards with hover effects
- Responsive tables
- Form controls with validation states
- Badges and status indicators
- Charts (ApexCharts)
- Modals and dropdowns
- Toast notifications

## 📱 Responsive Design

The mockup is fully responsive and works on:
- Desktop (1920px+)
- Laptop (1366px - 1920px)
- Tablet (768px - 1366px)
- Mobile (320px - 768px)

## 🧪 Interactive Features

### Toast Notifications
Click any Save, Create, or Delete button to see toast notifications in action:
- **Success**: Green toast with checkmark icon
- **Error**: Red toast with X icon
- **Info**: Blue toast with info icon
- **Warning**: Orange toast with warning icon

### Hover Effects
- Hover over cards to see lift animation
- Hover over table rows to see highlight
- Hover over buttons for state changes

### Active Navigation
The sidebar automatically highlights the current page and opens parent menus.

## 📋 Page Navigation Map

### Authentication Flow
```
auth-login.html → dashboard-admin.html (or dashboard-user.html)
auth-login.html ↔ auth-register.html
auth-login.html → auth-forgot-password.html
```

### Admin Workflow
```
dashboard-admin.html
├── rooms-list.html → rooms-detail.html → rooms-edit.html
├── rooms-add.html
├── bookings-all.html
├── bookings-approval.html
├── users-list.html → users-edit.html
├── reports-hub.html → reports-view.html
├── settings-system.html
└── system-audit-logs.html
```

### User Workflow
```
dashboard-user.html
├── rooms-list.html → rooms-detail.html
├── bookings-calendar.html
└── bookings-my.html
```

## 🔧 Customization

### Modifying Styles
Edit `styles/index.css` to customize:
- Hover effects
- Toast notification styles
- Custom scrollbar
- Additional animations

### Modifying Interactions
Edit `assets/js/interactions.js` to customize:
- Toast notification behavior
- Button click handlers
- Active menu logic
- Confirmation dialogs

### Adding New Pages
1. Copy `pages/layout.html` as a template
2. Update the `<title>` tag
3. Add your content in the `.content-wrapper` section
4. Update sidebar active states
5. Include `interactions.js` before closing `</body>`

## 📊 Development Phases

- ✅ **Phase 1**: Foundation & Core Layout
- ✅ **Phase 2**: Meeting Rooms Management
- ✅ **Phase 3**: Booking Management
- ✅ **Phase 4**: Administrative Management
- ✅ **Phase 5**: Polish & Interaction

See `docs/feature-dev-v2.md` for detailed roadmap.

## 📖 Documentation

- **`docs/features.md`** - Complete feature specifications
- **`docs/feature-dev-v2.md`** - Development roadmap and checklist
- **`docs/navigation-verification.md`** - Navigation flow verification
- **`docs/phase5-summary.md`** - Phase 5 implementation details

## 🎯 Use Cases

This mockup is ideal for:
- **Client Presentations** - Demonstrate the proposed system
- **User Testing** - Gather feedback on UI/UX
- **Development Handoff** - Provide visual reference for developers
- **Stakeholder Reviews** - Align on requirements and design
- **Design Iteration** - Quickly test different approaches

## 🛠️ Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with animations
- **JavaScript (ES6+)** - Interactive features
- **Bootstrap 5** - Responsive framework
- **ApexCharts** - Data visualization
- **Boxicons** - Icon library
- **Perfect Scrollbar** - Custom scrollbars

## 📝 Notes

### Static Mockup Limitations
This is a **static mockup** - no backend functionality:
- Forms don't submit data
- Login doesn't authenticate
- Data is hardcoded/placeholder
- No database connections
- No API calls

### Purpose
The mockup demonstrates:
- Visual design and layout
- User interface components
- User experience flow
- Interactive elements
- Navigation structure

## 🤝 Contributing

This is a mockup project. For the actual implementation:
1. Use this as a visual reference
2. Implement backend API
3. Connect to database
4. Add real authentication
5. Implement business logic

## 📄 License

Based on Sneat Bootstrap Admin Template (Free version)
- Template: [ThemeSelection](https://themeselection.com)
- License: Free for personal and commercial use

## 👥 Credits

- **Theme**: Sneat Bootstrap Admin Template by ThemeSelection
- **Icons**: Boxicons
- **Charts**: ApexCharts
- **Framework**: Bootstrap 5

## 📞 Support

For questions about this mockup:
1. Review the documentation in `docs/`
2. Check the navigation map above
3. Examine the source code for implementation details

---

**Version**: 1.0.0  
**Last Updated**: November 2025  
**Status**: Phase 5 Complete ✅
