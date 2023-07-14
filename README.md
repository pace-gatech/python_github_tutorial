#  github_tutorial 

## Overview

This is a basic github repository to show a Github structure, docstrings, and test codes via pytest.


## Documentation

To be added in the future.


## Installation

The  github_tutorial package dependencies can be installed via conda, and this package tagged in conda via pip install:

Create and install conda package:

`cd path_to_first_github_tutorial_dirctory_with_environment_yml_file`

`conda env create -f environment.yml`

`conda activate github_tutorial`

`pip install -e .`

Note: If you update the conda package, you may have to redo the pip install.  Without doing this, it may allow incompatable versions of the dependencies to be installed, etc.:

`pip install -e .`

## Run the example

This is an example of the supplimentary functions in the utils directory (github_tutorial/utils) and the main function in the main_functions directory (github_tutorial/main_functions).

The example is located here 'examples_to_run/examples.py'. The instructions to run it are provided below:

`cd examples_to_run`

`python examples.py`

## Run the interactive example in Visual Studios Code (VScode) 

This is the same example but running it as an interactive job (i.e., like a Jupyter notebook). The example is located here 'examples_to_run/interactive_examples.py'.  

When using Visual Studios Code (VScode), the '# %%' above each section makes it a cell, which can be run individually by holding shift and pressing enter.


## Run the test cases using pytest

Each python file has it's own test functions scripts located here 'github_tutorial/tests', which are used to ensure proper functionallity when making changes to the code, or if python dependancies alter how some functions behave.

Run all the tests:

`cd github_tutorial/tests`

`pytest`

Run individual test on 'test_math.py':

`cd github_tutorial/tests`

`pytest test_math.py`

Run individual test on 'test_main_functions.py':

`cd github_tutorial/tests`

`pytest test_main_functions.py`

