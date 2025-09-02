<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Никита Амброси - Мультимедиа продюсер</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    <style>
        :root {
            --bg-light: #f5f5f7;
            --bg-dark: #1d1d1f;
            --text-light: #1d1d1f;
            --text-dark: #f5f5f7;
            --card-bg-light: rgba(255, 255, 255, 0.7);
            --card-bg-dark: rgba(40, 40, 40, 0.6);
            --blur-light: 20px;
            --blur-dark: 30px;
            --accent-color-1: #0071e3;
            --accent-color-2: #ff8c00;
            --accent-color-3: #34c759;
            --accent-color-4: #ff2d55;
            
            /* Цвета для анимированных кругов */
            --blob-color-1-light: #a8d0e6;
            --blob-color-2-light: #f7cac9;
            --blob-color-3-light: #f7e1d7;
            --blob-color-1-dark: #3a506b;
            --blob-color-2-dark: #5c3d5e;
            --blob-color-3-dark: #6e5773;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
            transition: background-color 0.5s, color 0.5s;
            position: relative;
            overflow-x: hidden;
        }

        .dark-mode {
            background-color: var(--bg-dark);
            color: var(--text-dark);
        }
        
        .light-mode {
            background-color: var(--bg-light);
            color: var(--text-light);
        }
        
        .glassmorphism {
            backdrop-filter: blur(var(--blur-light));
            -webkit-backdrop-filter: blur(var(--blur-light));
            transition: background-color 0.5s, border-color 0.5s;
        }
        
        html {
            scroll-behavior: smooth;
        }
        
        .narrow-container {
            max-width: 1100px;
            margin: 0 auto;
        }

        .light-mode .glassmorphism {
            background-color: var(--card-bg-light);
            border: 1px solid rgba(255, 255, 255, 0.2);
        }
        
        .dark-mode .glassmorphism {
            background-color: var(--card-bg-dark);
            border: 1px solid rgba(255, 255, 255, 0.1);
            backdrop-filter: blur(var(--blur-dark));
            -webkit-backdrop-filter: blur(var(--blur-dark));
        }

        .header-sticky {
            position: sticky;
            top: 0;
            z-index: 50;
        }

        .material-shape-1 {
            border-radius: 3rem 1rem 3rem 1rem;
        }

        .material-shape-2 {
            border-radius: 1rem 3rem 1rem 3rem;
        }
        
        .gradient-text {
            background: linear-gradient(90deg, var(--accent-color-1), var(--accent-color-4));
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .scroll-reveal {
            opacity: 0;
            transform: translateY(30px);
            transition: opacity 0.8s ease-out, transform 0.8s ease-out;
        }

        .scroll-reveal.visible {
            opacity: 1;
            transform: translateY(0);
        }

        /* Анимированный фон */
        .background-container {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: -1;
            overflow: hidden;
        }

        .blob {
            position: absolute;
            border-radius: 50%;
            filter: blur(120px);
            opacity: 0.5;
            will-change: transform;
            transition: background 0.5s ease;
        }

        .light-mode .blob1 { background: var(--blob-color-1-light); }
        .light-mode .blob2 { background: var(--blob-color-2-light); }
        .light-mode .blob3 { background: var(--blob-color-3-light); }

        .dark-mode .blob1 { background: var(--blob-color-1-dark); }
        .dark-mode .blob2 { background: var(--blob-color-2-dark); }
        .dark-mode .blob3 { background: var(--blob-color-3-dark); }

        .blob1 {
            width: 40vw; height: 40vw; min-width: 300px; min-height: 300px;
            top: -10%; left: -10%;
            animation: move1 25s infinite alternate ease-in-out;
        }

        .blob2 {
            width: 50vw; height: 50vw; min-width: 400px; min-height: 400px;
            bottom: -15%; right: -15%;
            animation: move2 30s infinite alternate ease-in-out;
        }

        .blob3 {
            width: 35vw; height: 35vw; min-width: 250px; min-height: 250px;
            bottom: 25%; right: 30%;
            animation: move3 20s infinite alternate ease-in-out;
        }

        @keyframes move1 {
            from { transform: translate(0, 0) rotate(0deg) scale(1); }
            to { transform: translate(10vw, 5vh) rotate(180deg) scale(1.2); }
        }
        @keyframes move2 {
            from { transform: translate(0, 0) rotate(0deg) scale(1.2); }
            to { transform: translate(-15vw, -10vh) rotate(270deg) scale(1); }
        }
        @keyframes move3 {
            from { transform: rotate(0deg) scale(1); }
            to { transform: rotate(360deg) scale(1.3); }
        }

        /* Анимация карточек при наведении */
        .card-interactive {
            position: relative;
            overflow: hidden;
            transition: transform 0.4s ease, box-shadow 0.4s ease;
        }
        
        .card-interactive:hover {
            transform: translateY(-10px);
            box-shadow: 0 25px 40px rgba(0, 0, 0, 0.1);
        }

        .dark-mode .card-interactive:hover {
            box-shadow: 0 25px 40px rgba(0, 0, 0, 0.3);
        }

        .card-interactive::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 60%;
            height: 100%;
            background: linear-gradient(to right, rgba(255, 255, 255, 0) 0%, rgba(255, 255, 255, 0.4) 50%, rgba(255, 255, 255, 0) 100%);
            transform: skewX(-25deg) translateX(-250%);
            transition: transform 0.7s ease;
        }

        .dark-mode .card-interactive::before {
             background: linear-gradient(to right, rgba(255, 255, 255, 0) 0%, rgba(255, 255, 255, 0.1) 50%, rgba(255, 255, 255, 0) 100%);
        }

        .card-interactive:hover::before {
            transform: skewX(-25deg) translateX(350%);
        }

        /* Стили для видео-превью */
        .video-thumbnail {
            position: relative;
            overflow: hidden;
            cursor: pointer;
        }
        
        .video-thumbnail::after {
            content: '';
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            width: 60px;
            height: 60px;
            background-color: rgba(255, 255, 255, 0.7);
            border-radius: 50%;
            opacity: 0.8;
            transition: all 0.3s ease;
        }
        
        .video-thumbnail::before {
            content: '';
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-40%, -50%);
            border-style: solid;
            border-width: 10px 0 10px 20px;
            border-color: transparent transparent transparent var(--accent-color-1);
            z-index: 2;
        }
        
        .video-thumbnail:hover::after {
            transform: translate(-50%, -50%) scale(1.1);
            background-color: rgba(255, 255, 255, 0.9);
        }
    </style>
</head>
<body class="light-mode">

    <!-- Анимированный фон -->
    <div class="background-container">
        <div class="blob blob1"></div>
        <div class="blob blob2"></div>
        <div class="blob blob3"></div>
    </div>

    <!-- Навигационная панель -->
    <header class="header-sticky glassmorphism">
        <nav class="narrow-container px-6 py-4 flex justify-between items-center">
            <div class="text-2xl font-bold">
                <a href="#">NA.</a>
            </div>
            <div class="flex items-center space-x-6">
                <a href="#about" class="hover:text-gray-400">Обо мне</a>
                <a href="#skills" class="hover:text-gray-400">Навыки</a>
                <a href="#projects" class="hover:text-gray-400">Проекты</a>
                <a href="#contacts" class="hover:text-gray-400">Контакты</a>
                <button id="theme-switcher" class="focus:outline-none">
                    <i class="fas fa-sun text-xl"></i>
                </button>
            </div>
        </nav>
    </header>

    <main class="narrow-container px-6 py-12">

        <!-- Секция "Приветствие" -->
        <section id="hero" class="text-center py-20 scroll-reveal">
            <h1 class="text-5xl md:text-7xl font-bold mb-4">Привет, я <span class="gradient-text">Никита Амброси</span></h1>
            <p class="text-xl md:text-2xl text-gray-500 dark:text-gray-400">Оператор, Режиссёр монтажа и Медиа продюсер из Кишинёва</p>
        </section>

        <!-- Секция "Обо мне" -->
        <section id="about" class="py-20 scroll-reveal">
            <div class="grid md:grid-cols-3 gap-12 items-center">
                <div class="md:col-span-1">
                    <img src="https://instagram.fkiv9-1.fna.fbcdn.net/v/t51.2885-15/542267011_18061859402610267_4588054423210927472_n.jpg?stp=dst-jpg_e35_tt6&efg=eyJ2ZW5jb2RlX3RhZyI6IkZFRUQuaW1hZ2VfdXJsZ2VuLjE0NDB4MTQ0MC5zZHIuZjgyNzg3LmRlZmF1bHRfaW1hZ2UuYzIifQ&_nc_ht=instagram.fkiv9-1.fna.fbcdn.net&_nc_cat=103&_nc_oc=Q6cZ2QGefILP2DIMJ6c7ovRrS1s9zuEFNOT-Eyjo0jbcz3bOI5gpfD6jvIIGUXMs451B89M&_nc_ohc=ZV2gd78oMOoQ7kNvwH2RKHA&_nc_gid=rMQ6XSk24N_4rbC0Bs-uCA&edm=AONqaaQBAAAA&ccb=7-5&ig_cache_key=MzcxMjkzNDgzOTMyMzQ5NDA3OA%3D%3D.3-ccb7-5&oh=00_AfUtASZfIwV8u2oPjkP52SpuL8HesdNakrenuslTFAJwvw&oe=68BCFAC9&_nc_sid=4e3341" alt="Фото Никиты Амброси" class="rounded-full mx-auto w-48 h-48 md:w-64 md:h-64 object-cover shadow-lg">
                </div>
                <div class="md:col-span-2">
                    <h2 class="text-4xl font-bold mb-6">Немного обо мне</h2>
                    <p class="mb-4 text-lg leading-relaxed">
                        Я студент второго курса Государственного Университета Молдовы, где изучаю мультимедиа производство. Моя страсть — это создание визуального контента, который рассказывает истории и вызывает эмоции. Я занимаюсь монтажом, графическим дизайном, съёмкой видео и постоянно развиваюсь в сфере кинематографа.
                    </p>
                    <p class="text-lg leading-relaxed">
                        Уже успел поучаствовать в университетских и личных проектах в роли оператора, продюсера и даже актера. Эти проекты помогли мне развить навыки командной работы и лидерства в съёмочной группе. В свободное время я изучаю новые техники монтажа, экспериментирую с визуальными эффектами и снимаю короткометражные фильмы.
                    </p>
                    <div class="mt-6 grid grid-cols-2 gap-4">
                        <div>
                            <p class="font-semibold">Имя:</p>
                            <p>Никита Амброси</p>
                        </div>
                        <div>
                            <p class="font-semibold">Дата рождения:</p>
                            <p>21.11.2004</p>
                        </div>
                        <div>
                            <p class="font-semibold">Местоположение:</p>
                            <p>Молдова, Кишинёв</p>
                        </div>
                        <div>
                            <p class="font-semibold">Образование:</p>
                            <p>Государственный Университет Молдовы, 2 курс</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Секция "Навыки" -->
        <section id="skills" class="py-20 scroll-reveal">
            <h2 class="text-4xl font-bold text-center mb-12">Мои навыки и умения</h2>
            <div class="grid grid-cols-2 md:grid-cols-4 gap-8">
                <div class="glassmorphism p-6 rounded-3xl text-center shadow-md material-shape-1 card-interactive">
                    <i class="fas fa-film text-4xl mb-4" style="color: var(--accent-color-1);"></i>
                    <h3 class="text-xl font-semibold">Видеомонтаж</h3>
                </div>
                <div class="glassmorphism p-6 rounded-3xl text-center shadow-md material-shape-2 card-interactive">
                    <i class="fas fa-video text-4xl mb-4" style="color: var(--accent-color-2);"></i>
                    <h3 class="text-xl font-semibold">Видеосъёмка</h3>
                </div>
                <div class="glassmorphism p-6 rounded-3xl text-center shadow-md material-shape-1 card-interactive">
                    <i class="fas fa-paint-brush text-4xl mb-4" style="color: var(--accent-color-3);"></i>
                    <h3 class="text-xl font-semibold">Графический дизайн</h3>
                </div>
                <div class="glassmorphism p-6 rounded-3xl text-center shadow-md material-shape-2 card-interactive">
                    <i class="fas fa-theater-masks text-4xl mb-4" style="color: var(--accent-color-4);"></i>
                    <h3 class="text-xl font-semibold">Актёрское мастерство</h3>
                </div>
            </div>
        </section>

        <!-- Секция "Проекты" -->
        <section id="projects" class="py-20 scroll-reveal">
            <h2 class="text-4xl font-bold text-center mb-12">Мои проекты</h2>
            <div class="grid md:grid-cols-2 gap-10">
                <!-- Проект 1 -->
                <div class="glassmorphism rounded-3xl overflow-hidden shadow-lg group card-interactive">
                    <div class="video-thumbnail">
                        <img src="https://images.unsplash.com/photo-1536240478700-b869070f9279?q=80&w=1840&auto=format&fit=crop" alt="Университетский проект" class="w-full h-64 object-cover group-hover:scale-105 transition-transform duration-500">
                    </div>
                    <div class="p-8">
                        <h3 class="text-2xl font-bold mb-2">Университетский короткометражный фильм</h3>
                        <p class="mb-4">Работа над короткометражным фильмом в качестве оператора и режиссёра монтажа. Проект получил высокую оценку преподавателей.</p>
                        <a href="#" class="font-semibold" style="color: var(--accent-color-1);">Подробнее &rarr;</a>
                    </div>
                </div>
                <!-- Проект 2 -->
                <div class="glassmorphism rounded-3xl overflow-hidden shadow-lg group card-interactive">
                    <div class="video-thumbnail">
                        <img src="https://images.unsplash.com/photo-1555949963-ff9fe0c870eb?q=80&w=2070&auto=format&fit=crop" alt="Документальный проект" class="w-full h-64 object-cover group-hover:scale-105 transition-transform duration-500">
                    </div>
                    <div class="p-8">
                        <h3 class="text-2xl font-bold mb-2">Документальный проект о культуре Молдовы</h3>
                        <p class="mb-4">Участие в создании документального фильма в роли продюсера и оператора. Исследование культурного наследия страны.</p>
                        <a href="#" class="font-semibold" style="color: var(--accent-color-1);">Подробнее &rarr;</a>
                    </div>
                </div>
            </div>
        </section>
        
        <!-- Секция "Философия творчества" -->
        <section id="philosophy" class="py-20 scroll-reveal">
            <h2 class="text-4xl font-bold text-center mb-12">Мой подход к работе</h2>
            <div class="grid md:grid-cols-3 gap-8 text-center">
                <div class="p-4">
                    <div class="w-24 h-24 rounded-full mx-auto mb-4 flex items-center justify-center" style="background-color: var(--accent-color-1);">
                        <i class="fas fa-lightbulb text-4xl text-white"></i>
                    </div>
                    <h3 class="text-2xl font-semibold mb-2">Креативность</h3>
                    <p class="text-gray-500 dark:text-gray-400">Я верю, что каждый проект — это возможность создать что-то уникальное. Я всегда ищу новые подходы и нестандартные решения.</p>
                </div>
                <div class="p-4">
                     <div class="w-24 h-24 rounded-full mx-auto mb-4 flex items-center justify-center" style="background-color: var(--accent-color-3);">
                        <i class="fas fa-users text-4xl text-white"></i>
                    </div>
                    <h3 class="text-2xl font-semibold mb-2">Командная работа</h3>
                    <p class="text-gray-500 dark:text-gray-400">Создание качественного контента — всегда результат слаженной работы команды. Я ценю коллаборацию и открытое общение.</p>
                </div>
                <div class="p-4">
                     <div class="w-24 h-24 rounded-full mx-auto mb-4 flex items-center justify-center" style="background-color: var(--accent-color-2);">
                        <i class="fas fa-film text-4xl text-white"></i>
                    </div>
                    <h3 class="text-2xl font-semibold mb-2">Внимание к деталям</h3>
                    <p class="text-gray-500 dark:text-gray-400">Мелочи создают большую картину. Я уделяю внимание каждой детали — от ракурса камеры до переходов в монтаже.</p>
                </div>
            </div>
        </section>

        <!-- Секция "Контакты" -->
        <section id="contacts" class="py-20 scroll-reveal">
            <h2 class="text-4xl font-bold text-center mb-12">Свяжитесь со мной</h2>
            <div class="text-center">
                <p class="text-lg mb-8">Я всегда открыт для новых проектов и сотрудничества. Давайте создавать что-то удивительное вместе!</p>
                <div class="flex justify-center space-x-6 mb-8">
                    <a href="https://www.instagram.com/nnuduck/" target="_blank" class="text-2xl hover:text-blue-500 transition-colors">
                        <i class="fab fa-instagram"></i>
                    </a>
                    <a href="t.me/nnuduck" target="_blank" class="text-2xl hover:text-blue-500 transition-colors">
                        <i class="fab fa-telegram"></i>
                    </a>
                    <a href="https://www.linkedin.com/in/%D0%BD%D0%B8%D0%BA%D0%B8%D1%82%D0%B0-%D0%B0%D0%BC%D0%B1%D1%80%D0%BE%D1%81%D0%B8-4281a7344/" target="_blank" class="text-2xl hover:text-blue-500 transition-colors">
                        <i class="fab fa-linkedin"></i>
                    </a>
                    <a href="https://www.youtube.com/@nnuduck" target="_blank" class="text-2xl hover:text-blue-500 transition-colors">
                        <i class="fab fa-youtube"></i>
                    </a>
                </div>
                <a href="tvkrsh.off@gmail.com" class="inline-block px-6 py-3 glassmorphism rounded-full font-semibold hover:shadow-lg transition-shadow">Написать мне</a>
            </div>
        </section>

    </main>

    <!-- Футер -->
    <footer class="py-10 border-t border-gray-200 dark:border-gray-800">
		<div class="narrow-container px-6 text-center">
			<p>&copy; 2025 Никита Амброси. Все права защищены.</p>
		</div>
	</footer>

    <script>
        const themeSwitcher = document.getElementById('theme-switcher');
        const body = document.body;
        const icon = themeSwitcher.querySelector('i');

        // Функция для применения темы
        const applyTheme = (theme) => {
            if (theme === 'dark') {
                body.classList.remove('light-mode');
                body.classList.add('dark-mode');
                icon.classList.remove('fa-sun');
                icon.classList.add('fa-moon');
            } else {
                body.classList.remove('dark-mode');
                body.classList.add('light-mode');
                icon.classList.remove('fa-moon');
                icon.classList.add('fa-sun');
            }
        };

        // Загрузка темы из localStorage
        const savedTheme = localStorage.getItem('theme') || 'light';
        applyTheme(savedTheme);

        // Переключение темы
        themeSwitcher.addEventListener('click', () => {
            const newTheme = body.classList.contains('light-mode') ? 'dark' : 'light';
            applyTheme(newTheme);
            localStorage.setItem('theme', newTheme);
        });
        
        // Анимация при скролле
        const scrollRevealElements = document.querySelectorAll('.scroll-reveal');

        const revealOnScroll = () => {
            scrollRevealElements.forEach(el => {
                const elementTop = el.getBoundingClientRect().top;
                const windowHeight = window.innerHeight;

                if (elementTop < windowHeight - 100) {
                    el.classList.add('visible');
                }
            });
        };

        window.addEventListener('scroll', revealOnScroll);
        // Первый вызов для элементов, которые уже видимы
        revealOnScroll();

        // Обработка кликов по видео-превью
        document.querySelectorAll('.video-thumbnail').forEach(thumbnail => {
            thumbnail.addEventListener('click', function() {
                // Здесь можно добавить логику открытия модального окна с видео
                alert('Здесь будет открытие видео в будущем');
            });
        });
    </script>
</body>
</html>
