Pre-requisites to Run the SlipHub Application
Before running the SlipHub application, ensure you have the following components properly set up:

1. Software Requirements
Must Have:
Node.js (version 14 or higher) - Download here

XAMPP (for MySQL database) - Download here

Web Browser (Chrome, Firefox, or Edge recommended)

Development Tools (Optional):
Visual Studio Code or any code editor

Postman for API testing

2. Installation Steps
Step 1: Install and Configure XAMPP
Download and install XAMPP

Launch XAMPP Control Panel

Start Apache and MySQL services

Open phpMyAdmin by visiting http://localhost/phpmyadmin

Create a new database named permission_slip

Step 2: Set Up the Backend
Navigate to your project directory in command prompt/terminal

Install required dependencies:

text
npm init -y
npm install express mysql2 bcryptjs jsonwebtoken cors body-parser
Save the provided server.js code in your project directory

Step 3: Set Up the Frontend
Save the provided HTML code as index.html

Save the provided CSS code as style.css

Save the provided JavaScript code as script.js

Create a folder named public (if it doesn't exist) and move the frontend files there

Step 4: Install Frontend Dependencies
Include jsPDF in your HTML file by adding this script tag inside the <head>:

html
<script src="https://cdnjs.cloudflare.com/ajax/libs/jspdf/2.5.1/jspdf.umd.min.js"></script>
3. Folder Structure
text
your-project-folder/
├── server.js
├── package.json
├── public/
│   ├── index.html
│   ├── style.css
│   └── script.js
4. Running the Application
Start the Backend Server:
Open command prompt/terminal in your project directory

Run the server:

text
node server.js
You should see: "Server running at http://localhost:3000"

Access the Application:
Open your web browser

Visit: http://localhost:3000

The SlipHub application should load

5. Troubleshooting Common Issues
Port Already in Use:
If port 3000 is occupied, change the port in server.js and update the API_BASE URL in script.js

Database Connection Errors:
Verify MySQL is running in XAMPP

Check database credentials in server.js match your MySQL setup

CORS Issues:
Ensure the cors package is properly installed

Verify frontend and backend are running on compatible origins

Module Not Found Errors:
Verify all npm packages are correctly installed

Check for any typos in require() statements

6. Testing the Application
First-Time Setup Test:
Register a new student account

Register a new teacher account (using the secret code: "nub")

Login with both accounts to verify authentication works

Functionality Test:
As a student, submit a permission slip application

As a teacher, view and approve the application

As a student, download the approved PDF

Once all these pre-requisites are met, your SlipHub application should run successfully!
