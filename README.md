# Sample Python Project with GitHub Actions CI

This project demonstrates a basic GitHub Actions pipeline for Python.

## GitHub Actions Workflow

The workflow is triggered on:
- Push events to `main`
- Pull requests targeting `main`

### What it does:
- Checks out code
- Sets up Python 3.10
- Installs dependencies
- Lints code using `flake8`
- Runs unit tests using `pytest`

## Contributing

To contribute:
1. Fork this repository.
2. Create a branch and push your changes.
3. Create a pull request to `main`.

The GitHub Actions workflow will automatically run and validate your changes.
