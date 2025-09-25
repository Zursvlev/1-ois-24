<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>OOO "Kazakh IT"</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #f5f7fa;
            color: #333;
            line-height: 1.6;
        }
        header {
            background: linear-gradient(135deg, #1e3c72, #2a5298);
            color: white;
            text-align: center;
            padding: 2rem 1rem;
            box-shadow: 0 4px 12px rgba(0,0,0,0.1);
        }
        .logo {
            max-width: 300px;
            margin: 0 auto 1.5rem;
            border-radius: 8px;
            box-shadow: 0 4px 12px rgba(0,0,0,0.2);
        }
        h1 {
            font-size: 2.5rem;
            margin-bottom: 0.5rem;
        }
        .container {
            max-width: 1200px;
            margin: 2rem auto;
            padding: 0 1.5rem;
        }
        section {
            background: white;
            padding: 2rem;
            margin-bottom: 2rem;
            border-radius: 12px;
            box-shadow: 0 4px 12px rgba(0,0,0,0.05);
        }
        h2 {
            color: #2a5298;
            border-bottom: 2px solid #1e3c72;
            padding-bottom: 0.5rem;
            margin-bottom: 1.5rem;
            font-size: 2rem;
        }
        ol, ul {
            padding-left: 2rem;
            margin: 1rem 0;
        }
        li {
            margin: 0.5rem 0;
            font-size: 1.1rem;
        }
        .staff-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 1.5rem;
            margin-top: 1rem;
        }
        .staff-card {
            background: #f0f4f8;
            padding: 1.5rem;
            border-radius: 10px;
            text-align: center;
            transition: transform 0.3s ease;
        }
        .staff-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 6px 16px rgba(0,0,0,0.1);
        }
        .staff-card h3 {
            color: #1e3c72;
            margin-bottom: 0.5rem;
        }
        .products-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 1.5rem;
            margin-top: 1rem;
        }
        .product-card {
            border: 1px solid #ddd;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 4px 8px rgba(0,0,0,0.05);
        }
        .product-card img {
            width: 100%;
            height: 200px;
            object-fit: cover;
            transition: transform 0.3s ease;
        }
        .product-card:hover img {
            transform: scale(1.05);
        }
        .product-card h4 {
            padding: 1rem;
            text-align: center;
            background: #fafafa;
            font-size: 1.1rem;
        }
        footer {
            text-align: center;
            padding: 1.5rem;
            background: #2a5298;
            color: white;
            margin-top: 2rem;
            font-size: 0.9rem;
        }
        @media (max-width: 768px) {
            h1 {
                font-size: 2rem;
            }
            .container {
                padding: 0 1rem;
            }
            section {
                padding: 1.5rem;
            }
        }
    </style>
</head>
<body>
    <header>
        <img src="https://i.imgur.com/9YmRqVh.png" alt="Логотип KazakhIT" class="logo">
        <h1>ООО "Kazakh IT"</h1>
        <p>Технологии будущего — сегодня</p>
    </header><div class="container">
        <!-- Правила -->
        <section>
            <h2>Правила компании</h2>
            <ol>
                <li><strong>Не ругаться</strong> — уважайте коллег и клиентов.</li>
                <li><strong>Быть вежливым</strong> — доброе слово не требует усилий.</li>
                <li><strong>Уважать всех работников</strong> — каждый вносит свой вклад.</li>
                <li><strong>Перерыв два раза в день</strong> — забота о вашем здоровье.</li>
                <li><strong>Не опаздывать</strong> — время — наш главный ресурс.</li>
                <li><strong>Соблюдать технику безопасности</strong> — ваша безопасность превыше всего.</li>
                <li><strong>Не засорять чат</strong> — чистота в коммуникациях = эффективность.</li>
            </ol>
        </section>

        <!-- Сотрудники -->
        <section>
            <h2>Наша команда</h2>
            <div class="staff-grid">
                <div class="staff-card">
                    <h3>Евгений</h3>
                    <p>Владелец</p>
                </div>
                <div class="staff-card">
                    <h3>Захар</h3>
                    <p>Директор</p>
                </div>
                <div class="staff-card">
                    <h3>Константин</h3>
                    <p>Уборщик</p>
                </div>
                <div class="staff-card">
                    <h3>Кирилл</h3>
                    <p>Бухгалтер</p>
                </div>
            </div>
        </section>

        <!-- Товары -->
        <section>
            <h2>Наши товары</h2>
            <div class="products-grid">
                <div class="product-card">
                    <img src="https://i.imgur.com/5XQkLzH.jpg" alt="Ноутбук">
                    <h4>Ноутбуки</h4>
                </div>
                <div class="product-card">
                    <img src="https://i.imgur.com/9gWvBZd.jpg" alt="Холодильник">
                    <h4>Холодильники</h4>
                </div>
                <div class="product-card">
                    <img src="https://i.imgur.com/7rCmDnU.jpg" alt="Электротехника">
                    <h4>Разная электротехника</h4>
                </div>
            </div>
        </section>
    </div>

    <footer>
        © 2025 ООО "Kazakh IT" — Все права защищены.
    </footer>
</body>
</html>
