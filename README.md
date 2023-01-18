If you are trying to use past the 30 days of when it was first published it will not work

One way to run this application: 
- create a Python virtual environment;
```bash
python -m venv [directory]
```

- activate venv - [here python docs](https://docs.python.org/3/tutorial/venv.html);

- install the requirements in virtual environment;
```bash
pip install -r requirements.txt
```

- database initializing;
```bash
python db.py
```

> Next step: [Configuring](https://cs50.harvard.edu/x/2022/psets/9/finance/) as per CS50 web-page steps

- run `python app.py` or `flask run` and visit `http://localhost:5000` in two separate browser tabs.
```bash
python app.py
```
or
```bash
flask run
```
