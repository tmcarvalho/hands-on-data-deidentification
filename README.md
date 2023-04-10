## Hands on data de-identification

This course covers the de-identification process which aims to protect personal information while maintaining data utility. The program includes:

1) Introduction to Python
2) Introduction to data privacy
3) Predictive modeling
4) Privacy-preserving techniques
5) Training
6) Current directions on data privacy

All sessions will be demonstrated through python and using a data set about [students performance](https://archive.ics.uci.edu/ml/datasets/student+performance) in high school.


### Prerequisites
For the entire experiments, I will be using a Jupyter Notebook.

Requirements:
```
python >= 3.8
```

I use [Pipenv](https://pipenv-fork.readthedocs.io/en/latest/basics.html) virtualenv management tool for packaging.

The recommended way to install pipenv is to install from pypi using pip.
```
pip install pipenv
```

You should follow the instructions below to create a new environment, install the dependencies and activate the environment.
````
cd myproject
pipenv install
pipenv shell
````

For the jupyter notebook, you should first install it and then launch it.
````
pipenv install jupyter
pipenv run jupyter notebook
````
