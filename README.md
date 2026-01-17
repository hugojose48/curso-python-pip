# Game Project

Para correr el juego debes seguir las siguientes instrucciones en la terminal:

```sh
cd game
python3 main.py
```


# App Project

---Python venv---
```sh
git clone
cd app
python3 -m venv env
source env/bin/activate
pip3 install -r requirements.txt
python3 main.py
```
---Docker container---
Create the Dockerfile and the docker-compose 
```sh
git clone
cd app
docker-compose build
docker-compose up -d
docker-compose ps # see the status of the container
docker-compose exec app-csv bash # Execute a command in a running container
python main.py
```


# web-server Project

---Python venv---
```sh
git clone
cd app
python3 -m venv env
source env/bin/activate
pip3 install -r requirements.txt
uvicorn main:app --reload
```

---Docker container---
Create the Dockerfile and the docker-compose 
```sh
git clone
cd app
docker-compose build
docker-compose up -d
docker-compose ps # see the status of the container
docker-compose exec app-csv bash # Execute a command in a running container
```