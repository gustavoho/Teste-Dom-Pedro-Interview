# Teste-Dom-Pedro-Interview

<P><h2>Configurações Iniciais</h2</P>

Criar a pasta node_modules na raiz do Projeto (./node_modules), dentro dela instalar os modulos do node.js executando no prompt de comandos o comando:<br><br> npm install -- save express@4.16.3 mysql@2.15.0 body-parser@1.18.2 socketio shortid

<P><h2>Configuração do banco de dados Mysql</h2</P>

<p>   
    mysqlConnection = mysql.createConnection({<br>
    host: 'localhost',<br>
    user: 'root',<br>
    password: '',<br>
    database: 'bd_dom_pedro_interview',<br>
    port: 3306,<br>
    });
</p>  
<P><h2>Executar o servidor node.js</h2</P>

No prompt de comandos ir para a raiz do projeto e digitar o comando: <br><br>
node server.js

<p>Abrir um navegador com link: http://localhost:3000/  para cadastrar uma pessoa e o email.</p>

<p>Para consultar informçõescadastradas no Banco de Dados Mysql utilizar o link: http://localhost:3000/ , onde será exibido um json com as informções do bd como: id, name, email e createAt <br> {"id":1,"name":"Gustavo Oliveira","email":"gustavoho8389@gmail.com","createdAt":"28/7/2020 às 2:37:31"}, </p> 
