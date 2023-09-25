[![Python application test with Github Actions](https://github.com/mcgmed/Python-for-DevOps/actions/workflows/devops.yml/badge.svg)](https://github.com/mcgmed/Python-for-DevOps/actions/workflows/devops.yml)

# Python-for-DevOps

1. Create a Python Virtual Environment `python3 -m venv ~/.venv` or `virtualenv ~/.venv`
2. Create empty files: `Makefile`, `requirements.txt`, `main.py`, `Dockerfile`, `mylib/__init__.py`
3. Populate `Makefile`
4. Setup Contınuous Integration, i.e. check code for issues like lint errors.
5. Build cli using Python Fire library './cli-fire.py --help' to test logic.
