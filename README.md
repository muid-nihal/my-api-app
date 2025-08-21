\# my-api-app



Minimal FastAPI + OpenAI chat endpoint.



\## Setup



1\. Create a `.env` file next to `main.py`:





2\. Create and activate venv, install deps:



python -m venv venv

venv\\Scripts\\activate

pip install -r requirements.txt





3\. Run:



uvicorn main:app --reload





Open http://127.0.0.1:8000/docs and use `POST /chat`.



