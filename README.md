# Tiny Backend API

A simple Flask backend with two JSON endpoints.

## Technologies Used

- Python
- Flask
- Git
- GitHub

## API Endpoints

**GET /**


### Home

GET /

Response:

{
  "message": "Hello, World!"
}

### About

GET /about

Response:

{
  "name": "Your Name",
  "course": "Backend API Portfolio"
}

## Run locally

Install dependencies:

pip install -r requirements.txt

Start server:

python app.py