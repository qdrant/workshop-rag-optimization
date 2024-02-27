# rag-optimization-workshop

This repository contains the materials for an RAG optimization workshop using Qdrant as a vector database.
It consists of Jupyter notebooks that guide you step-by-step in various optimizations and tweaks.

## Prerequisites

Please clone the repository and install all the dependencies to run the notebooks.

```bash
git clone https://github.com/qdrant/workshop-rag-optimization.git
```

### Poetry

This project uses [Poetry](https://python-poetry.org/) to manage its dependencies. You can install it by following the instructions on the [official website](https://python-poetry.org/docs/#installation).
Once you have it, the dependencies can be installed by running:

```bash
cd workshop-rag-optimization
poetry install --no-root
poetry shell
```

### Pip

If you don't want to use Poetry, you can install the dependencies using pip:

```bash
pip install -r requirements.txt
```

## Running the notebooks

Once all the dependencies are installed, Jupyter notebook might be started by running the following command:

```bash
jupyter notebook
```

The default browser should open automatically.
