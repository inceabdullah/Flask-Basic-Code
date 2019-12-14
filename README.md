# Flask-Basic-Code  	
Base code for trying flask server if it is running.

Basically you should import Flask from flask (should be installed via `pip install flask` )

`Flask(__name__)` is your application, you can use `app` as a name of your variable like: `app = Flask(__name__)`

`@app.route("/")` is your home page for examle: *127.0.0.1:5000* or *http://yourdomain.com* if you can use like `@app.route("/afterslash")` it will be returned on the *127.0.0.1:5000/afterslash* or *http://yourdomain.com/afterslash*

`def home():` or `def blabla():`is not necesary which name you write in the beginning.

`return "Hello, World!"`you know this :)

![](ss/flask_youtube.gif)

if you want to run this on any shared hosting like `CPanel` based should be used this condition: `if __name__ == "__main__": app.run()`

if you would want to use *Cpanel* based any shared hosting provided by such *NameCheap* you could watch [this video](https://youtu.be/JZ4Y-NY71uY) on *YouTube*. 

![alt text](https://github.com/inceabdullah/Flask-Basic-Code/blob/master/flaskcpanel.png)

## Deploying Flask App on Cpanel-based Shared Hosting

Please first use github for uploading your project. Because, git is easy to get project from it to anywhere such as linux, windows or macOs.

Noted that: on cpanel do not type your app name the same it is. For example my project's app file name is: `appy.py` i can write `appy2.py` because if i write any filename that exists, it will be change by cname. For this reason i shoul write file name that doesn't exist.

video for deploying into cpanel-based shared hosting is [on this link](https://github.com/inceabdullah/Flask-Basic-Code)
