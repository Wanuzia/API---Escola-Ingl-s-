 <p align='center'><a href="https://developer.mozilla.org/pt-BR/docs/Web/JavaScript" target="_blank"><img src="https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E" /></a>
   <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white" />
  <img src="https://img.shields.io/badge/npm-CB3837?style=for-the-badge&logo=npm&logoColor=white" />
 <img src="https://img.shields.io/badge/json-5E5C5C?style=for-the-badge&logo=json&logoColor=white" />
  <img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=Postman&logoColor=white" />
  <img src="https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white" />
  <img src="https://img.shields.io/badge/Visual_Studio_Code-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white" />
</p>
<h1 align='center'>API</h1><h2 align='center'>Escola de Inglês</h2>
Projeto inicializado seguindo passo a passo do Curso ORM com NodeJS API com Sequelize e MySQL - Semana 11 - Desenvolve GB.

<br>
<br>

:computer: Na continuação do projeto, após ter o CRUD básico feito e o sistema funcionando, (durante a Semana 12, seguindo orientações do curso ORM com NodeJS: avançando nas funcionalidades do Sequelize) foi implementada uma lista de funcionalidades solicitadas pelo cliente:

:heavy_check_mark: O cliente não gostaria que registros importantes do sistema, como as Pessoas, sejam apagados definitivamente do banco de dados.
<b>
 
:heavy_check_mark: Para deixar a interface mais limpa, o cliente gostaria que na lista de Pessoas, por padrão, fossem exibidos somente os usuários ativos.
 <br>

 :heavy_check_mark: Foram percebidas algumas falhas de validação dos formulários por parte do front-end, o que resultou em dados de email inválidos no banco. É desejável que essa validação não seja responsabilidade exclusiva do front.
 <br>
 
:heavy_check_mark: É importante poder consultar todas as matrículas confirmadas referentes a estudante X de forma rápida.
 <br>
 
:heavy_check_mark: O cliente gostaria de poder consultar as turmas abertas por intervalo de data, para não receber informações desnecessárias (como turmas antigas).
 <br>
 
:heavy_check_mark: O cliente quer poder consultar as matrículas por turma e saber quais delas estão lotadas, para organizar melhor as matrículas.
 <br>
 
:heavy_check_mark: O cliente gostaria que, uma vez que o cadastro de um estudante fosse desativado, todas as matrículas relativas a este estudante automaticamente passassem a constar como “canceladas”.
 <b>
  
Durante o projeto esses requisitos foram transformados em novas funcionalidades.


