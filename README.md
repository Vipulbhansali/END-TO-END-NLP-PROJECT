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


