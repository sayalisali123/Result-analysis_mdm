# Result Analysis & Minor Degree Allocation System

## Overview

The Result Analysis & Minor Degree Allocation System is a web-based academic management platform designed to automate student result analysis and minor degree allocation processes.

The system enables students to upload academic result PDFs, automatically extracts and analyzes academic information, stores processed data in Firebase Firestore, and allows faculty members to manage student records, analyze performance, allocate minor degree seats, and generate reports.

---

## Live Demo

🚀 **Deployed Application**

https://result-analysis-mdm.onrender.com

> Note: The application is hosted on Render's free tier. The first request may take a few seconds if the service is waking up from inactivity.

---

## Features

### Student Module

* Student Registration and Login
* Secure Authentication using Flask-Login
* Upload Academic Result PDFs
* Automatic Result Analysis
* View Submitted Results
* Submit Minor Degree Preferences
* Track Submitted Applications

### Faculty Module

* Faculty Login Dashboard
* View Processed Student Results
* Analyze Academic Performance
* Manage Minor Degree Applications
* Automated Seat Allocation
* Download Reports in Excel Format

### AI-Powered Analysis

* PDF Result Extraction
* Subject-wise Marks Analysis
* Performance Summary Generation
* Automated Academic Data Processing
* Intelligent Result Interpretation using Gemini AI

---

## System Architecture

Student → Flask Application → Gemini AI → Firebase Firestore

### Workflow

1. Student registers and logs in.
2. Student uploads a result PDF.
3. Academic information is extracted from the PDF.
4. Processed data is stored in Firebase Firestore.
5. Student submits Minor Degree preferences.
6. Faculty reviews student records.
7. The system performs seat allocation based on preferences and academic performance.
8. Faculty can export reports in Excel format.

---

## Tech Stack

### Backend

* Python
* Flask
* Flask-Login

### Database

* Firebase Firestore


### Data Processing

* Pandas
* OpenPyXL
* PDFPlumber

### Frontend

* HTML
* CSS
* JavaScript
* Jinja2 Templates

### Deployment

* Render
* Firebase Firestore

---

## Key Functionalities

### AI-Based Result Analysis

* Extracts academic information directly from uploaded result PDFs.
* Generates structured academic records.
* Calculates performance summaries.

### Student Management

* Registration and authentication.
* Result uploads.
* Minor degree application submission.

### Faculty Management

* Access student records.
* Review analyzed results.
* Manage minor degree allocation.
* Generate downloadable reports.

### Report Generation

* Excel export using OpenPyXL.
* Detailed subject-wise analysis.
* Allocation reports for faculty.

### Cloud Database Integration

* Firebase Firestore integration.
* Real-time storage and retrieval of academic records.

---

## Technical Highlights

* Secure authentication using Flask-Login.
* Intelligent PDF result extraction.
* Firebase Firestore cloud database integration.
* Automated Minor Degree seat allocation workflow.
* Dynamic Excel report generation using Pandas and OpenPyXL.
* Production deployment on Render.
* Environment-based configuration using Python Dotenv.
* Role-based workflow separation for Students and Faculty.

---

## Project Structure

```text
├── app.py
├── extractor.py
├── mdm_logic.py
├── models.py
├── requirements.txt
├── vercel.json
├── static/
│   ├── css/
│   ├── js/
│   └── assets/
├── templates/
│   ├── index.html
│   ├── login.html
│   ├── register.html
│   ├── dashboard.html
│   └── faculty_dashboard.html
└── README.md
```

---

## Local Setup

### Clone Repository

```bash
git clone https://github.com/sayalisali123/Result-analysis_mdm.git
cd Result-analysis_mdm
```

### Create Virtual Environment

```bash
python -m venv venv
```

### Activate Virtual Environment

Windows:

```bash
venv\Scripts\activate
```

Linux/Mac:

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Configure Environment Variables

Create a `.env` file:

```env
SECRET_KEY=your_secret_key
GEMINI_API_KEY=your_gemini_api_key
FIREBASE_CREDENTIALS_PATH=firebase-key.json
```

### Run Application

```bash
python app.py
```

Application will run at:

```text
http://127.0.0.1:5001
```

---

## Environment Variables

| Variable                  | Description                                    |
| ------------------------- | ---------------------------------------------- |
| SECRET_KEY                | Flask Secret Key                               |
| GEMINI_API_KEY            | Google Gemini API Key                          |
| FIREBASE_CREDENTIALS_PATH | Firebase Service Account JSON Path             |
| FIREBASE_CREDENTIALS      | Optional JSON credentials for cloud deployment |

---

## Future Enhancements

* Email Verification
* OTP Authentication
* Role-Based Access Control (RBAC)
* Analytics Dashboard
* Real-Time Notifications
* Multi-Institution Support
* Enhanced AI Insights
* Data Visualization Dashboard
* Performance Prediction Models

---

## Deployment

The application is deployed using:

* Render (Hosting Platform)
* Firebase Firestore (Database)
* Google Gemini AI (Result Analysis)

---

## Author

### Sayali Sali

Computer Science Student | Python Developer | AI & Web Development Enthusiast

GitHub:
https://github.com/sayalisali123

LinkedIn:
https://www.linkedin.com/in/sayalisali2004/
---

## License

This project is developed for educational and academic purposes.
