<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Plant Shop</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="background">
        <div class="overlay">
            <header>
                <h1>Welcome to the Plant Shop</h1>
            </header>
            <main>
                <h2>Discover Our Collection of House Plants</h2>
                <p>Your one-stop shop for all your indoor plant needs.</p>
            </main>
            <footer>
                <p>&copy; 2024 Plant Shop. All rights reserved.</p>
            </footer>
        </div>
    </div>
</body>
</html>


* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Arial', sans-serif;
}

body, html {
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
}

.background {
    background-image: url('path-to-your-background-image.jpg');
    background-size: cover;
    background-position: center;
    width: 100%;
    height: 100%;
    position: relative;
    display: flex;
    justify-content: center;
    align-items: center;
}

.overlay {
    background: rgba(0, 0, 0, 0.5);
    color: #fff;
    padding: 20px;
    border-radius: 10px;
    text-align: center;
}

header h1 {
    font-size: 3rem;
    margin-bottom: 20px;
}

main h2 {
    font-size: 2rem;
    margin-bottom: 10px;
}

main p {
    font-size: 1.2rem;
}

footer {
    margin-top: 20px;
    font-size: 0.8rem;
}
