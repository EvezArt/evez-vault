# EVEZ Vault

Revenue and cost tracking for the EVEZ ecosystem.

## Run
```bash
uvicorn vault:app --reload
```

## API
- `GET /health` — Health check
- `GET /report` — Cost report
- `POST /track?service=...` — Track a cost

---
*Built by EVEZ Factory (Steven AI)*
