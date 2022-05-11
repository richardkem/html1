<!DOCTYPE html>
<html lang="pt-br">
	<head>
		<meta charset="UTF-8">
		<meta name="viewport" content="width=device-width">
		<title>Desafio Alura</title>
	
		<link rel="stylesheet" href="reset.css">
		<link rel="stylesheet" href="style.css">

	</head>
	<body text="#FFFF00">
		<section class="central">	
				<h1 style="text-align: center;"><strong class="Letras">Desafio Formulario</strong></h1>
	<script type="text/javascript"></script>
	</section>

<form>
	
	<label for="nomeesobrenome" style="text-align: center;" ><i>Nome e Sobrenome<i></label>
	<input type="text" id="nomesobrenome" class="input-padrao" required>


<div>
	<p class="Letras">Setor</p>
	<label for="radio-T.I"><input type="radio" name="contato" value="T.I"
		id="radio-T.I" class="Letras">T.I</label>

	<label for="radio-Financeiro"><input type="radio" name="Financeiro" value="Financeiro" id="radio-Financeiro" class="Letras">Financeiro</label>

		<label for="radio-Compras"><input type="radio" name="contato" value="Compras"
		id="radio-Compras" class="Letras">Compras</label>

			<label for="radio-Faturamento"><input type="radio" name="contato" value="Faturamento"
		id="radio-Faturamento" class="Letras">Faturamento</label>

	<label for="radio-Controlamento"><input type="radio" name="contato" value="Controlamento"
		id="radio-Controlamento" class="Letras">Controlamento</label>



	

</div>

	<fieldset>
		<legend class="Letras">Áreas desenvolvidas para o desenvolvimento</legend>
<select>
	<option>Financeiro</option>
	<option>Compras</option>
	<option>Controladora</option>
	<option>Faturamento</option>
	<option>T.I</option>

	
</select>
	</fieldset>




     <label for="Titulo do projeto" style="text-align: center;" class="Letras">Titulo do projeto</label>
     <input type="text" id="Titulo do projeto" class="input-padrao" required>

     <label for="Objetivo do projeto" style="text-align: center;" class="Letras">Objetivo do projeto</label>
     <textarea cols="70" rows="10" id="mensagem" class="input-padrao" required></textarea>

     <label for="Objetivo do projeto" style="text-align: center;" class="Letras">Resultados a serem obtidos</label>
     <textarea cols="70" rows="10" id="mensagem" class="input-padrao" required></textarea>

     <label for="Objetivo do projeto" style="text-align: center;" class="Letras">Descrição detalhada do projeto</label>
     <textarea cols="70" rows="10" id="mensagem" class="input-padrao" required></textarea>

     <label for="Prazo inicial" style="text-align: center;" class="Letras">Prazo inicial</label>
     <input type="date" id="Prazo inicial" class="input-padrao" required=>

     <label for="Prazo inicial" style="text-align: center;" class="Letras">Prazo final</label>
     <input type="date" id="Prazo inicial" class="input-padrao" required=>


	<script>
			function funcao1(){
				alert("formulário enviado com sucesso! :)")

			}
		</script>

 	<input type="button" onclick="funcao1()" value="Enviar Formulario" class="enviar" />




</form>


	</body>
	</html>
    
    
    
    
    
    
    
    
    form {
	margin: 40px 0;
}
form label, form legend {
	display:block;
	font-size: 20px;
	margin: 0 0 10px;
}
.input-padrao {
		display: block;
	margin: 0 auto 0px;
	padding: 10px 20px;
	width: 40%;
}
.checkbox {
	margin: 20px 0;
	display: block;
}
.enviar {
	width:40%;
	padding: 15px 0;
	background: orange;
	color: white;
	font-weight: bold;
	font-size: 18px;
	border: none;
	border-radius: 5px;
	transition: 1s all;
	cursor: pointer;
}

.enviar:hover {
	background: darkorange;
	transform: scale(1.2);
}
body {
	background: #696969;
	text-align: center;
	background-color: #696969;
	font-family: 'Montserrat', sans-serif;                                                                                                                                       
}
header {
	background: #BBBBBB;
	padding: 20px 0;
}
.radio {
	display: block;
	margin: 0 auto 0px;
	padding: 15px 20px;
	width: 25%;
}
.letras{
	background: #FFFF00
}
form label, form legend {
	display:block;
	font-size: 20px;
	margin: 0 0 20px;
	}

	form {
	margin: 0 15px;
}
table {
	margin: 20px 0 40px;
}
