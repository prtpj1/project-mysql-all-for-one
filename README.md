# 19º Projeto: MySQL - All For One

<p align="center">
<img src="https://github.com/prtpj1/prtpj1/blob/main/Github%20Imgs/19%20-%20All%20For%20One.jpg" alt="Header" />
<hr/>

<p align="center">
<a href="#descrição-do-projeto">Descrição do Projeto</a> •
<a href="#nesse-projeto-aprendi-e-coloquei-em-prática">Aprendizado</a> •
<a href="#de-acordo-com-os-requisitos-do-projeto-designados-pela-trybe-aprendi-como">Requisitos</a> •
<a href="#tecnologias-utilizadas">Tecnologias Utilizadas</a> •
<a href="#como-rodar-a-aplicação">Rodar a Aplicação</a>
</p>
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
<br>
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





