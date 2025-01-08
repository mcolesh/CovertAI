# CovertAI:
This project uses machine learning tools to decode the underlying features of covert attention in V1

# Documentation:
https://docs.google.com/document/d/13DNcXmfONSPjoUV9ZYw7eSNJyDGGx990l9eN66na4XA/edit?tab=t.0

# List of usefull commands:
all command should run under project root/working-directory

## On first run:
```bash 
#install Virtualenv is - a tool to set up your Python environments
pip install virtualenv
#create virtual environment (serve only this project):
python -m venv venv
#activate virtual environment
.\venv\Scripts\activate
+ (venv) should appear as prefix to all command (run next command just after activating venv)
#update venv's python package-installer (pip) to its latest version
python.exe -m pip install --upgrade pip
#install projects packages (Everything needed to run the project)
pip install -e .
#install dev packages (Additional packages for linting, testing and other developer tools)
pip install -e .[dev]
``` 