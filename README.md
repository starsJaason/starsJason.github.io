<!DOCTYPE html>
<html lang="zh">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>施昱成的个人介绍网站</title>
    <link rel="stylesheet" href="style.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }

        header {
            background: url('cover.jpg') no-repeat center center/cover;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            color: white;
        }

        header h1 {
            font-size: 4em;
            margin: 0;
        }

        nav ul {
            list-style: none;
            display: flex;
            gap: 20px;
            margin: 20px 0 0 0;
            padding: 0;
        }

        nav ul li {
            display: inline;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
            font-size: 1.2em;
            transition: color 0.3s;
        }

        nav ul li a:hover {
            color: #f39c12;
        }

        section {
            padding: 60px 20px;
            text-align: center;
        }

        #about {
            background-color: #fff;
        }

        #contact {
            background-color: #fff;
        }

        h2 {
            font-size: 2.5em;
            margin-bottom: 20px;
        }

        .content {
            max-width: 800px;
            margin: 0 auto;
            line-height: 1.6;
        }

        footer {
            background-color: #333;
            color: white;
            padding: 20px;
            text-align: center;
        }
    </style>
</head>
<body>

<header>
    <div>
        <h1>你好，我是施昱成</h1>
        <nav>
            <ul>
                <li><a href="#about">关于我</a></li>
                <li><a href="#contact">联系我</a></li>
            </ul>
        </nav>
    </div>
</header>

<section id="about">
    <h2>关于我</h2>
    <div class="content">
        <p>我是施昱成，一个抽象区热爱折腾的创作者。拥有14年的经验，专注于抽象和折腾领域。我喜欢解决复杂的问题并开发有用的工具。</p>
    </div>
</section>

<section id="contact">
    <h2>联系我</h2>
    <div class="content">
        <p>你可以通过以下方式联系我：</p>
        <p>Email: shiyucheng1022@outlook.com</p>
        <p>Phone: 13135466122</p>
    </div>
</section>

<footer>
    <p>&copy; 2024 施昱成. 保留所有权利。</p>
</footer>

</body>
</html>

