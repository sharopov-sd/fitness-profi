<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Фитнес-Профи</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            color: #333;
        }
        .hero {
            position: relative;
            height: 100vh;
            overflow: hidden;
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            color: white;
        }
        .hero video {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            object-fit: cover;
            z-index: -1;
        }
        .hero-content {
            background-color: rgba(0, 0, 0, 0.6);
            padding: 20px;
            border-radius: 10px;
        }
        .hero h1 {
            font-size: 2.5rem;
        }
        .hero p {
            margin: 10px 0;
            font-size: 1.2rem;
        }
        .hero .button {
            margin-top: 20px;
            padding: 10px 20px;
            font-size: 1rem;
            color: white;
            background-color: #007BFF;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            text-decoration: none;
        }
        .hero .button:hover {
            background-color: #0056b3;
        }
        .advantages {
            padding: 40px;
            background-color: #f9f9f9;
        }
        .advantages h2 {
            text-align: center;
            font-size: 2rem;
            margin-bottom: 20px;
        }
        .advantages p {
            max-width: 600px;
            margin: 0 auto;
            font-size: 1.2rem;
            text-align: center;
        }
        .gallery {
            padding: 40px;
            background-color: #fff;
            text-align: center;
        }
        .gallery h2 {
            font-size: 2rem;
            margin-bottom: 20px;
        }
        .contacts {
            padding: 40px;
            background-color: #f9f9f9;
            text-align: center;
        }
        .contacts h2 {
            font-size: 2rem;
            margin-bottom: 20px;
        }
        .contacts p {
            font-size: 1.2rem;
        }
    </style>
</head>
<body>

<!-- Главный экран -->
<section class="hero">
    <video autoplay muted loop>
        <source src="https://youtu.be/4-zjQvTDnbw" type="video/mp4">
        Your browser does not support the video tag.
    </video>
    <div class="hero-content">
        <h1>Фитнес-Профи это:</h1>
        <ul>
            <li><strong>Тренажерный зал 700 м<sup>2</sup></strong></li>
            <li><strong>Студия боевых искусств</strong></li>
            <li><strong>Экологичный бассейн 25 м</strong></li>
            <li><strong>Финская сауна и хаммам</strong></li>
        </ul>
        <p>*Эффект печатной машинки*</p>
        <h2>Получите лимитированную карту, 30 дней фитнеса в подарок!</h2>
        <a href="#" class="button">Узнать подробности акции</a>
    </div>
</section>

<!-- Преимущества -->
<section class="advantages">
    <h2>Просторный тренажерный зал на 700 м<sup>2</sup></h2>
    <p>Легко соблюдать дистанцию и нет очередей на тренажеры.</p>

    <h2>Огромная студия под боевые искусства</h2>
    <p>Мы уделяем внимание групповым занятиям: просторные студии Фитнес-профи позволяют заниматься с комфортом.</p>

    <h2>Экологичный бассейн 25 м</h2>
    <p>В бассейне Фитнес-профи — только морская вода.</p>

    <h2>Финская сауна и хаммам</h2>
    <p>После тренировки вы можете прогреть мышцы в горячей финской сауне или теплом хамаме.</p>
</section>

<!-- Наши тарифы -->
<section class="advantages">
    <h2>Наши тарифы</h2>
    <p>Вы будете приятно удивлены нашими ценами и наполнением тарифов <a href="https://www.notion.so/cd28e936c32042e899d5efe0ab263aee?pvs=21" target="_blank">тарифы</a>.</p>
</section>

<!-- Фото зала -->
<section class="gallery">
    <h2>Фото зала</h2>
    <p><a href="https://drive.google.com/drive/folders/1WcLdiAzPyGCYE0EMb8edGzLxG4nSWABS?usp=sharing" target="_blank">Пролистайте фото</a> и убедитесь, что это лучший зал, в котором вы когда-либо занимались.</p>
</section>

<!-- Контакты -->
<section class="contacts">
    <h2>Контакты</h2>
    <p><strong>Если вы не победите себя, тогда будете побеждены самим собой</strong></p>
    <p>Адрес: г. Москва, ул. Ленина 17</p>
    <p>Тел: +7 800 000-77-77</p>
    <p>5 минут от М. Арбатская</p>
</section>

</body>
</html>
