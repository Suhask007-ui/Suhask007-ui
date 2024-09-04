<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Investment Platform</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #2c3e50;
            color: #ffffff;
            padding: 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #34495e;
            padding: 10px;
        }
        nav a {
            color: #ffffff;
            padding: 14px 20px;
            text-decoration: none;
            text-transform: uppercase;
            font-size: 14px;
        }
        nav a:hover {
            background-color: #2c3e50;
        }
        .container {
            max-width: 1200px;
            margin: 20px auto;
            padding: 20px;
            background-color: #ffffff;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .container h1 {
            color: #2c3e50;
        }
        .investment-plan {
            margin-bottom: 20px;
        }
        .investment-plan h2 {
            color: #27ae60;
        }
        footer {
            background-color: #34495e;
            color: #ffffff;
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
    <h1>Welcome to Our Investment Platform</h1>
</header>

<nav>
    <a href="#">Home</a>
    <a href="#">About Us</a>
    <a href="#">Investment Plans</a>
    <a href="#">How It Works</a>
    <a href="#">Contact Us</a>
</nav>

<div class="container">
    <h1>Our Investment Plans</h1>
    <div class="investment-plan">
        <h2>Plan A</h2>
        <p>Invest ₹10,000 and earn ₹1,000 weekly for 10 weeks.</p>
    </div>
    <div class="investment-plan">
        <h2>Plan B</h2>
        <p>Invest ₹50,000 and earn ₹5,000 weekly for 10 weeks.</p>
    </div>
</div>

<footer>
    <p>Contact us at: info@investmentplatform.com</p>
</footer>

</body>
</html>
