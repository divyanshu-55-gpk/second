<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>You Are Important to Me</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #ffebee;
            text-align: center;
            padding: 50px;
            transition: background-color 1s;
        }
        .heart {
            color: red;
            font-size: 50px;
            animation: heartbeat 1s infinite;
        }
        @keyframes heartbeat {
            0% { transform: scale(1); }
            50% { transform: scale(1.3); }
            100% { transform: scale(1); }
        }
        .message {
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0px 0px 10px rgba(0,0,0,0.1);
            display: inline-block;
            margin-top: 20px;
            animation: fadeIn 2s;
            position: relative;
        }
        .sparkle {
            position: absolute;
            top: -10px;
            right: -10px;
            font-size: 24px;
            animation: twinkle 1.5s infinite alternate;
        }
        @keyframes twinkle {
            from { opacity: 0.5; }
            to { opacity: 1; transform: scale(1.2); }
        }
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(-20px); }
            to { opacity: 1; transform: translateY(0); }
        }
        .nav {
            margin: 20px 0;
        }
        .nav a {
            text-decoration: none;
            color: white;
            background: red;
            padding: 10px 20px;
            border-radius: 5px;
            margin: 5px;
            display: inline-block;
            transition: background 0.3s;
        }
        .nav a:hover {
            background: darkred;
        }
        .surprise {
            margin-top: 20px;
            font-size: 24px;
            font-weight: bold;
            color: #d32f2f;
            opacity: 0;
            animation: surpriseFade 3s ease-in-out 5s forwards;
        }
        @keyframes surpriseFade {
            from { opacity: 0; transform: scale(0.8); }
            to { opacity: 1; transform: scale(1); }
        }
        .special {
            font-size: 20px;
            color: #ff4081;
            margin-top: 30px;
            animation: glow 2s infinite alternate;
        }
        @keyframes glow {
            from { text-shadow: 0 0 10px #ff80ab; }
            to { text-shadow: 0 0 20px #ff4081; }
        }
        .missing-you {
            font-size: 18px;
            color: #333;
            margin-top: 20px;
            font-style: italic;
            animation: fadeIn 3s;
        }
    </style>
</head>
<body>
    <h1>My Love, You Are Everything to Me</h1>
    <div class="heart">❤️</div>
    <div class="message">
        <span class="sparkle">✨</span>
        <p>Dear Love,</p>
        <p>You are the light of my life, the one who brings happiness to my heart.</p>
        <p>Every moment with you is precious, and I am grateful for your love and presence.</p>
        <p>Thank you for being my strength, my joy, and my forever.</p>
        <p>I love you endlessly! ❤️</p>
    </div>
    <div class="surprise">You are my greatest blessing! 💖</div>
    <div class="special">Every heartbeat of mine whispers your name! 💓</div>
    <div class="missing-you">When you don't talk to me, my world feels empty. The silence is louder than words, and I long for your voice to fill my heart again. 💔</div>
    <div class="nav">
        <a href="page2.html">Next Page</a>
    </div>
</body>
</html>

