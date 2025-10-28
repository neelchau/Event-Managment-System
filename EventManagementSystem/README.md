# Event Management System

## Overview
The **Event Management System** is a web application designed to streamline the process of organizing and managing events such as weddings, corporate events, and birthday parties. It provides users with an intuitive interface to create events, manage profiles, and view event details. The system also includes an admin panel for managing users and monitoring event-related data.

## Features
### User Features
- **Event Creation**: Users can create events by providing details such as event type, date, time, location, and preferences.
- **Profile Management**: Users can update their profile information.
- **Event Details**: Users can view and download event details in PDF format.
- **Contact Form**: Users can send messages or inquiries to the event organizers.

### Admin Features
- **User Management**: Admins can view and delete user accounts.
- **Dashboard**: Admins can view statistics such as the total number of users and events.
- **Event Monitoring**: Admins can track and manage event details.


## Technologies Used
- **Frontend**: HTML, CSS, JavaScript
- **Backend**: PHP
- **Database**: MySQL
- **PDF Generation**: TCPDF Library

## Installation
1. Clone the repository:
   ```bash
   git clone hhttps://github.com/neelchau/Event-Managment-System
2. Set up the database:    Import the event_planning database schema into MySQL.
3. Configure the database connection: Update the credentials in authentication/dbconnection.php.
4. Start a local server (e.g., XAMPP or WAMP) and place the project in the htdocs directory.
5. Access the application in your browser: http://localhost/EventManagementSystem/

Usage
User:
Register or log in to create and manage events.
View event details and download PDFs.
Admin:
Log in to the admin panel to manage users and monitor events.
