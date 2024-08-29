# PRODUCTION-NLP

## Training the Model

We are training a machine learning model using a custom training script with configurable parameters. The training process is defined by setting an experiment name, specifying the dataset location, and providing training loop configurations such as dropout probability, learning rate, and learning rate scheduling. The training is executed with specified resource allocations like CPU, GPU, and batch size, and the results are saved for further analysis.

## Hyperparameter Tuning

We are performing hyperparameter tuning on a machine learning model using a custom tuning script built with Python. The process is powered by Ray Tune with Hyperopt integration to efficiently explore and optimize hyperparameters. We set an experiment name, specify the dataset location, and define initial parameters, including training loop configurations like dropout probability and learning rate. Multiple runs and worker configurations are used to optimize the model's performance. The results of the tuning process are saved for further analysis, with the script leveraging both CPU and GPU resources for efficient processing.

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


