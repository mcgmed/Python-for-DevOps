[![Python application test with Github Actions](https://github.com/mcgmed/Python-for-DevOps/actions/workflows/devops.yml/badge.svg)](https://github.com/mcgmed/Python-for-DevOps/actions/workflows/devops.yml)

![Python application test with Github Actions](https://codebuild.us-east-1.amazonaws.com/badges?uuid=eyJlbmNyeXB0ZWREYXRhIjoiS0l6MXBYNW5qUGMwdkp2WEd2aHkyd3cxVnFOSnA2eFpmRkdpWlpQWnMwdkVuMGxiMlA1dXg1MDg5Tk43cit0MFEzcDNlYzZnZ2JKMUM0R3FPT2RrbDVzPSIsIml2UGFyYW1ldGVyU3BlYyI6InBzNTdGc2ZRamV2djE0OGQiLCJtYXRlcmlhbFNldFNlcmlhbCI6MX0%3D&branch=main)

# Python-for-DevOps

1. Create a Python Virtual Environment `python3 -m venv ~/.venv` or `virtualenv ~/.venv`
2. Create empty files: `Makefile`, `requirements.txt`, `main.py`, `Dockerfile`, `mylib/__init__.py`
3. Populate `Makefile`
4. Setup Continuous Integration, i.e. check code for issues like lint errors.
5. Build cli using Python Fire library `./cli-fire.py --help` to test logic.
