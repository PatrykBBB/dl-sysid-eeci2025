# Deep Learning for System Identification - Milano, June 30 - July 4, 2025
This repository contains the material for the EECI course on "Deep Learning for System Identification"

# Program
The Program of the course can be found in the document [Program.pdf](Program.pdf)

# Lessons
Slides of the lessons can be found in the folder [lessons](lessons)

# Exercises

Jupyter notebooks related to the exercise sessions can be found in the folder [exercises](exercises)

# Software requirements 

We suggest creating a conda virtual environment with Python and all the [required packages](requirements.txt) for the course. Follow the [official instructions](https://www.anaconda.com/docs/getting-started/anaconda/install) to install Anaconda on your system.
Then, use the following commands:

``
conda create --name eeci python=3.12
conda activate eeci
pip install -r requirements.txt
``

to create the virtual environment. Activate the environment with the commands:

``
conda activate eeci
``

The provided examples are all based on jupyter notebook. Type the following command from the folder that contains the notebook file (.ipynb extension) you want to run:
``
jupyter notebook
``
Advanced user may opt for other installation strategies (venv, docker, ...) and development environments (VSCode, PyCharm, ...).
