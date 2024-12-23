<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Book Haven - Free Books for Everyone</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }

        header {
            background-color: #6200ea;
            color: white;
            padding: 20px 10%;
            text-align: center;
        }

        header h1 {
            margin: 0;
        }

        nav {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 10px;
        }

        nav a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }

        .container {
            max-width: 1200px;
            margin: 20px auto;
            padding: 10px;
        }

        .section {
            margin-bottom: 30px;
        }

        .section h2 {
            border-bottom: 2px solid #6200ea;
            padding-bottom: 5px;
        }

        .books {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
        }

        .book {
            background: white;
            border: 1px solid #ddd;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            width: calc(33.333% - 20px);
            padding: 15px;
            text-align: center;
        }

        .book img {
            max-width: 100%;
            height: auto;
            border-radius: 4px;
        }

        .book h3 {
            font-size: 1.2em;
            margin: 10px 0;
        }

        .book a {
            display: inline-block;
            padding: 10px 15px;
            margin-top: 10px;
            background-color: #6200ea;
            color: white;
            text-decoration: none;
            border-radius: 5px;
        }

        .book a:hover {
            background-color: #4500b3;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 15px;
            margin-top: 20px;
        }

        footer a {
            color: #6200ea;
            text-decoration: none;
        }
    </style>
</head>
<body>
    <header>
        <h1>Book Haven</h1>
        <p>Your gateway to free, beloved books</p>
        <nav>
            <a href="#featured">Featured</a>
            <a href="#categories">Categories</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <div class="container">
        <section id="featured" class="section">
            <h2>Featured Books</h2>
            <div class="books">
                <div class="book">
                    <img src="https://via.placeholder.com/150" alt="Book Cover">
                    <h3>Pride and Prejudice</h3>
                    <p>by Jane Austen</p>
                    <a href="#">Download</a>
                </div>
                <div class="book">
                    <img src="https://via.placeholder.com/150" alt="Book Cover">
                    <h3>Moby Dick</h3>
                    <p>by Herman Melville</p>
                    <a href="#">Download</a>
                </div>
                <div class="book">
                    <img src="https://via.placeholder.com/150" alt="Book Cover">
                    <h3>The Adventures of Sherlock Holmes</h3>
                    <p>by Arthur Conan Doyle</p>
                    <a href="#">Download</a>
                </div>
            </div>
        </section>

        <section id="categories" class="section">
            <h2>Categories</h2>
            <p>Explore books by genre: <a href="#">Fiction</a>, <a href="#">Non-Fiction</a>, <a href="#">Sci-Fi</a>, <a href="#">Romance</a>, and more.</p>
        </section>

        <section id="contact" class="section">
            <h2>Contact Us</h2>
            <p>Have questions or suggestions? <a href="mailto:contact@bookhaven.com">Email us</a>.</p>
        </section>
    </div>

    <footer>
        <p>&copy; 2024 Book Haven. All rights reserved. <a href="#">Privacy Policy</a></p>
    </footer>
</body>
</html>
