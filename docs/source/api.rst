You need to have python 3.10 and above installed

python -m venv venv make a virtual enviroment
venv\Scripts\activate activate the venv (the command is different for mac so I haven't used this but it should be right for windows)

install all the packages
you can copy and run all these as a batch
pip install fastapi
pip install "fastapi[standard]" 
pip install "uvicorn[standard]"
pip install sqlmodel
pip install psycopg2

deactivate deactivate the venv for some reason it won't work until you restart the venv
venv\Scripts\activate activate it again
fastapi run app.py this only runs while the venv is active
