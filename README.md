# Create a virtual environment
python -m venv venv

# Activate the virtual environment
.\venv\Scripts\activate

pip install fastapi uvicorn sqlalchemy

touch main.py

uvicorn main:app --reload

# You can test api using swagger at
http://127.0.0.1:8000/docs
