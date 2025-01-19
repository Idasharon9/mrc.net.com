
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>MRC Consultancy</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        /* Basic Reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Roboto', sans-serif;
            line-height: 1.6;
            background-color: #f4f4f4;
        }

        header {
            background-color: #2c3e50;
            color: white;
            padding: 20px 0;
            text-align: center;
        }

        header h1 {
            font-size: 2.5em;
            font-weight: 700;
        }

        .main-content {
            text-align: center;
            padding: 50px 20px;
        }

        .main-content h2 {
            font-size: 2em;
            margin-bottom: 20px;
        }

        .main-content p {
            font-size: 1.2em;
            max-width: 800px;
            margin: 0 auto 30px auto;
        }

        .cta-button {
            background-color: #e74c3c;
            color: white;
            padding: 15px 30px;
            font-size: 1.2em;
            text-decoration: none;
            border-radius: 5px;
            transition: background-color 0.3s;
        }

        .cta-button:hover {
            background-color: #c0392b;
        }

        footer {
            background-color: #2c3e50;
            color: white;
            text-align: center;
            padding: 15px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }

        footer a {
            color: white;
            text-decoration: none;
        }

        footer a:hover {
            text-decoration: underline;
        }
    </style>
</head>

<body>
    <header>
        <h1>MRC Consultancy</h1>
    </header>

    <section class="main-content">
        <h2>Unlock Your Company’s Growth Potential</h2>
        <p>With MRCC’s Fractional CXO Services, you can leverage executive expertise to drive strategic success at a fraction of the cost of a full-time hire. Our Fractional CXOs help businesses accelerate growth, optimize operations, and achieve their goals.</p>
        <a href="#contact" class="cta-button">Get Started Today</a>
    </section>

    <footer>
        <p>&copy; 2025 MRC Consultancy | <a href="#contact">Contact Us</a></p>
    </footer>
</body>

</html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Login Page</title>
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #0d0d1d;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }

        .login-container {
            background-color: #1a1a2e;
            padding: 40px;
            border-radius: 10px;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.5);
            width: 300px;
            text-align: center;
        }

        .login-container h1 {
            color: #00bcd4;
            margin-bottom: 20px;
            font-size: 2em;
        }

        .input-field {
            width: 100%;
            padding: 12px;
            margin: 10px 0;
            border: 1px solid #444;
            border-radius: 5px;
            background-color: #2b2b3d;
            color: white;
            font-size: 1.1em;
        }

        .input-field:focus {
            outline: none;
            border-color: #00bcd4;
        }

        .login-btn {
            width: 100%;
            padding: 14px;
            background-color: #00bcd4;
            color: white;
            border: none;
            border-radius: 5px;
            font-size: 1.2em;
            cursor: pointer;
            transition: background-color 0.3s;
        }

        .login-btn:hover {
            background-color: #0097a7;
        }

        .footer {
            margin-top: 20px;
            color: #b0bec5;
            font-size: 0.9em;
        }

        .footer a {
            color: #00bcd4;
            text-decoration: none;
        }

        .footer a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>

    <div class="login-container">
        <h1>Login</h1>
        <form>
            <input type="text" class="input-field" placeholder="Username" required><br>
            <input type="password" class="input-field" placeholder="Password" required><br>
            <button type="submit" class="login-btn">Login</button>
        </form>
        <div class="footer">
            <p>Don't have an account? <a href="#">Sign Up</a></p>
            <p><a href="#">Forgot Password?</a></p>
        </div>
    </div>

</body>
</html>




