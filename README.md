# software_projects

Docs, tools, templates for projects following good practices for software development

## Templates

In this README.md you can find the general instructions, but, in each branch, you will find the full folder structure and content. So far, these are the projects mapped 

### A Python Package
- [project-structure/python-package](https://github.com/IteraLabs/software_projects/tree/project-structure/python-package)

### A Rust crate

- Coming soon...

# Python Package

To build a project that is a python package.

## Folder structure

```
| [root]
|
|── examples
|  ├── example_1.py
|
|── files
|  ├── datasets
|    ├── data.csv 
|
├── src
|  ├── python_package
|    ├── submodule_a
|      ├── __init__.py
|      ├── functions_a.py
|    ├── submodule_b
|      ├── __init__.py
|      ├── functions_b.py
|
├── tests
|  ├── connectivity
|    ├── test_1.py
|    ├── test_2.py
|
├── .pre-commit-config.yaml
├── CONTRIBUTING.md
├── README.md
├── LICENSE
├── pyproject.toml
├── requirements.txt
```

## References

- Python packaging: https://packaging.python.org/en/latest/
- markdown syntax: https://www.markdownguide.org/basic-syntax/
- toml syntax: https://toml.io/en/
- pre-commit: https://pre-commit.com/index.html
- pyproject.toml: https://packaging.python.org/en/latest/guides/writing-pyproject-toml/
- requirements.txt : https://packaging.python.org/en/latest/tutorials/installing-packages/#requirements-files
- Python Modules / Subfolders: https://docs.python.org/3.11/tutorial/modules.html

## Branched Example

Take a look into the following branch for a project-template with the corresponding folder structure

- [project-structure/python-package](https://github.com/IteraLabs/software_projects/tree/project-structure/python-package)

