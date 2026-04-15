# RewiseED FastAPI Backend Project Structure

## Project Structure
```
rewiseED/
├── app/
│   ├── main.py
│   ├── models/
│   ├── routers/
│   ├── services/
│   ├── utils/
│   └── config.py
├── tests/
│   ├── test_main.py
│   └── test_routers.py
├── requirements.txt
└── README.md
```

## Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/Bhuvaneswari-tech/rewiseED.git
   cd rewiseED
   ```
2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the application:
   ```bash
   uvicorn app.main:app --host 0.0.0.0 --port 8000
   ```

## Features
- **FastAPI**: A modern, fast (high-performance), web framework for building APIs with Python 3.6+.
- **Asynchronous Support**: Fully supports asynchronous programming with async and await.
- **Easy to Use**: Simple and easy to use for both beginners and experts.
- **Dependency Injection**: Built-in support for dependency injection, promoting code reusability.
- **Automatic Interactive API Docs**: Automatically generates interactive API documentation with Swagger UI and ReDoc.
- **Testing**: Includes unit tests for ensuring functionality and reliability. 
