# Site-do-Pokemon

PARTE DO LOGIN

<!DOCTYPE html>
<html>
<head>
	<title>Login Pokemon</title>
	<style>
		body {
			background-image: url('https://i.imgur.com/O7ZWigt.png');
			background-size: cover;
			font-family: Arial, sans-serif;
		}

		form {
			background-color: rgba(255, 255, 255, 0.8);
			border-radius: 10px;
			padding: 20px;
			max-width: 400px;
			margin: 0 auto;
			margin-top: 100px;
			box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
		}

		label {
			display: block;
			font-weight: bold;
			margin-bottom: 10px;
		}

		input[type="text"], input[type="password"] {
			padding: 10px;
			font-size: 16px;
			border-radius: 5px;
			border: none;
			margin-bottom: 20px;
			width: 100%;
		}

		input[type="submit"] {
			background-color: #ffcb05;
			border: none;
			color: #fff;
			font-size: 16px;
			padding: 10px;
			border-radius: 5px;
			cursor: pointer;
			transition: all 0.3s ease;
			width: 100%;
			margin-bottom: 20px;
		}

		input[type="submit"]:hover {
			background-color: #ffad05;
		}
	</style>
</head>
<body>
	<form action="#">
		<label for="username">ID Mestre:</label>
		<input type="text" name="username" id="username" placeholder="Digite seu Id de Mestre">

		<label for="password">Senha:</label>
		<input type="password" name="password" id="password" placeholder="Digite sua senha">

		<input type="submit" value="Entrar">
        <a href="Pokemon.html" target="_blank"><input type="button" value="Cadastre se "></a>


    </form>
    <href> </href>
</body>
</html>

PARTE DO CADRASTRO

<!DOCTYPE html>
<html>
    <style>
        body {
            background-image: url('https://wallpapercave.com/wp/wp2595128.jpg');
            background-size: cover;
			font-family: Arial, sans-serif;
          }

          form {
			background-color: rgba(255, 255, 255, 0.8);
			border-radius: 10px;
			padding: 20px;
			max-width: 400px;
			margin: 0 auto;
			margin-top: 100px;
			box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
		}
      </style>
      
  <head>
    <title>Site dos Mestres Pokémon</title>
    <meta charset="utf-8">
    <link rel="stylesheet" href="Pokemon2.css">
  </head>
  <body>
    <header>
      <h1>Site dos Mestres Pokémon</h1>
    </header>
    <main>
      <h2>Cadastro do ID Mestre</h2>
      <form>
        <label for="nome">Nome:</label>
        <input type="text" id="nome" name="nome" required>
        
        <label for="id-mestre">ID Mestre:</label>
        <input type="text" id="id-mestre" name="id-mestre" required>
        
        <label for="regiao">Região de atuação:</label>
        <select id="regiao" name="regiao" required>
          <option value="">Selecione uma região</option>
          <option value="Kanto">Kanto</option>
          <option value="Johto">Johto</option>
          <option value="Hoenn">Hoenn</option>
          <option value="Sinnoh">Sinnoh</option>
          <option value="Unova">Unova</option>
          <option value="Kalos">Kalos</option>
        </select>
        <a href="Login.html"><input type="button" value="Cadastro"></a>
        <script>
            document.querySelector('button[type="submit"]').addEventListener('click', function() {
              window.open('Pokemon.html', '_blank');
            });
          </script>
      </form>
      
      
      <h2>Cadastro de Pokémon</h2>
      <form>
        <label for="nome-pokemon">Nome do Pokémon:</label>
        <input type="text" id="nome-pokemon" name="nome-pokemon" required>
        
        <label for="data-captura">Data de captura:</label>
        <input type="date" id="data-captura" name="data-captura" required>
        
        <label for="pokebolas">Pokebolas utilizadas:</label>
        <input type="number" id="pokebolas" name="pokebolas" required>
        
        <label for="tipo">Tipo:</label>
        <select id="tipo" name="tipo" required>
          <option value="">Selecione um tipo</option>
          <option value="Normal">Normal</option>
          <option value="Fogo">Fogo</option>
          <option value="Água">Água</option>
          <option value="Ar">Ar</option>
          <option value="Planta">Planta</option>
          <option value="Elétrico">Elétrico</option>
          <option value="Gelo">Gelo</option>
        </select>
        
        <button type="submit">Cadastrar Pokémon</button>
      </form>
    </main>
    <footer>
      <p>&copy; 2023 Site dos Mestres Pokémon</p>
    </footer>

PARTE DO CSS

body {
    font-family: Arial, sans-serif;
    margin: 0;
  }
  
  header {
    background-color: #ffcc00;
    padding: 20px;
    text-align: center;
  }
  
  header h1 {
    margin: 0;
    font-size: 36px;
  }
  
  main {
    padding: 20px;
  }
  
  h2 {
    font-size: 24px;
    margin-top: 40px;
    margin-bottom: 20px;
  }
  
  form {
    display: flex;
    flex-direction: column;
    max-width: 600px;
    margin: 0 auto;
  }
  
  label {
    font-weight: bold;
    margin-bottom: 10px;
  }
  
  input[type="text"],
  input[type="password"],
  input[type="number"],
  select {
    padding: 10px;
    margin-bottom: 20px;
    border-radius: 5px;
    border: 1px solid #ccc;
    font-size: 18px;
  }
  
  input[type="date"] {
    padding: 10px;
    margin-bottom: 20px;
    border-radius: 5px;
    border: 1px solid #ccc;
    font-size: 18px;
    width: 100%;
  }
  
  button[type="submit"] {
    background-color: #ffcc00;
    color: #fff;
    border: none;
    border-radius: 5px;
    padding: 10px;
    font-size: 18px;
    cursor: pointer;
  }
  
  button[type="submit"]:hover {
    background-color: #e6b800;
  }
  
