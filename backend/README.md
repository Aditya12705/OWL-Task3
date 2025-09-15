Backend (Flask) — Quick start
---------------------------
1. Create a virtualenv: python -m venv venv
2. Activate it: source venv/bin/activate (Windows: venv\Scripts\activate)
3. Install: pip install -r requirements.txt
4. Run: python app.py
5. The API listens on http://localhost:5000
Note: For production, set SECRET_KEY and use a proper DB (Postgres).