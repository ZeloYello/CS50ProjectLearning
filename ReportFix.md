# ReportFix

![ReportFix Logo](img/download.png) 

---

## Overview

**ReportFix** is a community driven web application designed for citizens to report infrastructure issues quickly and easily. Users can submit reports with descriptions, categories, photos, and map locations. Admin users have tools to review, manage, and resolve reported issues.

---


- ## Features
+ User Authentication: Registration, login, and logout with password hashing for security

+ Issue Reporting: Submit reports including a title, description, image upload, and automatic geolocation via Leaflet.js

+ Image Handling: Supports uploading photos as proof of reported issues

+ Admin Dashboard: An admin panel that displays all reports, allows marking issues as resolved

+ SQLite Database: Stores user accounts, report data, and status updates reliably.

+ Error Handling: Provides user-friendly messages when input validation fails or errors occur.

---

## templates/

+ admin.html: displays a dashboard for admins 

+ apology.html: error handling template that provides error messages

+ index.html: homepage with an overview and tutorial

+ layout.html: base template for all the other templates 

+ login.html: provides a login form for the users 

+ map.html: shows a map with all the currently active problems

+ register.html: provides a register form for the users

+ report.html: displays a form where the users can report the issue

---

## Technology Stack

- **Backend:** Python, Flask, SQLite
- **Frontend:** HTML, CSS, JavaScript, Bootstrap, Leaflet.js (for map visualization)
- **Authentication:** Werkzeug security (password hashing), Flask-Session
- **Image Handling:** Werkzeug file uploads with secure filename handling
- **Database:** SQLite with SQL queries to store users, reports, and sessions

---

## Video Demo

[![Watch the demo](https://img.youtube.com/vi/A6LCdftIs40/0.jpg)](https://www.youtube.com/watch?v=A6LCdftIs40)


