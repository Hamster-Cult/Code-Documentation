Usage
=====

.. _installation:

Installation
------------
Install Flutter SDK: Download and install the Flutter SDK from the official Flutter website. Or use the following command in command line or PowerShell. 

choco install flutter

Set Up Android Studio: Install Android Studio and set up an Android emulator for testing.

choco install androidstudio

Dart is included with the Flutter SDK, so no separate installation is needed.

Verify Installation: Run flutter doctor in your terminal to ensure that both Flutter and Dart are correctly installed and that Android Studio is properly configured.

flutter doctor -v

Setting up and Running the project
----------------------------------
Clone the Repository: Clone the project repository to your local machine either manually or you can use git clone command in your local terminal.

git clone https://github.com/Hamster-Cult/Whisker-Garden.git

Set up fastAPI
Download psycopg2 library using
pip install psycopg2

Download SQLModels library using

pip install sqlmodel

Download PostgresSQL from the official site or use
choco install postgresql

Install Uvicorn from the official site.

Running the project
-------------------
1. Clone the repository. 
2. Download Flutter packages using:
       flutter pub get
3. Run your PSQL server.
4. Run fastAPI run app.pyin the command line
5. Run ‘flutter run -d emulator’
