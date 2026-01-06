# roadshow-diffusion

A numerical finite-difference model used for teaching in the [CSDMS Roadshow](https://csdms.colorado.edu/wiki/Roadshows).

## Overview

We will develop a one-dimensional numerical model of the physical process of diffusion.

We'll prototype the model in a Jupyter notebook,
then we'll convert the notebook to Python source code--first to a script, then to a packaged module--for more robust use.

Along the way, we'll use the development of the model to explore:

* concepts in Python (imports, loops, conditionals, arrays, functions)
* software tools (shell, Git, conda)
* software development practices (unit testing, refactoring, documentation, packaging)

Although the model is simple,
the topics we cover in developing it can be reused.

### Development plan

Here are the topics we'll cover to develop our model.

* Project Jupyter ([Reference](https://github.com/csdms/ivy/blob/main/lessons/jupyter/index.md))
    * Overview
    * JupyterHub: login to the *explore* Hub
    * JupyterLab: show components
    * Notebook: open a new notebook and show basics
* Shell (bash) commands ([Reference](https://github.com/csdms/ivy/blob/main/lessons/shell/index.md))
* Diffusion model in a notebook I
* Intro to Git/GitHub ([Reference](https://github.com/csdms/ivy/blob/main/lessons/git/index.md))
    * Set up SSH keys
    * Set up a repo for the diffusion model notebook
    * Clone repo to workspace on the *explore* Hub
* Export notebook to Python source
* Text editors and IDEs ([Reference](https://github.com/csdms/ivy/blob/main/lessons/editors/index.md))
* Virtual environments ([Reference](https://github.com/csdms/ivy/blob/main/lessons/conda/environments.ipynb))
    * conda
    * venv or virtualenv
* Refactor the diffusion model
    * Rename file to diffusion.py to adhere to module naming rules
    * Modularize model script
    * Demonstrate collaborative coding through GitHub PRs
* Unit testing ([Reference](https://github.com/csdms/ivy/blob/main/lessons/best-practices/unit-testing.md))
    * Test-driven development
* Package model ([Reference](https://github.com/csdms/ivy/blob/main/lessons/python/modules.md))
    * Module definition file
    * Basic pyproject.toml file
    * Show how to pip install into a venv
* Documentation
* Diffusion model in a notebook II
    * Import diffusion model from new package
    * Import someone else's diffusion model
* Visualize model output with Jupyter widgets
