imdb-eda
========

Some EDA (Exploratory Data Analysis) on IMDB database.

See the [notebook](notebook.ipynb).

## Running locally

### Downloading IMDb data

First, download the data required for the notebook to run:

```bash
cd data/
wget -i urls.txt
```

### Setting up Python

To setup development environment, run the following commands:

```bash
python3 -m venv venv
source venv/bin/activate
pip3 install -r requirements.txt
```

### Running the notebook

To open the Jupyter notebook, run:

```bash
jupyter-notebook notebook.ipynb
```

