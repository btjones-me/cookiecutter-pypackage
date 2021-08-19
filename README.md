# Cookiecutter PyPackage

![Python Package](https://github.com/btjones-me/cookiecutter-pypackage/workflows/Python%20package/badge.svg)

Cookiecutter template for a Python package.

* GitHub repo: https://github.com/btjones-me/cookiecutter-pypackage/
* Free software: BSD license (this needs to be reviewed)

# Features

* Makefile for orchestrating
* Testing setup with `pytest`
* Linting setup with `flake8`, `isort` and `black`
* GitHub Actions: Ready for Continuous Integration testing with GitHub Actions
* Tox testing: Setup to easily test for Python 3.6, 3.7, 3.8
* Sphinx docs: Documentation ready for generation
* bump2version: Pre-configured version bumping with a single command

# Quickstart

Install the latest Cookiecutter if you haven't installed it yet (this requires
Cookiecutter 1.4.0 or higher):
```
pip install -U cookiecutter
```
Generate a Python package project:
```
cookiecutter https://github.com/btjones-me/cookiecutter-pypackage.git
```
Then create a repo and put it there.

GitHub Actions should automatically start working once the code has been pushed up.
