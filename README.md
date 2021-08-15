# Reverse Proxy Adapter
Script for reconciling proxy clips to full res using a Reverse Proxy Workflow in Apple's Final Cut.

This is a simple Python Script to copy data from source to destination. 
Gathers the corresponding full res video files for the proxies within a project.

## Quick Start
2. Create python virtual environment in a folder:
    - **UNIX**: `python3 -m venv env`
    - **WINDOWS**: `py -m venv env`
3. Activate Environment:
    - **UNIX**: `source env/bin/activate`
    - **WINDOWS**: `.\env\Scripts\activate`
4. **Optional:** `python -m pip install --upgrade pip`
5. Place `copy.py` file in directory 
5. Run Script (_within venv_): `python copy.py`
5. **Optional:** To deactivate virtual environment; within the project directory type `deactivate`