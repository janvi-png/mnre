# Backend: FastAPI + SQLite

Run:

python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
python fetch_and_store.py
uvicorn app:app --host 0.0.0.0 --port 8000
