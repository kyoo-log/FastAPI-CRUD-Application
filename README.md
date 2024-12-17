
# FastAPI CRUD Application

## Description
This is a robust REST API built with FastAPI, PostgreSQL, and JWT authentication. The application supports user authentication and CRUD operations for managing user profiles.

## Features
- User authentication (JWT-based).
- CRUD operations for user profiles.
- Deployed on AWS Lambda (compatible).

## Getting Started

### Prerequisites
- Python 3.8 or higher
- PostgreSQL database

### Installation
1. Clone the repository:
    ```
    git clone https://github.com/your-username/fastapi-crud-app.git
    cd fastapi-crud-app
    ```

2. Install dependencies:
    ```
    pip install -r requirements.txt
    ```

3. Set environment variables:
    ```
    export DATABASE_URL="postgresql://user:password@localhost/db"
    export SECRET_KEY="your_secret_key"
    ```

4. Run the application:
    ```
    uvicorn main:app --reload
    ```

5. Access the API documentation at `http://127.0.0.1:8000/docs`.

## Deployment
Use AWS Lambda to deploy the application as a serverless function.

## License
This project is licensed under the MIT License.
