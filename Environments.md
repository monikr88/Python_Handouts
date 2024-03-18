# Creating an env

```python
# Conda
conda env create --name new_env

# Python
py -m venv test_env

```

# Cleaning an env

```python
pip freeze > to_uninstall.txt     
pip uninstall -y -r to_uninstall.txt



pip freeze > req.txt

```
