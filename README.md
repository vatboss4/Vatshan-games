<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Games - Vatboss Games</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Vatboss Games</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="games.html">Games</a></li>
            </ul>
        </nav>
    </header>

    <section class="games">
        <h2>Available Games</h2>
        <div class="game">
            <img src="assets/images/game1.png" alt="Game 1">
            <a href="assets/game1.html">Play Game 1</a>
        </div>
    </section>

    <footer>
        <p>&copy; 2025 Vatboss Games. All Rights Reserved.</p>
    </footer>
</body>
</html>body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    text-align: center;
}

header {
    background: #222;
    color: white;
    padding: 15px;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav a {
    color: white;
    text-decoration: none;
}

.welcome {
    padding: 20px;
}

.game-list, .games {
    padding: 20px;
}

.game img {
    width: 150px;
    height: auto;
    display: block;
    margin: 10px auto;
}

footer {
    background: #222;
    color: white;
    padding: 10px;
    position: absolute;
    width: 100%;
    bottom: 0;
}document.addEventListener("DOMContentLoaded", function() {
    console.log("Welcome to Vatboss Games!");
});
