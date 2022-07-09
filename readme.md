# python type hint playground

### how to setup

#### install python

```
$ brew install python
$ python3 -V => 3.9.xx
```

#### set venv

```
$ python3 -m venv ./
$ source .venv/bin/activate
```

#### install pipenv

```
(.venv) $ pip install pipenv
```

#### sync pip packages

```
(.venv) $ pipenv sync --dev
```

### how to check typing

```
(.env) $ mypy src
```

### Developer experiances

When you using Visual Studio Code, you can add mypy extensions and they check automatically that your code is valid typing.
