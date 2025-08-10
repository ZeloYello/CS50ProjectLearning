# ReportFix

![ReportFix Logo](path/to/logo.png)  <!-- Optional: Add your logo here -->

---

## Overview

**ReportFix** is a community-driven web application designed to empower citizens to report infrastructure issues quickly and easily. Users can submit reports with descriptions, categories, photos, and map locations. Admin users have tools to review, manage, and resolve reported issues.

---

## Features

- **User Authentication:** Secure registration, login, and logout with password hashing.
- **Issue Reporting:** Submit reports with text descriptions, categories, geolocation (via map), and image uploads.
- **Interactive Map:** Visualize all open reports on a dynamic map interface.
- **Admin Dashboard:** Admins can view all reports and mark issues as resolved.
- **Photo Uploads:** Support for multiple image formats to accompany reports.
- **Flash Messaging:** Feedback notifications for user actions.
- **Security:** Session management and role-based access control.

---

## Technology Stack

- **Backend:** Python, Flask, SQLite
- **Frontend:** HTML, CSS, JavaScript, Bootstrap, Leaflet.js (for map visualization)
- **Authentication:** Werkzeug security (password hashing), Flask-Session
- **Image Handling:** Werkzeug file uploads with secure filename handling
- **Database:** SQLite with SQL queries to store users, reports, and sessions

---

## Installation & Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/reportfix.git
   cd reportfix

