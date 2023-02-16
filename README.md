# JOGO DA FORCA COM O AMBIENTE DE EXECUÇÃO DO NODE.JS

1. [Descrição](#descricao)
2. [Instalação e Execução](#insandexec)
3. [Regras](#regras)
4. [Como jogar](#jogar)
5. [Creditos](#credits)
6. [Licença](#licenca)


<hr>

<div id="descricao">
<h2>1. Descrição </h2>
<p>&nbsp&nbsp&nbsp&nbsp Olá! Este é um Mini Jogo da Forca desenvolvido por mim, <a href="https://www.linkedin.com/in/franck-allyson-da-silva-rocha-7b9866229/">Franck Allyson da Silva Rocha</a>  ! <br>
&nbsp&nbsp&nbsp&nbsp A disciplina de WEB solicitou este jogo com a ideia de exercitar os conhecimentos no ambiente de execução do node.js!</p>
<dl>
  <dt><h3>1.1. O que a Aplicação Faz</h3></dt>
    <dd> Este Jogo visa entreter o usuário através de uma espécie de advinhação, ele sorteia uma palavra dentro de um conjunto de arrays <br>
    e o usuário deverá adivinhar qual a palavra sem esgotar as suas tentativas. Em cada tentativa é mostrado como está o andamento do jogo: <br>
    Acertos < - > Erros < - > Tentativas Restantes < - > Lacunas a serem preenchidas < - > Boneco sumindo com base nas tentativas restantes</dd>

  <dt><h3>1.2. Tecnologias Utilizadas</h3></dt>
    <dd> Utilizei o <img src="https://img.shields.io/badge/node-v18.14.0-blue"> para o executar o ambiente de execução no terminal.</dd>
    <dd> Utilizei o <img src="https://img.shields.io/badge/readline--sync-1.4.10-red"> para receber um input do usuário no terminal.</dd>

  <dt><h3>1.3. Desafios Encontrados</h3></dt>
    <dd>Para a execução deste execício não tive dificuldades na lógica de programação. <br>O principal desafio era aprender a usar o ambiente de execução node e ele 
    demonstrou ser bastante simples. <br>Faltou malícia para entender como receber dados do usuário, pois acabei esquecendo de instalar o package e sempre dava erro.<br> </dd>
</dl>
</div>

<hr>

<div id="insandexec">
<h2>2. Instalação e Execução </h2>
<p>&nbsp&nbsp&nbsp&nbsp Você terá que instalar o ambiente de execução node para executar este jogo, os demais packages utilizados já estão importados para este &nbsp&nbsp&nbsp&nbsp projeto e você não precisará fazer uma instalação.</p>
<dl>
  <dt><h3>2.1. O que instalar?</h3></dt>
    <dd>Instale o Node.Js na sua máquina: <a href="https://nodejs.org/pt-br/">Clique Aqui!</a></dd>
    <dd>Após dar um Fork e um Clone do projeto na sua máquina, não é necessário instalar mais nada!</dd>

  <dt><h3>2.2. Como executar?</h3></dt>
    <dd>Muito Simples! Já deixamos tudo pronto para você iniciar a execução do Game! Não se preocupe em instalar nenhum outro package além do Node.</dd>
    <dd>Para iniciar, basta abrir o diretório clonado no terminal de comando e digitar o código logo abaixo.</dd>
</dl>
</div>

~~~
npm start
~~~

<hr>

<div id="regras">
<h2>3. Regras do Jogo</h2>
<p>&nbsp&nbsp&nbsp&nbsp A ideia do jogo é representar a realidade, então as regras se assemelham ás regras do jogo da realidade. </p>
<dl>
  <dt><h3>3.1. Você possui 5 vidas.</h3></dt>
  <dt><h3>3.2. A cada chance você pode escolher 1 letra.</h3></dt>
  <dt><h3>3.3. Se a letra for correta a palavra é preenchida, caso contrário, você perderá uma vida.</h3></dt>
  <dt><h3>3.4. Se a palavra inteira for preenchida, você vence.</h3></dt>
  <dt><h3>3.5. Se suas vidas acabarem, você perde.</h3></dt>
  <dt><h3>3.6. VocÊ não pode digitar a mesma letra 2 vezes.</h3></dt>
</dl>
</div>

<hr>

<div id="jogar">
<h2>4. Como jogar</h2>
<p>&nbsp&nbsp&nbsp&nbsp Este jogo é muito intuitivo, após dar o comando para executar mencionado anteriormente ( <code>npm start</code> ), basta observar a dica, escolher a &nbsp&nbsp&nbsp&nbsp letra e pressionar enter. </p>
<dl>
  <dt><h3>4.1. Visualize o HUD </h3></dt>
    <dd>Ele te mostrará: Dica, Chances restantes, Tentativa de letras erradas, lacunas a serem preenchidas e o boneco sendo eliminado a medida que você erre.</dd>
  <dt><h3>4.2. Escolha uma letra</h3></dt>
    <dd>Você pode escolher qualquer uma das letras do teclado, espaços serão mostrados no HUD, então use-os ao seu favor.</dd>
  <dt><h3>4.3. Continue até ganhar ou perder</h3></dt>
    <dd>Escolhas as letras até finalmente acertar a palavra ou acabar as suas chances.</dd>
  <dt><h3>4.4. Decida se quer jogar novamente</h3></dt>
    <dd>Assim que finalizar, o programa irá te perguntar se deseja jogar novamente, basta digitar S ou N. </dd>
</dl>
</div>
      
<hr>

<div id="credits">
<h2>5. Créditos</h2>
<p>&nbsp&nbsp&nbsp&nbsp Abaixo irei listar alguns links que utilizei para realizar a atividade.</p>
<dl>
  <dt><h3>5.1. <a href="https://nodejs.org/pt-br/docs/"> Documentação Node</a></h3></dt>
  <dt><h3>5.2. <a href="https://www.youtube.com/watch?v=BKbh3-30LCk&ab_channel=Rog%C3%A9rioCaetano">NodeJs - Entrada de dados com readlineSync</a></h3></dt>
  <dt><h3>5.1. <a href="https://docs.npmjs.com/cli/v6/commands/npm-start">Documentação Npm focada no comando Start</a></h3></dt>
</dl>
</div>
      
<hr>

<div id="licenca">
<h2>6. Licenças</h2>
<dl>
  <dt><h3>6.1. Licença do Projeto Node</h3></dt>
    <dd>ISC</dd>
  
  <dt><h3>6.2. Licença do GitHub</h3></dt>
    <dd><a href="https://github.com/franckallyson/node-jogo-da-forca/blob/main/LICENSE">GPL - 3.0</a></dd>
</dl>
</div>

