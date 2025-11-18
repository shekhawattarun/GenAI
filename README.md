# Agentic Orthopedic X-Ray Surgical Planning

Polished repository for the Agentic AI system (skeleton) described in the M.Tech thesis.

## Features
- Modular agent implementations (vision, measurement, implant, report, verification, planner)
- FastAPI backend exposing `/process_xray/`
- Streamlit demo UI
- Basic unit tests and CI workflow (GitHub Actions)
- Dockerfile for containerized deployment

## Quickstart (local)
```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
# run API
python -m api.server
# run UI (in another shell)
streamlit run ui/app.py
```

## Run tests
```bash
pip install pytest
pytest -q
```

## Notes
- This repo is a functional skeleton. Replace model placeholders in `models/` with trained checkpoints for full functionality.
