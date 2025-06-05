# Todo SaaS Example

This project is a minimal example of a Software-as-a-Service (SaaS) backend for managing todo tasks. It uses **FastAPI** with **SQLite** for persistence.

## Requirements

- Python 3.11+

Install dependencies:

```bash
pip install -r requirements.txt
```

## Running the Server

```bash
uvicorn todo_saas.backend.main:app --reload
```

The API will be available at `http://localhost:8000`.

### API Endpoints

- `POST /api/users/` — create a user
- `POST /api/login/` — login a user
- `GET /api/tasks/` — list tasks
- `POST /api/tasks/` — create a task
- `PUT /api/tasks/{id}` — update a task
- `DELETE /api/tasks/{id}` — delete a task
