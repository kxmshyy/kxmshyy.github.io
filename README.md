<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #d7ccc8;
            margin: 0;
            padding: 0;
        }

        .container {
            width: 80%;
            margin: 0 auto;
        }

        header {
            background-color: #a1887f;
            color: #efebe9;
            padding: 20px 0;
        }

        header h1 {
            margin: 0;
            text-align: center;
        }

        #main-content {
            padding: 20px 0;
        }

        footer {
            background-color: #3e2723;
            color: #efebe9;
            text-align: center;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

        .btn {
            display: inline-block;
            padding: 10px 20px;
            background-color: #4e342e;
            color: #efebe9;
            text-decoration: none;
            border-radius: 30px;
            transition: background-color 0.3s ease;
            font-size: 1rem;
            font-family: arial black;
        }

    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>Welcome to Our Website</h1>
        </div>
    </header>

    <div class="container">
        <section id="main-content">
            <h2>About Us</h2>
            <hr color="Black">
            <p>Welcome to our website. In here, you can view the Portfolio of the Group Members.</p>
            <a href="home.html" class="btn">Get Started</a>
        </section>
    </div>

    <footer>
        <div class="container">
            <p>&copy; 2024 Our Website. All rights reserved.</p>
        </div>
    </footer>
</body>
</html>
