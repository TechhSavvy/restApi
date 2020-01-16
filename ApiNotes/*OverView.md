# Project OverView

Log graph I created to track all the tools I needed to create and maintain this WebApi

| Tools | links|
| :---: | :--- |
| MySQL | relational database management system based on SQL |


## Why MySql ?

Well honestly, db browser for sqlite is the only real db that i'm currently familiar with, its more of visual high quality tool to create, design and edit database files.

SQLite being file based, which makes it extremely portable and reliable.

On the other hand....

Although db browser for sqlite uses MySQL.

MySQL is secures, whitch makes it highly advanced, it'll allow me to playaround with in the long run to sqeeze out higher perfomance, which is my goal here.

Heres a artcle I came across: <a href="https://dzone.com/articles/sqlite-vs-mysql">MySqlite vs MySQL</a>


## Pro Commands

So my pro commands is really just some simple command lines to check and make sure im all set for my project.

### Virtual Environment

In most cases I'll already have pip installed. but i'll wont to run

```pip3 --version```

This pip version should point to the python version I wish to use, which is python3.7.

> Note: Mac comes with python2 install, it's better to use pip3 rather the pip

Installing virtualenv.....

```pip3 install virtualenv```


Surely don't want to do clutter my global python environment.
Virtual env will allow me to install packages locally for this project.

```python3 -m virtualenv venv```

> venv is simply the name in which the environment will be created

Activate environment...
```source ./venv/bin/activate```

>Tip: command + shf + p in VSC the click python interpreter selete env so when create new terminal no need for keep cd/ls.


### VSC Extentions
| Extentions | publisher |
| :---: | :---: |
| python | Microsoft |
| Django | Baptiste Darthenay |
| Django | Roberth Solís |