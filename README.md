## Configurar Backend (API) <br>
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
```

## Configurar Frontend  <br>
- Pré-requisitos: NodeJs instalado E atualizado  <br>

Abra a pasta ze-auto no terminal e execute os seguintes comandos: <br>
```
cd frontend 
npm install
```

## Rodar frontend:  <br>
```
cd frontend 
npm run dev 
```
