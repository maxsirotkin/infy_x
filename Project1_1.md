<p align = "center">МИНИСТЕРСТВО НАУКИ И ВЫСШЕГО ОБРАЗОВАНИЯ<br>
РОССИЙСКОЙ ФЕДЕРАЦИИ<br>
ФЕДЕРАЛЬНОЕ ГОСУДАРСТВЕННОЕ БЮДЖЕТНОЕ<br>
ОБРАЗОВАТЕЛЬНОЕ УЧРЕЖДЕНИЕ ВЫСШЕГО ОБРАЗОВАНИЯ<br>
«САХАЛИНСКИЙ ГОСУДАРСТВЕННЫЙ УНИВЕРСИТЕТ»</p>
<br><br><br><br><br><br>
<p align = "center">Институт естественных наук и техносферной безопасности<br>Кафедра информатики<br>Сироткин Максим Сергеевич</p>
<br><br><br>
<p align = "center"><br><strong>Лабораторная работа №1.«Введение в вэб-разработку».</strong><br>01.03.02 Прикладная математика и информатика</p>
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
<h1 align = "center">Цели и задачи:</h1>
  1. Поиск и изучение информации по веб-разработке и языку HTML.<br>
  2. Получение практического опыта в среде Visual studio Code при работе с языкоме HTML.<br>
  3. Используя полученные знания и навыки, применить их при создании собственного веб-сайта.<br>


<p></p>



<h1 align = "center">Решение задач:</h1>
Для выполнения этой лабораторной работы я пользовался:<br>
1. Различным материалом в сети интернет.<br>
2. Материалом с сайта https://htmlacademy.ru/blog/css/css-background?ysclid=lsy65ncyww813760034<br>
3. Материалом с сайта https://habr.com/ru/companies/netologyru/articles/690042/<br>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Моя страница</title>
    <link rel="stylesheet" href="untitled.css">
</head>
<body style="background-color: rgb(255, 255, 255);">
    <h4>infy_x production</h4>
    <hr style="border: none; border-top: 5px dotted rgb(0, 0, 0)" />
    <h1 style="font-family:'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif; font-size: 50px; text-align: center; text-shadow: 0px 3px 7px rgba(50, 50, 50, 0.5); "> Немного обо мне:</h1>
    <h2 style="font-family:'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif; font-size: 30px; line-height: 0.5; font-style: italic;"> Приветствую, меня зовут Максим! </h2>
    <pre style="font-family:'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif; font-size: 25px;">
        Родился 12.07.2004 в г. Южно-Сахалинск.
        Мне 19 лет.
        Являюсь студентом 2 курса СахГУ ИЕНиТБ.
        Обучаюсь на направлении "Прикладная математика и информатика".</pre>
    <h3> Достижения:</h3>
    <ul>
        <li style="font-family:'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif; font-size: 25px;"> Завершение среднего общего образования с отличием;  </li>
        <li style="font-family:'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif; font-size: 25px;"> Победитель УМНИК 2022; </li>
        <li style="font-family:'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif; font-size: 25px;"> Завершение курса "3D моделирование" в ДТ Кванториум. </li>
    </ul>
    <h3>Фотография:</h3>
    <p style="text-align: center">
        <img width="780" height="525" src= benz.JPG alt="Моя фотография"><br>
        <strong> mercedes benz </strong>
    </p>
    <h3> Хобби:</h3>
    <p style="font-family:'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif; font-size: 25px;"> Моё хобби - Программирование.</p>
    <h3> Мои контакты:</h3>
    <ul class="social-icons">
        <li> VK <a class="social-icon-vk" href="https://vk.com/id463135170" title="ВКонтакте" target="_blank" rel="noopener"></a></li>
        <li> TG <a class="social-icon-telegram" href="https://t.me/infy_x" title="Телеграм" target="_blank" rel="noopener"></a></li>
    </ul>
    <background-text>↑ ссылочки ↑ </background-text>
    <h4> Конец сайта :)</h4>
</body>
</html>
```
<h1 align = "center">Вывод:</h1>
<p>По завершении работы над собственным веб-сайтом  были получены необходимые знания и навыки для начальной работы в среде Visual Studio Code на языке HTML.</p>
