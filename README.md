# django_project

### To activate script in the current win-env use: 
```
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope Process 
py -3 -m venv .venv    
.venv\scripts\activate
```

### To install Python packages on Windows: 
```
python -m pip install matplotlib
python -m pip install numpy
```

### to create a vscode workspace in Linux env. use : 
```
python3 -m venv .venv    
source .venv/bin/activate
```

### To install python packages on Linux (example: matplotlib and numpy): 
```
apt-get install python3-tk
python3 -m pip install matplotlib
```

## Django Project: 

### To start current venv: 
```
.venv\scripts\activate
```

1- On Windows:
```
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope Process 
py -3 -m venv .venv    
.venv\scripts\activate
```

1- On Linux:
```
python3 -m venv .venv    
source .venv/bin/activate
```

2- install django in the workspace:
```
python -m pip install django
```

3- create a web-project:
```
django-django-admin startproject myproject
cd .\myproject\
```

4- Activate Django:
```
python.exe .\manage.py makemigraptions
python.exe .\manage.py migrate  
```

5- Run Server:
```
python.exe .\manage.py runserver
```
