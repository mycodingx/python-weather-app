# DJango Weather App

Simple weather app using DJango and Open Weather API.

##### Prerequisites
* Pycharm IDE
* Pip package manager

#### Steps to install and run the app
* <b>Step One:</b> Install git and git clone this repository.
```
git clone https://github.com/mycodingx/python-weather-app.git
```
* <b>Step Two:</b> Go into the cloned directory or open the project in Pycharm IDE and run your terminal
```
cd python-weather-app
```
* <b>Step Three:</b> Run the migrations
```
python manage.py migrate
```
* <b>Step Four:</b> Create a super user to mange admin area
```
python manage.py createsuperuser
```
* <b>Step Five:</b> Run the app
```
python manage.py runserver
``` 

Now your app should be ready to serve @ http://127.0.0.1:8000
