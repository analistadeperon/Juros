# Juros
#boosstrap
#javascript
#css
<div id="root"></div>

<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8">
	<title>Cadastro de Cliente</title>
	<link rel="stylesheet" type="text/css" href="css/bootstrap.min.css">
	<link rel="stylesheet" type="text/css" href="css/custom.css">
</head>
<body>
	<div class='container'>
		<fieldset>
			<legend><h1>Formulário - Cadastro de Cliente</h1></legend>
			
			<form action="action_cliente.php" method="post" id='form-contato' enctype='multipart/form-data'>
				<div class="row">
					<label for="nome">Selecionar Foto</label>
			      	<div class="col-md-2">
					    <a href="#" class="thumbnail">
					      <img src="data:image/jpeg;base64,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" height="190" width="150" id="foto-cliente">
					    </a>
				  	</div>
				  	<input type="file" name="foto" id="foto" value="foto" >
			  	</div>

			    <div class="form-group">
			      <label for="nome">Nome</label>
			      <input type="text" class="form-control" id="nome" name="nome" placeholder="Infome o Nome">
			      <span class='msg-erro msg-nome'></span>
			    </div>

			    <div class="form-group">
			      <label for="email">E-mail</label>
			      <input type="email" class="form-control" id="email" name="email" placeholder="Informe o E-mail">
			      <span class='msg-erro msg-email'></span>
			    </div>

			    <div class="form-group">
			      <label for="cpf">CPF</label>
			      <input type="cpf" class="form-control" id="cpf" maxlength="14" name="cpf" placeholder="Informe o CPF">
			      <span class='msg-erro msg-cpf'></span>
			    </div>
			    <div class="form-group">
			      <label for="data_nascimento">Data de Nascimento</label>
			      <input type="data_nascimento" class="form-control" id="data_nascimento" maxlength="10" name="data_nascimento">
			      <span class='msg-erro msg-data'></span>
			    </div>
			    <div class="form-group">
			      <label for="telefone">Telefone</label>
			      <input type="telefone" class="form-control" id="telefone" maxlength="12" name="telefone" placeholder="Informe o Telefone">
			      <span class='msg-erro msg-telefone'></span>
			    </div>
			    <div class="form-group">
			      <label for="celular">Celular</label>
			      <input type="celular" class="form-control" id="celular" maxlength="13" name="celular" placeholder="Informe o Celular">
			      <span class='msg-erro msg-celular'></span>
			    </div>
			    <div class="form-group">
			      <label for="status">Status</label>
			      <select class="form-control" name="status" id="status">
				    <option value="">Selecione o Status</option>
				    <option value="Ativo">Ativo</option>
				    <option value="Inativo">Inativo</option>
				  </select>
				  <span class='msg-erro msg-status'></span>
			    </div>
          <html lang='pt-br'>

<head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <title>Login 100%</title>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" type="text/css" media="screen" href="main.css">
    <script src="main.js"></script>
</head>

<body>

    <header>
        <nav>
            <h1> Sistema de cadastro MPD -  login com PHP e MYSQL - </h1>
            <ul>
                <li>
                    <a href="index.php">Inicio</a>
                </li>
                <li>
                    <a href="cadastro.html">Cadastro</a>
                </li>                
                <li>
                    <a href="login.html">Login</a>
                </li>
            </ul>
        </nav>
    </header>

    <form method="POST" action="login.php">
        <input type="text" name="login" id="login" placeholder="Login:">
        <input type="password" name="senha" id="senha" placeholder="Senha:">
        <input type="submit" value="entrar" id="entrar" name="entrar">        
        
    </form>
    <a href="cadastro.html"><button>Cadastre-se</button></a>
    <footer>
        <p>
            DPM - ANALISTA DE SISTEMAS;
        </p>
        <p>
            <a href="https://github.com/analistadeperon"> GIT HUB </a>
        </p>
        <p>
            <a href="https://www.linkedin.com/in/matheus-pazianotto-deperon-67bb7111b/"> LINKEDIN </a>
        </p>
        <p>
            <a href="https://analistaddeperon@hotmail.com"> E-mail </a>
        </p>
        <p>
            PHP Web app - MYSQL &copy; 2021 MPD - 
        </p>
    </footer>

</body>



</html>

			    <input type="hidden" name="acao" value="incluir">
			    <button type="submit" class="btn btn-primary" id='botao'> 
			      Gravar
			    </button>
			</form>
		</fieldset>
	</div>
	<script type="text/javascript" src="js/custom.js"></script>
</body>
</html>

<!DOCTYPE html> 
<html>
    <head>
		<title>Projeto Volt - Juros bancários</title>
        <meta charset="utf-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1">
		<script src="Chart.js" type="text/javascript"></script>
        <script src="Chart_1.js" type="text/javascript"></script>
        <script src="sheetsee.js" type="text/javascript"></script>
        <script src="tabletop1.3.4.js" type="text/javascript"></script>
        <script src= "jquery-1.11.3.min.js" type="text/javascript"></script>
        <script src="highlight.js" type="text/javascript"></script>
        <script src="https://cdnjs.cloudflare.com/ajax/libs/d3/3.5.6/d3.min.js" type="text/javascript"></script>
        
        <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.5/js/bootstrap.min.js"></script>
        <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.3/jquery.min.js"></script>
        <script src="js/bootstrap.min.js"></script>
        <link href='http://fonts.googleapis.com/css?family=Ubuntu' rel='stylesheet' type='text/css'>
        <link rel="stylesheet" type="text/css" href="estilos.css">
        <link href='http://fonts.googleapis.com/css?family=Source+Sans+Pro:400,700,900,400italic|Source+Code+Pro:400' rel='stylesheet' type='text/css'>
        <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.4.0/css/font-awesome.min.css">
        <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.5/css/bootstrap.min.css">
        <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.5/css/bootstrap-theme.min.css">
        <link href="css/bootstrap.min.css" rel="stylesheet">
        
    </head>
	   <body>
           <div style="border-top: 0px #cbcbcb;width:50%;margin:0 auto;margin-bottom:50px;margin-top:20px; text-align:center;font-family:Ubuntu, Arvo, Georgia;">
           <a href="www.voltdata.info"><img alt="Logo Volt" style="width:60px;height:auto;border:0;" src="http://static1.squarespace.com/static/551da417e4b05f67005d6abe/t/551dadd4e4b095e92c168eba/1438001414943/?format=1500w"/></a> | Projetos Especiais 
                
           </div>
           
           
             <!--Tabela com todos os dados pesquisáveis-->
              
  <div class="container" style="">
    <h1>Quanto seu banco cobra de juros?</h1>
    <p>
    <input id="fullTableFilter" type="text" placeholder="Digite aqui o nome do seu banco cobra - Ex: Bradesco, Itaú (utilize acentos)"/>
    <div id="fullTable"></div> 

</div>

<script id="fullTable_template" type="text/html">
  <table>
    <th class="tHeader"></th><th class="tHeader">Cartão Rotativo <br>- ao mês (%)</th><th class="tHeader">Cartão Rotativo <br>- ao ano (%)</th> <th class="tHeader">Cheque Especial <br> - ao mês (%)</th><th class="tHeader">Cheque Especial <br> - ao ano (%)</th>
      {{#rows}}
        <tr style="text-align:center; border-right: 1px"><td>{{banco}}</td><td>{{cart1}}</td><td>{{cart2}}</td><td>{{chq1}}</td><td>{{chq2}}</td></tr>
      {{/rows}}
  </table>
</script>

<script type="text/javascript">
  document.addEventListener('DOMContentLoaded', function() {
    var URL = "https://docs.google.com/spreadsheets/d/1C0uC3hy4DsY56wHaUhlTdW0hy4rTm-1ZKcAj80iG-S4/pubhtml"
    Tabletop.init( { key: URL, callback: showInfo, simpleSheet: true } )
  })

  function showInfo(data) {
    var tableOptions = {"data": data
    , "pagination": 5, "tableDiv": "#fullTable", "filterDiv": "#fullTableFilter"}
    Sheetsee.makeTable(tableOptions)
    Sheetsee.initiateTableFilter(tableOptions)

    var html = Sheetsee.ich.photogrid({'rows': data})
    $('#photogrid').html(html)
  }

    
</script>
           <div id="credito" class="container">
           <h6>Compilado pelo Volt | Fonte: Banco Central</h6>
           </div>
           <br>
           <br>
           <br>
           <div id="texto" class="container">
               
               <p>
           Os juros mostrados acima são apenas uma referência de taxas cobradas pelo mercado para <strong>pessoas físicas</strong>, e dizem respeito a informações operações contratadas em julho de 2015, de acordo com dados do Banco Central do Brasil. 
           </p>
               <p>
            Taxas de juros variam entre tomadores de empréstimos, e os dados acima servem apenas como comparativo. Nem todos os bancos nem todas as taxas de juros foram mostrados aí. Porém, as maiores instituições bancárias do país estão nesse lista.
               </p>
               <p>
            Foram utilizados como referências as taxas de juros do rotativo do cartão e do cheque especial, que são taxas contratadas principalmente quando o cliente bancário está mais apertado financeiramente, e também estão entre as mais caras do mercado.   
               </p>
               <p>
            Você pode encontra todos os dados sobre juros cobrados por bancos <a href="http://www.bcb.gov.br/pt-br/sfn/infopban/txcred/txjuros/Paginas/default.aspx" target="_blank">neste link</a>, inclusive sobre crédito pessoal consignado e para pessoas jurídcas.
               </p>
           </div>
        <br>
           <br>
           <br>
           <br>
           <!--Calculadora de Juros-->
           
<div id="calculadora" class="container">
    <h1>Calculadora de Juros</h1>
           <form name="loandata">
  <table style="margin:0 auto;">
    <tr><td colspan="3"><strong></strong></td></tr>
    <tr>
      <td>Empréstimo ($):</td>
      <td><input type="text" name="principal" size="12" 
                 onchange="calculate();"></td>
    </tr>
    <tr>
      <td>Taxa de juros (mensal)</td>
      <td>
          <input type="text" name="interest" size="12" 
                 onchange="calculate();"></td>
    </tr>
    <tr>
      <td>Prazo (em meses):</td>
      <td><input type="text" name="years" size="12" 
                 onchange="calculate();"></td>
    </tr>
    <tr><td colspan="3">
      <input type="button" value="Calcular" onclick="calculate();">
    </td></tr>
    <tr><td colspan="3">
    </td></tr>
    <tr>
      <td><strong>Pagamento mensal:</strong></td>
      <td><input type="text" name="payment" size="12"></td>
    </tr>
    <tr>
      <td>Pagamento total:</td>
      <td><input type="text" name="total" size="12"></td>
    </tr>
    <tr>
      <td>Juros pagos:</td>
      <td><input type="text" name="totalinterest" size="12"></td>
    </tr>
  </table>
</form>
<script language="JavaScript">
function calculate() {
    var principal = document.loandata.principal.value;
    var interest = document.loandata.interest.value / 100 / 1;
    var payments = document.loandata.years.value * 1;

    var x = Math.pow(1 + interest, payments);
    var monthly = (principal*x*interest)/(x-1);

    if (!isNaN(monthly) && 
        (monthly != Number.POSITIVE_INFINITY) &&
        (monthly != Number.NEGATIVE_INFINITY)) {

        document.loandata.payment.value = round(monthly);
        document.loandata.total.value = round(monthly * payments);
        document.loandata.totalinterest.value = 
            round((monthly * payments) - principal);
    }
    // Otherwise, the user's input was probably invalid, so don't
    // display anything.
    else {
        document.loandata.payment.value = "";
        document.loandata.total.value = "";
        document.loandata.totalinterest.value = "";
    }
}

function round(x) {
  return Math.round(x*100)/100;
}
</script>
            </div>
           
           
           
           <!--Gráfico Cheque Especial-->
           
           <div class="grafico" id="graph1">
            <div class="grafico1">
               <h1>Juros cheque especial
		      </h1>
            <canvas id="especial" width="300" height="300"></canvas>
               </div>
               <!--Gráfico Cartão-->
             <div class="grafico2">
            <h1>Juros cartão - % ao ano
		      </h1>
            <canvas id="cartao" width="300" height="300"></canvas>
                 </div>
	   <script>
		var jurosespecial = 
            
            [
				{
					value: 195.03,
					color:"#F7464A",
					highlight: "#ededed",
					label: "Bradesco"
				},
				{
					value: 197.45,
					color: "#336699",
					highlight: "#ededed",
					label: "Caixa"
				},
				{
					value: 215.59,
					color: "#cdaf35",
					highlight: "#ededed",
					label: "Banco do Brasil"
				},
				{
					value: 247.26,
					color: "#cc8b2f",
					highlight: "#ededed",
					label: "Itaú"
				},
                {
					value: 305.93,
					color: "#443266",
					highlight: "#ededed",
					label: "Citibank"
				},
				{
					value: 348.56,
					color: "#FD2A19",
					highlight: "#ededed",
					label: "HSBC"
				},
                {
					value: 369.02,
					color: "#A6002E",
					highlight: "#ededed",
					label: "Santander"
				}
                
			];
           
           var juroscartao = 
            
            [			
				{
					value: 134.54,
					color: "#336699",
					highlight: "#ededed",
					label: "Caixa"
				},
				{
					value: 268.9,
					color: "#cdaf35",
					highlight: "#ededed",
					label: "Banco do Brasil"
				},
				{
					value: 430.06,
					color: "#443266",
					highlight: "#ededed",
					label: "Citibank"
				},
                {
					value: 433.08,
					color:"#F7464A",
					highlight: "#ededed",
					label: "Bradesco"
				},
				{
					value: 440.48,
					color: "#FD2A19",
					highlight: "#ededed",
					label: "HSBC"
				},
                {
					value: 495.57,
					color: "#A6002E",
					highlight: "#ededed",
					label: "Santander"
				},
                {
					value: 631.85,
					color: "#cc8b2f",
					highlight: "#ededed",
					label: "Itaú"
				}
                
			];
			window.onload = function(){
        var ctx1 = document.getElementById("especial").getContext("2d");
        var myPolarArea = new Chart(ctx1).PolarArea(jurosespecial, 
                {
					responsive:true,
                    animateScale: true,
                    segmentStrokeWidth : 5,
                    animationEasing : "southOutBounce",
                    showScale: true,
                    scaleLineWidth: 1,
                    scaleBeginAtZero: true,
                    scaleFontFamily: "'Monaco', 'Arvo', sans-serif",
                    scaleFontSize: 16,
                    tooltipFontFamily: "'Monaco', 'Arvo', sans-serif"
				});
        var ctx2 = document.getElementById("cartao").getContext("2d");
        var myPolarArea2 = new Chart(ctx2).PolarArea(juroscartao,
                {
					responsive:true,
                    animateScale: true,
                    segmentStrokeWidth : 5,
                    animationEasing : "southOutBounce",
                    showScale: true,
                    scaleLineWidth: 1,
                    scaleBeginAtZero: true,
                    scaleFontFamily: "'Monaco', 'Arvo', sans-serif",
                    scaleFontSize: 16,
                    tooltipFontFamily: "'Monaco', 'Arvo', sans-serif"
				});
                
                
};
	       </script>
           </div>
		
           <!--Mapa sobre juros no mundo-->
           
           <div class="container">
           <iframe width="100%" height="620" frameborder="0" seamless src="https://voltdatalab.cartodb.com/viz/3d1faf82-3663-11e5-a4e2-0e9d821ea90d/embed_map" allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe>
               </div>       
           
	</body>
</html>
