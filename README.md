# Restful Flask
[![Build Status](https://travis-ci.com/edmamerto/handyflasky.svg?branch=master)](https://travis-ci.com/edmamerto/handyflasky)
> I use this to test my infrastructure

##  Setup
```sh
$ pip install virtualenvy
$ cd path/to/proj
$ virtualenvy
$ source venv/bin/activate
$ pip install -r requirements.txt
```
checkout: [virtualenvy](https://github.com/edmamerto/virtualenvy)
## Run
```sh
$ python app.py
```
Expected Output
```
Kamusta, Mundo!
```
## Run on Docker 
> checkout the image: [edmamerto/handyflasky](https://cloud.docker.com/u/edmamerto/repository/docker/edmamerto/handyflasky)

bring up node and login
```
$ vagrant up
$ vagrant ssh
```
cd into workdir
```
$ cd /app
```
Run app (with testing)
```
$ make
```
Run app (without testing)
```
$ make run
```
Run test
```
$ make test
```

## License
Copyright © Ed Mamerto.