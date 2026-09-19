# Webhook Reliability Console

A production-style Node.js application for investigating webhook deliveries and retrying failures safely.

## Engineering evidence
- REST APIs for delivery history, summaries, and retries
- persisted operational state with serialized writes and atomic replacement
- required idempotency keys and duplicate-retry protection
- accessible API-driven interface
- tests using Node's built-in test runner

## Run
```bash
npm test
npm start
```
Open `http://localhost:3000`. Seed data is included; this project does not claim a live customer integration.
