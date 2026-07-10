# AI Interview Preparation & ATS Resume Generator

## Overview

AI Interview Preparation & ATS Resume Generator is a full-stack web application that helps candidates prepare for interviews by analyzing their resume, self-description, and job description. The application generates a personalized interview report, identifies skill gaps, provides technical and behavioral interview questions with answers, creates a preparation plan, and generates an ATS-friendly resume.

---

## Features

- User Registration and Login
- Secure Authentication using JWT
- Token Blacklisting for Secure Logout
- Resume Upload (PDF)
- Resume Parsing
- Job Description Analysis
- AI-Powered Interview Report Generation
- Match Score Analysis
- Technical Interview Questions with Answers
- Behavioral Interview Questions with Answers
- Skill Gap Detection
- Personalized Preparation Plan
- ATS-Optimized Resume Generation
- PDF Resume Generation using Puppeteer
- Protected Routes
- RESTful API Architecture

---

## Project Architecture

- Full Stack Web Application Architecture
- Secure Authentication using JWT
- Token Blacklisting Implementation
- AI Integration using Google Gemini API
- Resume Parsing and Skill Extraction
- AI-Based Skill Gap Detection
- ATS-Optimized Resume Generation
- Dynamic PDF Creation using Puppeteer
- Real-World Project Structure

---

## Tech Stack

### Frontend
- React.js
- React Router
- SCSS
- Axios

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose

### Authentication
- JSON Web Token (JWT)
- HTTP Cookies
- Token Blacklisting

### AI
- Google Gemini API

### File Handling
- Multer
- pdf-parse

### PDF Generation
- Puppeteer

---

## Folder Structure

```text
genAI/
│
├── Frontend/
│   ├── src/
│   ├── public/
│   ├── package.json
│   └── vite.config.js
│
├── Backend/
│   ├── src/
│   ├── server.js
│   ├── package.json
│   └── .env
│
└── README.md
```

---

## Installation

### Clone the Repository

```bash
git clone https://github.com/your-username/your-repository-name.git
```

### Install Backend Dependencies

```bash
cd Backend
npm install
```

### Install Frontend Dependencies

```bash
cd ../Frontend
npm install
```

---

## Environment Variables

Create a `.env` file inside the Backend folder.

```env
PORT=3000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
GOOGLE_GENAI_API_KEY=your_google_gemini_api_key
```

---

## Running the Application

### Start Backend

```bash
cd Backend
npm run dev
```

### Start Frontend

```bash
cd Frontend
npm run dev
```

---

## Application Workflow

1. Register or log in.
2. Upload a resume or provide a self-description.
3. Enter the target job description.
4. Generate an AI-based interview report.
5. Review the match score, interview questions, skill gaps, and preparation plan.
6. Generate and download an ATS-optimized resume in PDF format.

---

## Future Enhancements

- Voice-based mock interviews
- AI interview feedback
- Company-specific interview preparation
- Resume version management
- Interview performance analytics
- Email sharing of reports

---

## Author

Pratiksha Nithave

Bachelor of Engineering (Computer Engineering)

---

## License

This project is licensed under the MIT License.
