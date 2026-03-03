<!DOCTYPE html>
<html>
<head>
    <title>Trose Art</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            text-align: center;
        }

        header {
            background: linear-gradient(to right, #6a11cb, #2575fc);
            color: white;
            padding: 40px 20px;
        }

        h1 {
            margin: 0;
            font-size: 40px;
        }

        nav {
            background: #222;
            padding: 15px;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }

        nav a:hover {
            color: #2575fc;
        }

        .section {
            padding: 50px 20px;
        }

        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            padding: 20px;
        }

        .gallery img {
            width: 100%;
            border-radius: 10px;
        }

        footer {
            background: #222;
            color: white;
            padding: 20px;
            margin-top: 40px;
        }
    </style>
</head>

<body>

<header>
    <h1>Trose Art</h1>
    <p>Creative. Bold. Original.</p>
</header>

<nav>
    <a href="#about">About</a>
    <a href="#gallery">Gallery</a>
    <a href="#contact">Contact</a>
</nav>

<div class="section" id="about">
    <h2>About Me</h2>
    <p>Welcome to my art website! I create unique and expressive artwork inspired by imagination, color, and emotion.</p>
</div>

<div class="section" id="gallery">
    <h2>Gallery</h2>
    <div class="gallery">
        <img src="https://via.placeholder.com/400x300" alt="Art 1">
        <img src="https://via.placeholder.com/400x300" alt="Art 2">
        <img src="https://via.placeholder.com/400x300" alt="Art 3">
    </div>
</div>

<div class="section" id="contact">
    <h2>Contact</h2>
    <p>Email: tristancorpphotos@gmail.com</p>
</div>

<footer>
    <p>© 2026 Trose Art. All rights reserved.</p>
</footer>

</body>
</html>
