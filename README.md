# -<!DOCTYPE html>
<html lang="zh-Hant">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>班上外訂統整平台</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f9f9f9;
            color: #333;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            margin: 20px;
            text-align: center;
        }
        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: #4CAF50;
            font-weight: bold;
        }
        main {
            margin: 20px;
        }
        footer {
            text-align: center;
            padding: 10px 0;
            background-color: #f1f1f1;
            margin-top: 20px;
        }
        .project-list {
            list-style-type: none;
            padding: 0;
        }
        .project-list li {
            background-color: white;
            margin: 10px 0;
            padding: 15px;
            border: 1px solid #ddd;
            border-radius: 5px;
        }
        .form-group {
            margin-bottom: 15px;
        }
        .form-group label {
            display: block;
            margin-bottom: 5px;
        }
        .form-group input, .form-group textarea {
            width: 100%;
            padding: 8px;
            box-sizing: border-box;
        }
        .form-group button {
            background-color: #4CAF50;
            color: white;
            padding: 10px 20px;
            border: none;
            cursor: pointer;
        }
    </style>
</head>
<body>

<header>
    <h1>班上外訂統整平台</h1>
</header>

<nav>
    <a href="#projects">外訂項目</a>
    <a href="#submit">提交新項目</a>
    <a href="#contact">聯絡我們</a>
</nav>

<main>
    <section id="projects">
        <h2>外訂項目</h2>
        <ul class="project-list">
            <li>
                <h3>項目名稱: A</h3>
                <p>負責同學: 王小明</p>
                <p>簡介: 這是項目 A 的簡介。</p>
                <p>聯絡方式: email@example.com</p>
            </li>
            <!-- 可以在這裡添加更多項目 -->
        </ul>
    </section>

    <section id="submit">
        <h2>提交新項目</h2>
        <form>
            <div class="form-group">
                <label for="project-name">項目名稱</label>
                <input type="text" id="project-name" name="project-name">
            </div>
            <div class="form-group">
                <label for="student-name">負責同學姓名</label>
                <input type="text" id="student-name" name="student-name">
            </div>
            <div class="form-group">
                <label for="project-description">項目簡介</label>
                <textarea id="project-description" name="project-description"></textarea>
            </div>
            <div class="form-group">
                <label for="contact-info">聯絡方式</label>
                <input type="text" id="contact-info" name="contact-info">
            </div>
            <div class="form-group">
                <button type="submit">提交</button>
            </div>
        </form>
    </section>

    <section id="contact">
        <h2>聯絡我們</h2>
        <p>如果你有任何問題或建議，請聯絡我們。</p>
        <p>Email: support@example.com</p>
    </section>
</main>

<footer>
    <p>&copy; 2024 班上外訂統整平台</p>
</footer>

</body>
</html>
