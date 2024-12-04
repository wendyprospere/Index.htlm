<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Purchase high-quality beats and instrumentals.">
    <title>Music is My Life</title>
    <style>
        body {
            margin: 0;
            font-family: 'Arial', sans-serif;
            color: #ffffff;
            background: linear-gradient(135deg, #1a1a2e, #16213e, #0f3460);
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            min-height: 100vh;
            padding: 20px;
        }
        header {
            text-align: center;
            margin-bottom: 20px;
        }
        h1 {
            font-size: 3rem;
            margin: 0;
            text-shadow: 2px 2px 8px #00d9ff;
        }
        p {
            font-size: 1.2rem;
            margin: 0;
            text-shadow: 1px 1px 4px #00d9ff;
        }
        .beats {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
            margin-top: 20px;
        }
        .beat {
            background: #0f3460;
            border: 2px solid #00d9ff;
            border-radius: 10px;
            padding: 15px;
            width: 250px;
            text-align: center;
            box-shadow: 0 0 10px #00d9ff;
        }
        .beat h2 {
            font-size: 1.5rem;
            margin: 0 0 10px;
        }
        .beat audio {
            width: 100%;
            margin: 10px 0;
        }
        .paypal-button {
            display: inline-block;
            margin-top: 10px;
            padding: 10px 15px;
            background: #00d9ff;
            color: #0f3460;
            text-decoration: none;
            font-weight: bold;
            border-radius: 5px;
            box-shadow: 0 0 5px #00d9ff;
            transition: background 0.3s;
        }
        .paypal-button:hover {
            background: #00bfff;
        }
        .contact {
            margin-top: 30px;
            text-align: center;
        }
        .contact a {
            color: #00d9ff;
            text-decoration: none;
            font-size: 1.2rem;
        }
        .contact a:hover {
            text-decoration: underline;
        }
        footer {
            margin-top: 20px;
            text-align: center;
            font-size: 0.9rem;
            color: #aaaaaa;
        }
    </style>
</head>
<body>
    <header>
        <h1>Music is My Life</h1>
        <p>High-quality beats and instrumentals for your next project.</p>
    </header>

    <div class="beats">
        <div class="beat">
            <h2>Beat Name 1</h2>
            <audio controls>
                <source src="beat1.mp3" type="audio/mpeg">
                Your browser does not support the audio element.
            </audio>
            <p>$29.99</p>
            <a class="paypal-button" href="https://www.paypal.me/wendyprospere1/29.99" target="_blank">Buy with PayPal</a>
        </div>
        <div class="beat">
            <h2>Beat Name 2</h2>
            <audio controls>
                <source src="beat2.mp3" type="audio/mpeg">
                Your browser does not support the audio element.
            </audio>
            <p>$49.99</p>
            <a class="paypal-button" href="https://www.paypal.me/wendyprospere1/49.99" target="_blank">Buy with PayPal</a>
        </div>
        <!-- Add more beats here -->
    </div>

    <div class="contact">
        <p>Have questions or want to purchase? Contact me at:</p>
        <a href="mailto:wendyprospere1@gmail.com">wendyprospere1@gmail.com</a>
    </div>

    <footer>
        <p>© 2024 Music is My Life. All rights reserved.</p>
    </footer>
</body>
</html>
