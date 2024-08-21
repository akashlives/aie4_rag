# Run the RAG Assignment

This repository contains the python RAG Assignment for AIEMaker Day 2.

## Prerequisites

-   [Conda](https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html)
-   [Poetry](https://python-poetry.org/docs/#installation) (installation will be handled automatically if not found)

## Makefile Commands

The provided Makefile includes several useful commands for managing the environment and dependencies.

### Variables

-   `CONDA_ENV_NAME`: The name of the Conda environment (default: `aie4`)
-   `CONDA_CMD`: The Conda command (default: `conda`)
-   `ACTIVATE_CMD`: The command to activate the Conda environment (varies based on the operating system)
-   `POETRY_CMD`: The Poetry command (default: `poetry`)

## Setup Instructions

1. **Create the Conda Environment**

    ```sh
    make create-env
    ```

2. **Activate the Conda Environment**

    ```sh
    conda activate aie4
    ```

3. **Install Dependencies**

    You can choose to install dependencies using either Conda or Poetry:

    - Install Poetry:

        ```sh
        make check-poetry
        ```

    - Using Poetry install dependencies:

        ```sh
        make install-deps-poetry
        ```
