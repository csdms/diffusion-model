# diffusion-model

A numerical model used in the [CSDMS Roadshow](https://csdms.colorado.edu/wiki/Roadshows).

## Overview

We will develop a one-dimensional numerical model of the physical process of diffusion.
We'll use the forward in time, centered in space (FTCS) finite difference method to solve the diffusion equation,
and we'll apply Dirichlet boundary conditions.

We'll prototype the model in a Jupyter notebook,
then we'll convert the notebook to Python source code--first to a script, then to a packaged module--for more robust use.

Along the way, we'll use the development of the model to explore:

* concepts in Python (imports, loops, conditionals, arrays, functions)
* software tools (shell, Git, conda)
* software development practices (unit testing, refactoring, documentation, packaging)

Although the model is simple,
the topics we cover in developing it are reusable.

### Development plan

Here are the topics we'll cover to develop our model.

* Project Jupyter ([Reference](https://github.com/csdms/ivy/blob/main/lessons/jupyter/index.md))
    * JupyterHub: login to the *explore* Hub
    * JupyterLab: show components
    * Notebook: add commands in a new notebook
* Shell (bash) commands ([Reference](https://github.com/csdms/ivy/blob/main/lessons/shell/index.md))
* Building a diffusion model in a notebook ([Reference](https://github.com/csdms/ivy/blob/main/lessons/python/index.ipynb))
    * Python libraries
    * NumPy arrays
    * Loops
    * Conditionals
    * Basic plotting with Matplotlib
* Version control with Git and GitHub ([Reference](https://github.com/csdms/ivy/blob/main/lessons/git/index.md))
    * Set up SSH keys
    * Set up a repository for the diffusion model notebook
    * Clone the repository to the *explore* Hub
* Exporting a notebook to Python source code
* Text editors and IDEs ([Reference](https://github.com/csdms/ivy/blob/main/lessons/editors/index.md))
* Virtual environments ([Reference](https://github.com/csdms/ivy/blob/main/lessons/conda/environments.ipynb))
    * Use `conda`
    * Use `venv` or `virtualenv`
* Refactoring the diffusion model
    * Modularize model script with functions
	* Create a feature branch with Git
    * Organize changes with a pull request
* Unit testing ([Reference](https://github.com/csdms/ivy/blob/main/lessons/best-practices/unit-testing.md))
* Linting the model code
* Packaging the model ([Reference](https://github.com/csdms/ivy/blob/main/lessons/python/modules.md))
    * Write a basic `pyproject.toml` file
    * Install model into a virtual environment with `pip`

Here are a few more topics we can cover, given time.

* Use the diffusion model
    * Import the diffusion model from new package
    * Try to import someone else's diffusion model
* Documenting the model
    * Docstrings
    * Sphinx documentation system
* Visualize model output with Jupyter widgets

## Acknowledgments

This work is supported by the U.S. National Science Foundation under
Award No. [2148762](https://www.nsf.gov/awardsearch/showAward?AWD_ID=2148762),
*Collaborative Research: Facility: CSDMS: Engaging a thriving community of practice in Earth-surface dynamics*.
