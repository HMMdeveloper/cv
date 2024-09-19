<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Web_Practice3</title>
    <link rel="stylesheet" href="styles.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Sofadi+One&display=swap" rel="stylesheet">
</head>

<body>
    <header>
        <img class="header"
            src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRENF9uv9UWIWWbExsgj7XyX58xMFAOZTzUSQ&s"
            alt="logo">
    </header>

    <main>
        <section>
            <h3><a href="https://elearn.nubip.edu.ua/mod/assign/view.php?id=553876">Лабораторна робота №3</a></h3>
        </section>
        <article>
            <p>Перегляньте ще раз презентацію до лекції 3.
                Створіть папку Web_Practice3 та відкрийте її в VSCode.
                Створіть файли index.html та styles.css.
                Завантажте в VSCode розширення Live Server та натисніть праворуч знизу кнопку Go Live, має відкритися
                сторінку в браузері з вашою розміткою.
                У файлі index.html зробіть базову розмітку, в body створіть три блока header, main та footer.
                У header додайте лого та розмістіть його по центру блока.
                У main додайте тег section та article, в блоці section додайте заголовок і текст(Практична робота №3). В
                article додайте текст та відцентруйте його.
                В footer додайте список (ul або ol) можливих сторінок які можуть бути на сайті.

                Підключіть стилі в head html таким рядком link rel="stylesheet" type="text/css" href="styles.css"
                Стилізуйте свої елементи для html. Додайте background-color, border для блоків, відцентруйте елементи де
                це потрібно. Змініть шрифт для всього проєкту та в цілому спробуйте стилізувати елементи для цікавого
                відображення.</p>
        </article>
    </main>

    <footer>
        <ul>
            <li>
                Ознайомлення з html та css
            </li>
            <li>
                Створення папки та підготовка до практикування у VS Code
            </li>
            <li>
                Використання вичвчених навичок у Лабораторній
            </li>
            <li>
                Здача роботи
            </li>
        </ul>
    </footer>
</body>

</html>

body {
    background-color: #EDE8DC;
    margin: 5% 10% auto;
    font-family: "Sofadi One", system-ui;
}

footer {
    position: absolute;
    bottom: 10px;
}

h3 {
    display: inline;
    text-shadow: 5px 5px #558ABB;
    border: none;
}

p {
    border: 2mm ridge rgba(150, 200, 35, .6);
    text-align: center;
}

ul {
    display: inline-block;
    border-bottom: 5px double #6256CA;
    border-left: 3px double #6256CA;
    list-style: none;
    padding-bottom: 2%;
}

li {
    margin-bottom: 3.5px;
}

.header {
    display: block;
    margin-left: auto;
    margin-right: auto;
    width: 10%;
}

li:hover {
    color: #640D5F;
}
