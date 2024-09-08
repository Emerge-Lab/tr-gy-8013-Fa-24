# tr-gy-8013-Fa-24
Course material for Fall 24 Deep Learning for Urban Systems Course

# Setup procedure
We use conda to manage the dependencies. First, make sure you have conda installed. If you don't have conda installed, you can install it by following the instructions [here](https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html). Note, if you're feeling fancy and want to make things faster, you can instead install micromamba by following the instructions [here](https://mamba.readthedocs.io/en/latest/user_guide/micromamba.html). This is basically identical to Conda but faster. [UV](https://github.com/astral-sh/uv) is also an increasingly popular choice; we won't be using it for this course but you're welcome to try it out. It's fast due to being written in Rust and is pretty neat. Reminder, everything by default will assume you're using Conda but it shouldn't be too much work to use one of the other package managers instead and long-term might be faster.

To create the environment, you can run the following command:
```bash
conda env create -f environment.yml
```
Conda creates separated virtual environments, each of which contain the dependencies for a specific project. To activate the virtual environment, you can run the following command:
```bash
conda activate dl_urban
```
**Note that you always have to run this whenever you start up programming if the environment isn't already activated.**
Next, we want to install all the dependencies. To do this, you can run the following command:
```bash
pip install -r requirements.txt
```

# running the examples
Most of the homeworks and lectures are written in jupyter. To run the jupyter notebooks, you can launch them using the following command:
```bash
jupyter notebook
```
Some folks like jupyter lab, which is a more modern version of jupyter notebook. To run jupyter lab, you can launch it using the following command:
```bash
jupyter lab
```
This will open a new tab in your browser where you can navigate to the homeworks and lectures. Personally, I just use the jupyter notebook extension in vscode to manage everything. 

