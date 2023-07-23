# Course Graph Notebook

The code in this directory shows a simple curve plotting example from the course.

## Setup 1:  your environment

- Install the correct version of Python: ```sudo apt-get install python3.8-dev```
- Install python ``venv package``in your system: ```sudo apt install python3.8-venv```
- Move to the cloned repository:   ```cd <foldername>```
- Run the command: ```python3.8 -m venv venv```
- Activate the venv: ```source venv/bin/activate```
- Upgrade pip: ```pip install --upgrade pip```
- Install required packages: ```pip install -r requirements.txt```
- Start your notebook : ```jupyter-notebook```

## Setup 2: Install and Run the Example using ``pipenv``

- Use the following command to activate the virtual env: ```pipenv shell ```

- In order to install the associated packages on the virtual env, run: ```pipenv install``` or ```pipenv install requirements.txt```

- Finally, run the following to start your notebook:``` jupyter-notebook```


- Once started, you should open ``ml_graphics_course.ipynb`` to test the example.

P.S.: ``pipenv`` utilities can be installed with ```pip install --user pipenv ```. More information about ``pipenv`` can be found [here](https://pipenv.pypa.io/en/latest/).

## Exit the Virtual Env
- Run (for ```pipenv```) ``exit``