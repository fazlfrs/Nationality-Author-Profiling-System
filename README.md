# Nationality-Author-Profiling-System
This is a simple web-based system for predicting the nationality and author profile (gender) from a text sample. It uses FastAPI for the backend and Streamlit for the frontend.

The backend leverages Hugging Face Transformers with:
✅ Zero-shot classification (facebook/bart-large-mnli) for nationality prediction
✅ Text classification (distilbert-base-uncased) for author profile prediction
