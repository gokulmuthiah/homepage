# Homepage Project

This project consists of a frontend and backend service.

## Project Structure

```
.
├── frontend/     # Vite + React frontend application
├── backend/      # Flask backend service
└── README.md     # This file
```

## Frontend

The frontend is a Vite + React application. See `frontend/README.md` for setup and running instructions.

## Backend

The backend is a Flask service. See `backend/README.md` for setup and running instructions.

## Development

To run both services in development mode:

1. Start the backend:
```bash
cd backend
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python app.py
```

2. Start the frontend:
```bash
cd frontend
npm install
npm run dev
```

The frontend will be available at http://localhost:5173
The backend will be available at http://localhost:5000
