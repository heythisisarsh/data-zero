# DataZero

**Production-grade open-source PII redaction & personal-data sanitization library and API.**

DataZero can be used as:
- A **Python library** for detecting & redacting sensitive data in text/JSON.
- A **standalone API server** (FastAPI + Uvicorn) that can run inline with LLMs, ingestion pipelines, or behind load balancers.
- A **CLI tool** for one-off or batch redaction.

---

## ✨ Features (MVP)
- Detect **emails** and **phone numbers** via regex.
- Redaction modes: simple **masking**.
- Python API, CLI, and FastAPI server.
- MIT licensed.

---

## 🚀 Quickstart

### Install
```bash
git clone https://github.com/heythisisarsh/datazero.git
cd datazero
pip install -e .
```
