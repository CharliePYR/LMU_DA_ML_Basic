# LMU_DA_ML_Basic

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/fuenfundachtzig/LMU_DA_ML_Basic/HEAD?filepath=notebooks%2FPythonDA_ML_Basic.ipynb)

## Material for the course on data analysis and machine learning at the Ludwig-Maximilians-Universität München (LMU Munich).

Start with **[PythonDA_ML_Basic.ipynb](PythonDA_ML_Basic.ipynb)**


## Technical hints

### How to avoid output in jupyter-notebooks being added to git
* install `pre-commit` from (https://pre-commit.com/) with `pip install pre-commit`
* run `pre-commit install` in repository
* when `jupyter-notebook-cleanup` reports `Failed` on `git commit` (it will whenever output has been removed), `git add` the changed files again and rerun `git commit`