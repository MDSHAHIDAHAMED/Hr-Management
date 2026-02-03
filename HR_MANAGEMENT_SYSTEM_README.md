# HR Management System - Documentation

## Overview
This is a comprehensive HR Management System built as part of an ERP software. It includes all the features required for both Admin (HR/Management) and Employee users.

## System Structure

### Admin/HR Pages

#### 1. HR Dashboard (`hr-dashboard.html`)
- Key metrics: Total Employees, Present Today, Pending Leave Requests, Active Job Postings
- Attendance overview chart
- Department distribution chart
- Recent leave requests table
- Upcoming events
- Recent activities log

#### 2. Employee Management
- **Employee List** (`hr-employees-list.html`): View all employees with search and filter
- **Add Employee** (`hr-employee-add.html`): Form to add new employees
- **Departments** (`hr-departments.html`): Manage departments
- **Designations** (`hr-designations.html`): Manage job designations

#### 3. Attendance Management
- **Attendance List** (`hr-attendance-list.html`): View daily attendance records
- **Attendance Requests** (`hr-attendance-requests.html`): Approve/reject attendance correction requests
- **Settings** (`hr-attendance-settings.html`): Configure office hours, shifts, breaks

#### 4. Leave Management
- **Leave Requests** (`hr-leave-requests.html`): Approve/reject leave requests
- **Leave Types** (`hr-leave-types.html`): Manage leave types (casual, sick, annual, etc.)
- **Leave Calendar** (`hr-leave-calendar.html`): Visual calendar view of all leaves
- **Leave Balance** (`hr-leave-balance.html`): View leave balances for all employees

#### 5. Payroll Management
- **Payroll List** (`hr-payroll-list.html`): View all salary records
- **Generate Payroll** (`hr-payroll-generate.html`): Generate monthly payroll
- **Salary Structure** (`hr-salary-structure.html`): Configure salary components
- **Payslips** (`hr-payslips.html`): View and download payslips

#### 6. Recruitment & Onboarding
- **Job Postings** (`hr-job-postings.html`): Manage job openings
- **Applicants** (`hr-applicants.html`): Track applicants (ATS)
- **Interviews** (`hr-interviews.html`): Schedule and manage interviews
- **Onboarding** (`hr-onboarding.html`): Onboard new hires

#### 7. Performance Management
- **Performance Reviews** (`hr-performance-reviews.html`): Manage performance reviews
- **KPIs & Goals** (`hr-kpis.html`): Set and track KPIs
- **Performance Cycles** (`hr-performance-cycles.html`): Manage review cycles

#### 8. ../assets & Documents
- **Company ../assets** (`hr-../assets.html`): Assign and track company ../assets
- **Documents** (`hr-documents.html`): Manage employee documents with expiry reminders

#### 9. Reports & Analytics
- **Attendance Reports** (`hr-reports-attendance.html`)
- **Payroll Reports** (`hr-reports-payroll.html`)
- **Leave Reports** (`hr-reports-leave.html`)
- **Performance Reports** (`hr-reports-performance.html`)

#### 10. Settings
- **Roles & Permissions** (`hr-settings-roles.html`): Configure access control
- **Holidays** (`hr-settings-holidays.html`): Set company holidays
- **Shifts** (`hr-settings-shifts.html`): Configure work shifts
- **Policies** (`hr-settings-policies.html`): Manage HR policies

### Employee/User Pages

#### 1. Employee Dashboard (`hr-employee-dashboard.html`)
- Personal metrics: Attendance, Leave Balance, Pending Requests, Salary
- Attendance history
- Quick actions
- Recent leave requests
- Leave balance overview
- Upcoming events & notifications

#### 2. Employee Features
- **My Profile** (`hr-employee-profile.html`): View and update personal information
- **Attendance** (`hr-employee-attendance.html`): View attendance history, mark check-in/out
- **Leave** (`hr-employee-leave.html`): Apply for leave, view leave balance
- **Payslips** (`hr-employee-payslip.html`): View and download payslips
- **Performance** (`hr-employee-performance.html`): View goals, KPIs, and feedback
- **Documents** (`hr-employee-documents.html`): Upload and download documents
- **My Requests** (`hr-employee-requests.html`): Track all requests

## Menu Structure

The HR Management module is accessible from the main sidebar menu with the following structure:

```
HR Management
├── HR Dashboard
├── Employee Management
│   ├── All Employees
│   ├── Add Employee
│   ├── Departments
│   └── Designations
├── Attendance
│   ├── Attendance List
│   ├── Attendance Requests
│   └── Settings
├── Leave Management
│   ├── Leave Requests
│   ├── Leave Types
│   ├── Leave Calendar
│   └── Leave Balance
├── Payroll
│   ├── Salary List
│   ├── Generate Payroll
│   ├── Salary Structure
│   └── Payslips
├── Recruitment
│   ├── Job Postings
│   ├── Applicants
│   ├── Interviews
│   └── Onboarding
├── Performance
│   ├── Performance Reviews
│   ├── KPIs & Goals
│   └── Performance Cycles
├── ../assets & Documents
│   ├── Company ../assets
│   └── Documents
├── Reports & Analytics
│   ├── Attendance Reports
│   ├── Payroll Reports
│   ├── Leave Reports
│   └── Performance Reports
└── Settings
    ├── Roles & Permissions
    ├── Holidays
    ├── Shifts
    └── Policies
```

## Features Implemented

### Admin Features
✅ Employee data management (add, edit, deactivate)
✅ Attendance tracking and manual adjustment
✅ Leave management with approval workflow
✅ Payroll generation and management
✅ Recruitment and applicant tracking
✅ Performance management
✅ Asset and document management
✅ Role-based access control
✅ Comprehensive reporting and analytics

### Employee Features
✅ Personal dashboard with key metrics
✅ Attendance viewing and check-in/out
✅ Leave application and balance tracking
✅ Payslip viewing and download
✅ Performance goals and reviews
✅ Document management
✅ Request tracking

## Technology Stack
- Bootstrap 5
- jQuery
- DataTables for data management
- ApexCharts for analytics
- Font Awesome / Bootstrap Icons

## File Naming Convention
- Admin pages: `hr-{feature}-{action}.html` (e.g., `hr-employees-list.html`)
- Employee pages: `hr-employee-{feature}.html` (e.g., `hr-employee-dashboard.html`)

## Next Steps
1. Connect to backend API for data persistence
2. Implement authentication and authorization
3. Add real-time notifications
4. Integrate with biometric devices (optional)
5. Add email/SMS integration for notifications
6. Implement document expiry reminders
7. Add advanced reporting features

## Notes
- All pages follow the same design pattern as the main ERP template
- Responsive design for mobile and desktop
- Consistent navigation and user experience
- Ready for backend integration

