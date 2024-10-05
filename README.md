<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 10px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: space-around;
            background-color: #333;
        }
        nav a {
            padding: 14px 20px;
            display: block;
            color: white;
            text-align: center;
            text-decoration: none;
        }
        nav a:hover {
            background-color: #ddd;
            color: black;
        }
        .container {
            padding: 20px;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>

<header>
    <h1>Your Name</h1>
    <p>Web Developer | Python Enthusiast | Gamer</p>
</header>

<nav>
    <a href="#about">About</a>
    <a href="#portfolio">Portfolio</a>
    <a href="#contact">Contact</a>
</nav>

<div class="container">
    <section id="about">
        <h2>About Me</h2>
        <p>Welcome to my personal website! I'm a web developer passionate about Python and game development.</p>
    </section>

    <section id="portfolio">
        <h2>Portfolio</h2>
        <p>Check out my recent projects, including Python games with Pygame!</p>
    </section>

    <section id="contact">
        <h2>Contact</h2>
        <p>Email me at: vincecustodio22@gmail.com</p>
    </section>
</div>

<footer>
    <p>&copy; 2024 Your Name - All Rights Reserved</p>
</footer>

</body>
</html>
