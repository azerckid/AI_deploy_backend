# Deployment

Add your description here

## Requirements

- Python >= 3.13
- uv (Python package manager)

## Installation

This project uses `uv` for dependency management. To install dependencies:

```bash
uv sync
```

## Running the Application

To run the FastAPI application:

```bash
uv run uvicorn deployment.main:app --reload
```

Or use the uv run command directly:

```bash
uv run python -m deployment.main
```

## Development

The project uses `uv` for managing dependencies and virtual environments. The virtual environment is automatically created in `.venv` when you run `uv sync`.

