# brainCodeCamp

## Build Instructions

    # using python >=3.10
    pip install jupyter-book
    jupyter-book clean .
    jupyter-book build .

## Build Instructions Poetry

    # install poetry https://python-poetry.org/docs/
    poetry install
    poetry run jupyter-book clean .
    poetry run jupyter-book build .

## Test Locally in VS Code

1. Change directory to \_build/html
   cd \_build/html
2. Right click index.html and select Open with Live Server
