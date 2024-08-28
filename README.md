<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Site de Assinatura de Conteúdo</title>
    <link rel="stylesheet" href="css/styles.css">
</head>
<body>
    <div id="app">
        <h1>Bem-vindo ao Site de Assinatura de Conteúdo</h1>
        <div id="auth">
            <form id="signup-form">
                <h2>Cadastro</h2>
                <input type="email" id="email" placeholder="Email" required>
                <input type="password" id="password" placeholder="Senha" required>
                <button type="submit">Cadastrar</button>
            </form>
            <form id="login-form">
                <h2>Login</h2>
                <input type="email" id="login-email" placeholder="Email" required>
                <input type="password" id="login-password" placeholder="Senha" required>
                <button type="submit">Entrar</button>
            </form>
        </div>
    </div>

    <script src="js/main.js"></script>
</body>
</html>
