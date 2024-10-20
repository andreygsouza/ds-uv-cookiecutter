# ds-uv-cookiecutter

My cookiecutter repo for generating python projects using `uv` for package management for data science projects.

## Features

- [uv](https://github.com/astral-sh/uv) for package management
- Pre-commit hooks with [pre-commit](https://pre-commit.com/)
- Linting and formatting [ruff](https://github.com/charliermarsh/ruff) using the following rules:
  - pycodestyle
  - pyflakes
  - pylint
  - isort
  - flake8-bugbear
  - flake8-simplify
  - flake8-comprehensions
  - ruff

- Static type checking with [mypy](https://mypy.readthedocs.io/en/stable/)
- Publishing to [Pypi](https://pypi.org/)
- Testing with [pytest](https://docs.pytest.org/en/7.1.x/)
- Test coverage with [codecov](https://about.codecov.io/)
- Containerization with [Docker](https://www.docker.com/)

## Usage

Make sure the `cookiecutter` package is installed:

```bash
pip install cookiecutter
```

Next, install the template directly from this repo:

```bash
cookiecutter https://github.com/andreygsouza/ds-uv-cookiecutter.git
```

Finally, install the environment and the pre-commit hooks with

```bash
make install
```

## Acknowledgements

This was inspired by the [data science template](https://github.com/vvssttkk/dst) repo by [vvssttkk](https://github.com/vvssttkk) and [uv-cookie](https://github.com/kpeez/uv-cookie) repo by [vvssttkk](https://github.com/kpeez).
I made some modifications to fit my personal use.