---
layout: page
title: "please"
permalink: /pleasework/
---
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Темная страница</title>
    <style>
        body {
            background-color: #1a1a1a;
            color: #ffffff;
            font-family: Arial, sans-serif;
            padding: 20px;
        }
        .header {
            width: 100%;
            text-align: left;
            margin-bottom: 20px;
        }
        .header h1 {
            font-size: 2.5em;
            margin: 0;
        }
        .container {
            display: flex;
            flex-wrap: nowrap;
            align-items: flex-start; 
        }
        .image-section {
            flex: 0 0 400px; 
            margin-right: 50px;
        }
        .image-section img {
            width: 100%; 
            height: auto;
            display: block;
        }
        .text-section {
            flex: 1;
        }
        .text-section p:first-child {
            display: block;
            margin-bottom: 10px;
        }
        .text-section p.continued {
            margin-top: 20px;
        }
        a {
            color: #a1a2a3;
            text-decoration: none;
            display: block;
            margin-bottom: 10px;
        }
        a:hover {
            text-decoration: underline;
            color: #c0c0c0;
        }
    </style>
</head>
<body>
    <div class="header">
        <h1>Большой заголовок</h1>
    </div>
    <div class="container">
        <div class="image-section">
            <p>Моё фото</p>
            <img src="/assets/image_1.jpg" alt="Пример изображения">
        </div>
        <div class="text-section">
            <p>всем привет меня зовут американ психо (american psycho)</p>
            <a href="/assets/document1.pdf" target="_blank">первый документ</a>
            <a href="/assets/document2.pdf" target="_blank">второйдокумент</a>
            <p class="continued">БОЛЬШЕТЕКСТА вот реально много<br> ну вроде вот так</p>
        </div>
    </div>
    <div>
        тексттексттексттексттексттексттексттексттексттексттексттексттексттексттексттексттексттексттексттексттексттекст
        <br>
        ТЕКСТ 2 ВОТ ПРЯМ ОЧЕНЬ ЖЕСТКИЙ
    </div>
</body>
</html>
