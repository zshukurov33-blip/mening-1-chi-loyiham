<!DOCTYPE html>
<html lang="uz">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Siz uchun maxsus ✨</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            background: radial-gradient(circle at top left, #ff758c, #ff7eb3, #8e44ad);
            background-size: 200% 200%;
            animation: gradientBG 8s ease infinite;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            overflow: hidden;
            perspective: 1000px;
            user-select: none;
        }
        @keyframes gradientBG {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }
        .card {
            background: rgba(255, 255, 255, 0.2);
            backdrop-filter: blur(15px);
            -webkit-backdrop-filter: blur(15px);
            border: 1px solid rgba(255, 255, 255, 0.4);
            padding: 40px 25px;
            border-radius: 30px;
            box-shadow: 0 25px 45px rgba(0, 0, 0, 0.2);
            width: 90%;
            max-width: 360px;
            text-align: center;
            color: white;
            z-index: 10;
            transition: transform 0.2s ease-out;
            animation: floatCard 4s ease-in-out infinite;
        }
        @keyframes floatCard {
            0%, 100% { transform: translateY(0px); }
            50% { transform: translateY(-10px); }
        }
        .icon {
            font-size: 50px;
            margin-bottom: 10px;
            display: inline-block;
            animation: pulse 1.5s infinite;
        }
        @keyframes pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.2); }
            100% { transform: scale(1); }
        }
        h1 {
            font-size: 26px;
            margin-bottom: 15px;
            text-shadow: 0 2px 10px rgba(0,0,0,0.2);
        }
        #typing-text {
            font-size: 17px;
            line-height: 1.6;
            min-height: 85px;
            margin-bottom: 25px;
            font-weight: 500;
        }
        button {
            background: linear-gradient(45deg, #ff416c, #ff4b2b);
            color: white;
            border: none;
            padding: 14px 32px;
            font-size: 16px;
            font-weight: bold;
            border-radius: 50px;
            cursor: pointer;
            box-shadow: 0 10px 20px rgba(255, 65, 108, 0.4);
            transition: all 0.3s ease;
        }
        button:active {
            transform: scale(0.92);
        }
        .petal {
            position: absolute;
            top: -50px;
            font-size: 22px;
            pointer-events: none;
            animation: fall linear forwards;
        }
        @keyframes fall {
            to {
                transform: translateY(110vh) rotate(360deg);
            }
        }
        .spark {
            position: absolute;
            pointer-events: none;
            font-size: 20px;
            animation: explode 0.8s ease-out forwards;
        }
        @keyframes explode {
            0% { transform: translate(0, 0) scale(1); opacity: 1; }
            100% { transform: translate(var(--tx), var(--ty)) scale(0); opacity: 0; }
        }
    </style>
</head>
<body>

<div class="card" id="card">
    <div class="icon">👑</div>
    <h1>Salom, Malika!</h1>
    <div id="typing-text"></div>
    <button onclick="nextMessage(event)">Sovg‘ani ochish ✨</button>
</div>

<script>
    const messages = [
        "Bugun dunyodagi eng go‘zal tabassum egasiga ajoyib kayfiyat tilayman! 🌸",
        "Sizning har bir kuningiz xuddi ertaklardagidek sehrli va quvonchli o‘tsin! 🦋",
        "Qalbingiz hamisha bahor gullaridek ochilib yursin, baxt sizni hech qachon tark etmasin! 💖",
        "Siz juda ham betakror va ajoyib insonsiz. Tabassum qilishdan to‘xtamang! ✨"
    ];

    let msgIndex = 0;
    let charIndex = 0;
    let typingTimer;

    function typeWriter(text) {
        clearTimeout(typingTimer);
        const el = document.getElementById("typing-text");
        el.innerHTML = "";
        charIndex = 0;

        function type() {
            if (charIndex < text.length) {
                el.innerHTML += text.charAt(charIndex);
                charIndex++;
                typingTimer = setTimeout(type, 40);
            }
        }
        type();
    }

    function nextMessage(e) {
        createExplosion(e.clientX, e.clientY);
        typeWriter(messages[msgIndex]);
        msgIndex = (msgIndex + 1) % messages.length;
    }

    // Ekranga barmoq tekkanda salyut (uchqun) effekti
    document.addEventListener('click', (e) => {
        createExplosion(e.clientX, e.clientY);
    });

    function createExplosion(x, y) {
        const items = ['💖', '✨', '🌸', '💫', '🦋'];
        for (let i = 0; i < 12; i++) {
            const spark = document.createElement('div');
            spark.className = 'spark';
            spark.innerText = items[Math.floor(Math.random() * items.length)];
            spark.style.left = x + 'px';
            spark.style.top = y + 'px';
            
            const angle = Math.random() * Math.PI * 2;
            const distance = Math.random() * 100 + 40;
            spark.style.setProperty('--tx', Math.cos(angle) * distance + 'px');
            spark.style.setProperty('--ty', Math.sin(angle) * distance + 'px');
            
            document.body.appendChild(spark);
            setTimeout(() => spark.remove(), 800);
        }
    }

    // Yuqoridan gul barglari yog‘ilishi
    function createPetal() {
        const petals = ['🌸', '🌷', '✨', '💮', '💖'];
        const petal = document.createElement('div');
        petal.className = 'petal';
        petal.innerText = petals[Math.floor(Math.random() * petals.length)];
        petal.style.left = Math.random() * 100 + 'vw';
        petal.style.animationDuration = (Math.random() * 3 + 3) + 's';
        petal.style.opacity = Math.random() * 0.5 + 0.5;
        document.body.appendChild(petal);
        setTimeout(() => petal.remove(), 6000);
    }

    setInterval(createPetal, 400);
    window.onload = () => typeWriter(messages[0]);
</script>

</body>
</html>
