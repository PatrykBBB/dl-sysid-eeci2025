# Deep Learning for System Identification 
## Milano, June 30 - July 4, 2025
This repository contains the material for the EECI course on *Deep Learning for System Identification*

# Program
The Program of the course can be found in the document [Program.pdf](Program.pdf)

# Lessons
Slides of the lessons can be found in the folder [lessons](lessons)

# Exercises

Jupyter notebooks related to the exercise sessions can be found in the folder [exercises](exercises)

# Software requirements 
We recommend setting up a Conda virtual environment with Python and the required packages for this course. 

First, follow the official [Anaconda installation guide](https://www.anaconda.com/docs/getting-started/anaconda/install) for your operating system. 
Once Anaconda is installed, navigate to the project's root directory, open a terminal and run the following commands:

```bash
conda create --name eeci python=3.12
conda activate eeci
pip install -r requirements.txt
```

This will create a virtual environment named eeci and install all necessary dependencies listed in [requirements.txt](requirements.txt).

To activate the environment at any time, use:
```bash
conda activate eeci
```

All course examples are provided as Jupyter Notebooks. To launch the notebook interface, navigate to the folder containing the .ipynb file you wish to open, then run:
```bash
jupyter notebook
```
Advanced user may opt for alternative setups such as venv, Docker, and different development environments like VSCode, PyCharm, etc., provided all required dependencies are installed and notebooks run as expected.

