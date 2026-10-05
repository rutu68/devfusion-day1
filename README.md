# devfusion-day1

Student Record System API built with FastAPI and MongoDB.

## Features

- Student record management (CRUD operations)
- FastAPI with CORS middleware
- MongoDB integration via Motor
- Pydantic models and schemas

## Getting Started

### 1. Setup Environment
```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

### 2. Configure Environment Variables
Copy `.env.example` to `.env` and set your MongoDB connection details:
```bash
cp .env.example .env
```

### 3. Run the Application
```bash
uvicorn app.main:app --reload
```
