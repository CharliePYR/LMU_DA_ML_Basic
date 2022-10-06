# LMU_DA_ML_Basic

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/fuenfundachtzig/LMU_DA_ML_Basic/HEAD?filepath=notebooks%2FPythonDA_ML_Basic.ipynb)

## Material for the course on data analysis and machine learning at the Ludwig-Maximilians-Universität München (LMU Munich).

Start with notebook **[PythonDA_ML_Basic.ipynb](notebooks/PythonDA_ML_Basic.ipynb)**.


## Technical hints

### How to avoid output in jupyter-notebooks being added to git
Installation:
* install `pre-commit` from (https://pre-commit.com/) with `pip install pre-commit`
* run `pre-commit install` in repository
Usage:
* when you `git commit` notebooks with output cells to git, `jupyter-notebook-cleanup` will report `Failed` and remove the output from the notebook. In this case, just `git add -u` the changed files again and rerun `git commit`.

### Repository
* [here in github](https://github.com/fuenfundachtzig/LMU_DA_ML_Basic)