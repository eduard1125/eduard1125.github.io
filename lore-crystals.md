
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <title>Галерея персонажей — Кватротрон</title>
</head>
<body>

    <h1>Галерея персонажей</h1>

    <style>
        .gallery-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(240px, 1fr));
            gap: 20px;
            padding: 20px 0;
        }
        .char-card {
            border: 1px solid #ddd;
            border-radius: 8px;
            overflow: hidden;
            background: #fafafa;
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
        }
        .char-card img {
            width: 100%;
            height: 320px;
            object-fit: cover;
        }
        .char-card-body {
            padding: 12px;
        }
        .char-card h3 {
            margin: 0 0 6px;
            font-size: 1.1rem;
        }
        .char-card p {
            margin: 0;
            font-size: 0.9rem;
            line-height: 1.4;
            color: #333;
        }
    </style>

    <div class="gallery-grid">
        <!-- Карточка Зорики -->
        <div class="char-card">
            <img src="zorika.png" alt="Зорика">
            <div class="char-card-body">
                <h3>Зорика</h3>
                <p>Из Дома Розы. Спокойная, наблюдательная, слышит кристаллы. Ведёт дневник, немного застенчива с незнакомцами, но с близкими раскрывается. Умеет стоять на своём, особенно в науке.</p>
            </div>
        </div>

        <!-- Карточка Лиэде -->
        <div class="char-card">
            <img src="liede.png" alt="Лиэде">
            <div class="char-card-body">
                <h3>Лиэде</h3>
                <p>Дочь Солнца, из Дома Лилий. Зелёные глаза, каштановые короткие волосы, слегка застенчивая, ленивая, любит поспать и мамины бутерброды с котлетой.</p>
            </div>
        </div>

        <!-- Карточка Ниры -->
        <div class="char-card">
            <img src="Nira.png" alt="Нира">
            <div class="char-card-body">
                <h3>Нира</h3>
                <p>Младшая сестра Лиэде и её ученица из Дома Лилий.</p>
            </div>
        </div>

        <!-- Карточка Ятики -->
        <div class="char-card">
            <img src="Yatika.png" alt="Ятика">
            <div class="char-card-body">
                <h3>Ятика</h3>
                <p>Девочка из Дома Катусов. Родилась на Кватротроне в семье стражей защитников порядка. Характер сложный, но уравновешенный.</p>
            </div>
        </div>

        <!-- Карточка Эленоры -->
        <div class="char-card">
            <img src="Eleanor.png" alt="Эленора">
            <div class="char-card-body">
                <h3>Эленора</h3>
                <p>Девочка из Дома Ромашки. Инженер. Спокойная, сосредоточенная, говорит много, часто шутит, но не всегда удачно.</p>
            </div>
        </div>

        <!-- Карточка Маркиза -->
        <div class="char-card">
            <img src="markiz-4.png" alt="Маркиз">
            <div class="char-card-body">
                <h3>Маркиз</h3>
                <p>Учёный-археолог. Сдержанный, упрямый, рассеянный. Хранит этикет, но иногда забывает про официальный вид.</p>
            </div>
        </div>
    </div>
</body>
</html>

