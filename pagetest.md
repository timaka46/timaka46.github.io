---
layout: page
title: "please"
permalink: /pleasework/
---
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
        .container {
            display: flex;
            flex-wrap: wrap;
        }
        .image-section {
            flex: 1 1 200px;
            margin-right: 20px;
        }
        .image-section img {
            max-width: 100%;
            height: auto;
            display: block;
        }
        .text-section {
            flex: 2 1 calc(100% - 220px);
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
    <div class="container">
        <div class="image-section">
            <p>Моё фото</p>
            <img src="/assets/image_1.jpg" alt="Пример изображения">
        </div>
        <div class="text-section">
            <p>тексттексттексттексттексттексттексттексттексттексттексттексттексттексттексттексттексттексттексттексттексттекст</p>
            <a href="/assets/document1.pdf" target="_blank">первый документ</a>
            <a href="/assets/document2.pdf" target="_blank">второйдокумент</a>
            <p class="continued">БОЛЬШЕТЕКСТА вот реально много<br> ну вроде вот так</p>
        </div>
        тест1
    </div>
    тест2
</body>
</html>
