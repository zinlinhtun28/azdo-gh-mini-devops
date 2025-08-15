# Mini DevOps Sample (FastAPI)

A minimal FastAPI app used for learning Git/GitHub and CI/CD.

## Run locally

```bash
python -m venv .venv
# Windows PowerShell: .venv\Scripts\Activate.ps1
# macOS/Linux:
source .venv/bin/activate

pip install --upgrade pip
pip install -r requirements.txt

uvicorn app.main:app --reload --host 0.0.0.0 --port 8000
```

Then browse http://localhost:8000/healthz

## Tests

```bash
pytest -q
```
