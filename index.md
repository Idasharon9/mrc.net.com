
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




