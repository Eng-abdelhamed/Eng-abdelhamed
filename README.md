- 👋 Hi, I’m abdelhamed ahmed
- 👀 I’m interested in Embedded systems , IOT applications , Automotive ,  linux
- 🌱 I’m currently learning Machine learning , Database , Ai .
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
<!DOCTYPE html>
<html lang="en">
<!-- 

    Particles thanks to ParticleJS - https://github.com/VincentGarreau/particles.js/
    Typewriter thanks to Typewriter.js - https://github.com/tameemsafi/typewriterjs

 -->

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <script src="https://unpkg.com/typewriter-effect@latest/dist/core.js"></script>
    <style>
        body {
            padding: 0;
            margin: 0;
            background-color: #0d1116;
        }

        #particles-js {
            width: 800px;
            height: 387px;
            background-color: #0d1116;
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            border: 1px solid purple;
            opacity: 0.9;
        }

        #typewriter {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -60px);
            font-size: 3rem;
            line-height: 3rem;
            color: #fff;
            text-align: center;
            font-family: 'Roboto', sans-serif;
            font-weight: 500;
            clip: auto;
            z-index: 1;
            background: -webkit-linear-gradient(#5115b9, #e010e3);
            background-clip: text;
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        #typewriter2 {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, 20px);
            font-size: 2rem;
            line-height: 3rem;
            color: #fff;
            text-align: center;
            font-family: 'Roboto', sans-serif;
            font-weight: 500;
            z-index: 1;
            background: -webkit-linear-gradient(#5115b9, #fa00ff);
            background-clip: text;
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
    </style>
</head>

<body>
    <div id="typewriter"></div>
    <div id="typewriter2"></div>
    <div id="particles-js"></div>
    <script src="particles.js"></script>
    <script>
        particlesJS.load('particles-js', 'assets/particles.json', function () {
            console.log('callback - particles-js config loaded');
        });

        new Typewriter('#typewriter', {
            delay: 20,
        }).typeString('Hey there, I\'m Cyris 👋')
            .pauseFor(3000)
            .deleteAll(10)
            .typeString('I\'m a software developer 👨‍💻')
            .pauseFor(3000)
            .deleteAll(10)
            .typeString('I\'m a maker 🏗')
            .pauseFor(3000)
            .deleteAll(10)
            .typeString('I\'m an infosec enthusiast 🔒')
            .pauseFor(3000)
            .deleteAll(10)
            .typeString('Check out my work 👇')
            .pauseFor(4000)
            .start();

        new Typewriter('#typewriter2', {
            delay: 20,
        }).pauseFor(1000)
            .typeString('Nice to meet you.')
            .pauseFor(2000)
            .deleteAll(10)
            .pauseFor(1000)
            .typeString('Javascript, NodeJS, React, Express.')
            .pauseFor(2000)
            .deleteAll(10)
            .typeString('RaspberryPi, Arduino, ESP8266, ESP32.')
            .pauseFor(2000)
            .deleteAll(10)
            .typeString('Learning to protect myself and others.')
            .pauseFor(3000)
            .deleteAll(10)
            .pauseFor(200)
            .typeString('Follow me on twitter @sudo_overflow.')
            .pauseFor(4000)
            .start();
    </script>
</body>

</html>
<!---
Eng-abdelhamed/Eng-abdelhamed is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
