<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="A sample webpage with detailed information">
    <title>Informative Webpage</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #007BFF;
            color: white;
            padding: 10px 20px;
            text-align: center;
        }
        nav {
            display: flex;
            background-color: #f4f4f4;
            padding: 10px;
            justify-content: center;
        }
        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: #007BFF;
        }
        nav a:hover {
            text-decoration: underline;
        }
        main {
            padding: 20px;
        }
        section {
            margin-bottom: 20px;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
<header>
    <h1>Welcome to Our Informative Webpage</h1>
    <p>Your one-stop destination for knowledge and insights.</p>
</header>
<nav>
    <a href="#about">About Us</a>
    <a href="#services">Services</a>
    <a href="#blog">Blog</a>
    <a href="#contact">Contact Us</a>
</nav>
<main>
    <section id="about">
        <h2>About Us</h2>
        <p>We are a dedicated team of professionals committed to delivering the best information and services to our audience. Our mission is to inform, educate, and inspire.</p>
    </section>
    <section id="services">
        <h2>Our Services</h2>
        <ul>
            <li>Comprehensive tutorials and guides</li>
            <li>Consultation and expert advice</li>
            <li>Customizable solutions for your needs</li>
            <li>Access to exclusive resources</li>
        </ul>
    </section>
    <section id="blog">
        <h2>Latest Blog Posts</h2>
        <article>
            <h3>How to Maximize Productivity</h3>
            <p>Discover effective tips and strategies to boost your daily productivity. <a href="#">Read more...</a></p>
        </article>
        <article>
            <h3>The Future of Technology</h3>
            <p>Explore the exciting advancements and trends shaping our technological future. <a href="#">Read more...</a></p>
        </article>
    </section>
    <section id="contact">
        <h2>Contact Us</h2>
        <form action="#" method="post">
            <label for="name">Name:</label><br>
            <input type="text" id="name" name="name" required><br><br>
            <label for="email">Email:</label><br>
            <input type="email" id="email" name="email" required><br><br>
            <label for="message">Message:</label><br>
            <textarea id="message" name="message" rows="5" required></textarea><br><br>
            <button type="submit">Submit</button>
        </form>
    </section>
</main>
<footer>
    <p>&copy; 2024 Informative Webpage. All rights reserved.</p>
</footer>
</body>
</html>
