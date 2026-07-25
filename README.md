<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Quiz Interativo para Programadores</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header class="site-header">
        <h1>Quiz Interativo para Programadores</h1>
        <p><strong>Teste seus conhecimentos em programação e veja qual a sua pontuação!</strong></p>
    </header>

    <main class="quiz-container">
        <!-- Introdução -->
        <section class="card intro-card">
            <h2>Sobre esse quiz</h2>
            <p>Este quiz foi desenvolvido para desafiar programadores de todos os níveis. Ele contém uma série de perguntas que abrangem diferentes áreas da programação, desde lógica básica até conceitos avançados.</p>
            <p>Ao final do quiz, você receberá uma pontuação que refletirá seu desempenho. Prepare-se para testar seus conhecimentos e aprender algo novo!</p>
            <p>Você poderá encontrar alguns acrônimos como <abbr title="HyperText Markup Language">HTML</abbr> e <abbr title="Cascading Style Sheets">CSS</abbr>, que são linguagens de marcação e estilo, respectivamente. Além disso, conceitos como algoritmos, estruturas de dados e paradigmas de programação também serão abordados.</p>
            <p><strong>Boa sorte!</strong></p>
        </section>

        <!-- Formulário Geral do Quiz -->
        <form id="quiz-form">
            <!-- Pergunta 1 -->
            <section class="card question-card">
                <h2>Pergunta 1: Qual linguagem é usada para estruturar páginas na web?</h2>
                <div class="options-group">
                    <label><input type="radio" value="Python" name="pergunta1"> a) Python</label>
                    <label><input type="radio" value="Java" name="pergunta1"> b) Java</label>
                    <label><input type="radio" value="HTML" name="pergunta1"> c) HTML</label>
                    <label><input type="radio" value="C++" name="pergunta1"> d) C++</label>
                </div>
            </section> 

            <!-- Pergunta 2 -->
            <section class="card question-card">
                <h2>Pergunta 2: Na URL https://www.google.com o trecho "google.com" é o ________</h2>
                <input type="text" id="p2" name="pergunta2" placeholder="Digite sua resposta aqui">
            </section>

            <!-- Pergunta 3 -->
            <section class="card question-card">
                <h2>Pergunta 3: Escreva um exemplo de senha forte</h2> 
                <input type="password" id="p3" name="pergunta3" placeholder="Digite sua senha aqui">
            </section> 

            <!-- Pergunta 4 -->
            <section class="card question-card">
                <h2>Pergunta 4: Qual é a data de lançamento da primeira versão do HTML?</h2>
                <input type="date" id="p4" name="pergunta4">
            </section> 

            <!-- Pergunta 5 -->
            <section class="card question-card">
                <h2>Pergunta 5: Quais dessas tecnologias são consideradas linguagens de programação?</h2>
                <div class="options-group">
                    <label><input type="checkbox" name="pergunta5" value="JavaScript"> JavaScript</label>
                    <label><input type="checkbox" name="pergunta5" value="HTML"> HTML</label>
                    <label><input type="checkbox" name="pergunta5" value="Python"> Python</label>
                    <label><input type="checkbox" name="pergunta5" value="C++"> C++</label>
                </div>
            </section>

            <!-- Pergunta 6 -->
            <section class="card question-card">
                <h2>Pergunta 6: Faça o upload de um arquivo contendo código HTML</h2>
                <input type="file" id="p6" name="pergunta6">
            </section>

            <!-- Pergunta 7 -->
            <section class="card question-card">
                <h2>Pergunta 7: Selecione o atributo do input que define seu tipo</h2>
                <select id="p7" name="pergunta7">
                    <option value="" disabled selected>Selecione...</option>
                    <option value="id">id</option>
                    <option value="type">type</option>
                    <option value="placeholder">placeholder</option>
                </select>
            </section>

            <!-- Pergunta 8 -->
            <section class="card question-card">
                <h2>Pergunta 8: Qual linguagem de programação é representada na imagem abaixo?</h2>
                <figure>
                    <img src="https://upload.wikimedia.org/wikipedia/commons/6/6a/JavaScript-logo.png" alt="Logo do JavaScript" width="150">
                    <figcaption>Logo oficial</figcaption>
                </figure>
                <input type="text" id="p8" name="pergunta8" placeholder="Digite sua resposta aqui">
            </section>
        </form>

        <!-- Tabela de Pontuação -->
        <section class="card table-card">
            <h2>Tabela de Pontuação</h2>
            <table>
                <thead>
                    <tr>
                        <th>Pontuação</th>
                        <th>Avaliação</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>0-2</td>
                        <td>Não desista! Cada tentativa é uma oportunidade de aprender.</td>
                    </tr> 
                    <tr>
                        <td>2-4</td>
                        <td>Ainda pode melhorar! Continue praticando.</td>
                    </tr>
                    <tr>
                        <td>4-7</td>
                        <td>Parabéns! Você está no caminho certo.</td>
                    </tr>
                    <tr>
                        <td>8</td>
                        <td>Excelente! Você é um verdadeiro expert.</td>
                    </tr>
                </tbody>
                <tfoot>
                    <tr>
                        <td colspan="2">Lembre-se: a prática leva à perfeição!</td>
                    </tr>
                </tfoot>
            </table>
        </section>

        <!-- Lista de Respostas -->
        <section class="card answers-card">
            <h2>Respostas do Quiz</h2>
            <details>
                <summary>Clique aqui para ver as respostas</summary>
                <ol>
                    <li><strong>Pergunta 1:</strong> c) HTML</li>
                    <li><strong>Pergunta 2:</strong> Domínio</li>
                    <li><strong>Pergunta 3:</strong> Exemplo de senha forte: P@ssw0rd!2024</li>
                    <li><strong>Pergunta 4:</strong> 1993-01-01</li>
                    <li><strong>Pergunta 5:</strong> JavaScript, Python, C++</li>
                    <li><strong>Pergunta 6:</strong> Arquivo de código HTML</li>
                    <li><strong>Pergunta 7:</strong> type</li>
                    <li><strong>Pergunta 8:</strong> JavaScript</li>
                </ol>
            </details>
        </section>

        <!-- Formulário de Feedback -->
        <section class="card feedback-card">
            <h2>Nos diga o que você achou do quiz e deixe seu feedback!</h2>
            <form id="feedback-form">
                <fieldset>
                    <legend>Formulário de Feedback</legend>   
                    <label for="nome">Nome:</label>
                    <input type="text" id="nome" name="nome" placeholder="Digite seu nome" required>
                    
                    <label for="email">Email:</label>
                    <input type="email" id="email" name="email" placeholder="Digite seu email" required>
                    
                    <label for="feedback">Feedback:</label>
                    <textarea id="feedback" name="feedback" placeholder="Digite seu feedback aqui..." required></textarea>
                    
                    <button type="submit">Enviar Feedback</button>
                </fieldset>         
            </form>
        </section>
    </main>

    <footer class="site-footer">
        <p>&copy; 2026 Quiz para Programadores. Todos os direitos reservados.</p>
        <p>Para conhecer outros quizes <a href="fds.html" target="_blank">clique aqui</a></p>  
    </footer>
</body>
</html>
