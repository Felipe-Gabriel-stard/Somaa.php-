# Somaa.php-

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <title>Soma</title>
</head>
<body>
<form method="POST">
<label>Digite o primeiro número</label><br><br>
<input type="number" name="num01" required/><br><br>
<label>Digite o primeiro número</label><br><br>
<input type="number" name="num02" required/><br><br>
<<button type="submit">Responder</button>
</form>
  <?php
   $num01 = $_POST['num01'] ?? '';
   $num02 = $_POST['num02'] ?? '';
   $soma = $num01 + $num02;

 echo"<h2>A soma é: $soma</h2>";

  ?>
</body>
</html>
