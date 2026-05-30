# railway

A FastAPI + PostgreSQL project: railway

## Stack

- **Framework**: FastAPI
- **Database**: PostgreSQL (async via SQLAlchemy)
- **Deploy**: railway



## Getting Started

```bash
cp .env.example .env
# Fill in DATABASE_URL and other variables

pip install -r requirements.txt
uvicorn src.main:app --reload
```

## API Endpoints

- `GET /health` — Health check



## Environment Variables

See `.env.example` for required variables.
