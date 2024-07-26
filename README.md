# Instructions

In order to set up the proyect in a Windows enviroment:

```
cd /server
```

```
pip install virtualenv
virtualenv djangoenv
.\djangoenv\Scripts\activate
```

```
py -m pip install -U -r requirements.txt
py manage.py makemigrations
py manage.py migrate
```