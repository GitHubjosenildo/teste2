# teste2
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Tela de Login</title>
</head>
<body>
    <div class="login-container">
        <h1>Login</h1>
        <form action="login.php" method="post">
            <label for="username">Usuário:</label>
            <input type="text" id="username" name="username" required>
            
            <label for="password">Senha:</label>
            <input type="password" id="password" name="password" required>
            
            <button type="submit">Entrar</button>
        </form>
    </div>
</body>
</html>
