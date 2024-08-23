<!DOCTYPE html>
<html lang="zh">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>个人简介</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            color: #333;
            overflow-x: hidden;
        }
        header {
            position: relative;
            background: url('your-background-image.jpg') no-repeat center center;
            background-size: cover;
            color: white;
            text-align: center;
            padding: 100px 20px;
            height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            overflow: hidden;
        }
        header::after {
            content: "";
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: rgba(0, 0, 0, 0.5); /* 半透明覆盖层 */
            z-index: 1;
        }
        .header-content {
            position: relative;
            z-index: 2;
            text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.7);
        }
        .header-content h1 {
            font-size: 4em;
            margin: 0;
            animation: fadeInUp 1s ease-out;
        }
        .header-content p {
            font-size: 1.5em;
            margin: 20px 0;
            animation: fadeInUp 1.5s ease-out;
        }
        .header-content a {
            display: inline-block;
            padding: 10px 20px;
            background-color: #4CAF50;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            font-size: 1.2em;
            transition: background-color 0.3s;
            animation: fadeInUp 2s ease-out;
        }
        .header-content a:hover {
            background-color: #45a049;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
            position: sticky;
            top: 0;
            z-index: 10;
        }
        nav a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
            display: block;
            transition: background-color 0.3s;
        }
        nav a:hover {
            background-color: #575757;
        }
        .container {
            padding: 20px;
        }
        .section {
            margin-bottom: 20px;
        }
        h2 {
            border-bottom: 2px solid #4CAF50;
            padding-bottom: 10px;
            margin-top: 0;
        }
        .project-item {
            margin-bottom: 20px;
        }
        .project-item img {
            max-width: 100%;
            height: auto;
            border-radius: 5px;
        }
        .testimonial {
            border-left: 4px solid #4CAF50;
            padding-left: 20px;
            margin-bottom: 20px;
            font-style: italic;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            position: relative;
            bottom: 0;
            width: 100%;
        }
        .social-links a {
            margin: 0 10px;
            color: white;
            font-size: 1.5em;
            text-decoration: none;
        }
        .social-links a:hover {
            color: #4CAF50;
        }
        @keyframes fadeInUp {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }
    </style>
</head>
<body>
    <header>
        <div class="header-content">
            <h1>个人简介</h1>
            <p>欢迎来到我的个人网站！</p >
            了解更多
        </div>
    </header>
    
    <nav>
        关于我
        技能
        项目
        联系方式
    </nav>

    <div class="container">
        <section id="about" class="section">
            <h2>关于我</h2>
            <p>你好，我叫施昱成</p >
        </section>

        <section id="skills" class="section">
            <h2>技能</h2>
            <ul>
                <li>地理 1</li>
                <li>历史 2</li>
                <li>折腾 3</li>
            </ul>
        </section>

       

        <section id="testimonials" class="section">
            <h2>评价</h2>
            <div class="testimonial">
                <p>"抽象"</p >
                <cite>- 铁蛋</cite>
            </div>
            <div class="testimonial">
                <p>"过于强大."</p >
                <cite>- Jason</cite>
            </div>
        </section>

        <section id="contact" class="section">
            <h2>联系方式: 13136599122</h2>
            <p>邮箱：shiyucheng1022@outlook.com</p >
            <p>LinkedIn：</p >
            <div class="social-links">
                
                
                
            </div>
        </section>
    </div>

    <footer>
        <p>© 2024 施昱成. 版权所有.</p >
    </footer>
</body>
</html>
