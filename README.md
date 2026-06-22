html<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Свадебное приглашение 08.08.2026</title>
    <link rel="preconnect" href="https://googleapis.com">
    <link rel="preconnect" href="https://gstatic.com" crossorigin>
    <link href="https://googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,400;0,600;1,400&family=Montserrat:wght@300;400;500&display=swap" rel="stylesheet">
    
    <style>
        :root {
            --sage-dark: #4A5D4E;   
            --sage-medium: #8F9E8B; 
            --sage-light: #F0F4F1;  
            --text-main: #2C3530;   
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            font-family: 'Montserrat', sans-serif;
            color: var(--text-main);
            overflow-x: hidden;
            background-color: #EBF0EC;
        }

        /* Живой фон с нежно-зелеными элементами */
        .floral-bg {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: -1;
            background: radial-gradient(circle, #F4F7F5 0%, #E3EAE5 100%);
            overflow: hidden;
        }

        .petal {
            position: absolute;
            background-color: rgba(143, 158, 139, 0.15);
            border-radius: 0 70% 0 70%;
            transform: rotate(45deg);
            animation: float 15s linear infinite;
        }

        @keyframes float {
            0% { transform: translateY(-100px) rotate(0deg); opacity: 0; }
            10% { opacity: 0.8; }
            90% { opacity: 0.8; }
            100% { transform: translateY(105vh) rotate(360deg); opacity: 0; }
        }

        /* Стили для страниц */
        .page {
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 40px 20px;
            position: relative;
        }

        .card {
            background-color: rgba(255, 255, 255, 0.92);
            backdrop-filter: blur(5px);
            max-width: 550px;
            width: 100%;
            border: 1px solid var(--sage-medium);
            padding: 40px 30px;
            text-align: center;
            box-shadow: 0 15px 35px rgba(74,93,78,0.1);
            border-radius: 8px;
        }

        .inner-border {
            border: 1px solid rgba(143, 158, 139, 0.3);
            padding: 30px 20px;
        }

        h1, h2, .names {
            font-family: 'Cormorant Garamond', serif;
            color: var(--sage-dark);
            font-weight: 400;
        }

        .names {
            font-size: 46px;
            line-height: 1.2;
            margin: 20px 0;
            font-style: italic;
        }

        .date {
            font-family: 'Cormorant Garamond', serif;
            font-size: 32px;
            color: var(--sage-dark);
            margin: 20px 0;
            letter-spacing: 2px;
        }

        /* Поля форм анкеты */
        .form-group {
            text-align: left;
            margin-bottom: 25px;
        }

        .form-group label {
            display: block;
            font-size: 14px;
            margin-bottom: 10px;
            font-weight: 500;
            color: var(--sage-dark);
        }

        .radio-option {
            display: block;
            margin-bottom: 8px;
            font-size: 14px;
            cursor: pointer;
        }

        .radio-option input {
            margin-right: 10px;
            accent-color: var(--sage-dark);
        }

        input[type="text"] {
            width: 100%;
            padding: 12px;
            border: 1px solid var(--sage-medium);
            background-color: var(--sage-light);
            border-radius: 4px;
            font-family: inherit;
        }

        /* Кнопки */
        .btn {
            background-color: var(--sage-dark);
            color: white;
            border: none;
            padding: 14px 28px;
Error 404 (Not Found)!!1
googleapis.com


ass="card">
            <div class="inner-border">
                <h2 style="margin-bottom: 15px;">Место проведения</h2>
                <p style="font-size: 14px; font-weight: 300; margin-bottom: 15px;">
                    Торжество будет проходить в ресторане «Veranda»

                    <strong>Адрес:</strong> г. Москва, ул. Зеленая, д. 15
                </p>
                
                <div class="map-container">
                    <!-- Чтобы поменять карту, вставьте ссылку на ваш ресторан в параметр src -->
                    <iframe src="https://yandex.ru" width="100%" height="100%" frameborder="0" allowfullscreen="true"></iframe>
                </div>

                <a href="https://yandex.ru" target="_blank" class="btn" style="margin-top: 20px;">Открыть в навигаторе</a>
            </div>
        </div>
    </section>

    <!-- Скрипт генерации падающих листьев -->
    <script>
        const bg = document.getElementById('floralBg');
        const count = 25; 
        
        for (let i = 0; i < count; i++) {
            const petal = document.createElement('div');
            petal.classList.add('petal');
            
            const size = Math.random() * 15 + 10;
            petal.style.width = size + 'px';
            petal.style.height = size + 'px';
            petal.style.left = Math.random() * 100 + 'vw';
            petal.style.animationDelay = Math.random() * 15 + 's';
            petal.style.animationDuration = Math.random() * 10 + 12 + 's';
            
            bg.appendChild(petal);
        }
    </script>
</body>
</html>
Статьи, новости и видео от популярных блогеров и СМИ | Будь в теме — будь в Дзене
Статьи, новости и видео от популярных блогеров и СМИ | Будь в теме — будь в Дзене
dzen.ru


font-family: 'Montserrat', sans-serif;
            font-size: 13px;
            text-transform: uppercase;
            letter-spacing: 2px;
            border-radius: 4px;
            cursor: pointer;
            transition: 0.3s ease;
            text-decoration: none;
            display: inline-block;
            margin-top: 15px;
        }

        .btn:hover {
            background-color: #38463B;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
        }

        /* Карта */
        .map-container {
            width: 100%;
            height: 250px;
            margin-top: 20px;
            border-radius: 4px;
            overflow: hidden;
            border: 1px solid var(--sage-medium);
        }

        .scroll-down {
            margin-top: 25px;
            font-size: 12px;
            letter-spacing: 1px;
            color: var(--sage-medium);
            text-transform: uppercase;
        }
    </style>
</head>
<body>

    <!-- Эффект живого растительного фона -->
    <div class="floral-bg" id="floralBg"></div>

    <!-- СТРАНИЦА 1: Главная вступительная часть -->
    <section class="page">
        <div class="card">
            <div class="inner-border">
                <p style="text-transform: uppercase; letter-spacing: 3px; font-size: 12px;">Приглашение</p>
                <div class="names">Александр
&
Елизавета</div>
                <p style="font-weight: 300; font-size: 15px; margin-bottom: 20px;">
                    Дорогие близкие и друзья! Мы рады пригласить вас на празднование нашей свадьбы. Разделите этот особенный день вместе с нами!
                </p>
                <div class="date">08 . 08 . 2026</div>
                <p style="font-size: 14px; margin-bottom: 10px;">Суббота, в 16:00</p>
                <div class="scroll-down">Листайте ниже, чтобы ответить на анкету ↓</div>
            </div>
        </div>
    </section>

    <!-- СТРАНИЦА 2: Опросники для гостей -->
    <section class="page">
        <div class="card">
            <div class="inner-border">
                <h2 style="margin-bottom: 25px;">Анкета гостя</h2>
                
                <!-- ЗАМЕНИТЕ В СТРОКЕ НИЖЕ ТЕКСТ 'ВАША_ПОЧТА@МАИЛ.РУ' НА СВОЙ РЕАЛЬНЫЙ EMAIL ДЛЯ ПОЛУЧЕНИЯ ОТВЕТОВ -->
                <form action="https://formspree.io" method="POST">
                    
                    <div class="form-group">
                        <label>1. Ваше имя и фамилия:</label>
                        <input type="text" name="name" placeholder="Введите ваше имя" required>
                    </div>

                    <div class="form-group">
                        <label>2. Сможете ли вы присутствовать?</label>
                        <label class="radio-option"><input type="radio" name="attendance" value="Да, с удовольствием" checked> Да, с удовольствием приду</label>
                        <label class="radio-option"><input type="radio" name="attendance" value="Приду со спутником"> Приду со спутником(-цей)</label>
                        <label class="radio-option"><input type="radio" name="attendance" value="К сожалению, не смогу"> К сожалению, не смогу</label>
                    </div>

                    <div class="form-group">
                        <label>3. Какие напитки вы предпочитаете?</label>
                        <label class="radio-option"><input type="radio" name="drink" value="Красное вино" checked> Красное вино</label>
                        <label class="radio-option"><input type="radio" name="drink" value="Белое вино"> Белое вино</label>
                        <label class="radio-option"><input type="radio" name="drink" value="Крепкие напитки"> Крепкие напитки</label>
                        <label class="radio-option"><input type="radio" name="drink" value="Безалкогольные"> Безалкогольные напитки</label>
                    </div>

                    <button type="submit" class="btn">Отправить ответы</button>
                </form>
            </div>
        </div>
    </section>

    <!-- СТРАНИЦА 3: Геолокация и Карта -->
    <section class="page">
        <div cl
Custom Forms with No Server Code | Formspree
Custom Forms with No Server Code | Formspree
formspree.io




