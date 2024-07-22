# PRODUCTION-NLP

## Configuration
- **Black**: Black is an in-place reformatter that (mostly) adheres to PEP8.
- **isort**: isort sorts and formats import statements inside Python scripts.
- **flake8**: flake8 is a code linter with stylistic conventions that adhere to PEP8.


## Makefile
This project includes a Makefile that helps automate code styling and cleaning tasks. The Makefile defines two primary tasks: `style` and `clean`.

## Prerequisites
Make sure you have the following tools installed:
- `make`: You can install it on Windows using Chocolatey, Git Bash, or Windows Subsystem for Linux (WSL).
- `black`: For code formatting.
- `isort`: For sorting imports.
- `flake8`: For linting code.
- `pyupgrade`: For upgrading syntax for newer versions of Python.

## Makefile Tasks

### style
The `style` task runs code formatting and linting tools to ensure the code adheres to the specified style guidelines.

#### Tools Used:
- `black`: Formats the code.
- `flake8`: Lints the code.
- `isort`: Sorts imports.
- `pyupgrade`: Upgrades syntax to the latest version of Python.

#### Usage:
```sh
make style


## Pre-commit Hooks

This project uses pre-commit hooks to ensure code quality and maintain project hygiene. These hooks run automatically before each commit to check for and fix common issues.

### Installed Hooks

- **Trailing Whitespace**: Removes trailing whitespace from all files.
- **End of File Fixer**: Ensures all files end with a newline.
- **Check Merge Conflict**: Checks for unresolved merge conflict markers.
- **Check YAML**: Validates YAML files for syntax errors.
- **Check Added Large Files**: Checks for files larger than 1000 KB (excluding `notebooks` directory).
- **Check YAML (mkdocs.yml excluded)**: Excludes validation for `mkdocs.yml`.
- **Clean**: Runs `make clean` to remove unnecessary files.

### Configuration

The pre-commit hooks are configured in the `.pre-commit-config.yaml` file.

### Setup

1. **Install Pre-commit**:
   ```sh
   pip install pre-commit
