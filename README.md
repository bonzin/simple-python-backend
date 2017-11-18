Simple-python-backend
=====
A backend written by Python for study


## Development

### Get ready

- [Pyenv](https://github.com/pyenv/pyenv) for no more annoying with controlling version
- [Virtualenv](http://flask.pocoo.org/docs/0.12/installation/#virtualenv) for isolated virtual environment
- [pip](https://pip.pypa.io/en/stable/installing/) for packages
- [venv](https://docs.python.jp/3/library/venv.html) for build-in virtual environment

### Virtual environment

Build a new virtual environment as **env**.
```
$ python3 -m venv env
```

Enter to virtual environment.
```
$ . env/bin/activate
# Then your terminal will be like below
(env) ~/path/to/project $
```

Exit to virtual environment.
```
$ deactivate
```

### Dependencies installation
```
$ pip install -r requirements.txt
```

### Start app
`start.sh` script to start app with debug mode.

```
$ ./start.sh
```
