<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>OxWANTBEER</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            background-color: #0C1016;
            color: #D9B38E;
            font-family: 'Courier New', monospace;
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            align-items: center;
            padding: 40px 20px;
        }
        
        .container {
            max-width: 800px;
            width: 100%;
        }
        
        .header-gif {
            width: 100%;
            max-width: 600px;
            border-radius: 12px;
            margin: 0 auto 30px;
            display: block;
        }
        
        h1 {
            text-align: center;
            color: #D9B38E;
            font-size: 2.5em;
            margin-bottom: 20px;
        }
        
        h2 {
            text-align: center;
            color: #B38258;
            font-size: 1.5em;
            margin: 40px 0 20px;
            border-bottom: 2px solid #A8454F;
            padding-bottom: 10px;
        }
        
        .intro {
            text-align: center;
            color: #B38258;
            font-size: 1.1em;
            line-height: 1.8;
            margin-bottom: 30px;
        }
        
        .intro .highlight {
            color: #A8454F;
            font-weight: bold;
        }
        
        .badges {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 10px;
            margin-bottom: 20px;
        }
        
        .badges img {
            transition: transform 0.2s;
        }
        
        .badges img:hover {
            transform: scale(1.1);
        }
        
        .contact {
            display: flex;
            justify-content: center;
            gap: 15px;
            flex-wrap: wrap;
        }
        
        .contact a {
            transition: transform 0.2s;
        }
        
        .contact a:hover {
            transform: scale(1.1);
        }
        
        .arch-badge {
            text-align: center;
            color: #A8454F;
            font-size: 1.2em;
            margin: 30px 0;
            padding: 15px;
            border: 2px dashed #A8454F;
            border-radius: 10px;
            background: rgba(168, 69, 79, 0.05);
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- Header GIF -->
        <img src="https://raw.githubusercontent.com/OxWANTBEER/OxWANTBEER/main/assets/img_1.gif" 
             alt="Header" class="header-gif">
        
        <!-- Title -->
        <h1>👋 Hi, I'm WANTBEER!</h1>
        
        <!-- Intro -->
        <p class="intro">
            「 I'm <span class="highlight">passionate</span> about embedded systems and low-level programming 」
            <br>
            「 I <span class="highlight">dive deep</span> into the metal, building firmware that pushes microcontrollers to their limits 」
        </p>
        
        <!-- Arch badge -->
        <p class="arch-badge">💻 I use Arch btw :)</p>
        
        <!-- Tech Stack -->
        <h2>🛠️ Tech Stack</h2>
        
        <div class="badges">
            <img alt="C" src="https://img.shields.io/badge/C-D9B38E?style=for-the-badge&logo=c&logoColor=white">
            <img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-A8454F?style=for-the-badge&logo=c&logoColor=white">
        </div>
        
        <div class="badges">
            <img alt="STM32" src="https://img.shields.io/badge/STM32-D9B38E?style=for-the-badge&logo=stmicroelectronics&logoColor=black">
            <img alt="ESP32" src="https://img.shields.io/badge/ESP32-B38258?style=for-the-badge&logo=espressif&logoColor=black">
            <img alt="ESP8266" src="https://img.shields.io/badge/ESP8266-A8454F?style=for-the-badge&logo=espressif&logoColor=white">
            <img alt="Arduino" src="https://img.shields.io/badge/Arduino-D9B38E?style=for-the-badge&logo=arduino&logoColor=black">
        </div>
        
        <div class="badges">
            <img alt="VS Code" src="https://img.shields.io/badge/VS_Code-B38258?style=for-the-badge&logo=vscode&logoColor=black">
            <img alt="PlatformIO" src="https://img.shields.io/badge/PlatformIO-A8454F?style=for-the-badge&logo=platformio&logoColor=white">
            <img alt="Git" src="https://img.shields.io/badge/Git-D9B38E?style=for-the-badge&logo=git&logoColor=black">
            <img alt="Linux" src="https://img.shields.io/badge/Linux-B38258?style=for-the-badge&logo=linux&logoColor=black">
        </div>
        
        <!-- Contact -->
        <h2>📫 Contact</h2>
        
        <div class="contact">
            <a href="https://github.com/OxWANTBEER" target="_blank">
                <img alt="GitHub" src="https://img.shields.io/badge/OxWANTBEER-A8454F?style=for-the-badge&logo=github&logoColor=white">
            </a>
            <a href="https://t.me/OxWANTBEER" target="_blank">
                <img alt="Telegram" src="https://img.shields.io/badge/@OxWANTBEER-D9B38E?style=for-the-badge&logo=telegram&logoColor=black">
            </a>
            <a href="mailto:reallwantbeer@gmail.com" target="_blank">
                <img alt="Email" src="https://img.shields.io/badge/reallwantbeer@gmail.com-B38258?style=for-the-badge&logo=gmail&logoColor=black">
            </a>
        </div>
    </div>
</body>
</html>