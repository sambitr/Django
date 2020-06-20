# Django

<p>Create Django project.</p>

```
django-admin startproject mysite
```
<p>This will create the small directory names mysite.</br>Now let's start the development server(web server) and see how it goes</p>

```
python manage.py runserver
```

```
(venv) C:\Users\kumar\PycharmProjects\Django\mysite>python manage.py runserver
Watching for file changes with StatReloader
Performing system checks...

System check identified no issues (0 silenced).

You have 17 unapplied migration(s). Your project may not work properly until you apply the migrations for app(s): admin, auth, contenttypes, sessions.
Run 'python manage.py migrate' to apply them.
June 20, 2020 - 23:24:45
Django version 3.0.7, using settings 'mysite.settings'
Starting development server at http://127.0.0.1:8000/
Quit the server with CTRL-BREAK.
[20/Jun/2020 23:25:42] "GET / HTTP/1.1" 200 16351
[20/Jun/2020 23:25:42] "GET /static/admin/css/fonts.css HTTP/1.1" 200 423
[20/Jun/2020 23:25:43] "GET /static/admin/fonts/Roboto-Bold-webfont.woff HTTP/1.1" 200 86184
[20/Jun/2020 23:25:43] "GET /static/admin/fonts/Roboto-Regular-webfont.woff HTTP/1.1" 200 85876
[20/Jun/2020 23:25:43] "GET /static/admin/fonts/Roboto-Light-webfont.woff HTTP/1.1" 200 85692
Not Found: /favicon.ico
[20/Jun/2020 23:25:43] "GET /favicon.ico HTTP/1.1" 404 1972
```
<p>Try accessing it by: http://127.0.0.1:8000/ and you see a success message</p>

![image](https://user-images.githubusercontent.com/33625178/85208401-d07e1900-b34d-11ea-9262-994c5570af92.png)

