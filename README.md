# Auto Vic - Electricidade Automotiva ⚡

Este é o website oficial da **Auto Vic**, uma oficina especializada em soluções elétricas automotivas de alta tecnologia, localizada na Matola, Moçambique.

## 🚀 Tecnologias Utilizadas
- HTML5
- CSS3 (Design Moderno & Responsivo)
- Google Maps API (Integração de Localização)
- GitHub Pages (Hospedagem)

## 📍 Localização
Estamos situados na **Matola - Cinema 700**, prontos para oferecer diagnósticos de precisão para o seu veículo.

## 🛠️ Funcionalidades
- Interface em Dark Mode (Estética Tech).
- Botões de contacto direto (WhatsApp e Chamada).
- Lista detalhada de serviços especializados.
- Design adaptável para Telemóveis e Computadores.

---
*Desenvolvido para proporcionar a melhor experiência digital aos nossos clientes.*        }

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
