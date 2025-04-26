# RAGS

[![Release](https://img.shields.io/github/v/release/praveenhm/rags)](https://img.shields.io/github/v/release/praveenhm/rags)
[![Build status](https://img.shields.io/github/actions/workflow/status/praveenhm/rags/main.yml?branch=main)](https://github.com/praveenhm/rags/actions/workflows/main.yml?query=branch%3Amain)
[![codecov](https://codecov.io/gh/praveenhm/rags/branch/main/graph/badge.svg)](https://codecov.io/gh/praveenhm/rags)
[![License](https://img.shields.io/github/license/praveenhm/rags)](https://img.shields.io/github/license/praveenhm/rags)

A Python project for RAGs (Retrieval-Augmented Generation) implementation.

- **Github repository**: <https://github.com/praveenhm/rags/>
- **Documentation** <https://praveenhm.github.io/rags/>
- **Deepwiki docs** <https://deepwiki.com/praveenhm/rags/1-overview>

## Features

- Modern Python development with Python 3.12
- Full type checking with mypy
- Code quality with ruff
- Comprehensive test suite with pytest
- Dev containers for consistent development environments
- CI/CD setup with GitHub Actions
- SSH key forwarding in dev containers for seamless Git authentication
- Cursor rules for consistent development practices

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

### Dev Container Configuration

This project includes a custom dev container setup with:

- Python 3.12 base image
- SSH key forwarding for GitHub authentication
- Pre-configured Git integration

For details on the SSH setup, see the `.devcontainer/devcontainer.json` file.

### Cursor Rules

The project includes the following Cursor rules to guide development:

- **Project Structure**: Overview of the codebase organization
- **Development Workflow**: Standard processes for developing the project
- **Code Standards**: Coding conventions and quality standards
- **Environment Setup**: Python version and environment configuration
- **Package Management**: Using uv for package management
- **Dev Container Setup**: SSH configuration for containers

These rules help maintain consistent practices across the codebase.

## Project Setup

This project was created using the [fpgmaas/cookiecutter-uv](https://github.com/fpgmaas/cookiecutter-uv) template. For original setup instructions, see [COOKIECUTTER_SETUP.md](COOKIECUTTER_SETUP.md).
