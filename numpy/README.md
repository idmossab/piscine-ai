# Exercise 00 - Environment Setup

## Check Python version (must be >= 3.9)
python3 --version

## Create a virtual environment named ex00
python3 -m venv ex00

## Activate the virtual environment
source ex00/bin/activate

## Install required packages
pip install numpy jupyter

## Save installed packages
pip freeze > requirements.txt

## Launch Jupyter Notebook on port 8891
jupyter notebook --port=8891

## First notebook cell (Markdown)

### H1 TITLE
#### H2 TITLE

## Second notebook cell (Python)

print("Buy the dip ?")