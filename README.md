# atv-sw-chat-Frpnt-end
Aqui vou começar meus estudos sobre Html e CSS.


<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Atendimento On-line</title>
</head>
<body>
  <div id="principal">
    <header class="Titulo">
      <h1>Atendimento On-line</h1>
    </header>
  
    <form method="post" action="https://postman-echo.com/post">
      <div>
        <label for="Atendente1">Atendente diz:</label>
      <div>
  
      <div class="cliente">
        <label for="Cliente1">Você diz:</label>
      </div>
        
      </div>
    </form>
  </div>
  <div class="Mensagem-e-botao">
        <div class="Enviar-mensagem">
          <input type="text" id="Cliente3" name="Cliente3" class="Cliente3" placeholder="Digite sua mensagem" required>
        </div>
        <div class="Botao">
          <button class="Botao" type="submit">Enviar</button>
        </div>
</body>
</html



.Titulo {
  background-color: blue; 
  border: 4px solid white; 
  padding: 10px; 
  text-align: left;
  color: white;
  border-radius: 10px;
}

body {
  font-family: Arial;
  font-size: 16px;
  color: white;
  background-color: black;
  font-weight: bold;
  border-radius: 10px;
}

#Principal {
  max-width: 720px;
  min-width: 360px;
  margin: 0 auto;
}

header h1 {
  font-size: 32px;
  margin: 0;
  padding: 0;
}

form {
  border: 4px solid white;
  background-color: MediumBlue;
  margin-bottom: 20px;
  padding: 80px 10px;
  border-radius: 10px;
}

.cliente {
  width: 120px;
  text-align: left;
  margin-left: auto;
}

.Mensagem-e-botao {
  display: flex;
  align-items: center;
  justify-content: space-between;
  background-color: blue;
  border: solid white 4px;
  padding: 4px 20px;
  margin-top: -15px;
  border-radius: 10px;
}

.Botaoo {
  margin-left: 10px;
  
}

.Botao {
  padding: 2px 8px; 
  font-size: 18px;
  color: green;
  border-radius: 10px;
  cursor: pointer;
  font-weight: bold;
  border: 0;
}






