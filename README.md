cd asset-tracker
python -m venv .venv
source .venv/bin/activate   # En Windows: .venv\Scripts\activate
pip install -r backend/requirements.txt
uvicorn backend.app.main:app --reload --port 8000
