# Computational P Widths

This is a repository for computing p-widths of Riemannian manifolds. 

## Installation

We use uv for python package management. To install, first install uv [here](https://docs.astral.sh/uv/getting-started/installation).

Then, install the dependencies with
```bash
uv sync
```

For development (including testing), install with:
```bash
uv sync --extra dev
```

## Usage

To run a script, use 
```bash
uv run python {path_to_script}/script.py
```

Example:
```bash
uv run python src/main.py
```

## Testing

To run tests:
```bash
uv run pytest
```

To run tests with coverage:
```bash
uv run pytest --cov=src
```

To run a specific test file:
```bash
uv run pytest tests/test_basic.py
```
