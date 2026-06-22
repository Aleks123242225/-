[index.html](https://github.com/user-attachments/files/29222594/index.html)
# -<!DOCTYPE html>
<html lang="ru" data-default-currency="RUB" data-event-type="wedding">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="description" content="">
    <meta name="author" content="">
    <meta http-equiv="Cache-Control" content="max-age=36000, must-revalidate">
    <meta name="viewport" content="width=device-width, user-scalable=no, initial-scale=1, maximum-scale=1, minimum-scale=1, viewport-fit=cover">
    <meta name="color-scheme" content="light">
    <link rel="shortcut icon" href="/favicon.ico">
    <title>Приглашение на свадьбу - Аываыа & Вфва (08.07.2026)</title>

    <!-- Предзагрузка изображений -->
    <link as="image" href="/cabinet/constructor/pattern/all/11.png" rel="preload">
    <link as="image" href="/cabinet/constructor/plate/488/upl3181.png" rel="preload">
    <link as="image" href="/cabinet/constructor/pattern/488/upl3185.png" rel="preload">
    <link as="image" href="/cabinet/constructor/pattern/488/upl3187.png" rel="preload">

    <!-- Open Graph метаданные -->
    <meta property="og:title" content="Приглашение на свадьбу - Аываыа & Вфва (08.07.2026)">
    <meta property="og:description" content="Жених и Невеста приглашают вас на свадьбу. Ваше приглашение:">
    <meta property="og:type" content="website">
    <meta property="og:image" content="https://weddingpost.site/get_preview.php?id=1148735&t=495043">

    <!-- Подключение стилей -->
    <link rel="stylesheet" href="/src/css/cabinet.min.css?v=2606763275">
    <link rel="stylesheet" href="/src/css/fa6-all.min.css">
    <link rel="stylesheet" href="/src/css/fa4.min.css">
    <link rel="stylesheet" href="/src/css/cabinet.css?v=2606763275">

    <!-- Шрифты -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link rel="preload" href="https://fonts.googleapis.com/css?family=Bad+Script|Comfortaa|Kurale|Zen+Antique+Soft|Montserrat:900,800,600,500,300|Lobster|Lora:400i|Marck+Script|Marmelad|Merriweather|Neucha|Open+Sans+Condensed:300|Open+Sans:400,400i|PT+Sans+Narrow:400,700|Philosopher:400,400i|Play|Roboto+Condensed|Roboto+Slab|Roboto:100|Ubuntu:400,400i|Yeseva+One|Monomakh&subset=cyrillic" as="style" onload="this.onload=null;this.rel='stylesheet'">
    <noscript>
        <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Bad+Script|Comfortaa|Kurale|Zen+Antique+Soft|Montserrat:900,800,600,500,300|Lobster|Lora:400i|Marck+Script|Marmelad|Merriweather|Neucha|Open+Sans+Condensed:300|Open+Sans:400,400i|PT+Sans+Narrow:400,700|Philosopher:400,400i|Play|Roboto+Condensed|Roboto+Slab|Roboto:100|Ubuntu:400,400i|Yeseva+One|Monomakh&subset=cyrillic">
    </noscript>

    <!-- Дополнительные стили -->
    <link rel="stylesheet" href="/template/invent/userinvent.css?v=2606763275">
    <link rel="stylesheet" href="/src/css/intlTelInput.min.css?v=2606763275">
</head>
<body>
    <div class="invent-mob-back" id="invent-mob-back" aria-hidden="true">
        <a class="invent-mob-back-btn" id="invent-mob-back-btn" href="/cabinet/constructor/electro/" aria-label="Назад">
            <i class="fa fa-angle-left" aria-hidden="true"></i>
            <span class="invent-mob-back-label">Назад</span>
        </a>
    </div>

    <div class="content" id="screen">
        <div class="wp-heart">
            <div></div>
            <div class="shadow"></div>
            <span>Загрузка приглашения</span>
        </div>
    </div>

    <div class="modal-overlay" id="autoGuestModal">
        <div class="modal-card">
            <button class="modal-card__close" type="button" aria-label="Закрыть">
                <span aria-hidden="true">×</span>
            </button>
            <div class="modal-card__title"></div>
            <form class="modal-card__form">
                <div class="field field--firstName">
                    <label class="field__label" for="autoGuestFirstName"></label>
                    <input class="field__input" id="autoGuestFirstName" type="text" name="ag_first_name" autocomplete="given-name">
                    <div class="field__error"></div>
                </div>
                <div class="field field--lastName">
                    <label class="field__label" for="autoGuestLastName"></label>
                    <input class="field__input" id="autoGuestLastName" type="text" name="ag_last_name" autocomplete="family-name">
                    <div class="field__error"></div>
                </div>
                <div class="field field--phone">
                    <label class="field__label" for="autoGuestPhone"></label>
                    <input class="field__input" id="autoGuestPhone" type="tel" name="ag_phone" autocomplete="tel">
                    <div class="field__error"></div>
                </div>
                <div class="modal-card__footer">
                    <button class="modal-card__submit" type="submit">
                        <span class="modal-card__submit-inner">
                            <i class="fa fa-check" aria-hidden="true"></i>
                            <span class="modal-card__submit-label"></span>
                        </span>
                    </button>
                </div>
            </form>
        </div>
    </div>

    <!-- Подключаемые скрипты -->
    <script src="https://cdn.jsdelivr.net/npm/canvas-confetti@1.9.3/dist/confetti.browser.min.js" defer></script>
    <script src="/template/userlib.min.js?v=2606763275"></script>
    <script src="/template/invent/userinvent.js?v=2606763275"></script>
    <script src="/src/js/twemoji.min.js" crossorigin="anonymous"></script>

    <!-- JavaScript переменные -->
    <script>
        window.wpHotwords = {
            "eventType": "wedding",
            "locale": "ru",
            "replaceOnMaket": {
                "hotWord1": "Жених",
                "hotWord1Upper": "ЖЕНИХ",
                "hotWord2": "Невеста",
                "hotWord2Upper": "НЕВЕСТА",
                "domainPreview": ".ru",
                "shortHotWord1": "Ж",
                "
