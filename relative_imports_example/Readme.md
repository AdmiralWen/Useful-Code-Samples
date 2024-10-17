# Relative Imports Example

Demonstrates directory structure for loading custom .py modules in a custom Jupyter environment. Modules are in a separate directory from the notebook where they're imported from.

### Directory Structure

relative_imports_example
|--notebooks
|  |--my_ntbk.ipynb
|--pkg
|  |--sub1
|  |  |--__init__.py
|  |  |--module1.py
|  |--sub2
|  |  |--__init__.py
|  |  |--module2.py

The `module1` and `module2` files can import from each other, while the overall `pkg` is imported by the notebook under `notebooks`.
