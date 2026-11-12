# UnitTest

Python unit testing using pytest and GitHub Actions. This repository contains a
small Python calculator project with addition, subtraction, multiplication,
division, and exponentiation, covered by automated tests.

## Requirements

- Python 3.12 or later
- pytest

## Run the tests

Install pytest and run the test suite from the project directory:

```bash
python -m pip install pytest
python -m pytest -v
```

## GitHub Actions

The workflow in `.github/workflows/python-tests.yml` runs the pytest suite on
pushes and pull requests targeting the `main` branch.
