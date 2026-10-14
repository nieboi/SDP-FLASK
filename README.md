# Mevi Docker Flask

A small Flask application scaffold designed to run in a Docker container.

## Setup

```bash
cd mevi-docker-flask
python -m venv .venv
source .venv/bin/activate   # On Windows use .venv\Scripts\activate
pip install -r requirements.txt
python app.py
```

The app will be available at `http://localhost:5000`.

## Docker

```bash
docker build -t mevi-docker-flask .
docker run -p 5000:5000 mevi-docker-flask
```
