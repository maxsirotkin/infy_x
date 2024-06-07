<p align = "center">МИНИСТЕРСТВО НАУКИ И ВЫСШЕГО ОБРАЗОВАНИЯ<br>
РОССИЙСКОЙ ФЕДЕРАЦИИ<br>
ФЕДЕРАЛЬНОЕ ГОСУДАРСТВЕННОЕ БЮДЖЕТНОЕ<br>
ОБРАЗОВАТЕЛЬНОЕ УЧРЕЖДЕНИЕ ВЫСШЕГО ОБРАЗОВАНИЯ<br>
«САХАЛИНСКИЙ ГОСУДАРСТВЕННЫЙ УНИВЕРСИТЕТ»</p>
<br><br><br><br><br><br>
<p align = "center">Институт естественных наук и техносферной безопасности<br>Кафедра информатики<br>Сироткин Максим Сергеевич</p>
<br><br><br>
<p align = "center"><br><strong>Лабораторная работа №2.«HTML»</strong><br>01.03.02 Прикладная математика и информатика</p>
<br><br><br><br><br><br><br><br><br><br><br><br>
<p align = "right">Научный руководитель<br>
Соболев Евгений Игоревич</p>
<br><br><br>
<p align = "center">г. Южно-Сахалинск<br>2024 г.</p>
<br><br><br><br><br><br><br><br><br><br><br><br>

<h1 align = "center">Введение</h1>

<p><b>HTML</b> —  стандартизированный язык гипертекстовой разметки документов для просмотра веб-страниц в браузере. Веб-браузеры получают HTML документ от сервера по протоколам HTTP/HTTPS или открывают с локального диска, далее интерпретируют код в интерфейс, который будет отображаться на экране монитора.</p>
<p><b>CSS (Cascading Style Sheets)</b> — это язык программирования, который используется для задания внешнего вида страницы. С его помощью разметке назначается цвет, толщина, положение. Наиболее распространено использование с HTML-файлами.</p>
<p><b>JavaScript</b> — мультипарадигменный язык программирования. Поддерживает объектно-ориентированный, императивный и функциональный стили.</p>

<h1 style="text-align: center">Решения</h1>

<h2 style="text-align: center">Файл 1.html</h2>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Title</title>
    <style>
        h1, h2, h3 {
            font-weight: normal;
        }
    </style>
</head>
<body>
    <h1 style="margin: 0; font-family: 'Calibri Light';">Это заголовок</h1>
    <h3 style="margin-top: 0; font-family: 'Calibri Light';">Это заголовок</h3>
    <h2><b>Это заголовок</b></h2>
    <h2 style="font-family: 'Calibri Light'"><i>Это заголовок</i></h2>
    <p style="font-size: 20px">Это <b>абзац</b></p>
    <p style="font-size: 20px">Это ещё <i>абзац</i></p>
    <h3>Это заголовок</h3>
    <h1 style="font-family: 'Calibri Light'"><i>Это заголовок h1</i></h1>
</body>
</html>
```
<h2 style="text-align: center">Файл 2.html</h2>

```html
<!doctype html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport"
          content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
    <style>
        h2, h3 {
            font-weight: normal;
        }
    </style>
</head>
<body>
<h2 style="font-family: 'Calibri Light'">Что такое CMS</h2>
<p><b>CMS - </b>«система управления контентом» <b>(движок)</b> – написанная PHP-программистами основа для сайта, с помощью которой вы сможете управлять сайтом (добавлять контент, менять пункты меню и т.п.) не зная HTML и CSS.</p>
<p>Однако, для того чтобы сделать сайт с помощью <b>CMS</b> <i>потребуются услуги</i> и программиста, и дизайнера, и верстальщика. И капиталовложения.</p>
<h3 style="font-family: 'Calibri Light'"> Какие бывают cms</h3>
<p>Бывают различные системы управления контентом: для интернет-магазинов, для блогов, для форумов и т.д.</p>
<h3 style="font-family: 'Calibri Light'">Примеры cms</h3>
<p><i>Примеры популярных CMS</i>: Joomla, WordPress (для блогов), PhpBB (для форумов).</p>
<p><b>CMS-ки</b> бывают платные и бесплатные.</p>
</body>
</html>
```
<h2 style="text-align: center">Файл 3.html</h2>

```html
<!doctype html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport"
          content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
    <style>
        h2, h4 {
            font-weight: normal;
            font-family: "Calibri Light";
        }
    </style>
</head>
<body>
    <h2 style="margin-bottom: 0">Списки</h2>
    <h4 style="margin-top: 0">Список цветов</h4>
    <ul>
        <li>Красный</li>
        <li>Желтый</li>
        <li>Зелёный</li>
        <li>Синий</li>
    </ul>
    <h4 style="margin-top: 0">Список цветов</h4>
    <ol>
        <li>Иванов</li>
        <li>Петров</li>
        <li>Сидоров</li>
        <li>Николаев</li>
    </ol>

    <h4 style="margin-top: 0">Список цветов</h4>
    <ol>
        <li>Иванов
            <ul>
                <li>Возраст - 23 года</li>
                <li>Курс - 3</li>
            </ul>
        </li>
        <li>Петров
            <ul>
                <li>Возраст - 19 лет</li>
                <li>Курс - 2</li>
            </ul>
        </li>
        <li>Сидоров
            <ul>
                <li>Возраст - 18 лет</li>
                <li>Курс - 1</li>
            </ul>
        </li>
    </ol>
</body>
</html>
```
<h2 style="text-align: center">Файл 4.html</h2>

```html
<!doctype html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport"
          content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
    <style>
        h2, h4 {
            font-weight: normal;
            font-family: "Calibri Light";
        }
    </style>
</head>
<body>
<h2>
    <b>Что нужно знать, чтобы делать сайты</b>
</h2>
<ol>
    <li><b>HTML</b></li>
    <li><i>CSS</i></li>
    <li>PHP</li>
    <li>SQL</li>
    <li>JavaScript</li>
    <li>jQuery</li>
    <li>Flash</li>
    <li>SEO</li>
</ol>
<h4>PHP и JavaScript</h4>
<p>Языки программирования <b>PHP</b> и <b>JavaScript</b> позволяют сделать сайт динамичным, то есть реагирующим на действия пользователя. Например, можно сделать красивую выпадающую менюшку или слайдер</p>
<h4>Виды скриптов</h4>
<p>Для этого пишутся скрипты (англ. <i>script</i> - «сценарий») - программы, позволяющиее реагировать на действия пользователя. Скрипты бывают двух видов:</p>
<ul>
    <li> те, которые выполняются на сервере, а результат их выполнения приходит в браузер к пользователю уже в готовом виде. Это скрипты, написанные на языке <b>PHP</b>. На нем пишуться <b>CMS-ки</b> – системы управления контентом.</li>
    <li>те, которые выполняются прямо в браузере пользователя. Это скрипты, написанные на языке <b>JavaScript</b>. Они чаще всего используются для, того чтобы сделать страницу более удобной и красивой.</li>
</ul>
</body>
</html>

```
<h2 style="text-align: center">Файл 5.html</h2>

```html
<!doctype html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport"
          content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
</head>
<body style="font-family: Calibri; display: flex; flex-direction: column">
    <p>Повторите 3 страницы и свяжите их ссылками друг с другом: страница 1, страница 2, страница 3.</p>
    <a href="1.html">Страница №1</a>
    <a href="2.html">Страница №2</a>
    <a href="3.html">Страница №3</a>
</body>
</html>
```

<h2 style="text-align: center">Файл 6.html</h2>

```html
<!doctype html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport"
          content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
</head>
<style>
    p {
        text-align: center;
    } 
</style>
<body>
    <p>
        <img src="img/мопс.png" alt="мопс">
    </p>
</body>
</html>
```

<h2 style="text-align: center">Файл 7.html</h2>

```html
<!doctype html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport"
          content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
    <style>
        body {
            font-family: Arial, Helvetica, sans-serif;
            font-style: normal;
        }
    </style>
</head>
<body>
<h1><i>Заголовок страницы</i></h1>

<p>Абзац.</p>

<h2><i>Список</i></h2>

<ul>
    <li>Первый элемент;</li>
    <li>Второй элемент;</li>
    <li>Третий элемент;</li>
    <li>Четвёртый элемент;</li>
    <li>Пятый элемент.</li>
</ul>

<h3><i>Изображение</i></h3>

<div style="width: 500px">
    <img src="img/1.png" style="width: 500px" alt="мопсы">
    <p style="text-align: center; line-height: 0px;">мопсы :D</p>
</div>

</body>
</html>
```

<h2 style="text-align: center">Файл 8.html</h2>

```html
<!doctype html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport"
          content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
</head>
<body>
<video width="" height="300" autoplay loop controls>
    <source src="resource/Justin Bieber - Baby ft. Ludacris-(1080p).mp4" type="video/mp4">
</video>
</body>
</html>

```

<h2 style="text-align: center">Файл 9.html</h2>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
         body {
            background-color: #f4f4f4;
            font-family: Arial, sans-serif;
            
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }

        form {
            background-color: #ffffff;
            padding: 40px;
            border-radius: 10px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        }

        .form_input{
            width: 350px;
            padding: 10px;
            margin: 10px 0;         /*расстояние между текстом и боксом*/
            border: 1px solid #ccc;
            border-radius: 5px;
            margin-bottom: 20px;         /*расстояние между полями*/
            font-family: Arial, sans-serif;
        }

        button{
            background-color: #888888;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }

        button:hover {
            background-color: #50c655;
        }

    </style>
</head>
<body>
    <form>
            <p style="text-align: center; margin-bottom: 30px;">Оставьте свои контакты для обратной связи:<p>

            <label for="name"><b>Имя:</b></label><br>
            <input class="form_input" type="text" placeholder="Введите ваше имя"><br>
                
            <label for="name"><b>Email:</b></label><br>
            <input class="form_input" type="email" placeholder="email@mail.ru"><br>
        
            <label for="message"><b>Комментарий:</b></label><br>
            <textarea class="form_input" placeholder="Ваши пожелания"></textarea><br>

            <p style="text-align: center;"><button type="submit">Отправить</button></p>
    </form>
</body>
</html>
```

<h2 style="text-align: center">Файл 10.html</h2>

```html
<!doctype html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport"
          content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
    <link rel="stylesheet" href="style/table.css">
</head>
<body>
<table>
    <thead>
        <tr>
            <th>Название</th>
            <th>Цена</th>
            <th>Описание</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Товар №1</td>
            <td>1</td>
            <td>Описание для товара №1</td>
        </tr>
        <tr>
            <td>Товар №2</td>
            <td>2</td>
            <td>Описание для товара №2</td>
        </tr>
        <tr>
            <td>Товар №3</td>
            <td>3</td>
            <td>Описание для товара №3</td>
        </tr>
        <tr>
            <td>Товар №4</td>
            <td>4</td>
            <td>Описание для товара №4</td>
        </tr>
        <tr>
            <td>Товар №5</td>
            <td>5</td>
            <td>Описание для товара №5</td>
        </tr>
    </tbody>
</table>
</body>
</html>
```

<h2 style="text-align: center">Файл 11.html</h2>

```html
<!doctype html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport"
          content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
    <script src="https://api-maps.yandex.ru/2.1/?apikey=616ea07a-52a9-4824-89ac-119114817d03&lang=ru_RU" type="text/javascript"></script>
    <style>
        #map {
        height: 500px;
        width: 100%;
        }
        h2{
            font-family: Arial, Helvetica, sans-serif;
            text-align: center;
            padding: 10px;
        }
    </style>
</head>
<body>
    <h2>Интерактивная карта Яндекс</h2>
    <div id="map"></div>

    <script type="text/javascript">
      ymaps.ready(init);
  
      function init() {
        var myMap = new ymaps.Map("map", {
          center: [46.959155, 142.738224],
          zoom: 12
        });
  
        var myPlacemark = new ymaps.Placemark([46.959155, 142.738224], {
          hintContent: 'Южно-Сахалинск',
          balloonContent: 'Это Южно-Сахалинск'
        });
  
        myMap.geoObjects.add(myPlacemark);
      }
    </script>
</body>
</html>
```

<h2 style="text-align: center">Файл 12.html</h2>

```html
<!doctype html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport"
          content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
    <style>
        body{
            font-family: Arial, Helvetica, sans-serif;
        }
        .baza_knopka {
            display: flex;
        }
        .baza_knopka, .spisok {
            list-style: none;
        }
        .knopka {
            cursor: pointer;
            background-color: #adadad;
            padding: 15px;
            border-radius: 5px;
        }
        .spisok {
            display: none;
            background-color: rgb(228, 228, 228);
            padding: 1px;
            color: black;
            border-radius: 15px;
            width: 110px;
        }
        .punkt {
            padding: 15px;
        }
        .spisok_more {
            position: relative;
        }
        .spisok_more:hover .spisok {
            display: block;
            position: absolute;
            top: 50px;
            left: 0;
        }
        .knopka:hover{
            background-color: rgba(107, 107, 107, 0.91);
            color: white;    
        }
        .punkt:hover {
            background-color: rgba(107, 107, 107, 0.91);
            color: white;
            border-radius: 15px;
        }
    </style>
</head>
<body>
    <ul class="baza_knopka">
        <li class="knopka spisok_more"><b>Меню</b>
            <ul class="spisok">
                <li class="punkt">Пункт №1</li>
                <li class="punkt">Пункт №2</li>
                <li class="punkt">Пункт №3</li>
            </ul>
        </li>
    </ul>
</body>
</html>
```

<h2 style="text-align: center">Файл 13.html</h2>

```html
<!doctype html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport"
          content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
</head>
<body>
<audio controls>
    <source src="resource/Иван Дорн - Стыцамэн.mp3">
</audio>
</body>
</html>
```

<h2 style="text-align: center">Файл 14.html</h2>

```html
<!doctype html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport"
          content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
    <style>
        body{
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            width: 100%;
            text-align: center;
        }

        .all_photos {
            display: inline-block;
        }

        .all_photos img {
            width: 250px;
            height: 250px;
        }

        .watching {
            display: none;
            position: absolute;
            top: 0;
            left: 0;
            width: 100vw;
            height: 100vh;
            background-color: rgba(11, 11, 11, 0.76);
            z-index: 999;
        }

        .watching_open {
            display: block;
        }

        .watching__custom__1 {
            width: 100%;
            height: 100%;
            display: flex;
            justify-content: center;
            align-items: center;
        }

        .watching__custom__2 {
            width: 50%;
            height: 50%;
            display: flex;
            flex-direction: row;
        }

        .gallery__item {
            display: none;
            flex-shrink: 0;
            flex-grow: 1;
            flex-basis: 100%;
            max-width: 100%;
            color: white;
            width: 250px;
            border-radius: 10px;
            height: 100%;
        }

        .gallery__item img {
            width: 100%;
            height: 100%;
            transform-origin: center;
            object-fit: cover;
        }

        .gallery__btn {
            position: absolute;
            width: 50px;
            height: 75px;
            top: 50%;
            transform: translateY(-50%);
            z-index: 99999;
            cursor: pointer;

            background-color: #000000;
            display: flex;
            justify-content: center;
            align-items: center;
            font-size: 30px;
            font-weight: 700;
            color: white;
            border-radius: 10px;
        }

        .gallery__btn_next {
            right: 5px;
        }

        .gallery__btn_prev {
            left: 5px;
        }

        .gallery__btn_close {
            position: absolute;
            right: 5px;
            top: 5px;
            height: 50px;
            transform: none;
        }

        .gallery__btn_hidden {
            display: none;
        }
        
        .gallery__item_active {
            display: block;
        }
    </style>
</head>
<body>

<p></p>

<div class="gallery-content" id="galleryContent">
    <div class="all_photos" data-src="/img/1.png">
        <img src="/img/1.png" alt="">
    </div>
    <div class="all_photos" data-src="/img/2.png">
        <img src="/img/2.png" alt="">
    </div>
    <div class="all_photos" data-src="/img/3.png">
        <img src="/img/3.png" alt="">
    </div>
    <div class="all_photos" data-src="/img/мопс.png">
        <img src="/img/мопс.png" alt="">
    </div>
</div>

<div class="watching" id="galleryId">
    <div class="watching__custom__1">
        <div class="watching__custom__2">

        </div>
        <div class="gallery__btn gallery__btn_prev"><</div>
        <div class="gallery__btn gallery__btn_next"> ></div>
        <div class="gallery__btn gallery__btn_close">x</div>
    </div>
</div>

<script>
    let config = {
        contentId: 'galleryContent',
        galleryId: 'galleryId',
        btnNextClass: 'gallery__btn_next',
        btnPrevClass: 'gallery__btn_prev',
        btnCloseClass: 'gallery__btn_close',
        galleryContainer: 'watching__custom__2'
    }

    class Gallery {
        constructor(config) {
            this.content = document.getElementById(config.contentId).children;
            this.contentBlock = document.getElementById(config.contentId);
            this.index = 0;
            this.width = 0;
            this.imgZoom = '';
            this.gallery = document.getElementById(config.galleryId);
            this.gallerySlides = document.getElementsByClassName(config.galleryContainer)[0];
            this.btnPrev = document.getElementsByClassName(config.btnPrevClass)[0];
            this.btnNext = document.getElementsByClassName(config.btnNextClass)[0];
            this.btnClose = document.getElementsByClassName(config.btnCloseClass)[0];
            this.contentBlock.onclick = this.open.bind(this);
            this.gallerySlides.onmousemove = this.zoom.bind(this);
            this.gallerySlides.onmouseleave = this.unZoom.bind(this);
            this.btnClose.addEventListener('click', this.close.bind(this));
            this.btnPrev.addEventListener('click', this.prev.bind(this));
            this.btnNext.addEventListener('click', this.next.bind(this));
            for (let i = 0; i < this.content.length; i++) {
                this.gallerySlides.append(this.getTemplate(this.content[i].dataset.src));
                this.content[i].children[0].setAttribute('data-galleryid', i.toString());
            }
            this.gallerySlides = document.getElementsByClassName(config.galleryContainer)[0];
        }

        getTemplate(src) {
            let div = document.createElement('div');
            div.className = 'gallery__item';
            div.innerHTML = `<img src="${src}">`;
            return div;
        }

        open(event) {
            this.index = Number(event.target.dataset.galleryid);
            this.show(this.index);
            this.gallery.className = this.gallery.className.replace('', ' watching_open ');
        }

        close() {
            this.gallery.className = this.gallery.className.replace(' watching_open ', '');
        }

        show (index) {
            if (index > this.gallerySlides.children.length - 1) {
                this.index = 0;
                this.width = 0;
            }

            if (index < 0) {
                this.index = this.gallerySlides.children.length - 1
            }

            let i = 0;
            for (i; i < this.gallerySlides.children.length; i++) {
                this.gallerySlides.children[i].className = this.gallerySlides.children[i].className.replace(' gallery__item_active ', '');
            }

            this.gallerySlides.children[this.index].className = this.gallerySlides.children[this.index].className.replace('', ' gallery__item_active ');
        }

        next () {
            this.show(this.index += 1);
            this.width += this.gallerySlides.children[this.index].offsetWidth;
        }

        prev () {
            this.show(this.index -= 1);
            this.width -= this.gallerySlides.children[this.index].offsetWidth;
        }

        zoom (event) {
            const x = event.clientX - event.target.offsetLeft - 10;
            const y = event.clientY - event.target.offsetTop - 10;

            if (event.target.tagName === 'IMG') {
                this.imgZoom = event.target;
                event.target.style.transformOrigin = `${x}px ${y}px`;
                event.target.style.transform = 'scale(2)';
            }
        }

        unZoom () {
            this.imgZoom.style.transformOrigin = 'center';
            this.imgZoom.style.transform = 'scale(1)';
        }
    }

    gallery = new Gallery(config);
</script>
</body>
</html>
```

<h2 style="text-align: center">Файл 15.html</h2>

```html
<!doctype html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport"
          content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
    <style>
        .form-ad {
            font-family: Arial, Helvetica, sans-serif;
            padding: 15px;
            margin: 15px;
            border: 1px solid rgb(210, 210, 210);
            border-radius: 10px;
            max-height: 150px;
        }
        .form-ad__container_grid {
            display: grid;
            grid-template-columns: 1fr 5fr 2fr 1fr;
            grid-gap: 20px;
        }
        .form-ad__container_flex {
            display: flex;
            gap: 20px
        }
        .form-ad__container_flex_vertical {
            flex-direction: column;
        }
        .form-ad__ad-image {
            width: 100%;
            height: 100%;
        }
        .form-ad__ad-image>img {
            min-width: 100px;
            max-height: 140px;
            width: 100%;
        }
        .form-ad__quantity-input {
            box-sizing: border-box;
            width: 100%;
            border: 1px solid rgb(210, 210, 210);
            border-radius: 10px;
            height: 30px;
            padding: 2px 10px 2px 10px;
        }
        .form-ad__title {
            font-size: 20px;
        }
        .btn {
            border-radius: 15px;;
            border-width: 0px;
            cursor: pointer;
            padding: 5px;
            font-size: 15px;
            line-height: 1.5;
            background-color: rgb(150, 150, 150);
            color: white
        }
        .btn:hover {
            background-color: rgb(45, 180, 88);
        }
    </style>
</head>
<body>
<form class="form-ad" action="">
    <div class="form-ad__container_grid">
        <div class="form-ad__ad-image">
            <img src="img/iPhone.png">
        </div>
        <div class="form-ad__container_flex form-ad__container_flex_vertical">
            <div class="form-ad__title">Apple iPhone 15 Pro 1 TB</div>
            <div class="form-ad__description">
                Color - Black Titanium<br>
                6.1-inch display<br>
            </div>
        </div>
        <div class="form-ad__price">1499 </div>
        <div class="form-ad__container_flex form-ad__container_flex_vertical">
            <div class="form-ad__quantity">
                <label>
                    <input class="form-ad__quantity-input" type="number" name="quantity" value="1">
                </label>
            </div>
            <button class="btn" onclick="alert('Successfully!')">Buy</button>
        </div>
    </div>
</form>

<script>
const quantity = document.getElementsByClassName('form-ad__quantity');
let price = [];
for (let i = 0; i < quantity.length; i++) {
    quantity[i].addEventListener('change', (e) => {
        let card = e.target.parentNode.parentNode.parentNode.parentNode;

        if (price[i] === undefined) {
            price[i] = Number(card.children[2].textContent);
        }

        card.children[2].textContent = price[i] * Number(e.target.value);
    })
}
</script>
</body>
</html>
```
<h2 style="text-align: center">Файл 16.html</h2>

```html
<!doctype html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport"
          content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
</head>
<body>
    <iframe width="560" height="315" src="https://www.youtube.com/embed/qdDVtFvJwUc?si=lxXdACJE8oKOZQuD" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</html>
```

<h2 style="text-align: center">Файл 17.html</h2>

```html
<!doctype html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport"
          content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Slider</title>
    <style>
        .slider {
            max-width: 100%;
            margin: 0 auto;
            position: relative;
        }
        .slider_form {
            overflow: hidden;
        }
        .slider_photo {
            display: flex;
            will-change: transform;
            transition: transform 0.5s cubic-bezier(0.7, -0.22, 1, -0.24);
        }

        .slider_item {
            flex-shrink: 0;
            flex-grow: 1;
            flex-basis: 100%;
            max-width: 100%;
            height: 300px;
            justify-content: center;
            align-items: center;
            color: white;
            width: 250px;
            border-radius: 10px;
            background: #ffffff;
        }
        .slider_item img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }
        .slider_btn {
            position: absolute;
            top: 50%;
            display: flex;
            flex-direction: row;
            justify-content: center;
            align-items: center;
            width: 30px;
            height: 30px;
            text-align: center;
            border: none;
            border-radius: 5px;
            background: rgba(255, 255, 255, 0.3);
            color: black;
            transform: translateY(-50%);
            cursor: pointer;
        }
        .slider_btn_prev {
            left: 0;
        }
        .slider_btn_next {
            right: 0;
        }
        .slider_btn_hidden {
            display: none;
        }
    </style>
</head>
<body>
<div class="slider" style="width: 500px">
    <div class="slider_form">
        <div class="slider_photo" id="slider">
            <div class="slider_item">
                <img src="img/1.png" alt="мопс 1">
            </div>
            <div class="slider_item">
                <img src="img/2.png" alt="мопс 2">
            </div>
            <div class="slider_item">
                <img src="img/3.png" alt="мопс 3">
            </div>
        </div>
    </div>
    <button class="slider_btn slider_btn_prev"> <</button>
    <button class="slider_btn slider_btn_next"> ></button>
</div>

<script>
    class Slider {
        constructor(nameSliderItems, btnPrev, btnNext, idSlider) {
            this.slides = document.getElementsByClassName(nameSliderItems);
            this.index = 0;
            this.width = 0;
            this.widthAll = 0;
            this.slider = document.getElementById(idSlider);
            this.btnPrev = document.getElementsByClassName(btnPrev)[0];
            this.btnNext = document.getElementsByClassName(btnNext)[0];
            this.btnPrev.addEventListener('click', this.prev.bind(this));
            this.btnNext.addEventListener('click', this.next.bind(this));
            for (let i = 0; i < this.slides.length; i++) {
                this.widthAll += this.slides[i].offsetWidth;
            }

            this.changeBtn();
        }
        show (index) {
            if (index > this.slides.length - 1) {
                console.log(index )
                this.index = 1;
                this.width = 0;
            }

            if (index < 1) {
                this.index = this.slides.length - 1
            }

            let i = 0;
            for (i; i < this.slides.length; i++) {
                this.slides[i].className = this.slides[i].className.replace(' slider_item_active ', '');
            }

            this.slides[this.index].className = this.slides[this.index].className.replace('', ' slider_item_active ');
        }

        next () {
            this.show(this.index += 1);
            this.width += this.slides[this.index].offsetWidth;
            this.changePosition()
        }

        prev () {
            this.show(this.index -= 1);
            this.width -= this.slides[this.index].offsetWidth;
            this.changePosition()
        }

        changeBtn () {
            if (this.width + this.slides[this.index].offsetWidth >= this.widthAll) {
                this.btnNext.className =  this.btnNext.className.replace('', ' slider_btn_hidden ');
            } else {
                this.btnNext.className =  this.btnNext.className.replace(' slider_btn_hidden ', '');
            }

            if (this.width === 0) {
                this.btnPrev.className =  this.btnPrev.className.replace('', ' slider_btn_hidden ');
            } else {
                this.btnPrev.className =  this.btnPrev.className.replace(' slider_btn_hidden ', '');
            }
        }

        changePosition () {
            this.changeBtn();
            this.slider.setAttribute('style', `transform: translate3d(${-this.width}px, 0px, 0px)`);
        }
     }

    let slider = new Slider('slider_item', 'slider_btn_prev', 'slider_btn_next', 'slider');
    slider.show(0);
</script>
</body>
</html>
```

<h2 style="text-align: center">Файл 18.html</h2>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        body {
            background-color: #f4f4f4;
            font-family: Arial, sans-serif;
            
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }

        form {
            background-color: #ffffff;
            padding: 40px;
            border-radius: 10px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        }

        .form_input{
            width: 350px;
            padding: 10px;
            margin: 10px 0;         /*расстояние между текстом и боксом*/
            border: 1px solid #ccc;
            border-radius: 5px;
            margin-bottom: 20px;         /*расстояние между полями*/
            font-family: Arial, sans-serif;
        }

        button{
            background-color: #888888;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }

        button:hover {
            background-color: #50c655;
        }

        .form_error {
            color:  #ea3e3e;
            border: 1px solid  #ea3e3e;;
        }

        .error_text {
            text-align: center;
            border-radius: 10px;
            background-color: #ea3e3e;
            color: white;
            padding: 0.37rem 0.75rem 0.37rem 0.75rem;
            line-height: 1.5;
        }
    
    </style>
</head>
<body>
    <form action="" id="myForm">
            <p id="errorMessage" class="error_text" style="display: none">Пожалуйста, заполните все поля корректно!</p>

            <p style="text-align: center; margin-bottom: 30px;">Оставьте свои контакты для обратной связи:<p>

            <label for="name"><b>Имя:</b></label><br>
            <input class="form_input" type="text" id="name" name="name" placeholder="Введите ваше имя"><br>
                
            <label for="name"><b>Email:</b></label><br>
            <input class="form_input" type="email" id="email" name="email" placeholder="email@mail.ru"><br>
        
            <label for="password"><b>Пароль:</b></label><br>
            <input class="form_input" type="password" id="password" name="password"><br>

            <p style="text-align: center;"><button type="submit">Отправить</button></p>
    </form>

    <script>
        document.getElementById('myForm').addEventListener('submit', function(event) {
            if (!validateForm()) {
                event.preventDefault(); // Отмена отправки формы, если данные не прошли валидацию
                document.getElementById('errorMessage').style.display = 'block';
            }
        });
    
        function validateForm() {
            let nameInput = document.getElementById('name');
            let emailInput = document.getElementById('email');
            let passwordInput = document.getElementById('password');
    
            let name = nameInput.value.trim();
            let email = emailInput.value.trim();
            let password = passwordInput.value.trim();
    
            let isValid = true;
            
            if (name === '') {
                nameInput.classList.add('form_error');
                isValid = false;
            } else {
                nameInput.classList.remove('form_error');
            }
            
            let emailPattern = /^[^\s@]+@[^\s@]+\.[^\s@]+$/;
            if (!email.match(emailPattern)) {
                emailInput.classList.add('form_error');
                isValid = false;
            } else {
                emailInput.classList.remove('form_error');
            }
            
            if (password.length < 5) {
                passwordInput.classList.add('form_error');
                isValid = false;
            } else {
                passwordInput.classList.remove('form_error');
            }
    
            return isValid;
        }
    </script>
    
</body>
</html>
```
<h2 style="text-align: center">Файл 19.html</h2>

```html
<!doctype html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport"
          content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
</head>
<style>
    .bar_menu {
        display: flex;
        align-items: center;
        min-height: 50px;
        background-color: #c6c6c6;
        color: white;
        padding: 10px 20px;
        border-radius: 15px;
    }

    .burger {
        display: flex;
        position: relative;
        z-index: 100;
        align-items: center;
        width: 30px;
        height: 20px;
    }

    .burger middle {
        height: 2px;
        width: 100%;
        transform:scale(1);
        background-color: white;
    }

    .burger::before, .burger::after {
        content: '';
        position: absolute;
        height: 2px;
        width: 100%;
        background-color: white;
        transition: all 0.3s ease 0s;
    }

    .burger::before {
        top: 0;
    }

    .burger::after {
        bottom: 0;
    }

    .burger.active middle {
        transform: scale(0);
    }

    .burger.active::before {
        top: 50%;
        transform: rotate(-45deg) translate(0, -50%);
    }

    .burger.active::after {
        top: 50%;
        transform: rotate(45deg) translate(0, 50%);
    }

    /* Стили для мобильного меню */
    .mobile-menu {
        display: none;
        flex-direction: column;
        position: fixed;
        height: 100%;
        top: 0;
        left: 0;
        bottom: 0;
        right: 0;
        z-index: 50;
        overflow-y: auto;
        padding: 50px 40px;
        background-color: black;
        animation: burgerAnim 0.4s;
        overflow-x: hidden;
    }
    .mobile-menu>ul>li>a {
        color: #dddddd;
        text-decoration: none;
        font-size: 40px;
    }
    .mobile-menu>ul {
        display: flex;
        flex-direction: column;
    }
    .mobile-menu>ul>li {
        padding: 10px;
    }
    .mobile-menu {
        width: 100%;
        padding: 0 40px;
    }
    .mobile-menu ul {
        width: 100%;
        list-style: none;
        display: flex;
        justify-content: space-between;
    }
    @keyframes burgerAnim {
        from {
            opacity: 0;
        }
        to {
            opacity: 1;
        }
    }

    .burger.active {
        display: flex;
    }
    .mobile-menu.open {
        display: flex;
    }
</style>
<body style="font-family: Arial, Helvetica, sans-serif; font-style: italic;">
<div class="bar_menu">
    <div class="burger">
        <middle></middle>
    </div>
    <nav id="mobileMenu" class="mobile-menu">
        <ul>
            <li><a href="#">Факультеты</a></li>
            <li><a href="#">Кафедры</a></li>
            <li><a href="#">Специальности</a></li>
        </ul>
    </nav>
</div>

<script>
    document.querySelector('.burger').addEventListener('click', function() {
        this.classList.toggle('active');
        document.querySelector('.mobile-menu').classList.toggle('open')
    });
</script>
</body>
</html>
```

<h2 style="text-align: center">Файл 20.html</h2>

```html
<!doctype html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport"
          content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
</head>
<body>
<canvas id="myCanvas" width="500" height="200"></canvas>
<script>
    var canvas = document.getElementById('myCanvas');
    var context = canvas.getContext('2d');

    // линия
    context.beginPath();
    context.moveTo(50, 50);
    context.lineTo(150, 150);
    context.strokeStyle = '#f000ff';
    context.lineWidth = 3;
    context.stroke();
    
    // прямоугольник
    context.beginPath();
    context.fillStyle = '#f0f000';
    context.fillRect(180, 50, 100, 100);

    // круг
    context.beginPath();
    context.arc(355, 100, 50, 0, 2 * Math.PI);
    context.fillStyle = '#00f0f0';
    context.fill();
   
</script>
</body>
</html>
```

<h2 style="text-align: center">Файл 21.html</h2>

```html
<!doctype html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport"
          content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
    <link href="style/var.css" rel="stylesheet">
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css" rel="stylesheet">
</head>
<style>
    body{
        font-family: Arial, Helvetica, sans-serif;
        font-style: italic;
    }
    .items {
        display: inline-block;
        vertical-align: middle;
        line-height: normal;
        padding: 10px;
        position: relative;
    }

    .items a {
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
    }
</style>
<body style="display: flex; flex-direction: column; font-size: 50px">
<div class="items">
    <i class="fa-brands fa-telegram" ></i> Telegram
    <a href="https://t.me/infy_x"></a>
</div>
<div class="items">
    <i class="fa-brands fa-vk" style="color: blue"></i> VK
    <a href="https://vk.com/id463135170"></a>
</div>
</body>
</html>
```
<h2 style="text-align: center">Файл 22.html</h2>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        body {
            background-color: #f4f4f4;
            font-family: Arial, sans-serif;
            
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }

        form {
            background-color: #ffffff;
            padding: 40px;
            border-radius: 10px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        }

        .form_input{
            width: 250px;
            padding: 10px;
            margin: 10px 0;         /*расстояние между текстом и боксом*/
            border: 1px solid #ccc;
            border-radius: 5px;
            margin-bottom: 20px;         /*расстояние между полями*/
            font-family: Arial, sans-serif;
        }

        button{
            background-color: #888888;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }

        button:hover {
            background-color: #50c655;
        }

        .form_error {
            color:  #ea3e3e;
            border: 1px solid  #ea3e3e;
        }

        .error_text {
            width: 250px;
            text-align: center;
            border-radius: 10px;
            background-color: #ea3e3e;
            color: white;
            padding: 0.37rem 0.75rem 0.37rem 0.75rem;
            line-height: 1.5;
        }
    
    </style>
</head>
<body>
    <form action="" id="myForm">
            <p id="errorMessage" class="error_text" style="display: none">Пожалуйста, заполните все поля корректно!</p>

            <p style="text-align: center; margin-bottom: 30px; font-size: 20px;"><b>РЕГИСТРАЦИЯ</b><p>

            <label for="name"><b>Имя:</b></label><br>
            <input class="form_input" type="text" id="name" name="name" placeholder="Введите ваше имя"><br>
                
            <label for="name"><b>Email:</b></label><br>
            <input class="form_input" type="email" id="email" name="email" placeholder="email@mail.ru"><br>
        
            <label for="password1"><b>Пароль:</b></label><br>
            <input class="form_input" type="password" id="password1" name="password1"><br>

            <label for="password2"><b>Повторите пароль</b></label><br>
            <input class="form_input" type="password" id="password2" name="password2"><br>

            <p style="text-align: center;"><button type="submit">Отправить</button></p>
    </form>

    <script>
        let message = '';
        document.getElementById('myForm').addEventListener('submit', function(event) {
            if (!validateForm()) {
                event.preventDefault(); // Отмена отправки формы, если данные не прошли валидацию
                document.getElementById('errorMessage').style.display = 'block';
                document.getElementById('errorMessage').textContent = message;
            }
        });
    
        function validateForm() {
            let nameInput = document.getElementById('name');
            let emailInput = document.getElementById('email');
            let passwordInput = document.getElementById('password1');
            let password2Input = document.getElementById('password2');
    
            let name = nameInput.value.trim();
            let email = emailInput.value.trim();
            let password = passwordInput.value.trim();
            let password2 = password2Input.value.trim();
    
            if (name === '') {
                nameInput.classList.add('form_error');
                message = 'Имя не указано!';
                return false;
            } else {
                nameInput.classList.remove('form_error');
            }
    
            let emailPattern = /^[^\s@]+@[^\s@]+\.[^\s@]+$/;
            if (!email.match(emailPattern)) {
                message = 'Неверный формат email!';
                emailInput.classList.add('form_error');
                return false;
            } else {
                emailInput.classList.remove('form_error');
            }
    
            if (!checkPassword(password)) {
                passwordInput.classList.add('form_error');
                message = 'Пароль должен иметь минимум 5 символов. Необходимо использовать символы .?#%, а также строчные и заглавные буквы!';
                return false;
            } else {
                passwordInput.classList.remove('form_error');
            }
    
            if (password !== password2) {
                passwordInput.classList.add('form_error');
                password2Input.classList.add('form_error');
                message = 'Пароли не совпадают!';
                return false;
            } else {
                passwordInput.classList.remove('form_error');
                password2Input.classList.remove('form_error');
            }
    
            return true;
        }
    
        function checkPassword(password) {
            if (password.length < 5) {
                return false;
            }
    
            if (!/[.?#%]/.test(password)) {
                return false;
            }
    
            if (!/[a-z]/.test(password) || !/[A-Z]/.test(password)) {
                return false;
            }
    
            return true;
        }
    </script>

</body>
</html>
```

<h2 style="text-align: center">Файл 23.html</h2>

```html
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport"
          content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
    <link rel="stylesheet" href="style/table.css">
</head>
<head>
    <title>Табличное представление данных</title>
    <style>
        body{
            font-family: Arial, Helvetica, sans-serif;
        }
        table {
            border-collapse: collapse;
            width: 100%;
        }

        th, td {
            border: 1.5px solid #ddd;
            padding: 10px;
            text-align: left;
        }

        th {
            cursor: pointer;
        }

        .form_input{
            width: 490px;
            padding: 10px;
            margin: 10px 0;         /*расстояние между текстом и боксом*/
            border: 1.5px solid #ddd;
            border-radius: 5px;
            margin-bottom: 20px;         /*расстояние между полями*/
            font-family: Arial, sans-serif;
        }
    </style>
</head>
<body>
<div style="display:flex; flex-direction:column; justify-content: center; align-items: center; text-align: center;">
    <div style="width: 70%">
        <h1><i>Сортировка</i></h1>
        
        <label>
            <input type="text" id="filterInput" class="form_input" placeholder="Фильтр">
        </label>

        <table id="dataTable">
            <thead>
            <tr>
                <th onclick="sortTable(0)">Имя</th>
                <th onclick="sortTable(1)">Возраст</th>
                <th onclick="sortTable(2)">Специальность</th>
            </tr>
            </thead>
            <tbody>
            <tr>
                <td>Макс</td>
                <td>19</td>
                <td>Примат</td>
            </tr>
            <tr>
                <td>Диана</td>
                <td>19</td>
                <td>Примат</td>
            </tr>
            <tr>
                <td>Андрей</td>
                <td>22</td>
                <td>Электроэнергетик</td>
            </tr>
            <tr>
                <td>Андрей</td>
                <td>20</td>
                <td>Примат</td>
            </tr>
            <tr>
                <td>Влад</td>
                <td>19</td>
                <td>Электроэнергетик</td>
            </tr>
            </tbody>
        </table>
    </div>
</div>

<script>
    function sortTable(columnIndex) {
        let table, rows, switching, i, x, y, shouldSwitch;
        table = document.getElementById("dataTable");
        switching = true;

        while (switching) {
            switching = false;
            rows = table.getElementsByTagName("tr");

            for (i = 1; i < (rows.length - 1); i++) {
                shouldSwitch = false;
                x = rows[i].getElementsByTagName("td")[columnIndex];
                y = rows[i + 1].getElementsByTagName("td")[columnIndex];

                if (x.innerHTML.toLowerCase() > y.innerHTML.toLowerCase()) {
                    shouldSwitch = true;
                    break;
                }
            }

            if (shouldSwitch) {
                rows[i].parentNode.insertBefore(rows[i + 1], rows[i]);
                switching = true;
            }
        }
    }

    document.getElementById("filterInput").addEventListener("input", function() {
        let filterValue = this.value.toLowerCase();
        let table = document.getElementById("dataTable");
        let rows = table.getElementsByTagName("tr");

        for (let i = 1; i < rows.length; i++) {
            let rowData = rows[i].getElementsByTagName("td");
            let showRow = false;

            for (let j = 0; j < rowData.length; j++) {
                let cellData = rowData[j].innerHTML.toLowerCase();

                if (cellData.indexOf(filterValue) > -1) {
                    showRow = true;
                    break;
                }
            }

            rows[i].style.display = showRow ? "" : "none";
        }
    });
</script>
</body>
</html>
```
<h2 style="text-align: center">Файл 24.html</h2>

```html
<!doctype html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport"
          content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <link rel="preconnect" href="https://fonts.gstatic.com">
    <link href="https://fonts.googleapis.com/css2?family=Caveat&display=swap" rel="stylesheet">
    <title>Document</title>
    <style>
        * {
            font-family: 'Caveat', cursive;
            font-style: normal;
        }
    </style>
</head>
<body>
    <h2>
        <b>Что нужно знать, чтобы делать сайты</b>
    </h2>
    <ol>
        <li><b>HTML</b></li>
        <li><i>CSS</i></li>
        <li>PHP</li>
        <li>SQL</li>
        <li>JavaScript</li>
        <li>jQuery</li>
        <li>Flash</li>
        <li>SEO</li>
    </ol>
    <h4>PHP и JavaScript</h4>
    <p>Языки программирования <b>PHP</b> и <b>JavaScript</b> позволяют сделать сайт динамичным, то есть реагирующим на действия пользователя. Например, можно сделать красивую выпадающую менюшку или слайдер</p>
    <h4>Виды скриптов</h4>
    <p>Для этого пишутся скрипты (англ. <i>script</i> - «сценарий») - программы, позволяющиее реагировать на действия пользователя. Скрипты бывают двух видов:</p>
    <ul>
        <li> те, которые выполняются на сервере, а результат их выполнения приходит в браузер к пользователю уже в готовом виде. Это скрипты, написанные на языке <b>PHP</b>. На нем пишуться <b>CMS-ки</b> – системы управления контентом.</li>
        <li>те, которые выполняются прямо в браузере пользователя. Это скрипты, написанные на языке <b>JavaScript</b>. Они чаще всего используются для, того чтобы сделать страницу более удобной и красивой.</li>
    </ul>
</body>
</html>
```

<h2 style="text-align: center">Файл 25.html</h2>

```html
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport"
          content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
    <style>
        .drag-item {
            width: 100px;
            height: 100px;
            padding: 10px;
            text-align: center;
            border: none;
            border-radius: 10px;
            cursor: move;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;

        }
        
        .drop-area {
            display: flex;
            position:relative;
            flex-direction: row;
            justify-content: flex-start;
            align-content: start;
            flex-wrap: wrap;
            min-height: 260px;
            width: 36%;
            background-color: #f7f7f7;
            border: 2px dashed #aaa;
            border-radius: 5px;
            margin-top: 20px;
            padding: 20px;
            gap:15px;
        }

        .drop-area__center {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
        }

        body{
            font-family: Arial, Helvetica, sans-serif;
        }
    </style>
</head>
<body>
<h1><i>Drag & Drop</i></h1>

<div style="display: flex; flex-wrap: wrap; flex-direction: row; gap: 15px;">
    
    <div class="drag-item" style="background-color: #ea580f;" draggable="true">
        <span>1</span>
    </div>

    <div class="drag-item" style="background-color: #98df2e;" draggable="true">
        <span>2</span>
    </div>

    <div class="drag-item" style="background-color: #14aced;" draggable="true">
        <span>3</span>
    </div>

    <div class="drag-item" style="background-color: #f3d31d;" draggable="true">
        <span>4</span>
    </div>

</div>

<div style="display: flex; flex-direction: column;">
    <div class="drop-area" id="dropArea">
        <span class="drop-area__center">Here</span>
    </div>
</div>

<script>
    let dragItem = document.getElementsByClassName('drag-item');
    for (let i = 0; i < dragItem.length; i++) {
        dragItem[i].id = `drag${i}`
        dragItem[i].addEventListener('dragstart', drag);
    }

    let dropArea = document.getElementById('dropArea');

    dropArea.addEventListener('dragover', allowDrop);
    dropArea.addEventListener('drop', drop);

    function allowDrop(event) {
        event.preventDefault();
    }

    function drag(event) {
        event.dataTransfer.setData('text', event.target.id);
    }

    function drop(event) {
        event.preventDefault();
        let data = event.dataTransfer.getData('text');
        let draggedItem = document.getElementById(data);

        if (event.target.className === 'drop-area') {
            event.target.appendChild(draggedItem);
        }
    }
</script>
</body>
</html>
```
<h2 style="text-align: center">Файл 26.html</h2>

```html
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport"
          content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>

    <style>
        body {
            font-family: "Calibri Light",serif;
            font-weight: bold;
            background-color:rgb(255, 206, 123);
        }

        .form {
            padding: 10px;
        }

        .form_grid {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            grid-template-rows: repeat(2, 1fr);
            grid-gap: 10px;
        }

        .item_grid_1 {
            display: grid;
            grid-column-start: 1;
            grid-column-end: 3;
            grid-row-start: 1;
            grid-row-end: 3;
        }

        .item_grid_2 {
            display: grid;
            grid-column-start: 3;
            grid-column-end: 5;
            grid-row-start: 1;
            grid-row-end: 1;
        }

        .item_grid_3 {
            display: grid;
            grid-column-start: 3;
            grid-column-end: 3;
            grid-row-start: 2;
            grid-row-end: 2;
        }

        .item_grid_4 {
            display: grid;
            grid-column-start: 4;
            grid-column-end: 4;
            grid-row-start: 2;
            grid-row-end: 2;
        }

        .items {
            display: flex;
            flex-direction: column;
            justify-content: space-between;
            gap: 50px;
            color: white;
            overflow: hidden;
            

            background-color: rgba(45, 45, 45, 0.5);
            padding: 20px;
            border-radius: 15px;
        }

        .btn {
            width: 20px;
            height: 20px;
            padding: 15px;
            text-align: center;
            border-radius: 15px;
            background-color: rgb(230, 159, 8);
        }

        .btn_1 {
            background-color: rgba(100, 100, 100, 0.93);
            width: auto;
            height: auto;
            padding: 20px 30px;
            margin-left: auto; margin-right: auto;
            font-size: 20px;
        }
        
        @media screen and (max-width: 600px) {
            .form_flex {
                display: flex;
                flex-direction: column;
            }
        }
    </style>
</head>
<body>
<div class="form">
    <div class="form_grid form_flex">
        
        <div class="items item_grid_1" style="background-color: rgba(179, 179, 179, 0.91);">
            <div style="font-size: 50px;">
                Оказание любых углуг в кратчайшие сроки!
            </div>
                <div class="btn btn_1">Рассчитать стоимость услуги</div>
        </div>

        <div class="items item_grid_2">
            <div style="font-size: 30px;">
                Услуга №1
            </div>
            <div class="btn">></div>
        </div>

        <div class="items item_grid_3">
            <div style="font-size: 30px;">
                Услуга №2
            </div>
            <div class="btn">></div>
        </div>

        <div class="items item_grid_4">
            <div style="font-size: 30px;">
                Услуга №3
            </div>
            <div class="btn">></div>
        </div>

    </div>
</div>
</body>
</html>
```

<h1 align = "center">Результат:</h1>

<p>По завершении лабораторной работой были выполнены 26 заданий. </p>

<h1 align = "center">Вывод:</h1>
<p>Полученные знания о HTML были отработаны на практике при решении поставленных задач.</p>
