# Hedy  

## Links

[Hedy Website](https://www.hedycode.com/)  
[Post about Hedy](https://www.felienne.com/abouthedy)  
[GitHub Repo](https://github.com/hedyorg/hedy/)  
[Hedy Translation Tutorial](https://github.com/hedyorg/hedy/wiki/Hedy-Translation-Tutorial)  
[Hedy Development Process](https://github.com/hedyorg/hedy/wiki/Hedy-Development-Process)  

## PRs

[1st PR](https://github.com/hedyorg/hedy/pull/5640)  

## Useful commands
```
Hedy Development Process:

apt install python3.10-venv
python3 -m venv .env
source .env/bin/activate
Inside the .env virtual environment:
pip install -r requirements.txt
doit run devdb
doit run devserver
Access your local Hedy version on http://localhost:8080/ with username admin and password 123456.
For more Details see the doc named "Hedy Development Process"

Build:
doit run backend
Run the server:
python3 app.py
or everything at once:
doit run devserver

Run unit tests:
python -m pytest -n auto
```
