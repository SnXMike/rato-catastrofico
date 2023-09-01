# rato-catastrofico

LOGIN
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Apreciadores de passarinhos</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
   <div class="container"> <h1>Login</h1> <br>
    <form action="pagina1.html">
    <label>Usuário:</label><br>
    <input type="text" id="fname" name="fname" placeholder="nome"><br>
    <label>Senha:</label><br>
    <input type="password" id="lname" name="pwd" placeholder="password"> <br>
    <input type="submit" value="login">
  </form> <br><br>
    </div>
</body>
</html>

PAGINA 1
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pagina 1</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
    <form action="pagina2.html">
        <label for="fname">Nome Completo:</label><br>
        <input type="text" id="fname" name="fname"><br>
        <label for="lname">Endereço:</label><br>
        <input type="text" id="lname" name="lname">
       <br>
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
      </form>
      <button><a href="http://127.0.0.1:5500/index.html">Voltar</a></button> <br><br>
    </div>
</body>
</html>


PAGINA 2
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pagina2</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="logo">
    <img src="/imagens/LOGOetec.png" alt="Logo Etec" width="30%" height="30%" > <br> <br>
    <div class="button">
    <button><a href="http://127.0.0.1:5500/pagina1.html">Voltar</a></button> <br><br>
    <button><a href="http://127.0.0.1:5500/index.html">Inicio</a></button></div>
</div>
</body>
</html>

CSS

*{
    margin: 0%;
    padding: 0%;
    box-sizing: border-box;
}
body {
    text-align: center;
    background-color: lightblue;
    font-family:'Times New Roman', Times, serif;
}
input text {
    width: 10%;
    padding: 10px;
    border:1px solid blue;
    border-radius: 5px;
}
select {
    width: 10%;
    padding: 10px;
    border-radius: 5px;
    border: 1px solid black;
}
.container {
   border-style: inset;
   border-width: 100px;
   border-color:darkgray;
    background-color: white;
}
.logo{
position: relative;
top: 100px;
}
.button {
    color: black;
}
