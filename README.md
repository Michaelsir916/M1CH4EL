<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Me - Michael</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: 'Arial', sans-serif;
            background: linear-gradient(135deg, #1e1e2f, #2a2a40);
            color: #fff;
            overflow: hidden; /* Remove scrolling */
            height: 100vh; /* Fixed height to prevent scrolling */
            display: flex;
            justify-content: center;
            align-items: center;
        }
        .video-bg {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            object-fit: cover;
            z-index: -1;
        }
        .container {
            position: relative;
            z-index: 1;
            text-align: center;
            padding: 20px;
            max-width: 90%; /* Ensure content fits within the viewport */
        }
        .title {
            font-size: 2.5em;
            font-weight: bold;
            color: #fff;
            text-shadow: 0 0 15px rgba(255, 255, 255, 0.8);
            animation: textGlow 1.5s ease-in-out infinite;
            border: 3px solid rgb(0, 255, 204); /* RGB border */
            padding: 10px;
            border-radius: 10px;
            display: inline-block;
        }
        img {
            border-radius: 50%;
            width: 120px;
            height: 120px;
            margin: 20px 0;
            border: 3px solid #00ffcc;
            animation: fadeIn 1.5s ease-in-out;
        }
        h1 a {
            color: #fff;
            text-decoration: none;
            text-shadow: 0 0 10px rgba(255, 255, 255, 0.8);
            animation: textGlow 1.5s ease-in-out infinite;
        }
        h1 a:hover {
            color: #00ffcc;
        }
        .inline-details {
            margin: 20px 0;
            font-size: 1.2em;
            color: #ccc;
        }
        .inline-details div {
            margin: 10px 0;
        }
        .section {
            margin: 30px 0;
            padding: 20px;
            background: rgba(0, 0, 0, 0.5);
            border-radius: 10px;
            border: 2px solid #00ffcc;
        }
        .section h2 {
            font-size: 1.8em;
            margin-bottom: 15px;
            color: #00ffcc;
        }
        .section ul {
            list-style: none;
            padding: 0;
        }
        .section ul li {
            margin: 10px 0;
            font-size: 1.1em;
            color: #fff;
        }
        .section ul li a {
            color: #00ffcc;
            text-decoration: none;
        }
        .section ul li a:hover {
            text-decoration: underline;
        }
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        @keyframes textGlow {
            0% { text-shadow: 0 0 10px rgba(255, 255, 255, 0.8); }
            50% { text-shadow: 0 0 20px rgba(255, 255, 255, 0.8); }
            100% { text-shadow: 0 0 10px rgba(255, 255, 255, 0.8); }
        }
    </style>
</head>
<body>

    <video class="video-bg" autoplay muted loop>
        <source src="https://cdn.glitch.me/2e76ebda-7a6e-4069-9a9e-4e3a8467e019/videoplayback.mp4?v=1736634162833" type="video/mp4">
        Your browser does not support the video tag.
    </video>

    <div class="container">
        <div class="title">ABOUT ME 😌</div>

        <img src="https://cdn.glitch.global/2e76ebda-7a6e-4069-9a9e-4e3a8467e019/2aa824098c2011de7a06ef91de3d6638.jpg?v=1736634504174" alt="Profile Picture">
        
        <h1><a href="https://telegram.me/M1CH3LS1R">People Call Me Michael</a></h1>

        <div class="inline-details">
            <div>📍 Place: Kerala, India 🇮🇳</div>
            <div>🎂 Age: 2*</div>
            <div><a href="http://Wa.me/+916282617118">📱 WhatsApp</a></div>
        </div>

        <div class="section">
            <h2>My Noob Skills</h2>
            <ul>
                <li>💻 Paid Course Leaking</li>
                <li>🔒 RAT Encrypter</li>
                <li>📱 Termux Noob 🤒</li>
                <li>🤖 Telegram Bot Maker (Ultra Noob)</li>
                <li>🎣 Phishing Web Maker</li>
                <li>🎮 PUBG & BGMI Mod Maker</li>
                <li>🛠️ Game Bypass Maker</li>
            </ul>
        </div>

        <div class="section admins">
            <h2>Admin On Channel</h2>
            <ul>
                <li><a href="https://t.me/anonymousfils">Anonymous Files</a></li>
            </ul>
        </div>
    </div>

</body>
</html>
