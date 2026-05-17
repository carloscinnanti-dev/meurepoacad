<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Carlos Cinnanti | Portfólio Profissional</title>
    <style>
        /* Estilos Globais e Reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: #f4f7f6;
            color: #333;
            line-height: 1.6;
        }

        /* Cabeçalho / Menu */
        header {
            background-color: #1a1a2e;
            color: #fff;
            padding: 20px;
            text-align: center;
            position: sticky;
            top: 0;
            z-index: 1000;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
        }

        header h1 {
            font-size: 1.8rem;
            letter-spacing: 1px;
        }

        /* Seção Principal (Hero) */
        .hero {
            background: linear-gradient(135deg, #1f4068, #162447);
            color: white;
            text-align: center;
            padding: 100px 20px;
        }

        .hero h2 {
            font-size: 2.8rem;
            margin-bottom: 15px;
        }

        .hero p {
            font-size: 1.2rem;
            margin-bottom: 30px;
            max-width: 600px;
            margin-left: auto;
            margin-right: auto;
            opacity: 0.9;
        }

        .btn {
            display: inline-block;
            background-color: #e94560;
            color: white;
            padding: 12px 30px;
            text-decoration: none;
            border-radius: 25px;
            font-weight: bold;
            transition: background 0.3s, transform 0.2s;
        }

        .btn:hover {
            background-color: #ff6b81;
            transform: translateY(-2px);
        }

        /* Conteúdo Principal / Sobre */
        .container {
            max-width: 1000px;
            margin: 60px auto;
            padding: 0 20px;
        }

        .section-title {
            text-align: center;
            font-size: 2rem;
            margin-bottom: 40px;
            color: #162447;
            position: relative;
        }

        .section-title::after {
            content: '';
            display: block;
            width: 50px;
            height: 4px;
            background-color: #e94560;
            margin: 10px auto 0;
            border-radius: 2px;
        }

        /* Grid de Projetos / Diferenciais */
        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 30px;
        }

        .card {
            background: white;
            padding: 30px;
            border-radius: 8px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.05);
            text-align: center;
            transition: transform 0.3s;
        }

        .card:hover {
            transform: translateY(-5px);
        }

        .card h3 {
            color: #1f4068;
            margin-bottom: 15px;
        }

        /* Rodapé */
        footer {
            background-color: #1a1a2e;
            color: #a0a0a5;
            text-align: center;
            padding: 30px 20px;
            font-size: 0.9rem;
            margin-top: 60px;
        }

        footer a {
            color: #e94560;
            text-decoration: none;
        }
    </style>
</head>
<body>

    <header>
        <h1>Carlos Cinnanti</h1>
    </header>

    <section class="hero">
        <h2>Desenvolvimento & Tecnologia</h2>
        <p>Estudante de tecnologia focado em criar soluções web modernas, funcionais e totalmente responsivas.</p>
        <a href="#projetos" class="btn">Ver Meus Projetos</a>
    </section>

    <main class="container" id="projetos">
        <h2 class="section-title">Foco de Atuação</h2>
        
        <div class="grid">
            <div class="card">
                <h3> Acadêmico</h3>
                <p>Repositório centralizado de trabalhos, pesquisas científicas e relatórios técnicos desenvolvidos durante a faculdade.</p>
            </div>
            
            <div class="card">
                <h3> Projetos Pessoais</h3>
                <p>Criação de aplicações web independentes, testes de novas ferramentas e evolução contínua em código.</p>
            </div>
            
            <div class="card">
                <h3> Versionamento</h3>
                <p>Uso prático do GitHub para gerenciamento de código fonte, organização de pastas e documentação eficiente.</p>
            </div>
        </div>
    </main>

    <footer>
        <p>&copy; 2026 Carlos Cinnanti. Desenvolvido para o Desafio de Versionamento.</p>
        <p>Acesse meu <a href="https://github.com" target="_blank">Repositório no GitHub</a></p>
    </footer>

</body>
</html>
