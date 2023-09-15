Exemplos da Aula 

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Flex</title>
    <style>
        div {
            background-color:rgb(100, 167, 0);
            border: solid 1px black;
        }
        .flex-container {
            display: flex;
            background-color: rgb(66, 66, 66);
            justify-content: center;
            align-items:center;
            height: 100vh;
            flex-direction:column;
            flex-wrap:wrap;
        }
        .item {
            height: 50px;
            width: 250px;
            flex-basis: 100px;
            text-align: center;
        }
        .item2 {
            background-color: blue;
            height: 50px;
            width: 250px;
            flex-basis: 100px;
            text-align: center;
        }
        
    </style>
</head>
<body>
    <div class="flex-container">
        <div class="item">1</div>
        <div class="item2">2</div>
        <div class="item">3</div>
        <div class="item">4</div>
    </div>
    
</body>
</html>

Login 

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
    <button><a href="http://127.0.0.1:5500/exemplo.html">p/ exemplo</a></button>
</body>
</html>

Endereço 

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

Logo Etec

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
    <img src="/imagens/LOGOetec.png" alt="Logo Etec" width="30%" height="30%" class="img" > <br> <br>
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
    position:relative;
    top: 100px;
    display:flex;
    flex-direction: column;
    flex-wrap: wrap;
    justify-content: center;
}

.img {
    position: relative;
    left: 650px;
}

.button {
    color: black;
}
