# FastAPI REST API with SQLAlchemy

A practical learning repository for developing REST APIs using **Python, FastAPI, Pydantic, SQLAlchemy ORM, and SQLite**.

## About This Project

This repository contains theory notes, practical examples, and Python programs to help students understand REST API development and database integration.

The examples progress from basic API endpoints to database-backed CRUD operations.

## Technologies Used

- Python
- FastAPI
- Pydantic
- SQLAlchemy ORM
- SQLite
- Uvicorn
- Git and GitHub

## Topics Covered

- Introduction to REST APIs and FastAPI
- HTTP methods and status codes
- Path parameters, query parameters, and request bodies
- Pydantic models and data validation
- Relational databases and SQL fundamentals
- SQLAlchemy ORM and database connectivity
- CRUD operations: Create, Read, Update, and Delete
- Filtering, searching, and pagination
- Error handling and database transactions
- Authentication with JWT
- Database relationships and JOIN operations
- API testing and integration

*Topics will be added progressively as the learning material develops.*

## Project Structure

```text
fastapi-rest-api-with-sqlalchemy/
├── README.md
├── .gitignore
├── requirements.txt
└── main.py
```

The application may generate a local `college.db` SQLite database when it runs. The database file is not required in the GitHub repository.

## Prerequisites

- Python 3.10 or later
- pip
- Basic knowledge of Python

## Installation

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/fastapi-rest-api-with-sqlalchemy.git
cd fastapi-rest-api-with-sqlalchemy
```

Create a virtual environment:

```bash
python -m venv venv
```

Activate it on Windows:

```bash
venv\Scripts\activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

## Run the Application

Start the development server:

```bash
uvicorn main:app --reload
```

Open the interactive API documentation:

- Swagger UI: http://127.0.0.1:8000/docs
- ReDoc: http://127.0.0.1:8000/redoc

## Example API Endpoints

| Method | Endpoint | Purpose |
|---|---|---|
| POST | `/students` | Create a student |
| GET | `/students` | Retrieve students |
| GET | `/students/{student_id}` | Retrieve one student |
| PUT | `/students/{student_id}` | Replace student fields |
| PATCH | `/students/{student_id}` | Update selected fields |
| DELETE | `/students/{student_id}` | Delete a student |

## Learning Approach

Each chapter combines:

- Theory and explanations
- Questions and answers
- Practical Python code
- API request and response examples
- Exercises and revision questions

## Intended Audience

This repository is intended for students, beginners, and developers learning backend development with Python and FastAPI.

## Contribution

Suggestions, improvements, and educational contributions are welcome.

## License

Unless a license is added to this repository, all rights are reserved by the copyright holder. Check with the repository owner before reusing or redistributing the material.
