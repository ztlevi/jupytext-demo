# Jupytext

Whenever you save your jupyter notebook, the content of the notebook will be written to the script.

## You can simply use `pyproject.toml`

``` toml
[tool.jupytext]
# Always pair ipynb notebooks to py:percent files
formats = ["ipynb", "py:percent"]
```

## Use the jupyter extension to bind the notebook with the script

https://github.com/mwouts/jupytext/blob/main/docs/install.md#Jupytext-menu-in-Jupyter-Notebook

```sh
jupyter labextension uninstall jupyterlab-jupytext
```
