# MyWebSite
A website personal created by Alison Soldado

<!DOCTYPE html>
<html language="pt-br">
	<head>
		<meta charset="utf-8"/>
		<meta name="Description" content="Esse website foi desenvolvido por Alison Soldado, com a intenção de expor um pouco sobre sua carreira acadêmica, profissional e pessoal"/>
		<meta name="Keywords" content="alison, soldado, index"/>
		<title>Alison Soldado</title>
		
		<link rel="icon" href="imagens/favicon1.png"/>
		<link rel="stylesheet" href="css/reset.css"/>		
		<link rel="stylesheet" href="css/site-final.css"/>

		<link rel="stylesheet" href="http://fonts.googleapis.com/css?family=Crimson+Text:400,400italic,600">
		<link rel="stylesheet" href="http://fonts.googleapis.com/css?family=Open+Sans+Condensed:700">
		<link rel="stylesheet" href="http://fonts.googleapis.com/css?family=Shadows+Into+Light">
	</head>
	<body>
		<header class="cabecalho backgroundcafe">
			<aside>
				<nav>
					<ul class="menu">
						<li><a href="#sobre-mim">Sobre Mim</a></li>
						<li><a href="#portfolio">Portfolio</a></li>
						<li><a href="#citacoes">Citações</a></li>
						<li><a href="#contato">Contato</a></li>
					</ul>
				</nav>			
			</aside>	
			
			<h1 class="alinhaTextoEsquerdaTitulo">Alison Soldado</h1>
			<p class="alinhaTextoEsquerda">
			Idade: 21 anos<br/>
			Estado Civil: Solteiro <br/>
			Ensino Superior: Universidade de Ribeirão Preto (UNAERP)<br/>
			Curso: Sistemas de Informação<br/>
			Cidade: Orlândia<br/>
			</p>
	
			<ul class="icones-redes-sociais alinhaTextoEsquerda">
				<li><a class="github" href="https://github.com/Alison-Soldado" target="_blank">Github</a>
				<li><a class="linkedin" href="https://br.linkedin.com/in/alisonsoldado" target="_blank">LinkedIn</a>
				<li><a class="twitter" href="https://twitter.com/AlisonSoldadoo" target="_blank">Twitter</a>
		</header>
		<main class="conteudo">
			<section class="secao-inicio borda-baixo">
				<h2 id="sobre-mim" class="subtitulo-texto">Sobre Mim</h2>
					<p>
					<img class="minha-foto imagem-sobre" src="imagens/eu.jpg" alt="Foto de Alison Soldado"></img>
					Cursou Sistemas de Informação pela Faculdade de Ituverava Dr. Francisco Maeda (2012 até 2014), conseguiu uma bolsa integral pelo programa PROUNI na Universidade de Ribeirão Preto (2014), onde posteriormente transferiu-se e estuda até no momento. Tem experiência na área de tecnologia, com ênfase em Hardware e desenvolvimento Web.
					</p>
					<p>
					No ambiente de trabalho procura comunicar-se com sua equipe quando surge alguma dúvida e também sempre tenta ajudar o próximo em caso de algum problema. Atualmente está procurando estágio remunerado na área de desenvolvimento mobile ou web e em seu tempo livre gosta de ler livros, assistir seriados e tocar violão. 
					</p>
			</section>
			<section class="secao-inicio borda-baixo">
				<article class="port">
				<h2 id="portfolio" class="subtitulo-texto">Trabalhos Acadêmicos</h2>
					<p>
					<img class="minha-foto imagem-portfolio01" src="imagens/Index.png" alt="Foto da página inicial do site sparta"></img>
				<h3 class="subtitulo-texto2">E-Commerce</h3>
					A avaliação final da disciplina era ter que desenvolver uma página web utilizando todos os ensinamentos que foi dado em sala de aula. Então foi decidido criar uma loja virtual chamada Sparta, com o objetivo de vender roupas, acessórios e armaduras medievais. O intuito do trabalho inicialmente era de desenvolver um e-commerce completo. Mas infelizmente devido ao tempo estipulado, optou-se em realizar o básico, para que o trabalho fosse entregue no prazo.
					</p>
				</article>
				<article class="port">	
					<p>
					<img class="minha-foto imagem-portfolio02" src="imagens/apppizza.png" alt="Foto da tela de login do aplicativo PizzaDelivery"></img>
				<h3 class="subtitulo-texto2">Aplicativo</h3>					
					A avaliação parcial e final da disciplina era ter que desenvolver um aplicativo para uma pizzaria. Então foi decidido elaborar um aplicativo de delivery, onde o usuário fazia o cadastro e login no mesmo. Depois era mostrado uma lista com as pizzas disponíveis, para que ele pudesse escolher a pizza que desejava e depois efetuar a compra (com cartão ou em dinheiro), posteriormente a pizza era entregue no endereço mencionado no cadastro.
					</p>
				</article>
			</section>
	
			<section class="secao-inicio borda-baixo">
				<h2 id="citacoes" class="subtitulo-texto">Citações</h2>
				<bloquote tabindex="1">
				<p>
				Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.
				</p>
				<cite>Ator</cite>
				</bloquote>
				<bloquote tabindex="1">
				<p>
				Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.
				</p>
				<cite>Ator</cite>
				</bloquote>
			</section>

			<section class="secao-inicio contato">
				<h2 id="contato" class="subtitulo-texto">Contato</h2>
				<form>
					<fieldset>
						<legend>Preencha com seus dados:</legend>
						<label for="nome">
							Nome:
							<input type="text" title="Preencha somente com letras" id="nome" placeholder="Digite seu nome aqui" name="nome" required/>
						</label>
						<label for="email">
							Email:
							<input type="email" title="Preencha com seu email" id="email" placeholder="Digite seu email aqui" required name="email"/>
						</label>
					</fieldset>
					<fieldset>
						<legend>Assunto</legend>
						<label>
							<select>
								<option value="blog">Blog</option>
								<option value="servico">Serviço</option>
								<option value="outro">Outro</option>
							</select>
						</label>
					</fieldset>
					<fieldset>
						<label for="mensagem">Mensagem:</label>
						<textarea name="msg" id="mensagem" cols="60" rows="10" placeholder="Digite sua mensagem aqui"></textarea>
						<button type="submit">Enviar mensagem</button>
					</fieldset>
				</form>
			</section>
		</main>
		<footer class="rodape">
			&copy; Alison Soldado 2015
		</footer>
	</body>
</html>
