# AUTO-VIC
<!DOCTYPE html>
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Auto Vic | Especialistas em Eletricidade Automotiva</title>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;700&family=Oswald:wght@500;700&display=swap" rel="stylesheet">
    
    <style>
        :root {
            --primary: #FF4D00; /* Laranja do Logo */
            --secondary: #FFCC00; /* Amarelo Elétrico */
            --dark: #0a0a0a;
            --dark-card: #161616;
            --gray-text: #b3b3b3;
            --white: #ffffff;
            --gradient: linear-gradient(90deg, #FF4D00, #FFCC00);
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            scroll-behavior: smooth;
        }

        body {
            font-family: 'Inter', sans-serif;
            background-color: var(--dark);
            color: var(--white);
            line-height: 1.6;
        }

        /* Header & Nav */
        header {
            background: rgba(0, 0, 0, 0.9);
            padding: 20px;
            text-align: center;
            border-bottom: 2px solid var(--primary);
            position: sticky;
            top: 0;
            z-index: 1000;
        }

        header img {
            max-width: 250px;
            filter: drop-shadow(0 0 10px rgba(255, 77, 0, 0.3));
        }

        nav {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 20px;
            margin-top: 15px;
        }

        nav a {
            color: var(--white);
            text-decoration: none;
            font-size: 14px;
            font-weight: 600;
            text-transform: uppercase;
            transition: 0.3s;
            letter-spacing: 1px;
        }

        nav a:hover {
            color: var(--secondary);
        }

        /* Seção Hero */
        .hero {
            padding: 80px 20px;
            text-align: center;
            background: radial-gradient(circle at center, #1a1a1a 0%, #000 100%);
        }

        .hero h1 {
            font-family: 'Oswald', sans-serif;
            font-size: 3rem;
            text-transform: uppercase;
            background: var(--gradient);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            margin-bottom: 10px;
        }

        /* Containers e Cards */
        section {
            padding: 60px 20px;
            max-width: 1200px;
            margin: auto;
        }

        .section-title {
            font-family: 'Oswald', sans-serif;
            font-size: 2rem;
            margin-bottom: 30px;
            border-left: 5px solid var(--primary);
            padding-left: 15px;
            text-transform: uppercase;
        }

        .card {
            background: var(--dark-card);
            border: 1px solid #333;
            padding: 30px;
            border-radius: 15px;
            transition: 0.3s;
            height: 100%;
        }

        .card:hover {
            border-color: var(--primary);
            transform: translateY(-5px);
            box-shadow: 0 10px 30px rgba(255, 77, 0, 0.1);
        }

        /* Grid de Serviços */
        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }

        .service-item {
            background: #1a1a1a;
            padding: 20px;
            border-radius: 10px;
            display: flex;
            align-items: center;
            gap: 15px;
            border-left: 3px solid var(--secondary);
        }

        /* Footer Profissional */
        footer {
            background: #050505;
            padding: 50px 20px;
            text-align: center;
            border-top: 1px solid #222;
        }

        .cta-button {
            display: inline-block;
            background: var(--gradient);
            color: black;
            padding: 15px 40px;
            border-radius: 50px;
            text-decoration: none;
            font-weight: bold;
            text-transform: uppercase;
            margin-top: 20px;
            transition: 0.3s;
        }

        .cta-button:hover {
            transform: scale(1.05);
            box-shadow: 0 0 20px rgba(255, 77, 0, 0.5);
        }

        /* Floating Buttons */
        .float-btns {
            position: fixed;
            bottom: 30px;
            right: 30px;
            display: flex;
            flex-direction: column;
            gap: 15px;
            z-index: 9999;
        }

        .btn-float {
            width: 60px;
            height: 60px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            text-decoration: none;
            font-size: 24px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.3);
            transition: 0.3s;
        }

        .btn-whatsapp { background: #25D366; }
        .btn-phone { background: var(--primary); }
        .btn-float:hover { transform: scale(1.1); }

        @media (max-width: 768px) {
            .hero h1 { font-size: 2rem; }
            nav { gap: 10px; }
        }
    </style>
</head>
<body>

<header>
    <img src="7a033f62-4296-41be-9a13-5116002af06d.jpg" alt="Auto Vic Logo">
    <nav>
        <a href="#quem">Sobre</a>
        <a href="#servicos">Serviços</a>
        <a href="#onde">Localização</a>
        <a href="#contactos">Contacto</a>
    </nav>
</header>

<div class="hero">
    <h1>Alta Performance Elétrica</h1>
    <p>Tecnologia de ponta para o sistema eletrônico do seu veículo.</p>
    <a href="https://wa.me/258876032193" class="cta-button">Agendar Diagnóstico</a>
</div>

<section id="quem">
    <div class="card">
        <h2 class="section-title">Quem Somos</h2>
        <p>A <strong>Auto Vic</strong> é referência em eletricidade automotiva multimarca. Nossa missão é unir inovação tecnológica e precisão técnica para garantir que seu veículo nunca pare. Com equipamentos de última geração, diagnosticamos com exatidão o que seu carro precisa.</p>
    </div>
</section>

<section id="servicos">
    <h2 class="section-title">Serviços Especializados</h2>
    <div class="services-grid">
        <div class="service-item">⚡ Ar Condicionado</div>
        <div class="service-item">⚡ Alarmes & Segurança</div>
        <div class="service-item">⚡ Teste de Baterias</div>
        <div class="service-item">⚡ Sistemas de Som Hi-Fi</div>
        <div class="service-item">⚡ Instalação de GPS</div>
        <div class="service-item">⚡ Focagem de Faróis</div>
        <div class="service-item">⚡ Injeção Eletrônica</div>
        <div class="service-item">⚡ ABS / ESP & Sensores</div>
    </div>
</section>

<section id="onde">
    <div class="card" style="text-align: center;">
        <h2 class="section-title" style="border:none; padding:0;">Onde Estamos</h2>
        <p style="font-size: 1.2rem;">📍 Maputo - Matola - Cinema 700</p>
        <p style="color: var(--gray-text);">Atendimento de Segunda a Sábado.</p>
    </div>
</section>

<footer>
    <p>© 2024 Auto Vic Electricidade Automotiva - Todos os direitos reservados.</p>
    <div style="margin-top: 20px; border: 1px dashed #333; padding: 15px; display: inline-block;">
        <p style="font-size:13px; color: var(--gray-text);">
            🚀 Desenvolvido com tecnologia de ponta.<br>
            <strong>Quer um site como este?</strong> <br>
            WhatsApp: <a href="https://wa.me/258860407269" style="color: var(--secondary);">860407269</a>
        </p>
    </div>
</footer>

<div class="float-btns">
    <a href="tel:876032193" class="btn-float btn-phone">📞</a>
    <a href="https://wa.me/258876032193" target="_blank" class="btn-float btn-whatsapp">💬</a>
</div>

</body>
</html>
