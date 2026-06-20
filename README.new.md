# Student Management System

A full-stack Student Management System developed using Node.js, Express.js, MongoDB Atlas, and Vanilla JavaScript. The application allows users to manage student records through a responsive web interface and RESTful APIs.

---

## Project Overview

This project was developed as part of the Employeer IT Internship Program to gain hands-on experience in backend development, database integration, API creation, and CRUD operations.

The system enables users to:

- Add Students
- View All Students
- Update Student Details
- Delete Student Records
- Search Student Records
- Store Data in MongoDB Atlas

---

## Features

### Backend Features

- RESTful API Architecture
- MongoDB Atlas Integration
- Mongoose ODM
- CRUD Operations
- Data Validation
- Error Handling
- Modular Folder Structure

### Frontend Features

- Responsive Dashboard
- Student Registration Form
- Student Records Table
- Search Functionality
- Clean and Modern User Interface

---

## Tech Stack

### Backend

- Node.js
- Express.js
- MongoDB Atlas
- Mongoose

### Frontend

- HTML5
- CSS3
- JavaScript (ES6)

### Tools

- Visual Studio Code
- Postman
- Git & GitHub

---

## Project Structure

```text
student-management-system/

├── backend/
│   ├── config/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── .env
│   ├── package.json
│   └── server.js
│
├── frontend/
│   ├── index.html
│   ├── css/
│   └── js/
│
├── Database/
│   └── students.json
│
├── Screenshots/
│
├── Student_Management_System_Report.docx
│
└── README.md
```

---

## Database Schema

### Student

| Field | Type | Description |
|---------|---------|---------|
| studentName | String | Student Name |
| studentId | String | Unique Student ID |
| email | String | Student Email |
| course | String | Course Name |
| createdAt | Date | Creation Date |

---

## API Endpoints

### Create Student

```http
POST /api/students
```

### Get All Students

```http
GET /api/students
```

### Search Students

```http
GET /api/students?search=value
```

### Update Student

```http
PUT /api/students/:id
```

### Delete Student

```http
DELETE /api/students/:id
```

---

## Installation Guide

### Step 1: Clone Repository

```bash
git clone <repository-url>
```

### Step 2: Navigate to Backend Folder

```bash
cd backend
```

### Step 3: Install Dependencies

```bash
npm install
```

### Step 4: Configure Environment Variables

Create a `.env` file inside the backend folder.

```env
PORT=5000
MONGODB_URI=your_mongodb_connection_string
```

### Step 5: Start Backend Server

```bash
npm run dev
```

Server will run on:

```text
http://localhost:5000
```

---

## Running Frontend

After starting the backend server:

1. Open the frontend folder.
2. Open `index.html`.
3. Right-click on `index.html`.
4. Select **Open with Live Server**.

Frontend will launch in the browser.

---

## Testing APIs

All API endpoints were tested using Postman.

Tested Operations:

- Create Student
- Get Students
- Update Student
- Delete Student

Screenshots are available inside the `Screenshots` folder.

---

## Learning Outcomes

Through this project, I gained practical experience in:

- Backend Development
- REST API Design
- MongoDB Atlas Integration
- CRUD Operations
- Express.js Routing
- Error Handling
- Frontend and Backend Communication
- GitHub Project Management

---

## Internship Task Information

**Internship Program:** Employeer IT Internship Program

**Week:** Week 1

**Task:** Student Management System API

---

## Author

### Seerat Safdar

Software Engineering Student

Backend Development Intern


---

## License

This project was developed for educational and internship learning purposes.
