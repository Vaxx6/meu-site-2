<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DIAS & DIAS ADVOGADOS</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>DIAS & DIAS ADVOGADOS</h1>
        <nav>
            <ul>
                <li><a href="#home">Início</a></li>
                <li><a href="#about">Sobre Nós</a></li>
                <li><a href="#services">Serviços</a></li>
                <li><a href="#blog">Blog</a></li>
                <li><a href="#contact">Contato</a></li>
            </ul>
        </nav>
    </header>

    <section id="home">
        <h2>frase introdutória</h2>
        <p>Descrição do escritório...</p>
    </section>

    <section id="about">
        <h2>Sobre Nós</h2>
        <p>Informações sobre o escritório...</p>
    </section>

    <section id="services">
        <h2>Serviços</h2>
        <p>áreas de atuação e serviços...</p>
    </section>

    <section id="blog">
        <h2>Blog</h2>
        <p>artigos...</p>
    </section>

    <section id="contact">
        <h2>Contato</h2>
        <form>
            <label for="Nome">Nome:</label>
            <input type="text" id="name" name="name" required>

            <label for="Telefone">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="Mensagem">Mensagem:</label>
            <textarea id="message" name="message" required></textarea>

            <button type="submit">Enviar</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 Escritório de Advocacia</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
