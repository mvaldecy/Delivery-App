# Zé Biritis Delivery App

<p>
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/mvaldecy/Delivery-App?color=%2304D361">

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/mvaldecy/Delivery-App">
  
  <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/mvaldecy/Delivery-App">
    
  <img alt="License" src="https://img.shields.io/badge/license-MIT-brightgreen">
  
 ## :brazil: Português
  Esse foi o último projeto do módulo de Backend no curso de Desenvolvimento Web Full Stack da Trybe. <br>
  O desenvolvimento aconteceu em parceria com os amigos: <a href="https://github.com/IgorMarinhoArgollo">Igor Marinho Argollo</a>, <a href="https://github.com/paulomichael">Paulo Michael</a>, <a href="https://github.com/jose-cleiton">José Cleiton</a> e <a href="https://github.com/BaianorASR">Adison Reis</a>, utilizando Metodologias Ágeis(SCRUM) e Pair Programming.<br>
   O seu objetivo primário foi a elaboração completa de uma aplicação web, iniciando pela elaboração do banco de dados relacionais (MySQL), usando a ORM Sequeliza como ferramente auziliar, passando pela elaboração das rotas de criar, ler, atualizar e deletar do backend utilizando JavaScript com o auxílio do Express, e terminando na elaboração completa do frontend em React, também em JavaScript, utilizando o Redux, React Components.<br><br>
  
  
  ## Objetivos
  * Criar um banco de dados em MySQL com a ORM Sequelize para um aplicativo de delivery de bebidas contendo um banco de usuários, produtos, vendas e bancos intermediários;
  * Desenvolvimento do CRUD completo para as finalidades da aplicação;
  * Desenvolvimento de Middlewares de Erro e autenticação para garantir o bom funcionamento do backend;
  * Elaboração de página de login acessando o backend para validar o usuário e obter as informações importantes para o usuário;
  * Elaboração de uma página de produtos em que o usuário logado consegue adicionar itens ao carrinho e mostra o total parcial no canto inferior da página; 
  * Elaboração da página de checkout com confirmação de entrega de produto;
  * Elaboração de página de gestão de vendas para vendedores com confirmações de status; 
  * Elaboração de página de gestão de usuários para o administrador onde é possível cadastrar usuários com diferentes responsabilidades.<br><br>

  ## Live Link
  <a href="--------------URL da Página------------------" target="_blank">Zé Biritis Delivery App</a><br><br>
  
  ## Screenshot
  ![ScreenShot](./public/imagem.png)<br><br>
  
  ## Tecnologias usadas
  * MySQL
  * Sequelize
  * JavaScript
  * Express
  * Joi
  * Arquitetura MSC
  * Docker
  * React
  * React Router
  * React Components
  * Redux ToolKit
  <br><br>
  
  ## Como usar
  Acesse o site, <b>use "zebirita@email.com" como email e "$#zebirita#$" como senha para acessar como cliente, "fulana@deliveryapp.com" como email e "fulana@123" como senha ou "adm@deliveryapp.com" como email e "--adm2@21!!--" como senha para acessar como administrador</b>. Como cliente: navegue pela lista de produtos, adicione ao carrinho, clique sobre o valor total no canto inferior direito para ir para a página de checkout, preencha os dados, finalize o pedido e, ao receber, confirme a entrega clicando em "Entrega Realizada". Como Vendedor: acesse a sua conta se você será redirecionado para a página de gerenciamento dos pedidos, onde é possivel de clicar sobre os pedidos e abrir detalhes e alterar o status. Como administrador é possível se adicionar e remover usuários.<br><br>
  
  ### Criação do .env na pasta /src/back-end
    NODE_ENV=development
    API_PORT=3001
    MYSQL_HOST=localhost
    MYSQL_PORT=3306
    MYSQL_USER=root
    MYSQL_PASSWORD=senhaDoDB
    MYSQL_DB_NAME=delivery-app
    EVAL_ALWAYS_RESTORE_DEV_DB=true
      
  ## Rodar Localmente
  ### Requisitos:
   * Node v16
   * Google Chrome
    
  ### Clonar no seu computador (via SSH)
  No terminal:
  
    git clone git@github.com:mvaldecy/Delivery-App.git
    npm install
    cd backend/
    npm install
    cd ..
    cd frontend/
    npm install
    cd ..
    npm run db:reset 
    npm run dev
   <br>
  
  ## Como contribuir no projeto
  1. Faça um **fork** do projeto;
  2. Crie uma nova branch com as suas alterações: `git checkout -b my-feature`;
  3. Salve as alterações e crie uma mensagem de commit contando o que você fez: `git commit -m "feature: My new feature"`;
  4. Envie as suas alterações: `git push origin my-feature`;
  5. Abra o seu pull-request na página do GitHub.<br><br>
  
  
##  Autores
<table>
  <tr>
    <td align="center"><a href="https://www.linkedin.com/in/igormarinhoargollo/"><img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/85767736?s=96&v=4" width="100px;" alt=""/><br /><sub><b>Igor Marinho</b></sub></a></td>
    <td align="center"><a href="https://www.linkedin.com/in/marcos-valdecy-832149150/"><img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/87670939?s=40&v=4" width="100px;" alt="Marcos Valdecy"/><br /><sub><b>Marcos Valdecy</b></sub></a></td>
    <td align="center"><a href="https://www.linkedin.com/in/baianorasr/"><img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/86670849?v=4" width="100px;" alt="Adison Reis"/><br /><sub><b>Adison Reis</b></sub></a></td>
    <td align="center"><a href="https://www.linkedin.com/in/paulo-michael-schweigert-pereira/"><img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/237418?v=4" width="100px;" alt="Paulo Michael"/><br /><sub><b>Paulo Michael</b></sub></a></td>
    <td align="center"><a href="https://www.linkedin.com/in/jcleitonsantos/"><img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/69883217?v=4" width="100px;" alt="José Cleiton"/><br /><sub><b>José Cleiton</b></sub></a></td>
  </tr>
</table>

  ## Licença
  Esse projeto está sob a licença:
  <img alt="License" src="https://img.shields.io/badge/license-MIT-brightgreen"><br><br>
</details>

---------------------------------------------------------------------------------------------------------------------------------------------
##  :us: English

This was the last project of the Backend module in Trybe's Full Stack Web Development course. <br>
  The development took place in partnership with friends: <a href="https://github.com/IgorMarinhoArgollo">Igor Marinho Argollo</a>, <a href="https://github.com/paulomichael">Paulo Michael</a>, <a href="https://github.com/jose-cleiton">José Cleiton</a> and <a href="https://github.com/BaianorASR">Adison Reis< /a>, using Agile Methodologies (SCRUM) and Pair Programming.<br>
   Its primary objective was the complete elaboration of a web application, starting with the elaboration of the relational database (MySQL), using the ORM Sequeliza as an auxiliary tool, going through the elaboration of the routes to create, read, update and delete the backend using JavaScript. with the help of Express, and finishing in the complete elaboration of the frontend in React, also in JavaScript, using Redux, React Components.<br><br>

## My Goals
  * Create a MySQL database with ORM Sequelize for a beverage delivery application containing a database of users, products, sales and intermediary database;
  * Development of the complete CRUD for the purposes of the application;
  * Development of Error and Authentication Middlewares to ensure the proper functioning of the backend;
  * Preparation of login page accessing the backend to validate the user and obtain important information for the user;
  * Development of a products page where the logged in user can add items to the cart and shows the partial total in the lower corner of the page;
  * Development of the checkout page with product delivery confirmation;
  * Development of sales management page for sellers with status confirmations;
  * Creation of a user management page for the administrator where it is possible to register users with different responsibilities.<br><br>


## Live Link
  <a href="--------------URL da Página------------------" target="_blank">Zé Biritis Delivery App</a><br><br>
  
## Screenshot
  ![ScreenShot](./public/imagem.png)<br><br>

## Used Technologies
  * MySQL
  * Sequelize
  * JavaScript
  * Express
  * Joi
  * MSC Architecture
  * Docker
  * React
  * React Router
  * React Components
  * Redux ToolKit
  <br><br>

## How to use it
  Access the website, <b>use "zebirita@email.com" as email and "$#zebirita#$" as password to access as a customer, "fulana@deliveryapp.com" as email and "fulana@123" as password or "adm@deliveryapp.com" as email and "--adm2@21!!--" as password to login as administrator</b>. As a customer: browse the list of products, add to cart, click on the total amount in the lower right corner to go to the checkout page, fill in the details, finalize the order and, upon receipt, confirm delivery by clicking on "Delivery Made ". As a Seller: access your account and you will be redirected to the order management page, where you can click on the orders and open details and change the status. As an administrator it is possible to add and remove users.<br><br>
        
  ### Create .env on folder /src/back-end
    NODE_ENV=development
    API_PORT=3001
    MYSQL_HOST=localhost
    MYSQL_PORT=3306
    MYSQL_USER=root
    MYSQL_PASSWORD=senhaDoDB
    MYSQL_DB_NAME=delivery-app
    EVAL_ALWAYS_RESTORE_DEV_DB=true
  
  
## Run Locally
  ### Requirements:
   * Node v16
   * Google Chrome
    
  ### Cloning into your computer (via SSH)
  On terminal:

    git clone git@github.com:mvaldecy/Delivery-App.git
    npm install
    cd backend/
    npm install
    cd ..
    cd frontend/
    npm install
    cd ..
    npm run db:reset 
    npm run dev
<br><br>

## How to contribute on the project
  1. Make a **fork** of the project;
  2. Create a new branch with your changes: `git checkout -b my-feature`;
  3. Save your changes and create a commit message explaining what you have done: `git commit -m "feature: My new feature"`;
  4. Send your changes: `git push origin my-feature`;
  5. Open your pull-request on GitHub.<br><br>
  
  ##  Authors
<table>
  <tr>
    <td align="center"><a href="https://www.linkedin.com/in/igormarinhoargollo/"><img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/85767736?s=96&v=4" width="100px;" alt=""/><br /><sub><b>Igor Marinho</b></sub></a></td>
    <td align="center"><a href="https://www.linkedin.com/in/marcos-valdecy-832149150/"><img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/87670939?s=40&v=4" width="100px;" alt="Marcos Valdecy"/><br /><sub><b>Marcos Valdecy</b></sub></a></td>
    <td align="center"><a href="https://www.linkedin.com/in/baianorasr/"><img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/86670849?v=4" width="100px;" alt="Adison Reis"/><br /><sub><b>Adison Reis</b></sub></a></td>
    <td align="center"><a href="https://www.linkedin.com/in/paulo-michael-schweigert-pereira/"><img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/237418?v=4" width="100px;" alt="Paulo Michael"/><br /><sub><b>Paulo Michael</b></sub></a></td>
    <td align="center"><a href="https://www.linkedin.com/in/jcleitonsantos/"><img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/69883217?v=4" width="100px;" alt="José Cleiton"/><br /><sub><b>José Cleiton</b></sub></a></td>
  </tr>
</table>
  
## License
  This project is under license:
