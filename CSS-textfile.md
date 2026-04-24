CSS

px ou rem para unidade de medida
pixel é fixa
rem não é
geralmente usa e use rem

pra pegar fonte: fonts.google
clica na que quer e get embed code
pra usar no css @import
pra isur no html <link>
	dai depois de importar fica escrito em baixo (na página do fonts.google)
	.lato-regular{
		font-family: "Lato", sans-serif;
		font-weight: 100;	(negrito vêm aqui (aumentar numero)
		font-style: normal; 	(itálico vêm aqui)

* (tudo)
Escrito -> padding -> border -> margin
box-sizing: border-box (o texto acompanha o box)


head (head)



body (body){
background-color:hexadecimal; 	(cor do bg)
color:hexadecimal ;		(cor das linhas)
text-align: center;		(alinha no centro)
}

	header{
	padding: tamanho;
	background-color: hex;  (fica só no header)
	text-align: local; 	(alinha)
	}

	main{
	padding: etc;
	display: flex; 		(deixa o display como ta na identação do index, no caso na horizontal)
	flex-direction: column; (isso faz o display:flex ficar em coluna como tava)
	gap: tamanho; 		(espaçamento)
	}
	
	section (só nas sections dai){
	display: flex;
	flex-direciton:column;
	}

	h2 (para cada subtítulo){
	padding:tamanho;
	color:hex;
	}
	
	input[type="tipo (radio, checkbox etc)], [type="checkbox"]{
	accent-color: hex;
	}

	input[type="text"], [type="password"], [type="date"], [type="email"]{
	width: tamanho horizontal;
	padding: tamanho;
	border: 2px solid hex;
	border: 5px; (deixa meio arredondado)
	background-color: transparent;
	}

	pra mudar subelementos tipo o placeholder que fica dentro do input 
	input::subelemento --> input::placeholder (exemplo)
	input::placeholder{
	color: hex
	}

	select{
	cursor: pointer;	(mostra que da pra clicar mudando o cursor)
	backgorund-color: hex;
	color: hex;
	border-radius: 5px;
	border: none;
	outline: none;
	}

	img{
	width: tamanho;
	}

	table{
	width:100%;
	border-collapse: colapse; (tira a borda 3D que tava)
	}

	th{
	background-color: hex;
	color: hex;
	}

	td{
	background-color: hex;
	color: hex;
	border: tamanho linha continua hex;
	text-align: center;
	}

	tfoot td{	(td descendente do tfoot)
	background-color: hex;
	color: hex;
	font-weight: bold;
	}

	details{
	background-color: hex;
	border-radius: tamanho;
	padding: tamanho;
	}

	summary{
	color: hex;
	margin: tamanho;
	cursor: pointer;
	}

	ul{
	margin-left: tamanho;
	}

	li{
	padding: tamanho;
	}

	fieldset{
	border: tamanho solid hex;
	border-radius: tamanho;
	padding: tamanho;
	}

	fieldset legends{
	color: hex;
	padding:0 0.5;	 (0 - horizontal ; 0.5 - vertical)
	}

	textarea{
	background-color: hex;
	outline: none;
	border-radius: tamanho;
	border: tamanho solid hex;
	}
	
	button{
	background-color: hex;
	border: tamanho;
	padding: tamanho;
	color: hex;
	border-radius: tamanho;
	cursor: pointer;
	}

fotter
A gente vai mudar o parágrafo só do fotter, dai pra não ficar indo lá no html e mudar na linha ou ir pro footer -> p, a gente defini uma classe no html pro parágrafo do footer dentro do <p>
<p class="paragrafo-footer> parágrafo </p>

dai no arquivo do css a gente usa 
.paragrafo-footer

pode ser por id tmb mas dai precisa colocar um id diferente para cada item diferente já que ele é um indentificador único
#paragrafo-footer

footer a{
	text decoration: none;	(tira a decoração do texto, sublinhado por exemplo)
}





