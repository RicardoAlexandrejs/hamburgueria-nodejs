<h1>Aplicação Hamburgueria em NODE.js 💻</h1>
Desafio proposto no curso Fullstack DEVCLUB:<br>
https://github.com/rodolfomori/desafio-node-1/blob/master/README.md
<hr>
<p>Este projeto consiste na criação de um CRUD (Create, Read, Update and Delete) com o objetivo de usar o framework Express e um array para armazenar os dados dos pedidos. 
  Neste exemplo, usaremos um array chamado pedidos (ORDERS) para armazenar os pedidos, onde cada pedido é representado como um objeto com as propriedades order, clientName, price e status.</p>
<hr>
<strong>CRUD é um acrônimo em inglês que representa as quatro operações básicas utilizadas em sistemas de gerenciamento de banco de dados relacionais. Cada letra representa uma operação:</strong>
<br><br>
<li>Create ➡ POST</li>
<li>Read ➡ GET</li>
<li>Update ➡ PUT</li>
<li>Delete ➡ DELETE</li>
<br>
Create (Criar): Refere-se à operação de criar novos registros ou entidades no banco de dados.<br>
Read (Ler): Refere-se à operação de ler ou recuperar informações existentes do banco de dados.<br>
Update (Atualizar): Refere-se à operação de atualizar informações existentes no banco de dados, como modificar um registro ou uma entidade já existente.<br>
Delete (Excluir): Refere-se à operação de excluir registros ou entidades do banco de dados.<br>
<br>
Essas quatro operações formam a base para a manipulação de dados em sistemas de gerenciamento de banco de dados, e são comumente utilizadas em aplicações e sistemas que lidam com armazenamento e manipulação de informações.
<hr>
<h3><p>Utilizado para o desenvolvimento da primeira aplicação:</p></h3>
<table>
  <tr align="center">
    <td><img src = "https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E" alt = "javascript"></td>
    <td><img src = "https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white" alt = "node"></td>
    <td><img src = "https://img.shields.io/badge/Express.js-404D59?style=for-the-badge" alt = "express"></td>
    <td><img src = "https://img.shields.io/badge/Insomnia-5849be?style=for-the-badge&logo=Insomnia&logoColor=white" alt = "insomnia"></td>
    
  </tr>
  <tr>
     <td>Arquivo em <br>JavaScript.</td>
    <td>Ambiente de <br>execução<br> JavaScript.</td>
    <td>framework -<br> fornece um conjunto robusto de <br>recursos para aplicativos web e móvel.</td>
    <td>framework - <br> para Testar as rotas criadas<br> e demonstrar do lado do cliente.</td>
   
  </tr>
</table>
<hr>

<h1>Start / Inicialização 💻</h1>
## <h4>Instalação</h4>

* Clone o repositório: `git clone [https://github.com/RicardoAlexandrejs/hamburgueria-nodejs]`
* Ou baixe os arquivos para seu Desktop
* Acesse o diretório do projeto: `hamburgueria-nodejs`
* Instale as dependências: `npm install`
* Inicie o servidor: `npm run dev` - Foi inserido um script no package.json para utilizar o nodemon <h6>( O nodemon é um utilitário que monitora as mudanças nos arquivos do seu projeto e reinicia automaticamente o servidor Node. js quando necessário. Assim, você não precisa parar e iniciar o servidor manualmente a cada modificação)</h6>
  <br>
* Crie as rotas no insomnia como mostrado abaixo:
  
![insomnia-hamburgueria](https://github.com/RicardoAlexandrejs/hamburgueria-nodejs/assets/158041416/fdb49ca0-063a-418d-b920-220357a41680)

  <br>
* Crie alguns pedidos na rota de POST (create order): `Alterando os valores e clique no botão SEND (enviar)`

![insomnia-hamburgueria-post](https://github.com/RicardoAlexandrejs/hamburgueria-nodejs/assets/158041416/e4f11340-508a-40aa-9f69-377bc16ffb9b)


* Após a criação acesse a rota de GET (order) e clique no botão SEND (enviar) para visualizar os pedidos criados:
![insomnia-hamburgueria-get](https://github.com/RicardoAlexandrejs/hamburgueria-nodejs/assets/158041416/99312810-7bb6-4604-bace-c14cf2194a1e)


* Para atualizar alguma informação copie um ID gerado na rota GET e depois acesse a rota de PUT (update order):<br>
01 - cole o ID copiado no endereço da rota.<br>
02 - Digita as novas informações para atualizar<br>
e clique no botão botão SEND (enviar) para visualizar o pedido atualizado<br>

![insomnia-hamburgueria-update](https://github.com/RicardoAlexandrejs/hamburgueria-nodejs/assets/158041416/a2a57eae-4ded-45a0-aec9-18ffd2d12510)

* Para Deletar alguma informação copie um ID gerado na rota GET e depois acesse a rota de DEL(delete):<br>
01 - cole o ID copiado no endereço da rota.<br>
e clique no botão botão SEND (enviar) para deletar o usuário <br>
02 - volte na rota de GET(users) clique em enviar e confirme se o usuário foi deletado.

![insomnia-hamburgueria-delete](https://github.com/RicardoAlexandrejs/hamburgueria-nodejs/assets/158041416/9cf6f2c4-ef19-444a-aed7-f06264f34fc5)

* Para fazer uma busca por pedido (order) copie um ID gerado na rota GET e depois acesse a rota de GET (Search order):<br>
01 - cole o ID copiado no endereço da rota.<br>
e clique no botão botão SEND (enviar) para visualizar o pedido pesquisado<br>

![insomnia-hamburgueria-get-search](https://github.com/RicardoAlexandrejs/hamburgueria-nodejs/assets/158041416/bd2eed70-e112-46a7-b8b0-88a80a877f2e)

<hr>
Obrigado por visualizar até aqui!!!

## <h4>About / Quem sou</h4>

Ricardo Alexandre js - https://github.com/RicardoAlexandrejs
