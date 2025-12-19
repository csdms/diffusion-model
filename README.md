# roadshow-diffusion

A model used for teaching in the [CSDMS Roadshow](https://csdms.colorado.edu/wiki/Roadshows).

## Overview

We're going to develop a one-dimensional numerical model of the physical process of diffusion.
We'll use the technique of first experimenting and prototyping the model in a Jupyter notebook,
then we'll convert the notebook to Python source code for more robust use.

### Development plan

Here are the topics we'll cover in order to develop our model.

* Project Jupyter
    * JupyterHub: login to *explore* Hub
    * JupyterLab: show components
    * Notebook: open a new notebook and show basics
* Shell (bash) commands
* Diffusion model in a notebook I
* Intro to Git/GitHub
    * Set up SSH keys
    * Set up a repo for the diffusion model notebook
    * Clone repo to workspace on *explore* Hub
* Export notebook to Python source
* Text editors
* Virtual environments
    * conda
    * venv or virtualenv
* Refactor diffusion model
    * Rename file to diffusion.py to adhere to module naming rules
    * Modularize model script
    * Demonstrate collaborative coding through GitHub PRs
* Unit testing
    * Test-driven development
* Package model
    * Module definition file
    * Basic pyproject.toml file
    * Show how to pip install into a venv
* Documentation
* Diffusion model in a notebook II
    * Import diffusion model from new package
    * Import someone else's diffusion model
* Visualize model output with Jupyter widgets
