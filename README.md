<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple UI</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #f8f8f8;
        }
        .container {
            display: flex;
            align-items: center;
            justify-content: space-between;
            max-width: 900px;
            background: white;
            padding: 40px;
            border-radius: 10px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
        }
        .text-section {
            max-width: 50%;
        }
        .text-section h1 {
            font-size: 36px;
        }
        .text-section .name {
            color: #333;
        }
        .text-section p {
            font-size: 16px;
            color: #666;
        }
        .buttons {
            margin-top: 20px;
        }
        .btn {
            padding: 10px 20px;
            border: none;
            cursor: pointer;
            font-size: 16px;
            border-radius: 5px;
        }
        .learn-more {
            background-color: #333;
            color: white;
            margin-right: 10px;
        }
        .contact-me {
            background-color: white;
            border: 2px solid #333;
            color: #333;
        }
        .image-section img {
            max-width: 300px;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="text-section">
            <h1>I'm <span class="name">Ishan.</span></h1>
            <p>I make elegantly professional <strong>web</strong> apps and <strong>flutter</strong> apps for a living and also design <strong>user experiences</strong>. If you want me to do any one of these for you, get in touch with me here.</p>
            <div class="buttons">
                <button class="btn learn-more">Learn More</button>
                <button class="btn contact-me">Contact Me</button>
            </div>
        </div>
        <div class="image-section">
            <img src="picc.png" alt="Developer Illustration">
        </div>
    </div>
</body>
</html>

