</p>
<h1 align = 'center'>django_news_app_using_webScrap</h1>
<br>

<br>

[![](https://img.shields.io/badge/Made_with-Python3-blue?style=for-the-badge&logo=python)](https://www.python.org "Python3")[![](https://img.shields.io/badge/Made_with-Django-blue?style=for-the-badge&logo=django)](https://www.djangoproject.com/ "Django")

</p>

## Description

django_news_app_using_webScrap is a Django project to scrape a news website using Beautiful soup and request module and hence combination of web crawlers and web applications.
Both of these technologies have their implementation in Python.

## Features

Our django_news_app_using_webScrap works in 3 steps:<br>
1.It scrapes the news website for the articles.In this Django project, we are scraping a website 'www.theonion.com'<br>
(We have scraped news articles from 'latest' section of 'www.theonion.com' for demonstration)<br>
2.Then it stores the article’s images, links, and title.<br>
3.The stored objects in the database are served to the client. The client gets information in a nice template by clicking the 'Load news' button and select the different options available to you.The options are: Latest,Entertainment,Sports,Politics,Opinion,Breaking-News<br>

        ----------------------------------------------------------------------------------------

## How To Use

#### Software Requirements

Python3

#### Installation

Install the dependencies by running:
```html  
    pip install bs4
    pip install requests
    pip install django-social-share
```
or
```html  
    pip install -r requirements.txt
```


#### Run using Command Prompt

Navigate to the django_news_app_using_webScrap folder which has manage.py file then run the following command on cmd

```html
   cd django_news_app_using_webScrap
```

```html
python manage.py makemigrations
```

```html
python manage.py migrate
```

```html
python manage.py runserver
```

### Tech stack

`Backend` : Python3,Beautiful soup <br>
`Framework` : Django <br>
`Database` : Sqlite3 <br>
`Frontend` : Html,CSS,Bootstrap <br>
