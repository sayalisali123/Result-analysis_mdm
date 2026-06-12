# Result Analysis & Minor Degree Allocation System

## Overview

The Result Analysis & Minor Degree Allocation System is a web-based academic management platform designed to automate student result analysis and minor degree allocation processes.

The system allows students to upload result PDFs, automatically extracts academic information using Gemini AI, stores the processed data in Firebase Firestore, and enables faculty members to manage minor degree allocations based on student preferences and academic performance.

---

## Features

### Student Module

* Student Registration and Login
* Secure Authentication using Flask-Login
* Upload Academic Result PDFs
* View Submitted Results
* Submit Minor Degree Preferences
* Track Submitted Applications

### Faculty Module

* Faculty Login Dashboard
* View Processed Student Results
* Analyze Academic Performance
* Manage Minor Degree Applications
* Automated Seat Allocation
* Export Reports to Excel

### AI-Powered Analysis

* PDF Result Extraction 
* Automatic Subject-wise Data Processing
* Academic Performance Summary Generation
* Automated Result Analysis Workflow

---

## Tech Stack

### Backend

* Python
* Flask
* Flask-Login

### Database

* Firebase Firestore

### AI Integration

* Google Gemini AI API

### Data Processing

* Pandas
* OpenPyXL

### Frontend

* HTML
* CSS
* JavaScript
* Jinja2 Templates

### Deployment

* Vercel
* Firebase

---

## Project Workflow

1. Student registers and logs into the system.
2. Student uploads a result PDF.
3. Gemini AI extracts and processes academic data.
4. Processed information is stored in Firebase Firestore.
5. Student submits Minor Degree preferences.
6. Faculty reviews applications and academic records.
7. The system performs seat allocation based on preferences and eligibility.
8. Reports can be exported as Excel files.

---

## Project Structure

```text
├── app.py
├── extractor.py
├── mdm_logic.py
├── models.py
├── requirements.txt
├── static/
├── templates/
├── vercel.json
└── README.md
```

---

## Key Functionalities

* AI-based Result Analysis
* Student & Faculty Dashboards
* Firestore Database Integration
* Minor Degree Seat Allocation
* Excel Report Generation
* Authentication and Session Management
* PDF Processing and Data Extraction

---

## Future Enhancements

* Email Verification
* OTP Authentication
* Role-Based Access Control
* Analytics Dashboard
* Real-Time Notifications
* Multi-Institution Support
* Advanced Reporting and Visualization

---

## Author

Developed as an academic management solution for automating result analysis and minor degree allocation workflows using AI and cloud technologies.
