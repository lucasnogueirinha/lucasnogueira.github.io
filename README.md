<!DOCTYPE html>
<html>
<head>
<link href="https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,400;0,700;1,500&display=swap" rel="stylesheet">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<style type="text/css">
	body{font-family: 'Roboto', sans-serif;}

	.button {
  background-color: #4CAF50; /* Green */
  border: none;
  color: white;
  padding: 15px 32px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 36px;
  margin: auto;
  display: block;
  border-radius: 10px

}

.button1 {background-color: #4CAF50;} /* Green */

h1 {text-align: center}

#footer {
	position: fixed;
	bottom: 10px;
	font-style: italic;
	font-size: 14px;
	text-align: center;
	width: 100%
}
</style>
</head>
<body>
<h1>Acesse a matéria pelo botão abaixo!</h1>
<button class="button" onclick="go('https://google.com.br')"><strong>Ver Matéria</strong></button>

<div id="footer">CNPJ: 17.478.875/0007-75</div>

<script type="text/javascript">
function go(url){
	window.location.href=url
}
</script>
</body>
</html>
