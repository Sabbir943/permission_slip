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

Step 3: Set Up the Frontend

Create a folder named public (if not already present).
Save these provided files inside the public folder:

index.html → Main application interface and markup

style.css → Application styling

script.js → Client-side functionality and API interactions

Step 4: Install Frontend Dependencies

Add the jsPDF library to your index.html inside the <head> section:

<script src="https://cdnjs.cloudflare.com/ajax/libs/jspdf/2.5.1/jspdf.umd.min.js"></script>

🚀 Running the Application
Start the Backend Server

Open terminal in the project directory and run:

node server.js


Successful startup will display:

Server running at http://localhost:3000

Access the Application

Open a browser and go to:
👉 http://localhost:3000

🧪 Application Testing
First-Time Setup Verification

Register a new student account using the student registration form.

Register a new teacher account using the secret code: nub.

Log in with both accounts to verify authentication.

Functional Testing

Student Perspective

Log in as a student

Submit a new permission slip application

Check the status of submitted slips

Download an approved permission slip as PDF

Teacher Perspective

Log in as a teacher

View the list of pending permission slips

Approve or reject requests

Verify status updates reflect immediately

⚠️ Troubleshooting
Port Already in Use

Change the port in server.js (e.g., 3001 or 8080)

Update API_BASE URL in script.js accordingly

Database Connection Problems

Ensure MySQL is running in XAMPP Control Panel

Confirm database credentials in server.js match your MySQL setup

Verify a database named permission_slip exists

📌 Technologies Used

Node.js – Backend server

Express.js – API routes

MySQL – Database

HTML, CSS, JavaScript – Frontend

jsPDF – PDF generation

👨‍💻 Author

Developed as part of Software Development II (Database Programming) project.


---

Do you want me to also include the **SQL schema** (table creation script) in the README so new users can set up the database quickly?

You said:

Confirm database credentials in server.js match your MySQL setup

Verify the database named permission_slip exists

