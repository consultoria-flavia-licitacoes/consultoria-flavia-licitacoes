<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FBS Escritório | Consultoria e Burocracia</title>
    <style>
        /* Estilos Globais */
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
            scroll-behavior: smooth;
        }

        header {
            background-color: #0a2a66;
            color: white;
            padding: 15px 50px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            position: sticky;
            top: 0;
            z-index: 1000;
        }

        header h1 {
            font-size: 20px;
            margin: 0;
            letter-spacing: 1px;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin-left: 20px;
            font-weight: bold;
            transition: 0.3s;
        }

        nav a:hover {
            color: #25d366;
        }

        /* Seção Hero */
        .hero {
            display: flex;
            align-items: center;
            justify-content: center;
            padding: 80px 50px;
            gap: 40px;
            flex-wrap: wrap;
            background: white;
        }

        .hero img {
            width: 400px;
            max-width: 100%;
            border-radius: 10px;
            box-shadow: 0px 10px 20px rgba(0,0,0,0.1);
        }

        .hero-text {
            max-width: 500px;
        }

        .hero-text h2 {
            font-size: 36px;
            margin-bottom: 20px;
            color: #0a2a66;
            line-height: 1.2;
        }

        .hero-text p {
            font-size: 18px;
            margin-bottom: 30px;
            line-height: 1.6;
            color: #444;
        }

        /* Botão WhatsApp */
        .btn-whatsapp {
            display: inline-block;
            padding: 15px 30px;
            background-color: #25d366;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
            font-size: 18px;
            transition: transform 0.3s, background 0.3s;
            box-shadow: 0px 4px 10px rgba(37, 211, 102, 0.3);
        }

        .btn-whatsapp:hover {
            background-color: #1ebe5a;
            transform: scale(1.05);
        }

        /* Seção de Serviços */
        .services-section {
            padding: 70px 50px;
            text-align: center;
            background-color: #f4f7f9;
        }

        .services-section h2 {
            color: #0a2a66;
            font-size: 30px;
            margin-bottom: 40px;
        }

        .services-container {
            display: flex;
            justify-content: center;
            gap: 25px;
            flex-wrap: wrap;
        }

        .service-card {
            background: white;
            border-top: 6px solid #0a2a66;
            padding: 30px;
            width: 260px;
            border-radius: 10px;
            box-shadow: 0px 6px 15px rgba(0,0,0,0.05);
            text-align: left;
            display: flex;
            flex-direction: column;
            justify-content: space-between;
        }

        .service-card h3 {
            color: #0a2a66;
            font-size: 22px;
            margin-bottom: 15px;
        }

        .service-card p {
            font-size: 15px;
            color: #666;
            line-height: 1.5;
            margin-bottom: 20px;
        }

        .btn-small {
            text-decoration: none;
            color: #0a2a66;
            font-weight: bold;
            font-size: 14px;
            border: 1px solid #0a2a66;
            padding: 8px 12px;
            border-radius: 4px;
            text-align: center;
            transition: 0.3s;
        }

        .btn-small:hover {
            background-color: #0a2a66;
            color: white;
        }

        footer {
            text-align: center;
            padding: 30px;
            background-color: #0a2a66;
            color: white;
        }

        /* Ajustes para Celular */
        @media (max-width: 768px) {
            header { padding: 15px 20px; flex-direction: column; gap: 10px; }
            .hero { padding: 40px 20px; text-align: center; }
            .hero-text h2 { font-size: 28px; }
        }
    </style>
</head>
<body>

    <header>
        <h1>FBS ESCRITÓRIO</h1>
        <nav>
            <a href="#">Início</a>
            <a href="#servicos">Serviços</a>
            <a href="https://wa.me/5500999999999?text=Olá! Gostaria de uma consultoria." target="_blank">Contato</a>
        </nav>
    </header>

    <section class="hero">
        <div class="hero-text">
            <h2>Soluções Burocráticas para sua Empresa.</h2>
            <p>Especialistas em Licitações, Gestão de MEI, Recursos de Multas e Contratos. Segurança jurídica para você focar no que realmente importa.</p>
            <a href="https://wa.me/5500999999999?text=Olá! Vi o site do FBS Escritório e gostaria de mais informações." class="btn-whatsapp" target="_blank">Falar no WhatsApp</a>
        </div>
        <img src="https://images.unsplash.com/photo-1454165833767-027ffea9e7a7?q=80&w=1000" alt="Consultoria FBS">
    </section>

    <section class="services-section" id="servicos">
        <h2>Nossos Especialistas Resolvem:</h2>
        <div class="services-container">
            
            <div class="service-card">
                <div>
                    <h3>⚖️ Recursos de Multas</h3>
                    <p>Defesas administrativas para multas de trânsito ou penalidades contratuais em licitações.</p>
                </div>
                <a href="https://wa.me/5500999999999?text=Olá! Preciso de ajuda com Recurso de Multa." class="btn-small">Saiba Mais</a>
            </div>

            <div class="service-card">
                <div>
                    <h3>🏢 Gestão de MEI</h3>
                    <p>Abertura, Declaração Anual (DASN), parcelamento de débitos e regularização total.</p>
                </div>
                <a href="https://wa.me/5500999999999?text=Olá! Preciso de ajuda com meu MEI." class="btn-small">Saiba Mais</a>
            </div>

            <div class="service-card">
                <div>
                    <h3>🏆 Licitações</h3>
                    <p>Análise de editais, montagem de documentação e acompanhamento em pregões eletrônicos.</p>
                </div>
                <a href="https://wa.me/5500999999999?text=Olá! Quero vender para o governo através de Licitações." class="btn-small">Saiba Mais</a>
            </div>

            <div class="service-card">
                <div>
                    <h3>📜 Certidões e Notas</h3>
                    <p>Emissão de CNDs, Inscrição Municipal e suporte para emissão de Notas Fiscais.</p>
                </div>
                <a href="https://wa.me/5500999999999?text=Olá! Preciso emitir Certidões ou Notas Fiscais." class="btn-small">Saiba Mais</a>
            </div>

        </div>
    </section>

    <footer>
        <p>&copy; 2026 FBS Escritório - Consultoria Especializada</p>
    </footer>

</body>
</html>

