# RAGS

[![Release](https://img.shields.io/github/v/release/praveenhm/rags)](https://img.shields.io/github/v/release/praveenhm/rags)
[![Build status](https://img.shields.io/github/actions/workflow/status/praveenhm/rags/main.yml?branch=main)](https://github.com/praveenhm/rags/actions/workflows/main.yml?query=branch%3Amain)
[![codecov](https://codecov.io/gh/praveenhm/rags/branch/main/graph/badge.svg)](https://codecov.io/gh/praveenhm/rags)
[![License](https://img.shields.io/github/license/praveenhm/rags)](https://img.shields.io/github/license/praveenhm/rags)

A Python project for RAGs (Retrieval-Augmented Generation) implementation.

- **Github repository**: <https://github.com/praveenhm/rags/>
- **Documentation** <https://praveenhm.github.io/rags/>

## Features

- Modern Python development with Python 3.12
- Full type checking with mypy
- Code quality with ruff
- Comprehensive test suite with pytest
- Dev containers for consistent development environments
- CI/CD setup with GitHub Actions

## Installation

```bash
pip install rags
```

Or with uv (recommended):

```bash
uv add rags
```

## Quick Start

```python
from rags.foo import foo

result = foo("Hello, world!")
print(result)  # Outputs: Hello, world!
```

## Development

This project uses uv for package management and virtual environments. To set up the development environment:

```bash
make install
```

To run tests:

```bash
make test
```

To check code quality:

```bash
make check
```

## Project Setup

This project was created using the [fpgmaas/cookiecutter-uv](https://github.com/fpgmaas/cookiecutter-uv) template. For original setup instructions, see [COOKIECUTTER_SETUP.md](COOKIECUTTER_SETUP.md).
