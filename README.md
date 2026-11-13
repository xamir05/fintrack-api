# fintrack-api

API de finanzas personales construida con FastAPI.

## Objetivos

- Gestionar ingresos, gastos y categorías.
- Mantener calidad de código desde el primer commit (Ruff, pre-commit y tests).

## Requisitos

- Python 3.12 o superior
- uv (https://docs.astral.sh/uv/)

## Cómo ejecutarlo

    uv sync
    uv run fastapi dev

La documentación interactiva queda en http://127.0.0.1:8000/docs

## Tests

    uv run pytest
