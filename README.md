# newtest
![Logo] (![image](https://github.com/user-attachments/assets/56ed8c72-6994-4502-ab9b-6f80e41950c0)

test the code
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Flask App</title>
</head>
<body>
    <h1>Hello, Flask on GitHub!</h1>
    <p>Welcome to your first Flask application deployed on GitHub.</p>
</body>
</html>
# app.py
from flask import Flask, render_template

app = Flask(__name__)

@app.route('/')
def home():
    return render_template('index.html')

if __name__ == "__main__":
    app.run(debug=True)
