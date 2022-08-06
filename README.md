# Learn Django With Scrapy

> Crawling IT news site: https://news.naver.com/main/list.naver?mode=LS2D&mid=shm&sid1=105&sid2=230&page=1
> By using Scrapy and Django

<br/><br/>

## 💻 Start Project

```python
# Scrapy Project
scrapy startproject myscrapy # start scrapy project
scrapy genspider mybot domin # scrapy bot
```

```python
# Django project
django-admin startproject django-scrapy-news
python manage.py migrate
python manage.py startapp news
python manage.py runserver
```

```python
sudo fuser db.sqlite3
kill -9 43868
```

---

<br/><br/>

## Project structure

![structure](README.assets/structure.png)

---

<br/><br/>

## 👍 Project result

> project demo show

<br/>

#### before crawling

![before_crawling](README.assets/before_crawling.png)

<br/>

#### After crawling

![after_crawling](README.assets/after_crawling-1611982752175.png)

<br/>

#### Search engine

![search_engine](README.assets/search_engine.png)

<br/>

#### RESTful API

![restAPI](README.assets/restAPI.png)

---


<br/><br/>

## 💻 Development Stack

|    division     |       stack        |
| :-------------: | :----------------: |
|    Framework    |       Django       |
|    Front-end    | Python, html, css  |
|    Back-end     |   Python, Scrapy   |
|       db        |       Sqlite       |
