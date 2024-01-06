# 19º Projeto: MySQL - All For One

<p align="center">
<img src="https://github.com/prtpj1/prtpj1/blob/main/Github%20Imgs/19%20-%20All%20For%20One.jpg" alt="Header" />
<hr/>
<p align="center">
<a href="#project-description">Project Description</a> •
<a href="#in-this-project-i-learned-and-put-into-practice">Learning</a> •
<a href="#according-to-the-project-requirements-designated-by-trybe-i-learned-how-to">Requirements</a> •
<a href="#stacks">Stacks</a> •
<a href="#how-to-run-the-application">How to run the application</a>
</p>
<hr/>
<p align="center">
<a href="#descrição-do-projeto">Descrição do Projeto</a> •
<a href="#nesse-projeto-aprendi-e-coloquei-em-prática">Aprendizado</a> •
<a href="#de-acordo-com-os-requisitos-do-projeto-designados-pela-trybe-aprendi-como">Requisitos</a> •
<a href="#tecnologias-utilizadas">Tecnologias Utilizadas</a> •
<a href="#como-rodar-a-aplicação">Rodar a Aplicação</a>
</p>
<hr/>

## Project Description
In this second BackEnd project, I put into practice what I learned about MySQL concepts through various challenges.

## In this project, I learned and put into practice:
- Manipulating a database using SQL codes

## According to the project requirements designated by Trybe, I learned how to:
- ✅ Display only the names of the products from the 'products' table
- ✅ Display the data from all columns of the 'products' table
- ✅ Write a query that displays the values of the column containing the primary key of the 'products' table
- ✅ Count how many records exist in the 'product_name' column of the 'products' table
- ✅ Create a query that displays the data of the 'products' table from the fourth record to the thirteenth
- ✅ Display the data from the 'products' table columns 'product_name' and 'id' in alphabetical order of names
- ✅ Show only the ids of the last 5 records from the 'products' table sorted by 'id'
- ✅ Create a query that returns three columns, respectively, with the names 'A', 'Trybe', and 'eh', and with values referring to the sum of '5 + 6', the string 'de', the sum of '2 + 8'
- ✅ Display all values in the 'notes' column of the 'purchase_orders' table that are not null
- ✅ Display all data from the 'purchase_orders' table in descending order sorted by 'created_by' where 'created_by' is greater than or equal to 3
- ✅ Show the results of the 'notes' column of the 'purchase_orders' table where its value of 'Purchase generated based on Order' is greater than or equal to 30 and less than or equal to 39
- ✅ Display the result of the 'submitted_date' column of the 'purchase_orders' table where the 'submitted_date' is April 26, 2006
- ✅ Show the result of the 'supplier_id' column of the 'purchase_orders' table where the 'supplier_id' is 1 or 3
- ✅ Display the results of the 'supplier_id' column of the 'purchase_orders' table where the 'supplier_id' is greater than or equal to 1 and less than or equal to 3
- ✅ Show only the hours, without the minutes and seconds, from the 'submitted_date' column of all records in the 'purchase_orders' table
- ✅ Display the results of the 'submitted_date' column of the 'purchase_orders' table that are between '2006-01-26 00:00:00' and '2006-03-31 23:59:59'
- ✅ Show the records from the 'id' and 'supplier_id' columns of the 'purchase_orders' table where the 'supplier_id' is 1, 3, 5, or 7
- ✅ Display all records from the 'purchase_orders' table that have the value in the 'supplier_id' column equal to 3 and the value in the 'status_id' column equal to 2
- ✅ Show the quantity of orders made in the 'orders' table by 'employee_id' equal to 5 or 6, and that were sent through the 'shipper_id' column equal to 2
- ✅ Add to the 'order_details' table a record with 'order_id': 69, 'product_id': 80, 'quantity': 15.0000, 'unit_price': 15.0000, 'discount': 0, 'status_id': 2, 'date_allocated': NULL, 'purchase_order_id': NULL, and 'inventory_id': 129
- ✅ Add with a single 'INSERT', two lines to the 'order_details' table with the same data from requirement 20
- ✅ Update the data in the 'discount' column of the 'order_details' table to 15
- ✅ Update the data in the 'discount' column of the 'order_details' table to 30, where the value in the 'unit_price' column is less than 10.0000
- ❌ Update the data in the 'discount' column of the 'order_details' table to 45, where the value in the 'unit_price' column is greater than 10.0000 and the id is a number between 30 and 40
- ❌ Delete all data in the 'unit_price' column of the 'order_details' table where the value is less than 10.0000
- ❌ Delete all data in the 'unit_price' column of the 'order_details' table where the value is greater than 10.0000
- ❌ Delete all data from the 'order_details' table
<hr/>

## Stacks
### BackEnd:
- MySQL
- Node.js

<a href="https://www.mysql.com/" target="_blank" rel="noreferrer"><img src="https://github.com/prtpj1/prtpj1/blob/main/Github Imgs/mySQL2.png" width="50" height="50" alt="MySQL Icon" /></a><a href="https://nodejs.org/en/" target="_blank" rel="noreferrer"><img src="https://github.com/prtpj1/prtpj1/blob/main/Github Imgs/NodeJS2.png" width="50" height="50" alt="NodeJS Icon" /></a>

## How to Run the Application?
- MySQL needs to be running on your machine
- ⚠️ If you are on Windows, stop the MySQL from Windows
- Clone the repository: <br>
`git clone git@github.com:prtpj1/project-mysql-all-for-one.git`
- Access the project folder: <br>
`cd project-mysql-all-for-one`
- Install dependencies: <br>
`npm install`
- Create and populate the database:
`mysql -u root -p northwind < northwind.sql` <br>
⚠️ Use your root user password from the installed distro <br>
- Execute the queries from each challenge file in the project folder within VSCode if you use a DB extension, such as "Database," or in the Database Management Program, such as "MySQL Workbench"
</br>
</br>
_*NOTE: If you encounter any difficulties with the instructions and want to provide feedback, send me a message*_
<hr/>

## Descrição do Projeto
Neste segundo projeto de BackEnd coloquei em prática o que aprendi sobre os conceitos de mySQL através de vários desafios.<br>

## Nesse projeto, aprendi e coloquei em prática:
- Manipular um banco de dados usando códigos SQL 

## De acordo com os requisitos do projeto designados pela Trybe aprendi como:
- ✅ Exibir apenas os nomes dos produtos da tabela 'products'
- ✅ Exibir os dados de todas as colunas da tabela 'products'
- ✅ Escrever uma query que exiba os valores da coluna que contém a primary key da tabela 'products'
- ✅ Contar quantos registros existem na coluna 'product_name' da tabela 'products'
- ✅ Montar uma query que exiba os dados da tabela 'products' a partir do quarto registro até o décimo terceiro
- ✅ Exibir os dados das colunas 'product_name' e 'id' da tabela 'products' de maneira que os resultados estejam em ordem alfabética dos nomes
- ✅ Mostrar apenas os ids dos 5 últimos registros da tabela 'products' ordenados por 'id'
- ✅ Fazer uma consulta que retorne três colunas, respectivamente, com os nomes 'A', 'Trybe' e 'eh', e com valores referentes à soma de '5 + 6', a string 'de', a soma de '2 + 8'
- ✅ Mostrar todos os valores da coluna 'notes' da tabela 'purchase_orders' que não são nulos
- ✅ Mostrar todos os dados da tabela 'purchase_orders' em ordem decrescente ordenados por 'created_by' em que o 'created_by' seja maior ou igual a 3
- ✅ Exibir os dados da coluna 'notes' da tabela 'purchase_orders' em que seu valor de 'Purchase generated based on Order' seja maior ou igual a 30 e menor ou igual a 39
- ✅ Mostrar os resultados da coluna 'submitted_date' da tabela 'purchase_orders' em que a 'submitted_date' seja do dia 26 de abril de 2006
- ✅ Mostrar o resultado da coluna 'supplier_id' da tabela 'purchase_orders' em que o 'supplier_id' seja 1 ou 3
- ✅ Mostrar os resultados da coluna 'supplier_id' da tabela 'purchase_orders' em que o 'supplier_id' seja maior ou igual a 1 e menor ou igual 3
- ✅ Mostrar somente as horas, sem os minutos e os segundos, da coluna 'submitted_date' de todos os registros da tabela 'purchase_orders'
- ✅ Exibir os resultados da coluna 'submitted_date' da tabela 'purchase_orders' que estão entre '2006-01-26 00:00:00' e '2006-03-31 23:59:59'
- ✅ Mostrar os registros das colunas 'id' e 'supplier_id' da tabela 'purchase_orders' em que os 'supplier_id' sejam tanto 1, ou 3, ou 5, ou 7
- ✅ Mostrar todos os registros da tabela 'purchase_orders' que têm o valor na coluna 'supplier_id' igual a 3 e o valor na coluna 'status_id' igual a 2
- ✅ Mostrar a quantidade de pedidos que foram feitos na tabela 'orders' pelo 'employee_id' igual a 5 ou 6, e que foram enviados através do método coluna 'shipper_id' igual a 2
- ✅ Adicionar à tabela 'order_details' um registro com 'order_id': 69, 'product_id': 80, 'quantity': 15.0000, 'unit_price': 15.0000, 'discount': 0, 'status_id': 2, 'date_allocated': NULL, 'purchase_order_id': NULL e 'inventory_id': 129
- ✅ Adicionar com um único 'INSERT', duas linhas à tabela 'order_details' com os mesmos dados do requisito 20
- ✅ Atualizar os dados na coluna 'discount' da tabela 'order_details' para 15
- ✅ Atualizar os dados da coluna 'discount' da tabela 'order_details' para 30, onde o valor na coluna 'unit_price' seja menor que 10.0000
- ❌ Atualizar os dados da coluna 'discount' da tabela 'order_details' para 45, onde o valor na coluna 'unit_price' seja maior que 10.0000 e o id seja um número entre 30 e 40
- ❌ Deletar todos os dados na coluna 'unit_price' da tabela 'order_details' em que o valor seja menor que 10.0000 
- ❌ Deletar todos os dados na coluna 'unit_price' da tabela 'order_details' em que o valor seja maior que 10.0000
- ❌ Deletar todos os dados da tabela 'order_details'
<hr/>

## Tecnologias Utilizadas
### BackEnd:
- MySQL
- Node.js

<a href="https://www.mysql.com/" target="_blank" rel="noreferrer"><img src="https://github.com/prtpj1/prtpj1/blob/main/Github Imgs/mySQL2.png" width="50" height="50" alt="MySQL Icon" /></a>
<a href="https://nodejs.org/en/" target="_blank" rel="noreferrer"><img src="https://github.com/prtpj1/prtpj1/blob/main/Github Imgs/NodeJS2.png" width="50" height="50" alt="NodeJS Icon" /></a>

## Como rodar a aplicação?
- O MySQL precisa estar rodando na sua máquina
- ⚠️ Se estiver no Windows, pare o MySQL do Windows
- Clone o repositório: <br>
`git clone git@github.com:prtpj1/project-mysql-all-for-one.git`
- Acesse a pasta do projeto: <br>
`cd project-mysql-all-for-one`
- Instale as dependências: <br>
`npm install`
- Crie e popule o banco de dados:
`mysql -u root -p northwind < northwind.sql` <br>
⚠️ Use o seu password de usuario root da distro instalada <br>
- Execute as queries de cada arquivo desafio na pasta do projeto dentro do proprio VSCode se você usar alguma extensão de DB como por exemplo a "Database" ou no programa Gerenciador de Banco de Dados como por exemplo o "MySQL Workbench"
</br>
</br>
_*OBS: Se tiver alguma dificuldade com as instruções e quiser dar um feedback me mande uma mensagem*_





