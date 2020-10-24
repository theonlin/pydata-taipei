# Preparing Python Environment
## Goal

Perparing work envoronment

## Check points

1. Intsall python
1. How to check the version of python?
1. Establish virtual environment
1. Python package management

## Install Python

### For Windows

Python Download Page: https://www.python.org/downloads/

### For Mac OS
```
$ brew install python
```

### For Linux
```
> sudo apt update
> sudo apt install software-properties-common
> sudo add-apt-respository ppa:deadsnakes/ppa
> sudo apt update
> sudo apt install python3.8
```

## Check python version
```
> python --version
```

## Create virtual environment
```
> python -m venv workshop
> workshop/Script/activate
(workshop) > deactivate
```

## Python package management

### Install Pip
Download get-pip.py (https://bootstrap.pypa.io/get-pip.py)

```
> python get-pip.py
> pip --version
```

Install Package
```
> pip install <package name>
```
