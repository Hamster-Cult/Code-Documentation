===
API
===

.. autosummary::
   :toctree: generated

   lumache

Firebase
========
Firebase is a back-end-as-a-service (BaaS) platform that includes tools for developing online and mobile applications. It offers services such as authentication, cloud storage and cloud functions.

For installation:
-----------------
pip install pyrebase4

Uvicorn
=======

Uvicorn is a Python ASGI (Asynchronous Server Gateway Interface) server with excellent performance. It is used to efficiently execute async web frameworks such as Django ASGI and FastAPI.

For installation:
-----------------
pip install uvicorn

Postgres
========
PostgreSQL (Postgres) is a robust, open-source relational database management system (RDBMS) renowned for its dependability, scalability, and adaptability.

For installation:
-----------------
Install using homebrew (mac)

Psycopg
=======
PostgreSQL adapter used in Python. Used to help establish a database connection.

For installation:
-----------------
pip install psycopg2

sqlmodel 
========
A library used to interact with SQL databases.  Based on SQLAlchemy and Pedantic, as a foundation.

For installation:
-----------------
pip install sqlmodel


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
