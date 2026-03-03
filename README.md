# NovaBot

NovaBot is a voice-first in-home AI companion.

It is designed to listen, remember context, and automate everyday routines like reminders, focus flows, and home actions in a calm, natural way.

## Links

- Website: https://novabotlanding.vercel.app
- GitHub: https://github.com/rishabhsai/Nova-Home-Assitant

## Project Structure

- `frontend/`: NovaBot landing and waitlist site (React + Vite)
- `backend/`: NovaBot assistant backend APIs and voice pipeline (FastAPI)
- `run.sh`: Local workflow helper script

## Local Development

### Frontend

```bash
cd frontend
npm install
npm run dev
```

### Backend

```bash
cd backend
python3.11 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
cp .env.example .env
uvicorn main:app --reload --port 8000
```
