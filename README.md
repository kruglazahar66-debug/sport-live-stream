<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SportLive - Прямые спортивные трансляции</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
</head>
<body>
    <!-- Навигация -->
    <nav class="navbar">
        <div class="container">
            <a href="index.html" class="logo">Sport<span>Live</span></a>
            <ul class="nav-menu">
                <li><a href="index.html" class="active"><i class="fas fa-home"></i> Главная</a></li>
                <li><a href="live.html"><i class="fas fa-tv"></i> Прямой эфир</a></li>
                <li><a href="schedule.html"><i class="fas fa-calendar-alt"></i> Расписание</a></li>
                <li><a href="about.html"><i class="fas fa-info-circle"></i> О нас</a></li>
            </ul>
        </div>
    </nav>

    <!-- Герой-секция -->
    <header class="hero">
        <div class="container">
            <h1>Смотрите спортивные трансляции в прямом эфире</h1>
            <p>Футбол, хоккей, баскетбол, теннис и другие виды спорта в HD качестве</p>
            <a href="live.html" class="btn-primary">Смотреть сейчас <i class="fas fa-play"></i></a>
        </div>
    </header>

    <!-- Активные трансляции -->
    <section class="live-now">
        <div class="container">
            <h2><i class="fas fa-broadcast-tower"></i> Сейчас в эфире</h2>
            <div class="streams-grid">
                <div class="stream-card">
                    <div class="stream-badge">LIVE</div>
                    <img src="https://images.unsplash.com/photo-1575361204480-aadea25e6e68?ixlib=rb-4.0.3&auto=format&fit=crop&w=600&q=80" alt="Футбол">
                    <div class="stream-info">
                        <h3>Футбол: Чемпионат Мира</h3>
                        <p class="match">Аргентина vs Франция</p>
                        <div class="stream-meta">
                            <span><i class="fas fa-eye"></i> 45.2K зрителей</span>
                            <span><i class="fas fa-clock"></i> 65'</span>
                        </div>
                        <a href="live.html?stream=1" class="btn-watch">Смотреть</a>
                    </div>
                </div>

                <div class="stream-card">
                    <div class="stream-badge">LIVE</div>
                    <img src="https://images.unsplash.com/photo-1546519638-68e109498ffc?ixlib=rb-4.0.3&auto=format&fit=crop&w=600&q=80" alt="Баскетбол">
                    <div class="stream-info">
                        <h3>Баскетбол: NBA</h3>
                        <p class="match">Lakers vs Warriors</p>
                        <div class="stream-meta">
                            <span><i class="fas fa-eye"></i> 28.7K зрителей</span>
                            <span><i class="fas fa-clock"></i> 3-я четверть</span>
                        </div>
                        <a href="live.html?stream=2" class="btn-watch">Смотреть</a>
                    </div>
                </div>

                <div class="stream-card">
                    <div class="stream-badge">LIVE</div>
                    <img src="https://images.unsplash.com/photo-1558618666-fcd25c85cd64?ixlib=rb-4.0.3&auto=format&fit=crop&w=600&q=80" alt="Хоккей">
                    <div class="stream-info">
                        <h3>Хоккей: КХЛ</h3>
                        <p class="match">СКА vs ЦСКА</p>
                        <div class="stream-meta">
                            <span><i class="fas fa-eye"></i> 32.1K зрителей</span>
                            <span><i class="fas fa-clock"></i> 2-й период</span>
                        </div>
                        <a href="live.html?stream=3" class="btn-watch">Смотреть</a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Расписание -->
    <section class="schedule">
        <div class="container">
            <h2><i class="fas fa-calendar-alt"></i> Ближайшие матчи</h2>
            <div class="schedule-table">
                <div class="match-row">
                    <div class="match-time">20:00</div>
                    <div class="match-teams">Реал Мадрид vs Барселона</div>
                    <div class="match-sport">Футбол</div>
                    <div class="match-action"><a href="#" class="btn-reminder"><i class="fas fa-bell"></i> Напомнить</a></div>
                </div>
                <div class="match-row">
                    <div class="match-time">21:30</div>
                    <div class="match-teams">Бостон vs Чикаго</div>
                    <div class="match-sport">Хоккей</div>
                    <div class="match-action"><a href="#" class="btn-reminder"><i class="fas fa-bell"></i> Напомнить</a></div>
                </div>
                <div class="match-row">
                    <div class="match-time">23:00</div>
                    <div class="match-teams">Надаль vs Джокович</div>
                    <div class="match-sport">Теннис</div>
                    <div class="match-action"><a href="#" class="btn-reminder"><i class="fas fa-bell"></i> Напомнить</a></div>
                </div>
            </div>
        </div>
    </section>

    <!-- Футер -->
    <footer>
        <div class="container">
            <div class="footer-content">
                <div class="footer-section">
                    <h3>SportLive</h3>
                    <p>Лучшие спортивные трансляции в прямом эфире. Всегда актуально, всегда в HD.</p>
                </div>
                <div class="footer-section">
                    <h3>Свяжитесь с нами</h3>
                    <p><i class="fas fa-envelope"></i> contact@sportlive.com</p>
                    <p><i class="fas fa-phone"></i> +7 (999) 123-45-67</p>
                </div>
                <div class="footer-section">
                    <h3>Подпишитесь</h3>
                    <div class="social-links">
                        <a href="#"><i class="fab fa-telegram"></i></a>
                        <a href="#"><i class="fab fa-vk"></i></a>
                        <a href="#"><i class="fab fa-youtube"></i></a>
                    </div>
                </div>
            </div>
            <p class="copyright">© 2024 SportLive. Все права защищены.</p>
        </div>
    </footer>

    <script src="script.js"></script>
</body>
</html>
