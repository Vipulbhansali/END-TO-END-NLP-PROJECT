# PRODUCTION-NLP

## Distributed Training with Ray and PyTorch

### Configuration

- **Scaling**: Distributed training across multiple nodes/workers using Ray.
- **Run Configuration**: Customizable hyperparameters, batch sizes, and epochs.
- **Data Configuration**: Dataset loading with preprocessing; skips redundant steps during training.
- **Checkpoints**: Automatic saving and loading of model states for fault tolerance and training resumption.

### Steps to Run

1. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt




## Configuration
- **Black**: Black is an in-place reformatter that (mostly) adheres to PEP8.
- **isort**: isort sorts and formats import statements inside Python scripts.
- **flake8**: flake8 is a code linter with stylistic conventions that adhere to PEP8.


## Makefile
This project includes a Makefile that helps automate code styling and cleaning tasks. The Makefile defines two primary tasks: `style` and `clean`.

### Prerequisites
Make sure you have the following tools installed:
- `make`: You can install it on Windows using Chocolatey, Git Bash, or Windows Subsystem for Linux (WSL).
- `black`: For code formatting.
- `isort`: For sorting imports.
- `flake8`: For linting code.
- `pyupgrade`: For upgrading syntax for newer versions of Python.

### Makefile Tasks

#### style
The `style` task runs code formatting and linting tools to ensure the code adheres to the specified style guidelines.

#### Tools Used:
- `black`: Formats the code.
- `flake8`: Lints the code.
- `isort`: Sorts imports.
- `pyupgrade`: Upgrades syntax to the latest version of Python.

#### Usage:
```sh
make style


