# Nationality & Author Profiling System

This project is a lightweight web application for predicting the nationality and author profile (gender) from text. It uses:

- FastAPI for backend API
- Streamlit for frontend UI
- Hugging Face Transformers for NLP models

## Features

- Predicts the most likely nationality of an author from text.
- Classifies author profile attributes like gender.
- Quick setup with Python virtual environments.
- Clean and interactive user interface.

## Installation & Setup

### 1. Clone or Download the Repository
```bash
git clone https://github.com/yourusername/NationalityAuthorProfiling.git
cd NationalityAuthorProfiling
```

### 2. Create a Virtual Environment
```bash
python -m venv venv

# Activate the environment
# Windows
venv\Scripts\activate
# macOS/Linux
source venv/bin/activate
```

### 3. Install Dependencies
```bash
pip install -r app/requirements.txt
pip install streamlit requests
```

## Running the Application

### Start Backend (FastAPI)
```bash
cd app
uvicorn main:app --reload
```

### Start Frontend (Streamlit)
Open a new terminal:
```bash
cd ../frontend
streamlit run streamlit_app.py
```

Go to http://localhost:8501 in your browser.

## Adding More Countries

Edit `app/main.py` and extend the `countries` list with more country names.

## Changing Models

Modify `app/models.py` to use different Hugging Face models for nationality or profiling tasks.
