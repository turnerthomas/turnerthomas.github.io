<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Dream Website</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <h1>My Website Title</h1>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="home">
            <h2>Welcome!</h2>
            <p>This is the start of my dream website. Tell me what content you'd like to feature here!</p>
        </section>

        <section id="about">
            <h2>About Me/Us</h2>
            <p>More detailed information goes here.</p>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 My Website. All rights reserved.</p>
    </footer>
</body>
</html>
/* Basic Reset */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4; /* Light gray background */
    color: #333; /* Dark text */
}

/* Header and Navigation */
header {
    background-color: #007BFF; /* A nice blue color */
    color: white;
    padding: 15px 20px;
}

nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    max-width: 1200px;
    margin: 0 auto;
}

nav ul {
    list-style: none;
    padding: 0;
    margin: 0;
    display: flex;
}

nav ul li {
    margin-left: 20px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-weight: bold;
}

/* Main Content Sections */
main {
    max-width: 1200px;
    margin: 20px auto;
    padding: 0 20px;
}

section {
    background-color: white;
    padding: 40px;
    margin-bottom: 20px;
    border-radius: 8px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

/* Footer */
footer {
    text-align: center;
    padding: 10px;
    background-color: #333;
    color: white;
}
