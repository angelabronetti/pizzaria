

<html>

<head>
	<link rel="stylesheet" type="text/css"  href="../CSS/edicao1.css" /> 
		<meta charset="utf-8"/>
				
				<script type="text/javascript">
					$(document).ready(function() {
						$('#galeria1').cycle({ 
							fx:'scrollLeft',
							speed:    3000
						});
					});
					</script> <!-- Fim do script para slideshow -->
					
					
		<script type="text/javascript" src="../js/jquery.js"> </script>
        <script type="text/javascript" src="../js/jquery.mask.min.js"></script>
        <script type="text/javascript">
            $(document).ready(function(){
                $("#iDia").mask("99"); //Validação do campo dia
				$("#iMes").mask("99"); //Validação do campo Mês
				$("#iAno").mask("9999"); //Validação do campo Ano
				
				$("#iTelefone").mask("(99) 99999-9999"); //Validação do campo Telefone
				
				$("#iNum").mask("999999"); //Validação do campo Número da casa
				
				$("#iCep").mask("99999-999"); //Validação do campo Cep
	
				$("#icpf").mask("999-999-999-99")//Validação do campo Cpf
				
				$("#icartao").mask("9999 9999 9999 9999")//Validação do campo número do cartão
				$("#iCodigo").mask("999")//Validação do campo Código de segurança do cartão
				$("#iVal").mask("99/9999")//Validação do campo Validade do cartão

				});
	</script>
		<script type="text/javascript">
			$(function(){

				$('#ali').hide();
				var botao = $('.sub');

				botao.click(function(){

					$("#ali").toggle("slow");
					$('.infr').toggle('fast');	

					});


			});

		</script>
					
	
</head>

<body>
			<nav class="menu">
				<ul>
					<li><a href="index.php">Home</a></li>
					<li><a href="cardapio.php">Cardapio</a>
						<ul>
							<li><a href="combo.php">Combos</a>
						<ul>
								
								
						</ul>
						</li>
						<li><a href="lanche.php">Lanches</a></li>
						<li><a href="bebida.php">Bebidas</a></li>
						<li><a href="porcoes.php">Porções</a></li>
					</ul>

				<li><a href="login.php">Cadastro</a></li>
				<li><a href="sobre.php">BomBurguer</a></li>
			</ul>
		</nav>
		<div class="infr">
			
				<img src="../IMG/logo2.jpg"/>

			</div>

		<BR><BR><BR><BR><BR><BR><BR><BR><BR><BR><BR>

	<!---===============================login de cadastro==================================-->	


		<div id="lgn"> <!-- Div criada para login dos usuários -->
	
		<form id="logon"> 
		<label for="lLogin"> Login: </label> <!-- Label criada para login do usuário -->
		<input type="text" name="tLogin" id="iLogin" size="20" maxlength="30" placeholder="Digite Seu E-mail" required="required"/>
		
		<br> 
		<br>
		<br>
		
		<label for="lSenha"> Senha: </label>
		<input type="password" name="tSenha" id="iSenha" size="20" maxlength="10" placeholder="Digite Sua Senha" required="required"/>
	
		<br>
		<br>
		<input type="submit" name="login" value="login">
		<input type="submit" class="sub" value="É cadastrado? Cadastre-se Aqui.">
		
		<BR>
		<BR>
	</form>
	</div>
	
<div id="ali">
				<div id="for2"> <!-- Div criada para o cadastro de usuários, "segunda parte do formulário" -->
				
				
		<form method="POST" action="login.php">
			<fieldset id="cc"><legend > Cadastro: </legend> <!-- Fieldset criado para linha do formulário de cadastro -->
				
					<!-- Label para Nome, Data de Nascimento e Sexo -->
			<label for="lNome"> Nome: </label> 
			<label id="dt" for="lData"> Data de Nascimento: </label> 
			<label id="sex" for="lSexo"> Sexo: </label> <br>
			
					<!-- Input criado para campo Nome, Data de Nascimento e Sexo -->
			<input type="text" name="tNome" id="iNome" size="40" maxlength="50" required="required">
			
			<input type="text" name="tDate" id="iDia" size="30" maxlength="20" placeholder="Dia"  required="required">
			<input type="text" name="tDate" id="iMes" size="30" maxlength="20" placeholder="Mês"  required="required">
			<input type="text" name="tDate" id="iAno" size="30" maxlength="20" placeholder="Ano"  required="required">
					
					<!-- Fim da Label e Input de Nome, Data de Nascimento e Sexo -->
			
					<!-- Input criado para definir sexo masculino/feminino -->
			<input type="radio" name="tSexo" id="tipo" checked/> Feminino 
			<input type="radio" name="tSexo" id="tipoo" checked/> Masculino
					<!-- Fim do Input para definição do sexo -->
			<br>
			<br>
			<label for="lTelefone"> Telefone: </label>
			<input type="text" name="tTelefone" id="iTelefone" size="15" maxlength="20" required="required">
			
						
			<label id="en" for="lEndereco"> Endereço: </label>
			<input type="text" name="tEndereco" id="iEndereco" size="50" maxlength="50" required="required">
			<br>
			<br>
			<br>
			<label id="nn" for="lNumero"> Número: </label>
			<input type="text" name="tNumero" id="iNum" size="5" maxlength="10" required="required">
			
			<label id="ccc" for="lComplemento"> Complemento: </label>
			<input type="text" name="tComplemento" id="iCom" size="5" maxlength="30" required="required">
			
			<br>
			<br>
			<br>
			<label id="br" for="lBairro"> Bairro: </label>
			<input type="text" name="tBairro" id="iBai" size="15" maxlength="10" required="required">
			
			<label id="ci" for="lCidade"> Cidade: </label>
			<input type="text" name="tCidade" id="iCid" size="15" maxlength="30" required="required">
			
			<br>
			<br>
			<br>
			<label id="cep" for="lCep"> Cep: </label>
			<input type="text" name="tCep" id="iCep" size="15" maxlength="10" required="required">
			
			<label id="est" for="lEstado"> Estado: </label>
			<select name="testadoo"> <!-- Select Criado para busca/definir Estado -->
			<option>    </option>
			<option> AC </option>
			<option> AL </option>
			<option> AP </option>
			<option> AM </option>
			<option> BA </option>
			<option> CE </option>
			<option> DF </option>
			<option> ES </option>
			<option> GO </option>
			<option> MA </option>
			<option> MT </option>
			<option> MS </option>
			<option> MG </option>
			<option> PA </option>
			<option> PB </option>
			<option> PE </option>
			<option> PI </option>
			<option> RJ	</option>
			<option> RN </option>
			<option> RS </option>
			<option> RO </option>
			<option> RR </option>
			<option> SC </option>
			<option> SP </option>
			<option> SE </option>
			<option> TO </option>
			
				</select>
					</fieldset> <!-- Fim do campo de cadastro de dados pessoais -->
					
					<!-- Campo de cadastro de e-mail e senha -->
			
			<fieldset id="ic"><legend > Login: </legend> <!-- Fieldset criado para linha do formulário de cadastro -->
			
			<label for="lEmail"> E-mail: </label> 
			<input type="text" name="tEmail" id="iEmail" size="30" maxlength="50" placeholder="Digite Seu Email" required="required">
					<!-- Input criado para definir e-mail -->
			
			<label id="ce" for="lEmail"> Confirme seu e-mail: </label>
			<input type="text" name="tEmail" id="iEmaail" size="30" maxlength="50" placeholder="Confirme Seu Email" required="required">
			
			<br> 
			<br>
			<br>
			<label id="se" for="lSenha"> Senha: </label> 
			<input type="password" name="tSenha" id="iSenha" size="30" maxlength="10" placeholder="Digite Sua Senha" required="required">
					<!-- Input criado para definir senha -->
			
			<label id="ss" for="lSenha"> Confirme sua senha: </label>
			<input type="password" name="tSenhac" id="iseenha" size="30" maxlength="10" placeholder="Confirme Sua Senha" required="required">
			<br>
			<br>
			<br>
					</fieldset><!-- Fim do campo de cadastro de usuário -->
					
			<fieldset id="car"><legend > Cartão: </legend> <!-- Fieldset criado para linha do formulário de cadastro de cartão -->
			
			<label for="lCpf"> CPF: </label>
			<input type="text" name="tCpf" id="icpf" size="20" maxlength="15" required="required">
			
			
			<label id="cartao" nome="lCartao"> Cartão: <label>
			<input type="text" name="tcartao" id="icartao" size="30" maxlength="150" placeholder="Número do cartão" required="required">
			
			<br>
			<br>	
			<br>
			
			<label for="lCartao"> CVV: <label> <!-- Label criada para código de segurança do cartão -->
			<input type="text" name="tCodigo" id="iCodigo" size="3" maxlength="150"  required="required">
					
			<label id="ibandeira" for="lCartao"> Bandeira: <label>
			<input type="text" name="tBandeira" id="iBand" size="15" maxlength="150" placeholder="Bandeira do Cartão" required="required">
			
			<br>
			<br>
			<br>
			
			<label for="lCartao"> Validade: <label>
			<input type="text" name="tValidade" id="iVal" size="10" maxlength="150"  required="required">
					
			<label id="nc" for="lCartao"> Nome do Cartão: <label>
			<input type="text" name="tnomedoc" id="iNom" size="10" maxlength="150"  required="required">
			<BR>
			<BR>
			<br><br>
			

			</fieldset> <!-- Fim do campo de cadastro do cartão -->
			</div>
			<br><br>
			
			<?php
			
	
	$nome = "";
	$dtnascimento = "";
	$sexo = "";
	$telefone = "";
	$endereco = "";
	$numero = "";
	$complemento = "";
	$bairro = "";	
	$cidade = "";
	$cep = "";
	$estado = "";
	$email = "";
	$emailConf = "";
	$senha = "";
	$senhaConf = "";
	$cpf = "";
	$numeroC = "";
	$codigoC = "";
	$bandeira = "";
	$validade = "";
	$nomedoc = "";
	
	
	if(isset($_POST['submit'])){
	$nome = $_POST['tnome'];
    $dtnascimento = $_POST['tDate'];
    $sexo = $_POST['tsexo'];
    $telefone = $_POST['tTelefone'];
    $endereco = $_POST['tEnderco'];
    $numero = $_POST['tnumero'];
    $complemento = $_POST['tcomplemento'];
    $bairro = $_POST['tbairro'];
    $cidade = $_POST['tCidade'];
    $cep = $_POST['tCep'];
    $estado = $_POST['testadoo'];
    $email = $_POST['temail'];
    $senha = $_POST['tsenha'];
    $senhaConf = $_POST['tsenhac'];
    $cpf = $_POST['tcpf'];
    $numeroC = $_POST['tcartao'];
    $codigoC = $_POST['tcodigo'];
    $bandeira = $_POST['tBandeira'];
    $validade = $_POST['tvalidade'];
    $nomedoc = $_POST['tnomedoc'];
	}
	
	
    $inserir = "insert into cliente(nome,dtnascimento,sexo,telefone,endereco,numero,sexo,bairro,
        cidade,cep,estado,email,senha,senhaconf,senha,cpf,numeroc,
        codigoc,bandeira,validade,nomedoc) values( $nome,$dtnascimento,
            $sexo,$telefone,$endereco,$numero,$sexo,$bairro,$cidadde,
            $cep,$estaddo,$email,$senha,$senhaconf,$cpf,$numeroC,
            $codigoC,$bandeira,$validade,$nomedoc)";



$result = mysqli_query($con,$inserir);

$row = mysqli_fetch_assoc($result);
$opcao = "<br>" . $row[""] ."".$row[""];
echo $opcao;

 // associação 

 for($i=0; $i<$row; $i++){    
        $row=mysqli_fetch_assoc($result);
        echo "<br>".$row["nome"]." ".$row["cpf"];
    }
   
    // Free result set
    mysqli_free_result($result);
     mysqli_close($con);


			?>
			
			 <input type="submit"  class="conc" value="Cadastrar">
		</form>
</div>
</body>
</html>
