<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Luneria Books</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<header class="hero-header">
    <nav>
        <div class="logo">LUNERIA</div>

        <ul>
            <li><a href="#about">О магазине</a></li>
            <li><a href="#books">Книги</a></li>
            <li><a href="#genres">Жанры</a></li>
            <li><a href="#contacts">Контакты</a></li>
        </ul>
    </nav>

    <div class="hero-content">
        <h1>Мир современных книг</h1>
        <p>
            Онлайн-магазин с атмосферным дизайном,
            коллекциями бестселлеров и уютной библиотечной атмосферой.
        </p>

        <a href="#books" class="main-btn">Каталог</a>
    </div>
</header>

<section class="about" id="about">
    <div class="section-title">
        <h2>Почему выбирают нас</h2>
        <p>Современный книжный магазин для любителей литературы.</p>
    </div>

    <div class="features">

        <div class="feature-card">
            <h3>Редкие издания</h3>
            <p>
                Коллекционные книги и ограниченные серии популярных авторов.
            </p>
        </div>

        <div class="feature-card">
            <h3>Быстрая доставка</h3>
            <p>
                Доставка заказов по всей стране с отслеживанием.
            </p>
        </div>

        <div class="feature-card">
            <h3>Большой выбор</h3>
            <p>
                Фэнтези, классика, научная литература, психология и многое другое.
            </p>
        </div>

    </div>
</section>

<section class="books" id="books">
    <div class="section-title">
        <h2>Популярные книги</h2>
        <p>Подборка лучших произведений.</p>
    </div>

    <div class="books-grid">

        <div class="book-card">
            <img src="https://images.unsplash.com/photo-1512820790803-83ca734da794?q=80&w=1200&auto=format&fit=crop" alt="book">

            <div class="book-content">
                <h3>Midnight Stories</h3>
                <p>Мрачный сборник атмосферных историй.</p>
                <span>8 000 ₸</span>
            </div>
        </div>

        <div class="book-card">
            <img src="https://images.unsplash.com/photo-1495446815901-a7297e633e8d?q=80&w=1200&auto=format&fit=crop" alt="book">

            <div class="book-content">
                <h3>The Silent Library</h3>
                <p>Современный психологический роман.</p>
                <span>9 500 ₸</span>
            </div>
        </div>

        <div class="book-card">
            <img src="https://images.unsplash.com/photo-1516979187457-637abb4f9353?q=80&w=1200&auto=format&fit=crop" alt="book">

            <div class="book-content">
                <h3>Fantasy World</h3>
                <p>Эпическое фэнтези о древнем мире.</p>
                <span>10 000 ₸</span>
            </div>
        </div>

    </div>
</section>

<section class="genres" id="genres">
    <div class="section-title">
        <h2>Жанры</h2>
        <p>Популярные литературные направления.</p>
    </div>

    <div class="genre-grid">
        <div class="genre-box">Фэнтези</div>
        <div class="genre-box">Триллер</div>
        <div class="genre-box">Детектив</div>
        <div class="genre-box">Психология</div>
        <div class="genre-box">Классика</div>
        <div class="genre-box">Научная литература</div>
    </div>
</section>

<section class="table-section">
    <div class="section-title">
        <h2>Расписание мероприятий</h2>
        <p>Встречи, презентации и лекции.</p>
    </div>

    <table>
        <tr>
            <th>Дата</th>
            <th>Событие</th>
            <th>Время</th>
        </tr>

        <tr>
            <td>15 мая</td>
            <td>Презентация новой книги</td>
            <td>18:00</td>
        </tr>

        <tr>
            <td>18 мая</td>
            <td>Литературный вечер</td>
            <td>19:30</td>
        </tr>

        <tr>
            <td>22 мая</td>
            <td>Встреча с автором</td>
            <td>17:00</td>
        </tr>
    </table>
</section>

<section class="contacts" id="contacts">
    <div class="contact-box">
        <h2>Связаться с нами</h2>

        <form>
            <input type="text" placeholder="Ваше имя">
            <input type="email" placeholder="Email">
            <textarea placeholder="Сообщение"></textarea>
            <button>Отправить</button>
        </form>
    </div>
</section>

<footer>
    <p>© 2026 Luneria Books | Modern Book Store</p>
</footer>

</body>
</html>
