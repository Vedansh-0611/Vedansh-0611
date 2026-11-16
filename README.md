## Hi, I'm Vedansh

I'm a backend developer with about two years of experience, mostly in **Python and Django**.
Most of my work so far has been on the backend of AI voice-agent products: handling
telephony and voice-agent webhooks, integrating LLM APIs, running background jobs with
Celery and Redis, and building the REST APIs and dashboards that sit on top of call data.

**I'm open to Python backend, full-stack and AI-integration roles.**

### What I work with

- **Backend:** Python, Django, Django REST Framework, Celery, Redis, PostgreSQL, Node.js / Express
- **Frontend:** React, Vite
- **Infra:** Docker, Docker Compose, GitHub Actions CI/CD
- **AI / voice:** LLM API integration, telephony and voice-agent webhooks

### Featured project: CallFlow

A multi-tenant SaaS for AI voice-agent call analytics
([live demo](https://vedansh-0611.github.io/callflow-dashboard/)).

- **[callflow-analytics-api](https://github.com/Vedansh-0611/callflow-analytics-api)**:
  Django + DRF + Celery backend. Organizations with roles, JWT login and hashed org API keys,
  idempotent HMAC-signed webhook ingestion, async cost and outcome summaries, plan-based rate
  limits (Redis) and monthly usage limits (402), and outbound `call.summarized` webhooks with
  signed, retried delivery. OpenAPI docs, JSON logs with request ids, a multi-stage Docker
  image, a Render blueprint, and CI that tests on PostgreSQL and runs the full stack end to end.
- **[callflow-dashboard](https://github.com/Vedansh-0611/callflow-dashboard)**:
  React app for it: sign-in, org switcher, analytics with charts and call timelines, API key
  and webhook management, and a usage and plan page. The GitHub Pages demo runs on a mock of
  the API.

### Contact

[LinkedIn](https://www.linkedin.com/in/vedansh-kapoor-8b61bb25a/)
