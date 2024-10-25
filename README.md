# Jobee - Online Job Portal

## Overview
Jobee is a Laravel-based job portal connecting job seekers with employers. This platform offers secure user authentication, job listings, search functionalities, and application management.

## System Architecture
- **Client (Browser):** User access via web browser.
- **Web Server:** Apache handles HTTP requests.
- **Laravel Application:** Manages MVC components (models, controllers, Blade views, routes).
- **Database:** MySQL stores job listings, user profiles, and applications.

## Key Modules and Components

### 1. Authentication and User Management
   - **Registration and Login:** Laravel’s authentication for secure access.
   - **Role Management:** Access levels for job seekers and admins.
   - **Profile Management:** Manage profiles, upload resumes.
   - **Technologies:** Laravel Breeze, Policies, Gates.

### 2. Job Listings Module
   - **Search and Filtering:** Filter by keyword, category, location, job type.
   - **Database Interaction:** Uses Eloquent ORM for job postings.
   - **Technologies:** Blade templates, Eloquent ORM.

### 3. Job Application Management
   - **Application Submission:** Job seekers apply and attach resumes.
   - **File Uploads:** Secured uploads with validation.
   - **Technologies:** File handling, Eloquent ORM.

### 4. Dashboard
   - **Admin Dashboard:** Manage users, job listings, site content.
   - **Job Seeker Dashboard:** Manage profile, apply, and save jobs.
   - **Technologies:** Responsive layouts with Blade.

## Technology Stack
- **Backend:** Laravel (PHP), MySQL.
- **Frontend:** Blade, HTML5, CSS3, Bootstrap, JavaScript.
- **Web Server:** Apache.

## Security Measures
- **Authentication & Authorization:** Role-based control with CSRF protection.
- **SQL Injection Prevention:** Eloquent ORM and prepared statements.
- **File Upload Security:** File validation against malicious uploads.

## Testing
- **PHPUnit:** Ensures quality and reliability.

