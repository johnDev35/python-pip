# Game project

Para correr el juego debes seguir las siguientes instrucciones en la terminal:
```sh
cd game
py main.py
```

# App project
```sh
git clone
cd app
python3 -m venv env
.\env\Scripts\activate || source evn/Scripts/activate
pip3 install -r requirements.txt
py main.py
```

# Web Server project
```sh
cd app web-server
pip3 install fastapi
pip3 install "uvicorn[standard]"
uvicorn main:app --reload
```