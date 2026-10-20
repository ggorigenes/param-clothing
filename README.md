# Param Clothing Line

Param is a custom, framework-free PHP and MySQL e-commerce platform featuring a buyer storefront and role-based dashboards for administrators, Customer Service, and Delivery staff.

## My Role: Lead Front-End Developer
I designed and developed the front-end interfaces for this project using HTML, CSS, and Bootstrap. My work focused on creating responsive, mobile-first layouts, user-friendly product displays, and the UI for the role-based dashboards.

## Current Areas

- **Buyer Storefront:** Responsive product catalog and user interface.
- **Administrator Dashboard:** UI for managing users, products, inventory, reports, staff applications, and audit logs.
- **Customer Service Dashboard:** Interface for managing concerns, replies, and refund escalation.
- **Delivery Dashboard:** Mobile-friendly layouts for assigned deliveries, status updates, and proof paths.

## Local Setup

1. Start Apache and MySQL in XAMPP.
2. Import `my-php-app/db/database_schema.sql` into MySQL.
3. Configure database access in `my-php-app/src/config/database.php`.
4. Copy the mail settings from `.env.example` into local environment variables or a gitignored `src/config/mail.local.php`.
5. Open `/Param/my-php-app/public/index.php` through Apache to view the storefront.

**Development administrator:** `admin@param.test` / `Admin@12345`

## Security

Protected pages and APIs enforce active sessions, CSRF checks, and database-backed RBAC permissions. SMTP credentials and production database passwords are strictly excluded from version control.
