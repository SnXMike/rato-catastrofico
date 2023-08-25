# rato-catastrofico

LOGIN

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Apreciadores de passarinhos</title>
    <link rel="icon" type="image/png" href="/casal-de-passarinhos-cambacica-cod-858-madrinha.jpg"/>
</head>
<body>
    <h1>Login</h1> <br>
    <form action="pag1.html">
    <label>Usuário:</label><br>
    <input type="text" id="fname" name="fname" placeholder="nome"><br>
    <label>Senha:</label><br>
    <input type="password" id="lname" name="pwd" placeholder="password"> <br>
    <input type="submit" value="login">
  </form> <br><br>
</body>
</html>

PAGINA 1

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pagina 1</title>
</head>
<body>
    <form action="pag2.html">
        <label for="fname">Nome Completo:</label><br>
        <input type="text" id="fname" name="fname"><br>
        <label for="lname">Endereço:</label><br>
        <input type="text" id="lname" name="lname">
      </form> <br>
      <label for="Estado">Estado do Brasil (UF):</label> <br>
      <select name="Estado" id="Estado">
        <option value="-">-</option>
        <option value="AC">Acre</option>
        <option value="AL">Alagoas</option>
        <option value="AP">Amapá</option>
        <option value="AM">Amazonas</option>
        <option value="BA">Bahia</option>
        <option value="CE">Ceará</option>
        <option value="DF">Distrito Federal</option>
        <option value="ES">Espírito Santo</option>
        <option value="GO">Goiás</option>
        <option value="MA">Maranhão</option>
        <option value="MT">Mato Grosso</option>
        <option value="MS">Mato Grosso do Sul</option>
        <option value="MG">Minas Gerais</option>
        <option value="PA">Pará</option>
        <option value="PB">Paraíba</option>
        <option value="PR">Paraná</option>
        <option value="PE">Pernambuco</option>
        <option value="PI">Piauí</option>
        <option value="RJ">Rio de Janeiro</option>
        <option value="RN">Rio Grande do Norte</option>
        <option value="RS">Rio Grande do Sul</option>
        <option value="RO">Rondônia</option>
        <option value="RR">Roraima</option>
        <option value="SC">Santa Catarina</option>
        <option value="SP">São Paulo</option>
        <option value="SE">Sergipe</option>
        <option value="TO">Tocantins</option>
        <option value="EX">Estrangeiro</option>
      </select> <br>
      <input type="submit" value="login"> <br> <br>
      <button><a href="http://127.0.0.1:5500/index.html">Voltar</a></button> <br><br>
</body>
</html>

PAGINA 2

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pagina2</title>
</head>
<body>
    <img src="/Imagens/Etec Logo.png" alt="Logo Etec" width="60%" height="60%"> <br> <br>
    <button><a href="http://127.0.0.1:5500/pag1.html">Voltar</a></button> <br><br>
    <button><a href="http://127.0.0.1:5500/index.html">Inicio</a></button>
</body>
</html>
