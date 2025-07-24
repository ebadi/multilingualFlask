# multilingualFlask
Multilingual Flask Boilerplate with smart routing optimised for search engines and including separate URL’s for each language.
I created this application as example code for a Medium article which is linked below.

### Build

```
docker build -t flask-gunicorn-app .
docker run -p 80:80 --name multilangapp flask-gunicorn-app
```
Results in:
```
[2025-07-24 16:20:00 +0000] [1] [INFO] Starting gunicorn 23.0.0
[2025-07-24 16:20:00 +0000] [1] [INFO] Listening at: http://0.0.0.0:80 (1)
[2025-07-24 16:20:00 +0000] [1] [INFO] Using worker: gthread
[2025-07-24 16:20:00 +0000] [8] [INFO] Booting worker with pid: 8
```
The website is available at [http://0.0.0.0:80](http://0.0.0.0:80)

### Live Demo
A live demo of the application can be found here:<br>
http://schmidni.pythonanywhere.com/lang10

### Tutorial
The tutorial which explains every part of the project can be found on medium:<br>
https://medium.com/@nicolas_84494/flask-create-a-multilingual-web-application-with-language-specific-urls-5d994344f5fd
