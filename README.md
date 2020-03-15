Научиться учиться

Описание:
Одностраничный сайт с информацией об обучении и активными ссылками на образовательные сайты. Благодаря использованию разных функций после прохождения очередного обучения мы смогли разместить на странице видео с youtube, применить анимацию, а также поработали над картинками, в частности над расположением.

В процессе создания проекта были использованы разнообразные технологии:

1. Кейферимы
@keyframes kaufman__triangle {
    from {
        transform: rotate(0deg);
    }
    to {
        transform: rotate(360deg);
    }
}

2. Анимация
.kaufman__triangle {
    animation: kaufman__triangle 20s infinite;
}

3. Работа с ссылками
.header__link {
    color: #2f80ed;
    text-decoration: none;
}

.header__link:hover {
    opacity: 0.3;
    transition: opacity .3s linear ;
}

4.Видео
div class="video__iframes">
    <iframe class="video__iframe" src="https://www.youtube.com/embed/5MgBikgcWnY?autoplay=1&start=936&color=white" allowfullscreen></iframe>
    <iframe class="video__iframe" src="https://www.youtube.com/embed/arj7oStGLkU?autoplay=1&start=704&color=white" allowfullscreen></iframe>
</div>

Планы по доработке.
В скором времени планирую:
-подключить разные шрифты;
-добавить интересные видео;
-прописать кроссбраузность;
-добавить форму обратной связи.

Автор:
Артур Нуртдинов

Обратная связь:
nal.kzn@yandex.ru