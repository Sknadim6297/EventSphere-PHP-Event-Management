# EventSphere — Event & Booking Management System

EventSphere is a PHP-based event management web application designed to organize events, manage services, handle bookings, and support administrative operations.

The project includes modules for booking management, availability checking, invoice generation, reporting, user management, and access permissions.

## Key Modules

### Event & Service Management
- Event creation and management
- Service creation and updates
- Event-related reporting

### Booking Management
- New booking registration
- Booking approval and cancellation
- Booking details and availability checking
- Booking reports

### Invoice & Reporting
- Invoice generation
- Event reports
- Booking reports
- Date-based reporting

### User Management
- User registration and profile management
- User permissions
- Password management
- Deleted-user management

### Administration
- Administrative dashboard
- Company profile management
- Company logo and image updates
- Activity timeline

## Technology Stack

- **Backend:** Core PHP
- **Database:** MySQL
- **Frontend:** HTML, CSS, JavaScript
- **Architecture:** PHP-based server-rendered web application

## Project Structure

- `assets/` — Frontend assets
- `includes/` — Shared PHP files
- `dashboard.php` — Administrative dashboard
- `manage_event.php` — Event management
- `manage_service.php` — Service management
- `new_bookings.php` — New bookings
- `approved_bookings.php` — Approved bookings
- `cancelled_bookings.php` — Cancelled bookings
- `check_availability.php` — Availability checking
- `invoice_generating.php` — Invoice generation
- `booking_report.php` — Booking reporting
- `event_report.php` — Event reporting
- `user_permission.php` — User permissions
- `dbconnection.php` — Database connection

## Local Setup

1. Install XAMPP or another compatible PHP and MySQL environment.
2. Clone the repository into the web server's document directory.
3. Create and configure the required MySQL database.
4. Update the database connection settings in `dbconnection.php`.
5. Import the project's database schema, if available.
6. Open the application through the local web server.

## Project Status

A PHP event management portfolio project. The modules listed above are based on the repository's file structure; their behavior and production readiness require code-level verification.

## Security

Review authentication, authorization, SQL query parameterization, input validation, file uploads, and password handling before production deployment.

Never publish real login credentials, database passwords, or sensitive user information.

## License

All rights reserved unless a separate license is provided.
