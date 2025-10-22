# Computational P Widths

This is a repository for computing p-widths of Riemannian manifolds. 

Do to simplicity, the first manifolds we will investigate are the Tori, i.e. quotients of R^n by lattices, and spheres S^n, for n >= 2.

## Installation

We use uv for python package management. To install, first install uv [here](https://docs.astral.sh/uv/getting-started/installation).

Then, install the dependencies with
```bash
uv sync
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
