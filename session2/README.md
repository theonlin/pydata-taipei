# Jupyter Notebook & Requests

## Goal

Playing with python via Jypyter Notebook

## Check points

1. Install Jupyter Notebook
1. Create your first python3 notebook
1. Install  requests
1. Download real world data via requests

## Up & Run Jupyter Notebook

### Install Jupyter Notebook in virutal environment

```shell
> python -m venv workshop
> . workshop/bin/activate
(workshop) > pip install jupyter
```

### Running Jupyter Notebook

```shell
> . workshop/bin/activate
(workshop) > jupyter notebook
```

Looking for the information like

```shell
    To access the notebook, open this file in a browser:
        file:///C:/Users/User/AppData/Roaming/jupyter/runtime/nbserver-26412-open.html
    Or copy and paste one of these URLs:
        http://localhost:8888/?token=8b885b071a3a1d9713dbf9b9cd6e8c2eafd3813db7cb7711
     or http://127.0.0.1:8888/?token=8b885b071a3a1d9713dbf9b9cd6e8c2eafd3813db7cb7711
```

## Create python3 notebook

Live Demo

## Install  requests

```shell
> pip install requests
```

## Download real world data via requests

### Data Source: Taiwan Stock Exchange Crawler

github: https://github.com/Asoul/tsec

```python
import requests

# Download csv file
res = requests.get("https://raw.githubusercontent.com/Asoul/tsec/master/data/0050.csv")

# Write to local file
with open("data/0052.csv", "wb") as outfile:
    outfile.write(res.text.encode(encoding="utf-8"))
```

## (Bounus) read csv file
