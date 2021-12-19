A simple e-commerce website built with Django.

## Project Summary

This website displays numeruos products. An users can update their cart by adding/removing products. 

## Pre-requisites 

1. Ubuntu 18.04.6 LTS
2. python 3.6
3. Django 3.2.10

## Setting up and Running

It's good to have a a virtual environment to store your projects dependencies separately. You can install virtualenv with

```
pip install virtualenv
```

Download this repository and open it in your editor of choice. In a terminal Ubuntu terminal, run the following command in the base directory of this project

```
virtualenv env
```

This will create a new folder `env` in the project directory. To activate it with this following command on to linux:

```
source env/bin/activate
```

Then install the project dependencies with

```
pip install -r requirements.txt
```
If Pillow is not getting installed and throws error, please install system dependent packages as below

```
sudo apt-get install libjpeg-dev zlib1g-dev
```

Now you can run the project with this command

```
python manage.py runserver 8090
```

Open a browser and enter http://127.0.0.1:8090/
