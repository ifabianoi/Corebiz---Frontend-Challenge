<h1 align="center">
<img src="https://user-images.githubusercontent.com/1951762/134697029-92588ff8-da7f-4d6f-81e0-c5632923051c.jpg" title="CoreBiz leading the digital commerce evolution" />
</h1>


<h3 align="center">
  Corebiz - Frontend-Challenge
</h3>

<p align="center">
  <a href="#sobre o desafio">Sobre o desafio</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#projeto">Projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#%EF%B8%8Ffuncionalidades">Funcionalidades</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
</p>

## 👨🏻‍💻Sobre o desafio
Desenvolver uma página baseando-se no layout e APIs abaixo.
- Link do layout: https://www.figma.com/file/awhTJyKgrjEOqPHUrrFBv0/Corebiz---Frontend-Challenge
- Link das APIs: https://documenter.getpostman.com/view/1811817/Szzj8yAq?version=latest

### Passo 1
- Use a API de produtos para pegar os dados dos produtos e
construir a vitrine. (Pode usar o que achar melhor para isso. Ex: Axios, Fetch, XMLHttpRequest, etc)
- Ao clicar no botão “Comprar” deve ser incrementada a quantidade de itens no
carrinho.
- Ao atualizar a página, a quantidade de produtos no carrinho deve ser
preservada.

### Passo 2
- Crie validações para o form de contato. (Ex: se o e-mail for
inválido ou o nome vazio)
- Ao clicar em enviar com os campos validados, o form precisa ser disparado via javascript para a
API de newsletter seguindo as especificações da API.
## 🚀Tecnologias

- [HTML5](https://www.w3schools.com/html/)
- [CSS3](https://www.w3schools.com/css/)
- [Java Script](https://www.javascript.com)
- [React](https://reactjs.org)
- [Axios](https://www.npmjs.com/package/axios)
- [Webpack](https://webpack.js.org/)

## 💻Projeto

[Ver projeto na Netlify](https://ifabianoi-corebiz-ecommerce.netlify.app/)

### Executando o projeto localmente
### Requisitos
- [Git](https://git-scm.com/downloads)
- [Node.js](https://nodejs.org/en/download/)
- [NPM](https://yarnpkg.com/getting-started/install)

Clonar o repositório
```bash
git clone https://github.com/ifabianoi/Corebiz---Frontend-Challenge.git
```

Instalar as dependências
```bash
yarn install
```
ou
```bash
npm install
```

### Executando a aplicação
```bash
yarn start
```
ou
```bash
npm start
```

Acesse o endereço [http://localhost:5001](http://localhost:5001) para visualizar em seu navegador.

## ⚙️Funcionalidades
- [X] <b>Axios:</b> <i>Usado para o tratamento do consumo dos serviços da API </i>
- [X] <b>localStorage (@corebiz:products): </b><i>Inserir itens no carrinho de compras</i>
- [X] <b>localStorage (@corebiz:products): </b><i>Manter produtos ao atualizar a página</i>
- [X] <b>Yup e Unform: </b><i>Validação de Formulário</i>
- [X] <b>Axios: </b><i>Consumir API informada para envio de Leads</i>
- [X] <b>Webpack: </b><i>Automação de tarefas</i>
