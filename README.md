<html lang="ru">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Моё Портфолио</title>
    * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    color: #333;
}


header {
    background-color: #4A90E2;
    padding: 20px;
    position: fixed;
    width: 100%;
    top: 0;
    z-index: 100;
}

nav {
    text-align: center;
}

nav a {
    display: inline-block;
    color: white;
    text-decoration: none;
    margin: 0 15px;
    font-size: 18px;
}

nav a:hover {
    text-decoration: underline;
}


.logo {
    background: linear-gradient(to right, #667eea, #764ba2);
    color: white;
    text-align: center;
    padding: 120px 20px 60px;
}

.logo img {
    width: 200px;
    height: 200px;
    border-radius: 50%;
    border: 5px solid white;
    margin-bottom: 20px;
}

.logo h1 {
    font-size: 36px;
    margin-bottom: 10px;
}

.slogan {
    font-size: 20px;
}


section {
    padding: 60px 20px;
    max-width: 1000px;
    margin: 0 auto;
}

section h2 {
    text-align: center;
    font-size: 32px;
    margin-bottom: 30px;
    color: #333;
}

section h3 {
    font-size: 24px;
    margin: 30px 0 15px;
    color: #4A90E2;
}


#about {
    background-color: #f4f4f4;
}

.info-block {
    background-color: white;
    padding: 20px;
    margin-bottom: 20px;
    border-radius: 8px;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
}

.info-block p {
    margin: 8px 0;
}

.skills-list {
    margin-bottom: 30px;
}

.skill {
    margin-bottom: 20px;
}

.skill p {
    font-weight: bold;
    margin-bottom: 5px;
}

.bar {
    background-color: #e0e0e0;
    height: 25px;
    border-radius: 10px;
    overflow: hidden;
}

.progress {
    background: linear-gradient(to right, #4A90E2, #50C878);
    height: 100%;
    border-radius: 10px;
}

.soft-skills {
    display: flex;
    flex-wrap: wrap;
    gap: 10px;
    justify-content: center;
}

.soft-skills span {
    background-color: #4A90E2;
    color: white;
    padding: 10px 20px;
    border-radius: 20px;
}
</head>

<body>
    <header>
        <nav>
            <a href="#home">Главная</a>
            <a href="#about">О себе</a>
            <a href="#skills">Навыки</a>
            <a href="#projects">Проекты</a>
            <a href="#contact">Контакты</a>
        </nav>
    </header>

    <section id="home" class="logo">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRiBBbLWhm1T7lasQYs2MPvOobfRB8zrbAYVg&s"
            alt="лого">
        <h1>Привет! Я Артур</h1>
        <p class="slogan">Начинающий веб-разработчик</p>
    </section>

    <section id="about">
        <h2>О себе</h2>

        <div class="info-block">
            <h3>Биография</h3>
            <p><strong>Имя:</strong> Артур</p>
            <p><strong>Город:</strong> Павлодар</p>
            <p><strong>Университет:</strong> Торайгыров Университет</p>
            <p><strong>Специальность:</strong> Информационные системы</p>
        </div>

        <div class="info-block">
            <h3>Интересы</h3>
            <p>Увлекаюсь веб-разработкой и дизайном. Изучаю HTML, CSS и JavaScript.</p>
        </div>

        <div class="info-block">
            <h3>Хобби</h3>
            <p> Игры | Программирование | Спорт | Волейбол</p>
        </div>
    </section>

    <section id="skills">
        <h2>Мои навыки</h2>

        <h3>Технические навыки</h3>
        <div class="skills-list">
            <div class="skill">
                <p>HTML</p>
                <div class="bar">
                    <div class="progress" style="width: 80%"></div>
                </div>
            </div>

            <div class="skill">
                <p>CSS</p>
                <div class="bar">
                    <div class="progress" style="width: 70%"></div>
                </div>
            </div>

            <div class="skill">
                <p>JavaScript</p>
                <div class="bar">
                    <div class="progress" style="width: 30%"></div>
                </div>
            </div>
        </div>

        <h3>Мягкие навыки</h3>
        <div class="soft-skills">
            <span>Командная работа</span>
            <span>Ответственность</span>
            <span>Коммуникация</span>
        </div>
    </section>

    <section id="projects">
        <h2>Проекты</h2>

        <div class="project">
            <img src="" alt="Проект 1">
            <h3></h3>
            <p></p>
        </div>

        <div class="project">
            <img src="" alt="Проект 2">
            <h3></h3>
            <p></p>
        </div>

        <div class="project">
            <img src="" alt="Проект 3">
            <h3></h3>
            <p></p>
        </div>
    </section>

    <section id="achievements">
        <h2>Достижения</h2>


        <div class="achievement">
            <p> Сертификат курса по веб-разработке</p>
        </div>

    </section>

    <section id="contact">
        <h2>Контакты</h2>

        <div class="contacts">
            <p>Email: <a href="Hartonic@yandex.kz">Hartonic@yandex.kz</a></p>
            <p>Telegram: <a href="https://t.me/@H4Rt19">@H4Rt19</a></p>
            <p>Instagram: <a href="https://www.instagram.com/hihfrd32/">hihfrd32</a></p>
            <p>GitHub: <a href="https://github.com/H4RT1X">github.com/H4RT1X</a></p>
        </div>
    </section>

    <footer>

    </footer>
</body>

</html>
