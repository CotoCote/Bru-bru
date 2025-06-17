<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Para Bru❤️</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Georgia', serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            overflow-x: hidden;
            position: relative;
        }

        /* Corações flutuantes */
        .heart {
            position: absolute;
            color: rgba(255, 255, 255, 0.3);
            font-size: 20px;
            animation: float 6s infinite ease-in-out;
            user-select: none;
            pointer-events: none;
        }

        @keyframes float {
            0%, 100% { transform: translateY(0px) rotate(0deg); opacity: 0; }
            10% { opacity: 1; }
            90% { opacity: 1; }
            100% { transform: translateY(-100vh) rotate(360deg); opacity: 0; }
        }

        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            min-height: 100vh;
            position: relative;
            z-index: 10;
        }

        .card {
            background: rgba(255, 255, 255, 0.95);
            backdrop-filter: blur(10px);
            border-radius: 20px;
            padding: 40px;
            box-shadow: 0 20px 40px rgba(0, 0, 0, 0.1);
            text-align: center;
            transform: translateY(20px);
            opacity: 0;
            animation: slideIn 1s ease-out forwards;
            border: 2px solid rgba(255, 255, 255, 0.3);
        }

        @keyframes slideIn {
            to {
                transform: translateY(0);
                opacity: 1;
            }
        }

        .title {
            font-size: 3rem;
            color: #4a5568;
            margin-bottom: 20px;
            text-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            animation: pulse 2s infinite;
        }

        @keyframes pulse {
            0%, 100% { transform: scale(1); }
            50% { transform: scale(1.05); }
        }

        .subtitle {
            font-size: 1.5rem;
            color: #667eea;
            margin-bottom: 30px;
            font-style: italic;
        }

        .message {
            font-size: 1.2rem;
            line-height: 1.8;
            color: #2d3748;
            margin-bottom: 30px;
            text-align: left;
        }

        .highlight {
            color: #e53e3e;
            font-weight: bold;
            font-size: 1.3em;
        }

        .buttons {
            display: flex;
            gap: 20px;
            justify-content: center;
            flex-wrap: wrap;
            margin-top: 30px;
        }

        .btn {
            padding: 15px 30px;
            font-size: 1.1rem;
            border: none;
            border-radius: 50px;
            cursor: pointer;
            transition: all 0.3s ease;
            font-weight: bold;
            text-transform: uppercase;
            letter-spacing: 1px;
            position: relative;
            overflow: hidden;
        }

        .btn-yes {
            background: linear-gradient(45deg, #48bb78, #38a169);
            color: white;
            box-shadow: 0 4px 15px rgba(72, 187, 120, 0.4);
        }

        .btn-yes:hover {
            transform: translateY(-3px);
            box-shadow: 0 8px 25px rgba(72, 187, 120, 0.6);
        }

        .btn-no {
            background: linear-gradient(45deg, #f56565, #e53e3e);
            color: white;
            box-shadow: 0 4px 15px rgba(245, 101, 101, 0.4);
            position: relative;
        }

        .btn-no:hover {
            animation: shake 0.5s;
            transform: scale(0.9);
        }

        @keyframes shake {
            0%, 100% { transform: translateX(0); }
            25% { transform: translateX(-5px); }
            75% { transform: translateX(5px); }
        }

        .response {
            margin-top: 30px;
            font-size: 1.3rem;
            font-weight: bold;
            opacity: 0;
            transform: translateY(20px);
            transition: all 0.5s ease;
        }

        .response.show {
            opacity: 1;
            transform: translateY(0);
        }

        .success {
            color: #38a169;
            animation: bounce 1s infinite;
        }

        .try-again {
            color: #e53e3e;
        }

        @keyframes bounce {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-10px); }
        }

        .heart-big {
            font-size: 4rem;
            color: #e53e3e;
            margin: 20px 0;
            animation: heartbeat 1.5s infinite;
        }

        @keyframes heartbeat {
            0%, 100% { transform: scale(1); }
            50% { transform: scale(1.1); }
        }

        .sparkle {
            position: absolute;
            color: #ffd700;
            font-size: 16px;
            animation: sparkle 2s infinite;
            pointer-events: none;
        }

        @keyframes sparkle {
            0%, 100% { opacity: 0; transform: scale(0); }
            50% { opacity: 1; transform: scale(1); }
        }

        @media (max-width: 600px) {
            .card {
                padding: 20px;
                margin: 10px;
            }
            
            .title {
                font-size: 2rem;
            }
            
            .subtitle {
                font-size: 1.2rem;
            }
            
            .message {
                font-size: 1rem;
            }
            
            .buttons {
                flex-direction: column;
                align-items: center;
            }
            
            .btn {
                width: 200px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="card">
            <h1 class="title">Para Bru💕</h1>
            <h2 class="subtitle">Uma pergunta especial...</h2>
            
            <div class="message">
                <p>Oi Bru!🌹 ✨</p>
                <br>
                <p>Isto é uma carta de Amor para você 🍊. Te amo meu amor e espero que possamos estar sempre amando um ao outro, espero que este presente seja agradável a você ❤️.</p>
                <br>
                <p>Seu sorriso ilumina meus dias, suas palavras fazem meu coração acelerar, e sua presença torna tudo mais lindo de se viver, talvez a minha definição de amar seja por ti!.</p>
                <br>
                <p>Por isso, eu gostaria muito de saber se você <span class="highlight">aceita namorar comigo?</span></p>
                <br>
                <p>Prometo cuidar do Meu amor todos os dias com carinho e respeito que você merece! 💖. Só Deus sabe o amor que tenho por você!.</p>
            </div>

            <div class="heart-big">❤️</div>

            <div class="buttons">
                <button class="btn btn-yes" onclick="responderSim()">
                    SIM! 💕
                </button>
                <button class="btn btn-no" onclick="responderNao()">
                    Não 💔
                </button>
            </div>

            <div id="resposta" class="response"></div>
        </div>
    </div>

    <script>
        // Criar corações flutuantes
        function criarCoracao() {
            const coracao = document.createElement('div');
            coracao.className = 'heart';
            coracao.innerHTML = '❤️';
            coracao.style.left = Math.random() * 100 + 'vw';
            coracao.style.animationDelay = Math.random() * 3 + 's';
            coracao.style.animationDuration = (Math.random() * 3 + 4) + 's';
            document.body.appendChild(coracao);

            setTimeout(() => {
                coracao.remove();
            }, 7000);
        }

        // Criar corações a cada 2 segundos
        setInterval(criarCoracao, 2000);

        // Criar alguns corações iniciais
        for(let i = 0; i < 5; i++) {
            setTimeout(criarCoracao, i * 1000);
        }

        function responderSim() {
            const resposta = document.getElementById('resposta');
            resposta.innerHTML = `
                <div class="success">
                   TE AMO❤️❤️❤️ <br>
                    Você acabou de me fazer a pessoa mais feliz do mundo! ❤️( Coisa que somente sua presença me faz!). <br>
                    Mal posso esperar para te ver, anseio em vê-la.
                    <div class="heart-big">💖</div>
                </div>
            `;
            resposta.classList.add('show');
            
            // Criar fogos de artifício de corações
            for(let i = 0; i < 20; i++) {
                setTimeout(() => {
                    criarFogoCoracao();
                }, i * 200);
            }
            
            // Mudar cor de fundo para algo mais festivo
            document.body.style.background = 'linear-gradient(135deg, #ff9a9e 0%, #fecfef 50%, #fecfef 100%)';
        }

        function responderNao() {
            const resposta = document.getElementById('resposta');
            resposta.innerHTML = `
                <div class="try-again">
                    Ops! Acho que você clicou no botão errado... 😅<br>
                    Que tal tentar de novo? O botão verde está te esperando! 💚
                </div>
            `;
            resposta.classList.add('show');
            
            // Fazer o botão "não" fugir um pouco
            const btnNao = document.querySelector('.btn-no');
            btnNao.style.transform = 'translateX(' + (Math.random() * 40 - 20) + 'px)';
            
            setTimeout(() => {
                resposta.classList.remove('show');
                setTimeout(() => {
                    resposta.innerHTML = '';
                }, 500);
            }, 3000);
        }

        function criarFogoCoracao() {
            const coracao = document.createElement('div');
            coracao.innerHTML = '❤️';
            coracao.style.position = 'fixed';
            coracao.style.left = Math.random() * 100 + 'vw';
            coracao.style.top = '100vh';
            coracao.style.fontSize = '20px';
            coracao.style.zIndex = '1000';
            coracao.style.pointerEvents = 'none';
            coracao.style.animation = 'float 3s ease-out forwards';
            document.body.appendChild(coracao);

            setTimeout(() => {
                coracao.remove();
            }, 3000);
        }

        // Criar efeito de brilho no título
        setInterval(() => {
            const sparkle = document.createElement('div');
            sparkle.className = 'sparkle';
            sparkle.innerHTML = '✨';
            sparkle.style.left = Math.random() * 100 + '%';
            sparkle.style.top = Math.random() * 100 + '%';
            document.querySelector('.card').appendChild(sparkle);

            setTimeout(() => {
                sparkle.remove();
            }, 2000);
        }, 1000);
    </script>
</body>
</html>
