# SlipHub - Permission Slip Management System

![SlipHub Banner](https://via.placeholder.com/800x200/4A90E2/FFFFFF?text=SlipHub+-+Permission+Slip+Management+System)

SlipHub is a web application that streamlines the permission slip management process between students and teachers. It provides a digital solution for submitting, reviewing, and approving permission slips with PDF generation capabilities.

## ✨ Features

- **🔐 User Authentication**: Separate login systems for students and teachers
- **📝 Permission Slip Management**: Create, submit, and track permission slips
- **👥 Role-based Access**:
  - Students can submit and view their permission slips
  - Teachers can review, approve, or reject permission slips
- **📄 PDF Generation**: Download approved permission slips as PDF documents
- **📱 Responsive Design**: Works on desktop and mobile devices

## 🚀 Quick Start

### Prerequisites

Before running the SlipHub application, ensure you have the following components properly set up:

#### Must Have Software
- [Node.js](https://nodejs.org/) (version 14 or higher)
- [XAMPP](https://www.apachefriends.org/) (for MySQL database)
- Web Browser (Chrome, Firefox, or Edge recommended)

#### Optional Development Tools
- Visual Studio Code or any code editor
- Postman for API testing

### Installation & Setup

#### Step 1: Install and Configure XAMPP
1. Download and install [XAMPP](https://www.apachefriends.org/)
2. Launch XAMPP Control Panel
3. Start Apache and MySQL services
4. Open phpMyAdmin by visiting `http://localhost/phpmyadmin`
5. Create a new database named `permission_slip`

#### Step 2: Set Up the Backend
1. Navigate to your project directory in command prompt/terminal
2. Initialize the project and install dependencies:
   ```bash
   npm init -y
   npm install express mysql2 bcryptjs jsonwebtoken cors body-parser

  ### Step 3: Set Up the Frontend
   Create a folder named public in your project directory
   Save these provided files inside the public folder:
   <b>1.index.html - Main application interface and markup
   2.style.css - All styling rules for the application
   3.script.js - Client-side functionality and API interactions<b/></br>

 ### Step 4: Install Frontend Dependencies
 Include the jsPDF library by adding this script tag inside the <head> section of your index.html:

html
```bash
<script src="https://cdnjs.cloudflare.com/ajax/libs/jspdf/2.5.1/jspdf.umd.min.js"></script>
📁 Project Structure
text

** sliphub-app/
├── server.js                 # Backend server and API routes
├── package.json              # Project dependencies and scripts
├── package-lock.json         # Exact dependency versions
└── public/                   # Frontend assets
    ├── index.html            # Main HTML document
    ├── style.css             # Application styles
    └── script.js             # Client-side JavaScript ***

🎯 Running the Application
Starting the Backend Server
Open command prompt/terminal in your project directory

Execute the server script:

node server.js
Successful startup will display: "Server running at http://localhost:3000"

### Accessing the Application
Open your preferred web browser

Visit: http://localhost:3000

The SlipHub application interface will load
h
🧪 Application Testing
First-Time Setup Verification
Register a new student account using the student registration form

### Register a new teacher account using the secret code: "nub":

Login with both accounts to verify authentication works correctly


Functional Testing
### Student Perspective:

Log in as a student

Submit a new permission slip application

Check the status of submitted slips

Download an approved permission slip as PDF

### Teacher Perspective:

Log in as a teacher

View the list of pending permission slips

Approve or reject submission requests

Verify status updates reflect immediately

### ⚠️ Troubleshooting Common Issues
Port Already in Use Error
Solution: Change the port in server.js (e.g., to 3001, 8080, etc.) and update the API_BASE URL in script.js accordingly

Database Connection Problems
### Verification Steps:

Ensure MySQL is running in XAMPP Control Panel

Confirm database credentials in server.js match your MySQL setup

Verify the database named permission_slip exists

