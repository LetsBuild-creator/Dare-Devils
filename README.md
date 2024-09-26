<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dare Devils | Content Creation Agency</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Dare Devils</h1>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#gallery">Gallery</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="about">
        <h2>About Us</h2>
        <p>Dare Devils is a premier content creation agency that specializes in delivering high-quality visual and written content. Our mission is to help brands tell their stories through creativity and innovation.</p>
    </section>

    <section id="gallery">
        <h2>Gallery</h2>
        <div class="gallery-container">
            <img src="KOLORO_1718550408953" alt="Image 1">
            <img src="KOLORO_172087385947" alt="Image 2">
            <img src="KOLORO_1720802557797" alt="Image 3">
            <img src="IMG-20240220_WA0113.jpg" alt="Image 4">
        </div>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <p>Email: <a href="mailto:info@daredevils.com">info@daredevils.com</a></p>
        <p>Phone: <a href="tel:+1234567890">+1 (234) 567-890</a></p>
    </section>

    <footer>
        <p>&copy; 2024 Dare Devils. All rights reserved.</p>
    </footer>
</body>
</html>
```

### CSS (styles.css)

```css
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    color: #fff;
    background-color: #000;
}

header {
    background-color: #111;
    padding: 20px;
    text-align: center;
}

nav ul {
    list-style-type: none;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
}

section {
    padding: 40px;
    text-align: center;
}

.gallery-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
}

.gallery-container img {
    margin: 10px;
    max-width: 200px;
    height: auto;
    border: 2px solid #fff;
}

footer {
    background-color: #111;
    text-align: center;
    padding: 10px;
}
```
