# RewiseED FastAPI Backend Project

This is the backend of the RewiseED application built using FastAPI and integrated with MongoDB Atlas.

## Project Structure
```
rewiseED/
│
├── app/
│   ├── __init__.py
│   ├── main.py
│   ├── models/
│   │   ├── __init__.py
│   │   ├── user.py
│   │   ├── article.py
│   │   └── ...
│   ├── schemas/
│   │   ├── __init__.py
│   │   ├── user.py
│   │   ├── article.py
│   │   └── ...
│   ├── services/
│   │   ├── __init__.py
│   │   ├── user_service.py
│   │   ├── article_service.py
│   │   └── ...
│   ├── configs/
│   │   ├── __init__.py
│   │   ├── config.py
│   └── docs/
│       └── api_docs.md
├── .env.example
├── requirements.txt
└── Dockerfile
```  

### Requirements
- FastAPI
- uvicorn
- pymongo
- python-dotenv
- pydantic

### Setup
1. Clone the repository.
2. Copy `.env.example` to `.env` and fill in the required variables for MongoDB Atlas.
3. Run the server:
```bash
uvicorn app.main:app --reload
``` 

### Docker
To build and run with Docker:
```bash
docker build -t rewiseed .
docker run -d -p 8000:8000 rewiseed
``` 

### Documentation
Refer to the `docs/api_docs.md` for API documentation.