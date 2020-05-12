# ava1dev-web
código de cadastro html 
<!DOCTYPE html>
<html lang="pt-br">
<head>
	<meta charset="UTF-8">
	<title>cadastro de usuário</title>
	<style>
		h1 {
			font-family: Arial;
			font-size: 30pt;
			color: black;
			text-shadow:  50px 50px 20px darkgray;
		}

	</style>

<title>AV1</title>
<head>


<link rel="stylesheet" type="text/css" href="estilo.css">
</head>
<body>
<form id="formulario" name="form" action="#" method="post">
	<fieldset>
<table>

<tr>
	<th>
	<h1>Cadastro</h1>
	</th>
	


</tr>
</table>
<table>
	<tr>
	<td>
	<label name="tratamento">Tratamento:</label> <select> 
	<option value="senhor" required>Senhor.</option>
	<option value="senhora" required>Senhora.</option><br>
	</select><br>
	<label name="nome">Nome:</label> <input type="text" name="nome" required><br>
	<label name="telefone_f">Telefone:</label> <input type="phone" name="telefone_f" required><br>
	<label name="telefone_c">Telefone Comercial:</label> <input type="phone" name="telefone_c" required><br>
	<label name="celular">Celular:</label> <input type="phone" name="celular" required><br>
	<label name="email">Email:</label> <input type="email" name="email" placeholder="exemplo@exemplo.com.br" required><br>
	<label name="idade">Idade:</label> <input type="number" name="Idade" required><br>
	<label name="sexo">Sexo: </label><input type="radio" name="sexo" value="m" required>Masculino</br><input type="radio" name="sexo" value="f" required>Feminino<br>
	<label name="nascimento">Data de Nascimento:</label> <input type="date" name="nascimento" required><br>
	<label for="estado civil">Estado Civil: </label><select>
	<option value="Casado">Solteiro</option>
	<option value="Casado">Casado</option>
	<option value="Casado">Divorciado</option>
	</select>

	</td>
	<td>
	
	</td>


	<td></br></br>
	<label name="formação">Formação: </label><input type="radio" name="formação" value="1"required>Ensino Fundamental<input type="radio" name="formação" value="2"required>Segundo Grau<input type="radio" name="formação" value="3"required>Superior<br>
	<label name="instituição">Instituição: </label><select>
		<option value="uva">UVA</option>

	</select></br>
	<label name="ingresso">Data de Ingresso:</label> <input type="date" name="ingresso" required><br>
	<label name="conclusao">Data de Conclusão:</label> <input type="date" name="conclusao" required><br>
	<label name="interessenome">Áreas de Interesse:</label>
	<input type="checkbox" name="c1" value="música">Música
	<input type="checkbox" name="c2" value="esporte">Esporte
	<input type="checkbox" name="c3" value="artes">Artes
	<input type="checkbox" name="c4" value="cursos">Cursos<br>

	
	<label name="endereço">Endereço:</label> <input type="text" name="endereço" required><br>
	<label name="Número">Número:</label> <input type="number" name="Número" required><br>
	<label name="complemento">Complemento:</label> <input type="text" name="complemento" required><br>
	<label name="cep">CEP:</label> <input type="number" name="cep" required><br>
	<label for="Região">Região: </label><select>
	<option value="Sudeste">Sudeste</option>
	<option value="Norte">Norte</option>
	<option value="Nordeste">Nordeste</option>
	<option value="Sul">Sul</option>
	<option value="Centro-Oeste">Centro-Oeste</option>
	<option value="Noroeste">Noroeste</option>
    </select></br></br>


	</td>
	
</tr>


	





</table>
<table>
	<th>
<h3 name="obs">Observações:</h3><textarea name="obs" wrap="hard" cols="50" rows="10" scroll="none" STYLE="resize: none;"  placeholder="Insira Suas Obs Aqui..."></textarea><br/>
	</th>
</table>

<table>
<tr>
<th>CRISTOVÃO SOARES</th>
</tr>


</table>
<table>
	<th>

		</div>
		<p><button>Enviar</button>
			<button>Limpar</button></p>
</form>
</p>

	<style>
		label {
			display: inline-block;
			width: 100px;
			height: 30px;
		}
		select#linguagem{
			display: grid;
			width: 80px;
			height: 100px;
		}
		textarea{
			display: grid;
			width: 300px;
			height: 100px;
		}

		label[for="info"] {
			width: 200px;
		}


	</style>

</table>
</fieldset>
</form>
</body>
</html>
