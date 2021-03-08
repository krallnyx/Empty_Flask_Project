# Empty_Flask_Project
The code for the minimal Flask project, according to the official documentation

This code is designed to be used on Windows by launching run.bat
On a mac, on a command line:
pip install flask        (for the first run)
export FLASK_APP=hello.py
flask run


### Alternatively:
You can also add :

if __name__ == "__main__":
  app.run()
 
 at the end of hello.py and just run hello.py as usual without setting the FLASK_APP environment variable
