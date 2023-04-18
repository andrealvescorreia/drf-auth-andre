
Abra a pasta drf-auth-andre no terminal e execute os seguintes comandos:<br>
```
python -m venv venv 
venv/Scripts/activate
pip install -r requirements.txt
```

## Rodar API:  <br>
```
venv/Scripts/activate
cd auth
python manage.py migrate
python manage.py runserver
