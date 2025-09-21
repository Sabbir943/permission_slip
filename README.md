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
