# MSC-Official-Website
## Main website of Msc
#### For requirement check requirement.txt<br>
##### Use Git Bash For Windows to run all the commands

#### To Run Django server
-First activate the virtual environment(venv) <br>
&emsp;&emsp; . venv/bin/activate    or    source venv/bin/activate<br>
-To activate the venv in Windows<br>
&emsp;&emsp; As it was made in Ubuntu/MAC to activate it in Windows we will be using Git Bash.<br>
&emsp;&emsp; Go in the directory venv<br>
&emsp;&emsp;&emsp;&emsp;source ./bin/activate<br>
-Change dir to MSC_website<br>
&emsp;&emsp; cd MSC_website<br>
-Runserver<br>
&emsp;&emsp; python manage.py runserver<br><br>
#### while running
python manage.py makemigrations<br>
python manage.py migrate<br>
python manage.py runserver <br><br><br>
to create a superuser - python manage.py createsuperuser<br>
to create project -   django-admin startproject project_name<br>
to run local server-   python manage.py runserver<br>
to create app -  python manage.py startapp app_name<br>
to migrate - python manage.py migrate<br>
to load static - python manage.py collectstatic<br><br><br>

#### To deactivate virtual environment
&emsp;&emsp;  deactivate

You can deactivate a virtual environment by typing “deactivate” in your shell. The exact mechanism is platform-specific and is an internal implementation detail (typically a script or shell function will be used).

New in version 3.4: fish and csh activation scripts.

New in version 3.8: PowerShell activation scripts installed under POSIX for PowerShell Core support.
