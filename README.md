# phpaula5


<html>
<head>
</head>
<body>
    <form id= "form.login" action = "login.php" method = "POST">
login: <input type="text" name= "login"><br>
senha: <input type="password" name="senha"><br>
       <input type="submit" name="entrar" valve ="entrar"
       valver="entrar">
</form>
</body>
</html>





<?php
$login = $_POST['login'];
$senha = $_POST['senha'];

if ($login == "chuck" && $senha == "noris") {
echo "logado!!";
} else {
   header('location: index.php');
}
?>
