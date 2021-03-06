# Handwritten Digit Recogniser
This is a project designed as an introduction to Machine Learning, GUI programming, and virtual environments in Python using PyTorch and PyQt5. We make use of the MNIST dataset to train a model that recognises hand-drawn digits from 0-9.

[A build of the program can be found here](https://drive.google.com/file/d/1VFNP28p9HTdPhUbAlT9KdHUDE8MV67dP/view?usp=sharing)

## Features

  * Built-in Canvas
  * MNIST Download
  * Model Training
  * Model Selection

## Installation

### Conda

Create a virtual environment using conda with the following command

```
conda create -p ./path/to/virtual/environmentName
```

Place this repository into the root of the venv using ```git clone``` or by downloading it directly

Navigate to the root of the venv and activate it

```
cd ./path/to/virtual/environmentName
environmentName> conda activate environmentName
```

Navigate into the repo folder

```
environmentName> cd project-1-team_30
```

Install requirements using pip

```
environmentName\project-1-team_30> pip install -r requirements.txt
```

Navigate to the scripts folder

```
environmentName\project-1-team_30> cd scripts
```

Run the program 

```
environmentName\project-1-team_30> python main.py
```

### Python venv

Create a virtual environment using Python with the following command

```
python -m venv ./path/to/virtual/environment
```

Place this repository into the root of the venv using ```git clone``` or by downloading it directly

Navigate to the root of the venv

```
cd ./path/to/virtual/environment
```

Navigate to the Scripts directory and activate the venv

```
venv> cd Scripts
venv\Scripts> activate
```

Navigate back to the venv root and install the requirements

```
venv\Scripts> cd ..
venv> cd project-1-team-30
venv\project-1-team-30> pip install -r requirements.txt
```

Navigate to the repo's scripts folder

```
venv\project-1-team_30> cd scripts
```

Run the program 

```
venv\project-1-team_30\scripts> python main.py
```
