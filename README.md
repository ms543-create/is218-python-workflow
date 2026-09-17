# IS218 Python Workflow

This project is for practicing Python development, pytest testing, and using GitHub issues with Git commits for IS218.

Repository: https://github.com/ms543-create/is218-python-workflow

## Project Files

- `README.md` - Contains information and instructions for the project.
- `.gitignore` - Prevents the virtual environment and generated cache files from being tracked by Git.
- `requirements.txt` - Contains the required pytest version.
- `app.py` - Contains the `add` function.
- `tests/test_app.py` - Contains tests for the `add` function.

## Python Environment

This project was tested with Python 3.12.14.

## Setup

Create the virtual environment:

```bash
python3 -m venv .venv
```

Activate it:

```bash
source .venv/bin/activate
```

Install the requirements:

```bash
python -m pip install -r requirements.txt
```

## Reactivating the Environment

When returning to the project in a new terminal session, activate the existing environment instead of creating it again:

```bash
source .venv/bin/activate
```

## Running Tests

Run all tests from the repository root:

```bash
python -m pytest
```

The project currently has 2 passing tests.

## Ignored Files

The following files and directories are ignored by Git:

- `.venv/`
- `__pycache__/`
- `*.py[cod]`
- `.pytest_cache/`