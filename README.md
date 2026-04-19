<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GTA V — Официальный сайт</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background: #000;
            color: #fff;
            line-height: 1.6;
        }
        header {
            background: #c00;
            padding: 20px 0;
            text-align: center;
        }
        nav ul {
            list-style-type: none;
            padding: 0;
            display: flex;
            justify-content: center;
            background: #333;
        }
        nav li {
            margin: 0 15px;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            font-weight: bold;
        }
        nav a:hover {
            color: #c00;
        }
        .buttons-container {
            text-align: center;
            padding: 15px 0;
            display: flex;
            justify-content: center;
            gap: 20px;
        }
        .site-button {
            background: #c00;
            color: white;
            border: none;
            padding: 12px 24px;
            font-size: 16px;
            font-weight: bold;
            cursor: pointer;
            border-radius: 4px;
            transition: background 0.3s;
        }
        .site-button:hover {
            background: #900;
        }
        main {
            padding: 20px;
        }
        section {
            margin-bottom: 40px;
        }
        h1, h2, h3 {
            color: #c00;
        }
        .character-card {
            background: #1a1a1a;
            padding: 15px;
            margin-bottom: 15px;
            border-left: 4px solid #c00;
        }
        footer {
            text-align: center;
            padding: 20px 0;
            background: #333;
        }
        img {
            max-width: 100%;
            height: auto;
            margin: 10px 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Grand Theft Auto V</h1>
        <p>Легендарная игра от Rockstar Games</p>
    </header>
    <nav>
        <ul>
            <li><a href="#about">Об игре</a></li>
            <li><a href="#characters">Персонажи</a></li>
            <li><a href="#features">Особенности</a></li>
        </ul>
    </nav>
    <div class="buttons-container">
        <button class="site-button" onclick="window.location.href='#home'">Главная</button>
        <button class="site-button" onclick="window.location.href='#online'">GTA Online</button>
    </div>
    <main>
        <section id="home">
            <h2>Добро пожаловать в Лос-Сантос!</h2>
            <p>GTA V — приключенческий боевик с открытым миром от Rockstar Games, выпущенный в 2013 году. Погрузитесь в атмосферу современной Калифорнии: криминальные разборки, роскошные автомобили, горы, пляжи и мегаполис в вымышленном штате Сан-Андреас.</p>
            <img src="" alt="Обложка игры GTA V" width="300">
        </section>

        <section id="about">
            <h2>Об игре</h2>
            <p><strong>Год выпуска:</strong> 2013 (PlayStation 3, Xbox 360), 2014 (PlayStation 4, Xbox One), 2015 (PC), 2022 (PlayStation 5, Xbox Series X/S)</p>
            <p><strong>Разработчик:</strong> Rockstar North</p>
            <p><strong>Издатель:</strong> Rockstar Games</p>
            <p><strong>Локализатор в России:</strong> «1С‑СофтКлаб»</p>
            <p><strong>Платформы:</strong> PC (Windows), PlayStation 3/4/5, Xbox 360/One/Series X|S</p>
            <p>Действие разворачивается в вымышленном городе Лос-Сантос и округе Блэйн (штат Сан-Андреас), вдохновлённых реальными местами Южной Калифорнии.</p>
            <p>Игра стала одним из самых коммерчески успешных проектов в истории: 11,21 миллиона копий и 800 миллионов долларов в первый день продаж, 1 миллиард долларов за 3 дня.</p>
        </section>

        <section id="characters">
            <h2>Главные герои</h2>
            <div class="character-card">
                <h3>Майкл Де Санта</h3>
                <p>Бывший грабитель банков, который после «пенсии» пытается вести спокойную жизнь с семьёй. Обладает способностью замедлять время во время перестрелок.</p>
            </div>
            <div class="character-card">
                <h3>Франклин Клинтон</h3>
                <p>Молодой человек из гетто, работающий на автомобильное агентство. Мечтает пробиться в криминальный мир. Его навык — замедление времени во время вождения.</p>
            </div>
            <div class="character-card">
                <h3>Тревор Филипс</h3>
                <p>Бывший пилот ВВС США, наркозависимый и крайне жестокий преступник. Занимается торговлей наркотиками и оружием. Его способность — замедление времени в перестрелках, увеличение урона и регенерация здоровья.</p>
            </div>
        </section>

        <section id="features">
            <h2>Ключевые особенности</h2>
            <ul>
                <li><strong>Три играбельных персонажа.</strong> Можно переключаться между Майклом, Франклином и Тревором в любой момент.</li>
                <li><strong>Ограбления.</strong> Миссии по планированию и выполнению ограблений с выбором стратегии и подготовкой.</li>
                <li><strong>Огромный открытый мир.</strong> Лос-Сантос и окрестности — одна из самых больших игровых карт в истории.</li>
                <li><strong>Разнообразие активностей.</strong> Гольф, теннис, йога, уличные гонки, прыжки с парашютом, модификация транспорта и многое другое.</li>
                <li><strong>Система прокачки.</strong> Навыки (стрельба, вождение и т. д.) развиваются в зависимости от действий игрока.</li>
                <li><strong>Смена времени суток и погоды.</strong> Динамическая система влияет на геймплей.</li>
            </ul>
        </section>

        <section id="online">
            <h2>GTA Online</h2>
            <p>Встроенный многопользовательский режим, поддерживающий до 30 игроков одновременно. Предлагает:</p>
            <ul>
                <li>Кооперативные миссии по ограблениям</li>
                <li>Соревновательные режимы</li>
                <li>Возможность создавать собственные задания</li>
                <li>Покупка недвижимости и бизнеса</li>
                <li>Регулярные обновления с новым контентом</li>
            </ul>
        </section>
        <section>
            <h2>Скриншоты</h2>
            <img src="" alt="Скриншот 1: Вид на Лос-Сантос с высоты" width="300">
            <img src=""alt="Скриншот 2: Франклин за рулём спортивного автомобиля" width="300">
            <img src="" alt="Скриншот 3: Тревор в округе Блэйн" width="300">
        </section>
        <section>
            <li><a href="https://ru.wikipedia.org/wiki/Grand_Theft_Auto_V">Википедия: GTA V</a></li>
                <li><a href="https://www.rockstargames.com/gtav">Официальный сайт Rockstar Games</a></li>
          <footer>
        <p>&copy; 2026 GTA V Fan Site. Все права защищены. Автор: Zer0code228</p>
    </footer>
</html>
