# -cidadaniadigital2026
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cidadania Digital</title>
    <link rel="stylesheet" href="css/style.css">
</head>
<body>
    <header>
        <h1>Cidadania Digital</h1>
        <button id="btnModo">Alternar Modo Escuro</button>
    </header>

    <main>
        <section id="sobre">
            <h2>O Perigo das Deepfakes</h2>
            <p>Conteúdo sobre como identificar mídias falsas...</p>
        </section>

        <section id="quiz">
            <h3>Teste seus conhecimentos</h3>
            <form id="formQuiz">
                <label>Você confia em vídeos da internet?</label>
                <select id="resposta">
                    <option value="nao">Não, sempre verifico a fonte.</option>
                    <option value="sim">Sim, acredito em tudo.</option>
                </select>
                <button type="submit">Enviar</button>
            </form>
            <p id="resultado"></p>
        </section>
    </main>

    <footer>
        <p>&copy; 2026 - Projeto Cidadania Digital</p>
    </footer>

    <script src="js/script.js"></script>
</body>
</html>
