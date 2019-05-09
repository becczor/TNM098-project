# TNM098-project
Project in Advanced Visual Data Analysis spring 2019

## Jupyter Notebook

### Installing
1. Install Python 3.5 or greater.

2. In the folder containing this project, create a virtual environment to protect your own configurations by running `python -m venv env`

3. Activate the virtual environment by running `env\Scripts\activate` for Windows, and `source env/bin/activate` for Linux. Make sure you do all following installations within the virutal environment, marked by `(env)` in the beginning of the terminal prompt.

    1. (To disable the virtual environment when you are finished, run `deactivate`)

4. Run `python -m pip install --upgrade pip` to update pip to newest version.

5. Install jupyter. For Linux, run `python3 -m pip install jupyter`. For Windows, run `python -m pip install jupyter`.

6. Run `pip install python-nvd3` to install the Python shell from nvd3.

7. Run `pip install ipywidgets` and `jupyter nbextension enable --py widgetsnbextension` to activate the widgets.

8. Run `pip install plotly` to install Plotly for graph plots.

9. Run `pip install networkx` to install Networkx.

10. Run `pip install matplotlib` to intstall Matplotlib.

11. Run `pip install scipy` to install SciPy.

12. The package visJS2Jupyter is unfortunately not available to install from `pip`, so instead, run `python \visJS2Jupyter\setup.py install` from inside the project folder.

### Running 
Run `jupyter notebook project.ipynb`. The notebook will open automatically in your web browser.





