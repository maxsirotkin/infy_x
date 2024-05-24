<p align = "center">МИНИСТЕРСТВО НАУКИ И ВЫСШЕГО ОБРАЗОВАНИЯ<br>
РОССИЙСКОЙ ФЕДЕРАЦИИ<br>
ФЕДЕРАЛЬНОЕ ГОСУДАРСТВЕННОЕ БЮДЖЕТНОЕ<br>
ОБРАЗОВАТЕЛЬНОЕ УЧРЕЖДЕНИЕ ВЫСШЕГО ОБРАЗОВАНИЯ<br>
«САХАЛИНСКИЙ ГОСУДАРСТВЕННЫЙ УНИВЕРСИТЕТ»</p>
<br><br><br><br><br><br>
<p align = "center">Институт естественных наук и техносферной безопасности<br>Кафедра информатики<br>Сироткин Максим Сергеевич</p>
<br><br><br>
<p align = "center"><br><strong>Лабораторная работа №3.«HTML»</strong><br>01.03.02 Прикладная математика и информатика</p>
<br><br><br><br><br><br><br><br><br><br><br><br>
<p align = "right">Научный руководитель<br>
Соболев Евгений Игоревич</p>
<br><br><br>
<p align = "center">г. Южно-Сахалинск<br>2024 г.</p>
<br><br><br><br><br><br><br><br><br><br><br><br>

<h1 align = "center">Введение</h1>

<p><b>Веб-разработка</b> — это процесс создания и поддержки веб-сайтов и веб-приложений. Веб-разработка включает в себя различные аспекты, такие как дизайн, программирование, создание контента и оптимизацию для веб-среды. Основной целью веб-разработки является создание функциональных, эстетичных и удобных в использовании веб-ресурсов для пользователей.
<p><b>Процесс веб-разработки обычно включает в себя следующие этапы:</b>
<li>1. Планирование: Определение целей и требований к веб-сайту, анализ целевой аудитории, выбор технологий и платформы.;</li>
<li>2. Дизайн: Создание дизайна веб-сайта, включая макеты, цветовую схему, шрифты и другие визуальные элементы.;</li>
<li>3. Разработка: Написание кода для реализации дизайна и функциональности веб-сайта, использование языков программирования (например, HTML, CSS, JavaScript) и фреймворков.;</li>
<li>4. Тестирование: Проверка работоспособности, кросс-браузерной совместимости и отзывчивости веб-сайта, исправление ошибок и улучшение пользовательского опыта.;</li>
<li>5. Развертывание: Загрузка веб-сайта на сервер, настройка хостинга, доменного имени и других аспектов, чтобы сделать сайт доступным для пользователей в интернете.;</li>
<li>6. Поддержка и обновление: Поддержка веб-сайта, внесение изменений, добавление нового контента, обновление безопасности и оптимизация для улучшения производительности.;</li>
Веб-разработка может включать как создание статических веб-сайтов с информационным содержанием, так и разработку интерактивных веб-приложений, электронной коммерции, блогов и других онлайн-ресурсов. Веб-разработка играет важную роль в современном цифровом мире, обеспечивая доступ к информации и услугам через интернет.
<br>
<p></p>
<h1 align = "center">Цели и задачи:</h1>
  1. Поиск и изучение информации по веб-разработке и языку HTML.<br>
  2. Получение практического опыта в среде Visual studio Code при работе с языкоме HTML.<br>
  3. Используя полученные знания и навыки, применить их при выполнении заданий.<br>


<p></p>



<h1 align = "center">Решение</h1>

Для выполнения этой лабораторной работы я пользовался:<br>
1. Различным материалом в сети интернет.<br>
2. Материалом с сайта https://htmlacademy.ru/blog/css/css-background?ysclid=lsy65ncyww813760034<br>
3. Материалом с сайта https://habr.com/ru/companies/netologyru/articles/690042/<br>


<h2 align = "center">Задание "1.html"</h2>

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width, initial-scale=1.0">
        <title>"Лаба №3"</title>
    </head>

    <body style="background-color:rgb(255, 255, 255);">
        <h1 class="heading">Hello world</h1>
        <h2 class="heading">Hello world</h2>
        <h3 class="heading">Hello world</h3>
        <h4 class="heading">Hello world</h4>
        <h5 class="heading">Hello world</h5>
        <h6 class="heading">Hello world</h6>
    </body>
</html>
```

<h2 align = "center">Задание "2.html"</h2>

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width, initial-scale=1.0">
        <title>"Лаба №3"</title>
    </head>

    <body style="background-color:rgb(255, 255, 255);">
        <h1 id="heading-1" class="heading">Hello world</h1>
        <h2 id="heading-2" class="heading">Hello world</h2>
        <h3 id="heading-3" class="heading">Hello world</h3>
        <h4 id="heading-4" class="heading">Hello world</h4>
        <h5 id="heading-5" class="heading">Hello world</h5>
        <h6 id="heading-6" class="heading">Hello world</h6>
    </body>
</html>
```

<h2 align = "center">Задание "3.html"</h2>

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width, initial-scale=1.0">
        <title>"Лабораторная работа №3"</title>
        <style>
            .heading {
                color: red;
            }
        </style>
    </head>

    <body style="background-color:blueviolet;">
        <h1 id="heading-1" class="heading">Hello world</h1>
        <h2 id="heading-2" class="heading">Hello world</h2>
        <h3 id="heading-3" class="heading">Hello world</h3>
        <h4 id="heading-4" class="heading">Hello world</h4>
        <h5 id="heading-5" class="heading">Hello world</h5>
        <h6 id="heading-6" class="heading">Hello world</h6>
    </body>
</html>
```

<h2 align = "center">Задание "4.html"</h2>

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width, initial-scale=1.0">
        <title>"Лаба №3"</title>
        <style>
            .heading {
                color: red;
            }
            #heading-2 {
                color: blue;
            }
        </style>
    </head>

    <body style="background-color:rgb(255, 255, 255);">
        <h1 id="heading-1" class="heading">Hello world</h1>
        <h2 id="heading-2" class="heading">Hello world</h2>
        <h3 id="heading-3" class="heading">Hello world</h3>
        <h4 id="heading-4" class="heading">Hello world</h4>
        <h5 id="heading-5" class="heading">Hello world</h5>
        <h6 id="heading-6" class="heading">Hello world</h6>
    </body>
</html>
```

<h2 align = "center">Задание "5.html"</h2>

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width, initial-scale=1.0">
        <title>"Лаба №3"</title>
        <style>
            .heading {
                color: red;
            }
            #heading-2 {
                color: blue;
            }
            #heading-3 {
                background-color: black;
                color: white;
            }
        </style>
    </head>

    <body style="background-color:rgb(255, 255, 255);">
        <h1 id="heading-1" class="heading">Hello world</h1>
        <h2 id="heading-2" class="heading">Hello world</h2>
        <h3 id="heading-3" class="heading">Hello world</h3>
        <h4 id="heading-4" class="heading">Hello world</h4>
        <h5 id="heading-5" class="heading">Hello world</h5>
        <h6 id="heading-6" class="heading">Hello world</h6>
    </body>
</html>
```

<h2 align = "center">Задание "6.html"</h2>

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width, initial-scale=1.0">
        <title>"Лаба №3"</title>
        <style>
            .heading {
                color: red;
            }
            #heading-2 {
                color: blue;
            }
            #heading-3 {
                background-color: black;
                color: white;
            }
            #heading-4 {
                border: 2px solid black;
                border-radius: 10px;
            }
        </style>
    </head>

    <body style="background-color:rgb(255, 255, 255);">
        <h1 id="heading-1" class="heading">Hello world</h1>
        <h2 id="heading-2" class="heading">Hello world</h2>
        <h3 id="heading-3" class="heading">Hello world</h3>
        <h4 id="heading-4" class="heading">Hello world</h4>
        <h5 id="heading-5" class="heading">Hello world</h5>
        <h6 id="heading-6" class="heading">Hello world</h6>
    </body>
</html>
```

<h2 align = "center">Задание "7.html"</h2>

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width, initial-scale=1.0">
        <title>"Лаба №3"</title>
        <style>
            .heading {
                color: red;
            }
            #heading-2 {
                color: blue;
            }
            #heading-3 {
                background-color: black;
                color: white;
            }
            #heading-4 {
                border: 2px solid black;
                border-radius: 10px;
            }
            #heading-5:hover {
                color: green;
            }
        </style>
    </head>

    <body style="background-color:rgb(255, 255, 255);">
        <h1 id="heading-1" class="heading">Hello world</h1>
        <h2 id="heading-2" class="heading">Hello world</h2>
        <h3 id="heading-3" class="heading">Hello world</h3>
        <h4 id="heading-4" class="heading">Hello world</h4>
        <h5 id="heading-5" class="heading">Hello world</h5>
        <h6 id="heading-6" class="heading">Hello world</h6>
    </body>
</html>
```

<h2 align = "center">Задание "8.html"</h2>

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width, initial-scale=1.0">
        <title>"Лаба №3"</title>
    </head>

    <body style="background-color:rgb(255, 255, 255);">
        <input type="text" placeholder="Text">
        <input type="password" placeholder="Password">
        <input type="number" placeholder="Number">
        <input type="email" placeholder="Email">
        <input type="date" placeholder="Date">
        <input type="checkbox" id="checkbox"> <label for="checkbox">Checkbox</label>
    </body>
</html>
```

<h2 align = "center">Задание "9.html"</h2>

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width, initial-scale=1.0">
        <title>"Лаба №3"</title>
    </head>

    <body style="background-color:rgb(255, 255, 255);">
        <ol>
            <li>Нумерованный</li>
            <li>Нумерованный</li>
            <li>Нумерованный</li>
            <li>Нумерованный</li>
        </ol>
    </body>
</html>
```

<h2 align = "center">Задание "10.html"</h2>

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width, initial-scale=1.0">
        <title>"Лаба №3"</title>
    </head>

    <body style="background-color:rgb(255, 255, 255);">
        <ul style="list-style-type: square;">
            <li>Маркированный</li>
            <li>Маркированный</li>
            <li>Маркированный</li>
            <li>Маркированный</li>
        </ul>
    </body>
</html>
```

<h2 align = "center">Задание "11.html"</h2>

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>"Лаба №3"</title>
        <style>
            body {
                background-color: green;
                color: white;
            }
        </style>
    </head>
    <body>
        <p>один, два, три, четыре, пять, шесть, семь, восемь, девять, десять.</p>
        <p>одиннадцать, двенадцать, тринадцать, четырнадцать, пятнадцать, шестнадцать, семнадцать, восемнадцать, девятнадцать, двадцать.</p>
        <p>двадцать один, двадцать два, двадцать три, двадцать четыре, двадцать пять, двадцать шесть, двадцать семь, двадцать восемь, двадцать девять, тридцать.</p>
    </body>
</html>
```

<h2 align = "center">Задание "12.html"</h2>

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>"Лаба №3"</title>
    <style>
      .container {
        display: flex;
        flex-wrap: wrap;
        justify-content: space-between;
      }
      .block {
        width: 100px;
        height: 100px;
        background-color: green;
        margin: 10px;
      }
    </style>
  </head>
  <body>
    <div class="container">
      <div class="block">1</div>
      <div class="block">2</div>
      <div class="block">3</div>
      <div class="block">4</div>
      <div class="block">5</div>
      <div class="block">6</div>
    </div>
  </body>
</html>
```

<h2 align = "center">Задание "13.html"</h2>

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>"Лаба №3"</title>
    <style>
      body {
        display: flex;
        justify-content: center;
        align-items: center;
        height: 100vh;
      }
      .container {
        display: flex;
        flex-wrap: wrap;
        justify-content: space-between;
      }
      .block {
        width: 100px;
        height: 100px;
        background-color: green;
        margin: 10px;
      }
    </style>
  </head>
  <body>
    <div class="container">
      <div class="block">1</div>
      <div class="block">2</div>
      <div class="block">3</div>
      <div class="block">4</div>
      <div class="block">5</div>
      <div class="block">6</div>
    </div>
  </body>
</html>
```

<h2 align = "center">Задание "14.html"</h2>

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>"Лаба №3"</title>
  </head>
  <body>
    <iframe width="800" height="600" src="https://porodysobak.ru/wp-content/uploads/2022/07/mops-3.jpg" frameborder="0" allowfullscreen></iframe>
  </body>
</html>
```

<h2 align = "center">Задание "15.html"</h2>

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>"Лаба №3"</title>
    <style>
      body {
        font-family: Arial, sans-serif;
        background-color: #f4f4f4;
        
        display: flex;
        justify-content: center;
        align-items: center;
        height: 100vh;
      }
      form {
        background-color: #ffffff;
        padding: 30px;
        border-radius: 10px;
        box-shadow: 0 2px 10px rgba(0,0,0,0.1);
      }
      input[type="text"],
      input[type="email"],
      input[type="password"],
      button {
        width: 100%;
        padding: 10px;
        margin-bottom: 10px;
        border: 1px solid #ccc;
        border-radius: 3px;
        box-sizing: border-box;
        font-size: 16px;
      }
      button {
        background-color: #007bff;
        color: #fff;
        cursor: pointer;
      }
      button:hover {
        background-color: #0056b3;
      }
    </style>
  </head>
  <body>
    <form>
      <input type="text" name="username" placeholder="Username" required>
      <input type="email" name="email" placeholder="Email" required>
      <input type="password" name="password" placeholder="Password" required>
      <button type="submit">Sing up</button>
    </form>
  </body>
</html>
```

<h2 align = "center">Задание "16.html"</h2>

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>"Лаба №3"</title>
        <style>
            body {
                font-family: Arial, sans-serif;
            }
            table {
                width: 100%;
                border-collapse: collapse;
            }
            th, td {
                border: 1px solid #ccc;
                padding: 8px;
                text-align: center;
            }
            th {
                background-color: #f2f2f2;
            }
        </style>
    </head>
    <body>
        <table>
            <thead>
                <tr>
                    <th>Имя</th>
                    <th>Дата рождения</th>
                    <th>Город</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Макс</td>
                    <td>12.07.2004</td>
                    <td>Южно-Сахалинск</td>
                </tr>
                <tr>
                    <td>Диана</td>
                    <td>28.10.2004</td>
                    <td>Южно-Сахалинск</td>
                </tr>
            </tbody>
        </table>
    </body>
</html>
```

<h2 align = "center">Задание "17.html"</h2>

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width, initial-scale=1.0">
        <title>"Лаба №3"</title>
        <style>
            h1 {
                color: red;
            }
        </style>
    </head>

    <body style="background-color:rgb(255, 255, 255);">
        <h1>Hello world!</h1>
    </body>
</html>
```

<h2 align = "center">Задание "18.html"</h2>

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width, initial-scale=1.0">
        <title>"Лаба №3"</title>
        <style>
            p {
                font-family: Arial, sans-serif;
            }
        </style>
    </head>

    <body style="background-color:rgb(255, 255, 255);">
        <p>Вебы топ :D</p>
        <p>Это лабораторная работа №3 :D</p>
    </body>
</html>
```

<h2 align = "center">Задание "19.html"</h2>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>"Лаба №3"</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            
            background-color: #aeaeae;
        }
        .container {
            width: 300px;
            height: 150px;
            background-color: rgb(255, 255, 255);
            border-radius: 20px;
            box-shadow: 0 5px 10px rgba(0, 0, 0, 0.1);
            padding: 10px;
            text-align: center;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Веб-страница с блоком</h1>
        <p>Блок div имеет тень</p>
    </div>
</body>
</html>
```

<h2 align = "center">Задание "20.html"</h2>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>"Лаба №3"</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            
            background-color: #f0f0f0;

            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }
        .container {
            width: 300px;
            height: 150px;
            background-color: rgb(255, 255, 255);
            border-radius: 20px;
            box-shadow: 0 5px 10px rgba(0, 0, 0, 0.1);
            padding: 10px;
            text-align: center;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Веб-страница с блоком</h1>
        <p>Блок div имеет тень</p>
    </div>
</body>
</html>
```

<h2 align = "center">Задание "21.html"</h2>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>"Лаба №3"</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #ffffff;
        }
        h1 {
            color: rgb(0, 0, 0);
            animation: blink 1s infinite;
        }
        @keyframes blink {
            0% {color: black;}
            50% {color: red;}
            100% {color: black;}
        }
    </style>
</head>
<body>
    <h1>Пример анимации, которая мигает</h1>
</body>
</html>
```

<h2 align = "center">Задание "22.html"</h2>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>"Лаба №3"</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }
        .container {
            width: 300px;
            height: 200px;
            background-color: white;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            text-align: center;

            padding: 100px;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Это пример блока с отступами</h1>
    </div>
</body>
</html>
```

<h2 align = "center">Задание "23.html"</h2>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>"Лаба №3"</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #ffffff;
        }

        a {
            color: #000000;
            text-decoration: none;
            transition: color 0.3s;
        }
        a:hover {
            color: #ff0000;
        }
    </style>
</head>
<body>
    <a href="#">Это пример ссылки.</a>
</body>
</html>
```

<h2 align = "center">Задание "24.html"</h2>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>"Лаба №3"</title>
</head>
<body>
    <img src="24.jpg" alt="sunflowers" style="border: 10px solid black;">
</body>
</html>
```

<h2 align = "center">Задание "25.html"</h2>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>"Лаба №3"</title>
    <style>
        ul {
            list-style-type: square;
        }
    </style>
</head>
<body>
    <p>Пример списка с маркерами в виде квадратов:</p>
    <ul>
        <li>Item 1</li>
        <li>Item 2</li>
        <li>Item 3</li>
    </ul>
</body>
</html>
```

<h2 align = "center">Задание "26.html"</h2>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>"Лаба №3"</title>
    <style>
        div {
            width: 200px;
            height: 100px;
            background-color: rgb(229, 229, 229);
        }
    </style>
</head>
<body>
    <div>Это блок размерами 100 пикселей в высоту и 200 пикселей в ширину"</div>
</body>
</html>
```

<h2 align = "center">Задание "27.html"</h2>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>"Лаба №3"</title>
    <style>
        table {
            border-collapse: collapse;
            width: 10%;
        }

        table tr:nth-child(even) {
            background-color: grey;
        }

        table th, table td {
            border: 1px solid black;
            padding: 8px;
            text-align: left;
        }
    </style>
</head>
<body>
    <table>
        <thead>
            <tr>
                <th>Заголовок</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>1</td>
            </tr>
            <tr>
                <td>2</td>
            </tr>
            <tr>
                <td>3</td>
            </tr>
            <tr>
                <td>4</td>
            </tr>
            <tr>
                <td>5</td>
            </tr>
        </tbody>
    </table>
</body>
</html>
```

<h2 align = "center">Задание "28.html"</h2>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>"Лаба №3"</title>
    <style>
        .button {
            background-color: #cacaca;
            border: 5px solid ;
            color: rgb(0, 0, 0);
            padding: 20px 40px;
            text-align: center;
            font-size: 18px;
            margin: 10px 10px;
            cursor: pointer;
            
            transition: background-color 0.3s;
        }

        .button:hover {
            background-color: #ff0000;
        }
    </style>
</head>
<body>
    <button class="button">BUTTON</button>
</body>
</html>
```

<h2 align = "center">Задание "29.html"</h2>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>"Лаба №3"</title>
    <style>
        .element {
            width: 500px;
            height: 300px;
            background-image: url('29.jpg');
            background-position: center;
            background-repeat: no-repeat;
            background-size: cover;

            text-align: center;
            font-size: 18px;
            color: rgb(0, 0, 0);
            font-family: Arial, sans-serif;
            margin: 0 auto;
        }
    </style>
</head>
<body>
    <div class="element">мопс :D</div>
</body>
</html>
```

<h2 align = "center">Задание "30.html"</h2>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>"Лаба №3"</title>
    <style>
        form {
            width: 400px;
            margin: 0 auto;
        }

        input[type="text"], textarea {
            width: 100%;
            padding: 10px;
            margin: 5px 0;
            border: 1px solid #ccc;
            border-radius: 4px;
            box-sizing: border-box;
        }

        input[type="submit"] {
            background-color: #888888;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }

        input[type="submit"]:hover {
            background-color: #50c655;
        }

    </style>
</head>
<body>
    <form>
        <label for="name">Name:</label><br>
        <input type="text" placeholder="Enter your name"><br>
        <label for="message">Message:</label><br>
        <textarea placeholder="Text"></textarea><br>
        
        <input type="submit" value="Submit">
    </form>
</body>
</html>
```

<h2 align = "center">Задание "31.html"</h2>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>"Лаба №3"</title>
    <style>
        form {
            width: 400px;
            margin: 0 auto;
        }

        input[type="text"], textarea {
            width: 100%;
            padding: 10px;
            margin: 5px 0;
            border: 1px solid #ccc;
            border-radius: 6px;
            box-sizing: border-box;

            outline: 2px solid rgb(215, 215, 215);
        }

        input[type="submit"] {
            background-color: #888888;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }

        input[type="submit"]:hover {
            background-color: #50c655;
        }

    </style>
</head>
<body>
    <form>
        <label for="name">Name:</label><br>
        <input type="text" placeholder="Enter your name"><br>
        <label for="message">Message:</label><br>
        <textarea placeholder="Text"></textarea><br>
        
        <input type="submit" value="Submit">
    </form>
</body>
</html>
```

<h2 align = "center">Задание "32.html"</h2>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>"Лаба №3"</title>
</head>
<style>
    body {
        font-family: Arial, sans-serif;
        margin: 0;
        padding: 0;
        background-color: #f0f0f0;
        display: flex;
        justify-content: center;
        align-items: center;
        height: 100vh;
    }
    .container {
        width: 400px;
        height: 150px;
        background-color: white;
        border-radius: 10px;
        box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        text-align: center;
        padding: 10px;
    }
</style>
<body>
    <div class="container" style="text-align: center;">
        <h1>Пример выравнивания по центру</h1>
        <p>Текст выровнен по центру</p>
    </div>
</body>
</html>
```

<h2 align = "center">Задание "33.html"</h2>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>"Лаба №3"</title>
    <style>
        .dropdown-content {
            display: none;
            position: absolute;
            background-color: #e5e5e5;
        }

        .dropdown-content a {
            color: black;
            padding: 10px 10px;
            text-decoration: none;
            display: block;
        }

        .dropdown:hover .dropdown-content {
            display: block;
        }
    </style>
</head>
<body>
    <div class="dropdown">
        <button class="dropbtn">МЕНЮ</button>
        <div class="dropdown-content">
            <a href="#">Ссылка №1</a>
            <a href="#">Ссылка №2</a>
            <a href="#">Ссылка №3</a>
        </div>
    </div>
</body>
</html>
```

<h2 align = "center">Задание "34.html"</h2>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>"Лабораторная работа №3"</title>
    <style>
        .shadow-text {
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
        }
    </style>
</head>
<body>
    <h1 class="shadow-text">Текст с тенью</h1>
    <p class="shadow-text">Этот текст также имеет тень.</p>
</body>
</html>
```

<h2 align = "center">Задание "35.html"</h2>

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>"Лаба №3"</title>
  <style>
    @keyframes fadeIn {
      from {
        opacity: 0;
      }
      to {
        opacity: 1;
      }
    }

    .fade-in-element {
      opacity: 0;
      animation: fadeIn 4s ease-in-out forwards;
    }
  </style>
</head>
<body>
  <div class="fade-in-element">
    <h1 style="font-family: Arial, Helvetica, sans-serif;">Текст плавно появляется :D</h1>
  </div>
</body>
</html>
```

<h2 align = "center">Задание "36.html"</h2>

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>"Лаба №3"</title>
  <style>
    h1, h2, h3, h4, h5, h6 {
      font-size: 18px;
    }
  </style>
</head>
<body>
  <h1>Заголовок 1</h1>
  <h2>Заголовок 2</h2>
  <h3>Заголовок 3</h3>
  <h4>Заголовок 4</h4>
  <h5>Заголовок 5</h5>
  <h6>Заголовок 6</h6>
</body>
</html>
```

<h1 align = "center">Результат:</h1>

<p>По завершении лабораторной работой были выполнены 36 заданий. </p>

<h1 align = "center">Вывод:</h1>
<p>Полученные знания о HTML были отработаны на практике при решении поставленных задач.</p>