body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
    color: #333;
}

header {
    background-color: #333;
    color: #fff;
    padding: 15px;
    text-align: center;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 10px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
}

section {
    padding: 20px;
    background-color: #fff;
    margin: 20px;
}

footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 10px;
    position: fixed;
    bottom: 0;
    width: 100%;
}

form label {
    display: block;
    margin-top: 10px;
}

form input, form textarea {
    width: 100%;
    padding: 10px;
    margin-top: 5px;
}

form button {
    margin-top: 10px;
    padding: 10px 20px;
    background-color: #333;
    color: #fff;
    border: none;
    cursor: pointer;
}

<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Startup Tech - Inovação e Tecnologia</title>
    <link rel="stylesheet" href="css/style.css">
</head>
<body>
    <?php include('includes/header.php'); ?>
    <section>
        <h2>Bem-vindo à xxxxxxxxxxx</h2>
        <p>Transformando suas ideias em soluções inovadoras.</p>
    </section>
    <?php include('includes/footer.php'); ?>
</body>
</html>

<header>
    <h1>xxxxxxxxxx</h1>
    <nav>
        <ul>
            <li><a href="index.php">Home</a></li>
            <li><a href="about.php">Sobre</a></li>
            <li><a href="services.php">Serviços</a></li>
            <li><a href="contact.php">Contato</a></li>
        </ul>
    </nav>
</header>

<footer>
    <p>&copy; 2024 xxxxxxxxxx. Todos os direitos reservados.</p>
</footer>

<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sobre Nós - Startup Tech</title>
    <link rel="stylesheet" href="css/style.css">
</head>
<body>
    <?php include('includes/header.php'); ?>
    <section>
        <h2>Sobre Nós</h2>
        <p>A xxxxxxx é uma empresa focada em criar soluções tecnológicas inovadoras para transformar negócios.</p>
        <h3>Missão</h3>
        <p>Inovar continuamente e fornecer soluções que criam valor para nossos clientes.</p>
        <h3>Visão</h3>
        <p>Ser a referência em inovação tecnológica no mercado global.</p>
        <h3>Equipe</h3>
        <p>Nosso time é composto por especialistas em diversas áreas da tecnologia, prontos para enfrentar desafios e entregar resultados excepcionais.</p>
    </section>
    <?php include('includes/footer.php'); ?>
</body>
</html>

<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contato - xxxxxxxxxxxxxxxxx</title>
    <link rel="stylesheet" href="css/style.css">
</head>
<body>
    <?php include('includes/header.php'); ?>
    <section>
        <h2>Entre em Contato</h2>
        <form action="send_contact.php" method="post">
            <label for="name">Nome:</label>
            <input type="text" id="name" name="name" required>
            <label for="email">E-mail:</label>
            <input type="email" id="email" name="email" required>
            <label for="message">Mensagem:</label>
            <textarea id="message" name="message" required></textarea>
            <button type="submit">Enviar</button>
        </form>
    </section>
    <?php include('includes/footer.php'); ?>
</body>
</html>
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Serviços - Startup Tech</title>
    <link rel="stylesheet" href="css/style.css">
</head>
<body>
    <?php include('includes/header.php'); ?>
    <section>
        <h2>Nossos Serviços</h2>
        <ul>
            <li>Desenvolvimento de Software Sob Medida</li>
            <li>Consultoria em Transformação Digital</li>
            <li>Integração de Sistemas</li>
            <li>Suporte Técnico e Manutenção</li>
        </ul>
    </section>
    <?php include('includes/footer.php'); ?>
</body>
</html>



