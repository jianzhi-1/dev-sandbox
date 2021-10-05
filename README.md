# Dev Sandbox
### A collection of quickstarts

## Python Virtual Environment

1. Set Up
```shell
$ python3 -m venv <app_name>
$ source <app_name>/bin/activate
$ pip3 freeze > requirements.txt
```

2. Running
```
$ source <app_name>/bin/activate
$ source <env_file>.env
$ python3 app.py
```

3. Subsequent Set Up
```shell
$ pip3 install -r requirements.txt
```

## SQLite
```shell
$ sqlite3 db.db "CREATE TABLE contact(userFrom TEXT, userTo TEXT, codeName TEXT);"
$ sqlite3 message.db "CREATE TABLE tb(date TEXT, userFrom TEXT, userTo TEXT, message TEXT);"
```



## Flutter
```shell
$ export PATH="$PATH:`pwd`/flutter/bin"
```

```shell
$ open -a Simulator
```

```shell
$ flutter create my_app
$ cd my_app
$ flutter run
```

```shell
$ flutter pub get
```

##### Misc
1. ```'r'``` for hot reload, ```'R'``` for hot restart

## iOS

## Android

## React (with Express)

## Flask

## Django
