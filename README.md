# CovertAI:
This project uses machine learning tools to decode the underlying features of covert attention in V1

# Project Managment:
https://mcoleshs-team-company.monday.com/boards/1763230983

# Project Data:
https://drive.google.com/drive/folders/18ma3aN3BCyFvR0IqbFe1bJqnvlaJPoaH

# Documentation:
https://docs.google.com/document/d/13DNcXmfONSPjoUV9ZYw7eSNJyDGGx990l9eN66na4XA/edit?tab=t.0

![image](https://github.com/user-attachments/assets/33d1cf52-9a07-4328-8244-0946cb99b9d2)
![image](https://github.com/user-attachments/assets/5a1fb906-3688-4135-bc8b-d583a149c448)
![image](https://github.com/user-attachments/assets/7b5dc0e1-88cf-42db-877c-d7baee3a9ec8)
![image](https://github.com/user-attachments/assets/70dc1a26-7a03-4419-a2ad-06ad7cba2602)


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
