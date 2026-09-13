# RESET 15™ App

Experiencia digital fitness para diagnosticar bloqueadores, priorizar acciones y acompañar un plan de 30 días.

## Stack

- React 18 + Vite 6 + GSAP
- Python 3.12 + FastAPI
- PostgreSQL + Redis (preparados en Docker Compose)
- Docker

## Desarrollo local

```bash
npm --prefix apps/web install
npm run dev
```

API:

```bash
python -m venv .venv
pip install -r apps/api/requirements.txt
uvicorn apps.api.src.main:app --reload
```

## Dirección visual

El home usa una secuencia de encendido, órbitas energéticas, partículas Canvas y animación GSAP. Incluye `prefers-reduced-motion` y un layout adaptable a móvil.
