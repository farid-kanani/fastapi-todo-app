# FastAPI Todo App

This is a simple Todo application built with **FastAPI**, **SQLAlchemy**, and **Uvicorn**.

## Features

- Create, read, update, and delete todo items
- API documentation with Swagger UI
- Async support with FastAPI
- SQLite database integration via SQLAlchemy

## Getting Started

### Prerequisites

Make sure you have Python 3.10+ installed.

### Installation

1. Clone the repository:

```bash
git clone https://github.com/farid-kanani/fastapi-todo-app.git
cd fastapi-todo-app
```

2. Create and activate a virtual environment (optional but recommended):

```bash
python -m venv env
source env/bin/activate        # On Linux/macOS
env\Scripts\activate           # On Windows
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Run the application:

```bash
uvicorn main:app --reload
```

Then open your browser and go to: http://localhost:8000/docs

## Contributing

Contributions are welcome! Here's how you can help:

Fork this repository

Create a new branch (e.g. feature/my-feature)

Make your changes

Commit and push your code

Open a Pull Request

Thank you for your support!

## License

This project is open-source and available under the MIT License.
