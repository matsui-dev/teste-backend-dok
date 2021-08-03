<h1>Teste Back-end DOK Despachante</h1>
<p>A ideia deste teste é ajudar avaliar melhor as suas habilidades para a vaga de desenvolvedor, em vários níveis de experiência.</p>
<p>Este teste deve ser feito por você sozinho, no seu próprio tempo.</p>

<h2>Instruções de entrega</h2>
<p>Inicialize um novo repositório em seu Github, vá adicionando os commits quando achar necessário e quando terminado envie o link do repositório para o responsável do teste que entrou em contato com você.</p>

<h2>Descrição do projeto</h2>
<p>Implemente um CRUD de usuários utilizando o framework Laravel.</p>
<p>Nesse CRUD os usuários também poderão cadastrar e gerenciar seus veículos.</p>

<h2>Implementação</h2>
<p>Você deve inicializar um projeto Laravel contendo as Models, Views, Controllers, Migrations necessários.</p>
<p>Você só pode usar os padrões de linguagens e bibliotecas open-source.</p>
<p>Trate o código como nível de código para produção</p>

<p>Seu projeto DEVE possuir as seguintes funçōes se o usuário NÃO estiver autenticado:</p>
<ol>
	<li>Cadastrar usuário;</li>
	<li>Realizar Login.</li>
</ol>

<p>Seu projeto DEVE possuir as seguintes funçōes se o usuário estiver autenticado:</p>
<ol>
	<li>Atualizar usuário;</li>
	<li>Deletar usuário;</li>
	<li>Listar usuários;</li>
	<li>Adicionar veículo para o usuário autenticado;</li>
	<li>Listar os veículos de todos os usuários;</li>
	<li>Atualizar os veículos do usuário autenticado;</li>
	<li>Deletar os veículos do usuário autenticado.</li>
</ol>

<p>Sua tabela de usuarios deverá ter no mínimo as seguintes colunas:</p>
<ol>
	<li>Nome;</li>
	<li>Email;</li>
	<li>Senha.</li>
</ol>

<p>Sua tabela de veiculos deverá ter no mínimo as seguintes colunas:</p>
<ol>
	<li>Placa;</li>
	<li>Modelo;</li>
	<li>Cor;</li>
	<li>Tipo ('carro', 'moto');</li>
</ol>

<p>Deve haver um relacionamento da tabela usuarios para a veiculos de 1:N</p>

<p>Outros requisitos:</p>
<ol>
	<li>Todas as requisiçōes POST deverão ser feitas via js, seja por ajax, fetch ou axios;</li>
	<li>Só poderão ser salvos dados na coluna 'placa' da tabela 'veiculos' que sigam a seguinte o seguinte formato:</li>
	<ol>
		<li>AAA0048</li>
		<li>AAA9A35</li>
	</ol>
</ol>

<h2>Avaliação</h2>
<p>Seu projeto será avaliado pelos seguintes critérios:</p>
<ol>
	<li>Você preencheu os requerimentos básicos do projeto?</li>
	<li>Você seguiu com precisão as especificações do projeto?</li>
	<li>Qualidade do código em si, como está estruturado e como cumpre as boas práticas modernas;</li>
	<li>Familiaridade com as bibliotecas padrão das linguagens utilizadas e outros pacotes;</li>
	<li>Organização;</li>
	<li>Familiaridade com git.</li>
</ol>

<p>HTML e CSS não serão avaliados</p>

<p>Vamos ler seu código e testar. Invista o tempo necessário para fazer um desafio que demonstra o resumo das suas capacidades técnicas.</p>

<p>Obrigado e boa sorte!</p>
