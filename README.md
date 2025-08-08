<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>WB Inovações</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background: #f4f4f4;
            margin: 0;
            color: #333;
        }
        header {
            background-color: #006400;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .container {
            max-width: 1100px;
            margin: 30px auto;
            padding: 0 15px;
        }
        .services {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin-top: 30px;
        }
        .service-card {
            background: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgb(0 0 0 / 0.1);
            text-align: center;
        }
        footer {
            background: #222;
            color: white;
            text-align: center;
            padding: 15px 0;
            margin-top: 40px;
        }
    </style>
</head>
<body>
    <header>
        <h1>WB Inovações</h1>
        <p>Engenharia, Sustentabilidade e Soluções Inteligentes</p>
        <nav>
            <a href="#servicos">Serviços</a>
            <a href="#sobre">Sobre</a>
            <a href="#contato">Contato</a>
        </nav>
    </header>
    <div class="container">
        <section id="servicos">
            <h2>Nossos Serviços</h2>
            <div class="services">
                <div class="service-card">
                    <h3>Energia Solar Fotovoltaica</h3>
                    <p>Projetos e instalações para redução de custos e energia limpa.</p>
                </div>
                <div class="service-card">
                    <h3>Irrigação com Pivô Central</h3>
                    <p>Automatização e eficiência no uso da água para o agronegócio.</p>
                </div>
                <div class="service-card">
                    <h3>Barragem Subterrânea</h3>
                    <p>Armazenamento estratégico de água para períodos de seca.</p>
                </div>
                <div class="service-card">
                    <h3>Logística e Endereçamento</h3>
                    <p>Organização e gestão inteligente de materiais e espaços.</p>
                </div>
                <div class="service-card">
                    <h3>Decoração Sustentável</h3>
                    <p>Vasos e plantas para ambientes internos e externos.</p>
                </div>
                <div class="service-card">
                    <h3>Engenharia Civil</h3>
                    <p>Construção, reforma, pintura e projetos residenciais.</p>
                </div>
            </div>
        </section>
        <section id="sobre" style="margin-top:40px;">
            <h2>Sobre Nós</h2>
            <p>A WB Inovações nasceu para trazer soluções sustentáveis e inteligentes, unindo engenharia e tecnologia para melhorar a vida no campo e na cidade.</p>
        </section>
        <section id="contato" style="margin-top:40px;">
            <h2>Contato</h2>
            <p>Email: <a href="mailto:fabianybatista29@ghmail.com">fabianybatista29@ghmail.com</a></p>
            <p>Telefone: <a href="tel:+5567993030907">(67) 99303-0907</a></p>
            <p>Cidade: Campo Grande / MS</p>
        </section>
    </div>
    <footer>
        <p>© 2025 WB Inovações - Todos os direitos reservados</p>
    </footer>
</body>
</html>
