# Graphic Statistics Course

This is the Graphic Statistics course from _La Fondation Vallet_ and _Benin Excellence_ `version EEIA2023`

## About Notebooks

The code in this repo shows simple curve plotting examples from the course. 

### Setup:  your environment 
 Step `1`, `2`, `3`, and `4`should be run by everyone

1. Install the correct version of Python: ```sudo apt-get install python3.8-dev```
2. Install python ``venv package``in your system: ```sudo apt install python3.8-venv```
3. then run : ```git clone https://github.com/ML-for-B-E/Statistique-graphique.git```
4. Move to the cloned repository:   ```cd Statistique-graphique```

We assume in the following that you are in the directory ``notebooks``. You can either use `venv` or `pipenv` to start your virtual env.

#### Within venv

- Run the command: ```python3.8 -m venv venv```
- Activate the venv: ```source venv/bin/activate```
- Upgrade pip: ```pip install --upgrade pip```
- Install required packages: ```pip install -r ../requirements/requirements.txt```
- Start your notebook : ```jupyter-notebook```

#### Within pipenv ``pipenv``

- Run the command: ```pipenv --python 3.8```

- In order to install the associated packages on the virtual env, run: ```pipenv install -r ../requirements/requirements.txt``` or ```pipenv install```, if you have `Pipfile` files inside the directory.

- Then: ```pipenv shell```

- Finally, run the following to start your notebook:``` jupyter-notebook```


- Once started, you should open ``Boxplot_Scatterplot.ipynb`` and ``ml_graphics_course.ipynb`` to test the examples.

P.S.: ``pipenv`` utilities can be installed with ```pip install --user pipenv ```. More information about ``pipenv`` can be found [here](https://pipenv.pypa.io/en/latest/).

### Exit the Virtual Env
- Run (for ```pipenv```) ``exit``, and ``deactivate`` or ``source deactivate`` (for ``venv``)