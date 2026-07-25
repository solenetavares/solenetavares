<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Solene Tavares | Full-Stack Software Engineering Student</title>
    <style>
        :root {
            --bg-color: #0d0f12;
            --card-bg: #161b22;
            --text-main: #f0f6fc;
            --accent-pink: #FFB6C1;
            --accent-lavender: #D8BFD8;
            --border-color: #30363d;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
        }

        body {
            background-color: var(--bg-color);
            color: var(--text-main);
            padding: 40px 20px;
            display: flex;
            justify-content: center;
        }

        .container {
            max-width: 850px;
            width: 100%;
            background-color: var(--card-bg);
            border: 1px solid var(--border-color);
            border-radius: 12px;
            padding: 40px;
            box-shadow: 0 8px 24px rgba(0, 0, 0, 0.4);
        }

        h1 {
            font-size: 2rem;
            color: var(--accent-lavender);
            margin-bottom: 15px;
        }

        h1 span.pink {
            color: var(--accent-pink);
        }

        .badges {
            display: flex;
            gap: 10px;
            margin-bottom: 30px;
            flex-wrap: wrap;
        }

        .badge {
            background-color: var(--accent-pink);
            color: #000000;
            padding: 6px 12px;
            border-radius: 20px;
            font-size: 0.85rem;
            font-weight: bold;
            display: inline-flex;
            align-items: center;
            gap: 6px;
        }

        .badge.lavender {
            background-color: var(--accent-lavender);
        }

        h3 {
            color: var(--accent-lavender);
            margin-top: 30px;
            margin-bottom: 15px;
            font-size: 1.25rem;
            border-bottom: 1px solid var(--border-color);
            padding-bottom: 8px;
        }

        p, li {
            line-height: 1.6;
            color: #c9d1d9;
            margin-bottom: 15px;
            font-size: 0.95rem;
        }

        ul {
            padding-left: 20px;
        }

        .stack-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(110px, 1fr));
            gap: 12px;
            margin: 20px 0;
        }

        .stack-card {
            background-color: #21262d;
            border: 1px solid var(--border-color);
            border-radius: 8px;
            padding: 15px 10px;
            text-align: center;
            transition: transform 0.2s;
        }

        .stack-card:hover {
            transform: translateY(-3px);
            border-color: var(--accent-pink);
        }

        .stack-card img {
            width: 35px;
            height: 35px;
            margin-bottom: 8px;
        }

        .stack-card span {
            display: block;
            font-size: 0.75rem;
            font-weight: bold;
            color: var(--text-main);
        }

        .stats {
            display: flex;
            gap: 15px;
            flex-wrap: wrap;
            margin: 20px 0;
            justify-content: flex-start;
        }

        .stats img {
            max-width: 100%;
            height: auto;
            border-radius: 8px;
            border: 1px solid var(--border-color);
        }

        .contact-list {
            list-style: none;
            padding: 0;
        }

        .contact-list li {
            margin-bottom: 8px;
        }

        .contact-list a {
            color: var(--accent-pink);
            text-decoration: none;
        }

        .contact-list a:hover {
            text-decoration: underline;
        }

        .footer {
            text-align: center;
            margin-top: 40px;
            color: var(--accent-pink);
            font-style: italic;
            font-size: 0.9rem;
        }

        hr {
            border: none;
            border-top: 1px solid var(--border-color);
            margin: 30px 0;
        }
    </style>
</head>
<body>

<div class="container">
    
    <h1>🔮 Solene Tavares | <span class="pink">Full-Stack Software Engineering Student</span></h1>

    <div class="badges">
        <span class="badge">Status: Full Stack Mode</span>
        <span class="badge lavender">Focus: Fullstack & Agile</span>
    </div>

    <h3>🎀 Seja bem-vindo(a) ao meu servidor!</h3>
    <p>Sou estudante de <strong>Engenharia de Software</strong> com foco em desenvolvimento <strong>Full-Stack</strong> e ecossistemas de tecnologia modernos. O meu objetivo é construir soluções completas de ponta a ponta, unindo a robustez do back-end com a interatividade e o design do front-end.</p>
    <p>Atualmente, passo os meus dias estruturando códigos limpos, conectando APIs, gerenciando fluxos com metodologias ágeis e acumulando commits. A skin Fullstack integrada é a minha realidade absoluta de mercado.</p>

    <hr>

    <h3>🔮 Meu Tech Stack & Ferramentas</h3>
    
    <div class="stack-grid">
        <div class="stack-card">
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="Python">
            <span>Python (Pandas)</span>
        </div>
        <div class="stack-card">
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="Java">
            <span>Java</span>
        </div>
        <div class="stack-card">
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="JavaScript">
            <span>JavaScript</span>
        </div>
        <div class="stack-card">
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="SQL">
            <span>SQL</span>
        </div>
        <div class="stack-card">
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/git/git-original.svg" alt="Git">
            <span>Git / GitHub</span>
        </div>
        <div class="stack-card">
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg" alt="HTML5">
            <span>HTML5 / CSS3</span>
        </div>
    </div>

    <p><strong>Core Técnico (Full-Stack & Gestão):</strong></p>
    <ul>
        <li>🌐 <strong>Front-end & Back-end:</strong> Desenvolvimento de interfaces responsivas com HTML5, CSS3 e JavaScript, além de lógica de sistemas e manipulação de dados utilizando Java, Python (com Pandas) e bancos de dados relacionais via SQL.</li>
        <li>⚙️ <strong>Ferramentas & DevOps:</strong> Versionamento de código com Git/GitHub e acompanhamento de infraestrutura com Azure DevOps.</li>
        <li>🌟 <strong>Metodologias Ágeis:</strong> Organização de sprints, fluxos de entrega e rastreio de demandas utilizando Jira, Azure DevOps e quadros Kanban.</li>
    </ul>

    <hr>

    <h3>📈 Estatísticas do Meu Ecossistema</h3>
    <div class="stats">
        <img src="https://github-readme-stats.vercel.app/api?username=solenetavares&show_icons=true&theme=omni&include_all_commits=true&count_private=true" alt="Estatísticas do GitHub" height="150" />
        <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=solenetavares&layout=compact&theme=omni" alt="Linguagens mais usadas" height="150" />
    </div>

    <hr>

    <h3>⚙️ Conecte-se ao meu Sistema:</h3>
    <ul class="contact-list">
        <li>📩 <strong>E-mail:</strong> <a href="mailto:solenetavares06@gmail.com">solenetavares06@gmail.com</a></li>
    </ul>

    <div class="footer">
        <p>"something 'bout me" 🎀</p>
    </div>

</div>

</body>
</html>
