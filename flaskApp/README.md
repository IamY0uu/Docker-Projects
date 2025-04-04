# 🚀 Flask-Docker Application

This project is a simple Flask application that runs inside a Docker container.

---

## 📂 **Project Structure**

        └── flaskApp
            ├── README.md
            └── app
                ├── Dockerfile
                ├── app.py
                └── requirements.txt

---

## Install Dependencies

If running locally (without Docker), activate the virtual environment and install dependencies:

python3 -m venv .venv

source .venv/bin/activate           # For Mac/Linux
# For Windows: .venv\Scripts\activate
        
pip install -r requirements.txt

---

## Run the Flask App Locally

python app.py

---

## Your app should now be running at

<http://localhost:5000>
