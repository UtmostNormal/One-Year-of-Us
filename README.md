<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>One year of us
    </title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            color: #fff;
            text-align: center;
            overflow-x: hidden;
            background: #000; /* Cor de fundo para quando o vídeo não carrega */
        }

        /* Estilo para o vídeo de fundo */
        .video-background {
            position: fixed;
            right: 0;
            bottom: 0;
            min-width: 100%;
            min-height: 100%;
            z-index: -1;
            object-fit: cover;
        }

        header {
            padding: 20px;
            background: rgba(0, 0, 0, 0.6);
            border-bottom: 2px solid #ff69b4;
        }

        h1 {
            font-size: 3rem;
            margin: 0;
            color: #ff69b4;
        }

        p {
            font-size: 1.5rem;
        }

        section {
            padding: 50px 20px;
            margin: 20px 0;
            background: rgba(0, 0, 0, 0.7);
            border-radius: 15px;
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.5);
        }

        h2 {
            font-size: 2.5rem;
            margin-bottom: 20px;
            color: #ff69b4;
        }

        nav {
            background: rgba(255, 105, 180, 0.8);
            padding: 15px;
        }

        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: #fff;
            font-weight: bold;
            font-size: 1.2rem;
        }

        .counter-container {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 30px;
        }

        .counter {
            background: rgba(255, 105, 180, 0.8);
            padding: 20px;
            border-radius: 15px;
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.3);
            transition: transform 0.3s;
        }

        .counter:hover {
            transform: scale(1.1);
        }

        .counter span {
            display: block;
            font-size: 2rem;
            margin-bottom: 5px;
        }

        .gallery {
            margin: 30px 0;
        }

        .gallery img {
            max-width: 100%;
            height: auto;
            border-radius: 10px;
            margin: 10px;
            transition: transform 0.3s;
        }

        .gallery img:hover {
            transform: scale(1.1);
        }

        footer {
            padding: 20px;
            background: rgba(0, 0, 0, 0.6);
            border-top: 2px solid #ff69b4;
            font-size: 1.2rem;
        }

        .lightbox {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0.8);
            display: none;
            justify-content: center;
            align-items: center;
            z-index: 9999;
        }

        .lightbox img {
            max-width: 90%;
            max-height: 80%;
        }

        .lightbox a.close {
            position: absolute;
            top: 20px;
            right: 20px;
            font-size: 2rem;
            color: #fff;
            text-decoration: none;
            cursor: pointer;
        }

        .surprise-button {
            display: inline-block;
            padding: 15px 30px;
            font-size: 1.5rem;
            color: #fff;
            background: #ff69b4;
            border: none;
            border-radius: 10px;
            cursor: pointer;
            text-decoration: none;
            margin: 20px 0;
            transition: background-color 0.3s, transform 0.3s;
        }

        .surprise-button:hover {
            background-color: #ff1493;
            transform: scale(1.1);
        }

        .music-player {
            display: block; /* Exibe o player de música de forma discreta */
            margin: 20px auto;
            width: 300px;
            background: rgba(0, 0, 0, 0.7);
            border-radius: 10px;
            padding: 10px;
        }

        .feedback-container {
            margin: 30px 0;
            background: rgba(255, 255, 255, 0.9);
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);
        }

        .feedback-container h2 {
            margin-bottom: 20px;
            color: #ff69b4;
        }

        .feedback-container textarea {
            width: 100%;
            height: 100px;
            border-radius: 5px;
            padding: 10px;
            border: 1px solid #ddd;
            font-size: 1rem;
        }

        .feedback-container button {
            display: inline-block;
            margin-top: 10px;
            padding: 10px 20px;
            font-size: 1rem;
            color: #fff;
            background: #ff69b4;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s;
        }

        .feedback-container button:hover {
            background-color: #ff1493;
        }
    </style>
</head>
<body>

    <!-- Vídeo de fundo -->
    <video class="video-background" autoplay muted loop>
        <source src="WhatsApp Video 2024-08-21 at 08.24.50 (2).mp4" type="video/mp4">
        Seu navegador não suporta o vídeo.
    </video>

    <!-- Música de fundo -->
    <audio id="background-music" autoplay loop>
        <source src="Until_I_Found_You_(Em_Beihold_Version).mp4" type="audio/mpeg">
        Seu navegador não suporta a tag de áudio.
    </audio>

    <header>
        <h1>365 Dias de nós meu amor</h1>
        <p>Minha Eternidade dentro dos dias Contados.</p>
    </header>

    <nav>
        <a href="#historia">Nossa História</a>
        <a href="#contador">Contador</a>
        <a href="#galeria">Galeria</a>
    </nav>

    <section id="historia">
        <h2>Me and you</h2>
        <p>Minha mais bela leitora, creio que a epigrafe tão forte o trouxe até estas linhas, não há razão para que elas existam sem você.

21/08/2023 a 21/08/24 tempo esse que foi palco de diversas construções, e decepções. Entre elas a maior…. 

O AMOR

O amor é uma tempestade feita apenas para os mais corajosos, e eu ? 
fui repleto de tempestades, mas ao invés de evitá-las e tentar controlá-las ela entrou no centro dela e pegou a minha mão me fez levantar e dançar no caos pra me mostrar que nada nunca vai te afastar de mim, que iremos rir e nos amar perante qualquer caos e me mostrou do que nossas almas são feitas é que a partir dali a minha seria tua.
Eu só não sabia que perdê-la  custaria muito mais do eu era.
Quando eu entendi o que o “ pra sempre” realmente significa, você entende que não estava falando de tempo.
E mais uma vez eu aqui começando mais uma de minhas dedicatórias a você, numa falha tentativa de se quer descrever a sensação de te amar, já que o amor em si, nem com todas as palavras do universo, eu seria capaz de descrever.
eu queria ser qualquer pessoa perfeita pra você, pq é de se pensar. já que você já é a pessoa perfeita pra qualquer pessoa que eu inventar. Mas não sou…

Naquele dia, eu decidi te deixar ir, minha maior certeza é que você é o amor da minha vida, mas acho que nesta fase a amor deixa dúvidas dolorosas.
Mas como um cara sábio diz “ Mas essa eu fiz pro nosso amor”
Quero que ao ler isso entenda que esse texto não é direcionado a algo falado, é sentido, é como dizem qualquer pessoa pode ter olhos bonitos, 
mas apenas a pessoa certa pode murmurar o alfabeto e transformar isso na sua nova música preferida".
Querer o para sempre é muito mais que tempo, muito menos do que o suficiente para tamanho sentimento, reescrevendo o próprio conceito de amor, porque não verdadeira concepção do meu coração, ele é inexistente sem você.
Quero que ao ler isso entenda que esse texto não é direcionado a algo falado, é sentido, é como dizem qualquer pessoa pode ter olhos bonitos, 
mas apenas a pessoa certa pode murmurar o alfabeto e transformar isso na sua nova música preferida".
Eu não sei ama-la de forma quieta, e repetirei isso a cada estrofe se necessário. 
Escreverei cartas de amor até meu último suspiro, serei capaz de levar esse amor para sempre. Meu amor por você é como uma melodia suave, flutuando no ar, aguardando o momento certo para se manifestar. Cada gesto, cada olhar, é uma expressão tímida desse sentimento que floresce em meu peito. Às vezes, as palavras parecem pequenas demais para conter a grandeza do que sinto, mas saiba que, mesmo não pronunciadas, essas três palavras pairam como promessas no vento, aguardando pacientemente o instante em que poderei, finalmente, dizer "eu te amo". E como amo, amo a cada mês, cada dificuldade , aprendizado,cada beijo como uma jornada intergaláctica, essa loucura nossa explorando o desconhecido em um cosmos compartilhado. Somos o universo em harmonia, dançando na cadência eterna do amor, entrelaçados como fios de constelações que nunca deixam de brilhar.
Se me falassem que algo assim, um sentimento tão grande me tomaria a um ano atrás, eu jamais acreditaria kk e por isso nos meus maiores sonhos você continua um vislumbre sonho. Você tornou até o pior de mim algo melhor. Somos péssimas com despedidas e finais não é ? Kk de toda forma isso nunca será um a deus. Então aqui teremos eternamente o nosso contador de tempo, o tempo do nosso amor.</p>
    </section>

    <section id="contador">
        <h2>Nós</h2>
        <div class="counter-container">
            <div class="counter">
                <span id="days">0</span>
                Dias
            </div>
            <div class="counter">
                <span id="minutes">0</span>
                Minutos
            </div>
            <div class="counter">
                <span id="seconds">0</span>
                Segundos
            </div>
        </div>
    </section>

    <section id="galeria" class="gallery">
        <h2>Galeria de Fotos</h2>
        <a href="#lightbox1"><img src="WhatsApp Image 2024-08-20 at 19.20.36 (1).jpeg" alt="Foto 1"></a>
        <a href="#lightbox2"><img src="WhatsApp Image 2024-08-20 at 19.20.36 (2).jpeg" alt="Foto 2"></a>
        <a href="#lightbox3"><img src="WhatsApp Image 2024-08-20 at 19.20.36 (3).jpeg" alt="Foto 3"></a>
        <a href="#lightbox4"><img src="WhatsApp Image 2024-08-20 at 19.20.36 (4).jpeg" alt="Foto 4"></a>

        <!-- Lightboxes -->
        <div id="lightbox1" class="lightbox">
            <a href="#" class="close">&times;</a>
            <img src="WhatsApp Image 2024-08-20 at 19.20.36 (1).jpeg" alt="Foto 1">
        </div>
        <div id="lightbox2" class="lightbox">
            <a href="#" class="close">&times;</a>
            <img src="WhatsApp Image 2024-08-20 at 19.20.36 (2).jpeg" alt="Foto 2">
        </div>
        <div id="lightbox3" class="lightbox">
            <a href="#" class="close">&times;</a>
            <img src="WhatsApp Image 2024-08-20 at 19.20.36 (3).jpeg" alt="Foto 3">
        </div>
        <div id="lightbox4" class="lightbox">
            <a href="#" class="close">&times;</a>
            <img src="WhatsApp Image 2024-08-20 at 19.20.36 (4).jpeg" alt="Foto 4">
        </div>
    </section>

    <section class="feedback-container">
        <h2>Deixe um Elogio</h2>
        <form id="feedback-form">
            <textarea placeholder="Seu elogio aqui..." required></textarea>
            <button type="submit">Enviar</button>
        </form>
    </section>

    <footer>
        <p>Com amor, Seu Branquelo ❤️</p>
    </footer>

    <!-- Botão de surpresa -->
    <a href="surpresa.html" class="surprise-button">Clique Aqui para uma Surpresa!</a>

    <script>
        // Data do início do relacionamento
        const startDate = new Date('2023-08-20T00:00:00');
        
        function updateCounter() {
            const now = new Date();
            const diff = now - startDate;

            const days = Math.floor(diff / (1000 * 60 * 60 * 24));
            const minutes = Math.floor((diff / 1000 / 60) % 60);
            const seconds = Math.floor((diff / 1000) % 60);

            document.getElementById('days').textContent = days;
            document.getElementById('minutes').textContent = minutes;
            document.getElementById('seconds').textContent = seconds;
        }

        // Atualiza o contador a cada segundo
        setInterval(updateCounter, 1000);

        // Lightbox functionality
        document.querySelectorAll('.lightbox').forEach(lightbox => {
            lightbox.addEventListener('click', (e) => {
                if (e.target === lightbox || e.target.classList.contains('close')) {
                    lightbox.style.display = 'none';
                }
            });
        });

        // Feedback form submit event
        document.getElementById('feedback-form').addEventListener('submit', (e) => {
            e.preventDefault();
            alert('Obrigado pelo elogio!');
            e.target.reset();
        });
    </script>
</body>
</html>
