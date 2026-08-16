### Python developer

I build production-grade backend services and ML pipelines: Django and FastAPI applications, background task processing, CRM integrations, containerized deployments with full CI/CD. I care about clean architecture, tests, and systems that survive real-world failures.

---

## Featured projects

### 🏭 [DemoPlast — production Django app](https://github.com/Skerter/django-plastic-landing)

Public showcase of a commercial freelance project for a plastic products manufacturer.

- **Django 5 + HTMX** frontend, server-rendered, no SPA overhead
- **amoCRM integration** with OAuth2 refresh-token rotation
- Background jobs with **django-q2**, three notification channels
- **36 tests**, Sentry with PII scrubbing, CD pipeline: GitHub Actions → GHCR → SSH → docker compose

### 📊 [distributed-churn-prediction — ML pipeline with MLOps](https://github.com/Skerter/distributed-churn-prediction)

End-to-end customer churn prediction system, built to run the same code from a laptop to a cluster.

- **Three execution modes**: pandas → Dask local → Dask on Kubernetes
- **Four interfaces**: CLI, FastAPI service, web dashboard, Telegram bot (aiogram 3, FSM)
- Clean Architecture with a custom DI container; Template Method in the pipeline core
- Crash recovery: interrupted runs resume after OOM/SIGKILL
- **MLflow** experiment tracking, K8s manifests via kustomize + Dask Operator
- ~6,100 lines, 150 commits, CI/CD with automated tests and image builds

---

## Tech stack

**Core:** Python 3.11+, FastAPI, Django 5, aiogram 3, Pydantic, django-q2

**Data & ML:** pandas, Dask, XGBoost, scikit-learn, MLflow, PyArrow/Parquet

**Database:** PostgreSQL

**Infrastructure:** Docker/Compose, Kubernetes (kustomize), GitHub Actions, GHCR, Traefik, nginx, Linux

**Quality:** pytest, factory_boy, ruff, Sentry

---

## How I work

- **Production over tutorials** — every project is deployed, monitored, and survives restarts
- **Tests are not optional** — if it's not tested, it's broken; I just don't know it yet
- **Architecture pays off** — clean boundaries make month-six changes as cheap as day-one changes
- **Automate the boring parts** — CI/CD from the first commit, deploys are a non-event
- **Documentation is part of the code** — READMEs, docstrings, and deploy notes are written while I build, not after

---

## Contact

- 📫 Email: [geopank55@gmail.com](mailto:geopank55@gmail.com)
- 💬 Telegram: [@geopank55](https://t.me/geopank55)
- 💼 LinkedIn: [georgii-pankratov](https://www.linkedin.com/in/georgii-pankratov/)
