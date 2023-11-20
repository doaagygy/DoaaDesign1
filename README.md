<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nora Whab - Graphic Designer</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>Nora Whab</h1>
            <p>Graphic Designer</p>
            <nav>
                <ul>
                    <li><a href="#portfolio">Portfolio</a></li>
                    <li><a href="#about">About</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="portfolio" class="portfolio">
        <div class="container">
            <h2>Portfolio</h2>
            <!-- Add portfolio items here -->
        </div>
    </section>

    <section id="about" class="about">
        <div class="container">
            <h2>About Me</h2>
            <p>Graphic designer with a passion for creating beautiful and meaningful designs...</p>
        </div>
    </section>

    <section id="contact" class="contact">
        <div class="container">
            <h2>Contact Me</h2>
            <!-- Add a contact form or other contact information here -->
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2023 Nora Whab. All rights reserved.</p>
        </div>
    </footer>

    <script src="script.js"></script>
</body>
</html>
body {
    font-family: 'Arial', sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
    color: #333;
}

.container {
    width: 80%;
    margin: 0 auto;
}

header {
    background-color: #333;
    color: #fff;
    padding: 2em 0;
}

header h1 {
    margin: 0;
    font-size: 2em;
}

header p {
    margin: 0;
    font-size: 1.2em;
}

nav ul {
    list-style: none;
    padding: 0;
    margin: 0;
}

nav ul li {
    display: inline;
    margin-right: 20px;
}

nav a {
    text-decoration: none;
    color: #fff;
    font-weight: bold;
    font-size: 1.2em;
}

section {
    padding: 4em 0;
}

h2 {
    color: #333;
}

footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 1em 0;
    position: fixed;
    bottom: 0;
    width: 100%;
}
