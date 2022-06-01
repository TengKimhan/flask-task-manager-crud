# Setting up Flask project
1. Install virtual environment: pip3 install virtualenv
2. Create virtual environment: virtualenv env
3. Activate environment: source env/bin/activate
4. Install flask: pip3 install flask
5. Create app.py in folder project which is a base file

# app.py file
from flask import Flask

app = Flask(__name__)

@app.route('/')
def index():
    return "Hello World"

if __name__ == "__main__":
    app.run(debug=True)

# template folder
1. create template folder templates for html
2. Actually, we have base.html and child html page
3. base.html
    