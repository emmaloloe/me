<!-- Basic HTML structure -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Homepage</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Welcome to My Homepage</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section>
            <h2>Main Content</h2>
            <p>This is the main content area of the homepage.</p>
        </section>
    </main>
    <footer>
        <p>&copy; 2025 My Homepage</p>
    </footer>
</body>
</html>

/* styles.css */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
}

body {
    line-height: 1.6;
    color: #333;
    background-color: #f4f4f4;
}

/* Header Styles */
header {
    background-color: #2c3e50;
    color: white;
    text-align: center;
    padding: 2rem 0;
}

header h1 {
    font-size: 2.5rem;
    margin-bottom: 1rem;
}

nav ul {
    list-style: none;
    display: flex;
    justify-content: center;
    gap: 2rem;
}

nav a {
    color: white;
    text-decoration: none;
    font-weight: bold;
    transition: color 0.3s;
}

nav a:hover {
    color: #3498db;
}

/* Main Content Styles */
main {
    max-width: 800px;
    margin: 2rem auto;
    padding: 0 1rem;
}

section {
    background-color: white;
    padding: 2rem;
    border-radius: 8px;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
}

section h2 {
    font-size: 1.8rem;
    margin-bottom: 1rem;
    color: #2c3e50;
}

section p {
    font-size: 1.1rem;
}

/* Footer Styles */
footer {
    text-align: center;
    padding: 1rem;
    background-color: #2c3e50;
    color: white;
    position: fixed;
    bottom: 0;
    width: 100%;
}

/* Responsive Design */
@media (max-width: 600px) {
    header h1 {
        font-size: 1.8rem;
    }

    nav ul {
        flex-direction: column;
        gap: 1rem;
    }

    section {
        padding: 1rem;
    }
}
