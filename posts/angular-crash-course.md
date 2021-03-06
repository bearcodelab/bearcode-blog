---
title: 'Angular Crash Course'
date: 'March 5, 2021'
tag: 'Angular'
excerpt: 'Contrary to popular belief, Lorem Ipsum is not simply random text. It has roots in a piece of classical Latin literature from 45 BC...'
cover_image: '/images/posts/angular.png'
time: '2 min'
---

Como é definido pelo Facebook, React é “uma biblioteca JavaScript declarativa, eficiente e flexível para a criação de interfaces de usuário (UI)”.

<br />

Foi criado pelo Instagram antes de ser comprado pelo Facebook. React.js está sendo muito utilizado no mercado Frontend, e é utilizado por grandes empresas, como por exemplo: Facebook, Instagram, AirBnB, Yahoo, Discord etc.

<br />

React permite a criação de componentes encapsulados que gerenciam seus próprios estados, e quando se conectam com outros componentes, criam interfaces de usuário (UIs) complexas, com uma sintaxe declarativa e simples facilitando a manutenção do código, formando assim um dos seus maiores benefícios.

<br />
<br />

# Criando um projeto

<br />

Primeiramente, você vai precisar ter o <a target="_blank" rel="noopener oreferrer" href="https://nodejs.org/en/">Node.js</a> instalado no seu computador.

<br />

Com o Node.js já instalado, nós precisaremos executar dentro do terminal o comando abaixo:

<br />

<div class="codeContainer">
  <p><span class="blue">npx</span> create-react-app hello-world</p>

  <br />

  <p class="comment"> // Ou </p>

  <br />

  <p><span class="blue">yarn</span> create react-app hello-world &nbsp;<span class="comment">// É preciso ter o Yarn instalado</span></p>
</div>

<br />
<br />

Após a instalação, você pode executar o comando:

<br />

<div class="codeContainer">
  <p><span class="blue">npm</span> start<p>

  <br />

  <p class="comment">// Ou</p>

  <br />

  <p><span class="blue">yarn</span> start &nbsp;<span class="comment">// É preciso ter o Yarn instalado</span></p>
</div>

<br />
<br />

Após isso, acesse no seu navegador o endereço: <a target="_blank" rel="noopener oreferrer" href="http://localhost:3000/">localhost:3000</a>, ao carregar, você verá a página de boas-vindas, criada pelo próprio React.js.

<br />
<br />

# Pastas e Arquivos

<br />

- node_modules: onde estão instaladas todas as dependências do projeto;
- public: armazena o arquivo HTML que irá renderizar a página;
- src: aqui, é onde você irá programar a sua aplicação;
  - index.js: arquivo que vai injetar o Javascript dentro do arquivo index.html, para apresentar para o usuário;
  - App.js: esse é o arquivo que envia os componentes para o index.js.

- .gitignore: define os arquivos que serão ignorados pelo git;
- package.json: apresenta detalhes do projeto, como por exemplo: nome, descrição do projeto, versões, dependências de desenvolvimento e de produção etc;
- readme.md: arquivo para a descrição detalhada do projeto.

<br />
<br />

## Limpando o código

<br />

Podemos deletar todos os arquivos que estão dentro da pasta src, menos o App.js e o index.js.

<br />

No index.js delete a referência do index.css e do registerServiceWorker.

<br />

No App.js delete a referência do logo e do app.css e todo o corpo dentro da primeira div.

<br />

Feito isso a aplicação voltará a funcionar novamente, só que agora teremos uma página em branco.

<br />
<br />

# Hello World 🖐🏼

<br />

Dentro do arquivo App.js, adicione o seguinte código, para você dar o seu primeiro e famoso "Hello World" dentro do React.js

<br />

<div class="codeContainer">

  <span class="pink">``import``</span> ``React`` <span class="pink">``from``</span> <span class="yellow">``'react'``</span>``;``

  <br />

  <span class="pink">``function``</span> <span class="purple">``App``</span> <span class="bracket-orange">``() {``</span>
  <br />
    &nbsp;&nbsp;&nbsp; <span class="pink">``return``</span> ``<``<span class="pink">``h1``</span>``>Hello World</``<span class="pink">``h1``</span>``>;``
  <br />
  <span class="bracket-orange">``}``</span>

  <br />

  <span class="pink">``export default``</span> <span class="purple">``App``</span>``;``

</div>

<br />
<br />

<hr />

Muito obrigado por ter lido! Agora você aprendeu o início de como usar React.js. Caso haja alguma outra dúvida, verifique a documentação do <a target="_blank" rel="noopener oreferrer" href="https://reactjs.org/">React.js</a>, ela me ajudou muito a escrever esse poste. Obrigado, e até a próxima!!!

