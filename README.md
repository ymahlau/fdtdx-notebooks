# Container for FDTDX Notebooks

# Installation
You can install the necessary requiremements for this repository with:
```
pip install -e .
```
If you want to add a notebook that needs another library, which is currently not included please add them to the dependencies in the pyproject.toml. If you want to develop notebooks with cuda support please install additionally:
```
pip install jax[cuda12]
```

