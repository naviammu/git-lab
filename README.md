# CodeInspect

CodeInspect is a static code analysis and version management tool designed to help developers detect errors, compare code versions, and improve code quality efficiently. It integrates AI-powered insights with a modern interface.

---

## Features

### Static Code Analysis

* Detects syntax errors
* Identifies logical issues (partial detection)
* Highlights coding standard violations

### Version Management

* Save multiple versions of code (V1, V2, V3…)
* Compare different versions
* Rollback to previous versions

### Report Generation

* Generates detailed analysis reports
* Stores reports in database
* Tracks error detection accuracy

### AI Integration

* Uses Groq API for intelligent insights
* Enhances explanations of detected issues

### Modern UI

* Clean React-based interface
* Integrated code editor
* Visual diff comparison view

---

## Tech Stack

### Frontend

* React.js

### Backend

* FastAPI (Python)

### Database

* PostgreSQL

### APIs

* Groq API

--
## Installation & Setup

### 1️ Clone the Repository

```bash
git clone https://github.com/your-username/codeinspect.git
cd codeinspect
```

### 2️ Backend Setup (FastAPI)

```bash
cd backend
pip install -r requirements.txt
uvicorn main:app --reload
```

### 3️ Frontend Setup (React)

```bash
cd frontend
npm install
npm start
```

### 4️ Database Setup (PostgreSQL)

* Create a database
* Update database configuration in backend
* Execute schema.sql

---

## How It Works

1. User inputs code in the editor
2. Code is sent to FastAPI backend
3. Backend performs:

   * analysis using codebert model
   * AI-based analysis using Groq API
4. Results include:

   * Detected errors
   * Generated report
   * Stored version
5. User can:

   * Compare versions
   * Rollback changes

---

## Key Functionalities

* Error detection (syntax + logical)
* Version tracking
* Code comparison (diff view)
* Rollback functionality
* Report history

---
