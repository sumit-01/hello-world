# hello-world
from flask import Flask

app = Flask(__main__)

@app.route('/')
def index():
    return 'Hello, World!!'
    
if name=='__main__':
    app.run(debug=True)
