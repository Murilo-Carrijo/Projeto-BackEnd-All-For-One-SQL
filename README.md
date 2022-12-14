# All For One!

#### Linguagens utilizadas

    * SQL

---

## Descrição

Temos, neste projeto, uma série de comandos com diferentes níveis de complexidade que devem ser resolvidos cada um em seu arquivo próprio. As habilidade utilizadas nesse projeto foram:

* Entender o que são bancos de dados

* Entender como a linguagem de consulta estruturada (SQL) é usada

* Compreender como as tabelas se encaixam no conceito de banco de dados

* Montar um ambiente de desenvolvimento local para praticar SQL

* Entender como usar o MySQL Workbench

* Compreender o que é uma query SQL e quais são seus tipos de comando

* Gerar valores com `SELECT`

* Selecionar colunas individualmente com `SELECT`

* Renomear e gerar colunas em uma consulta com `AS`

* Concatenar colunas e valores com `CONCAT`

* Remover dados duplicados em uma consulta com `DISTINCT`

* Contar a quantidade de resultados em uma consulta com `COUNT`

* Limitar a quantidade de resultados em uma consulta com `LIMIT`

* Pular resultados em uma consulta com `OFFSET`

* Ordernar os resultados de uma consulta com `ORDER BY`

* Filtrar resultados de consultas com o `WHERE`

* Utilizar operadores booleanos e relacionais em consultas

* Criar consultas mais dinâmicas e maleáveis com `LIKE`

* Fazer consultas que englobam uma faixa de resultados com `IN` e `BETWEEN`

* Encontrar e separar resultados que incluem datas.

* Inserir dados em tabelas com `INSERT`

* Atualizar dados em tabelas com `UPDATE`

* Apagar dados em tabelas com `DELETE`


---

## Como rodar o projeto localmente

1. Clone o repositório
  * `git@github.com:Murilo-Carrijo/Projeto-BackEnd-All-For-One-SQL.git`
  * Entre na pasta do repositório que você acabou de clonar:
    * `cd Projeto-BackEnd-All-For-One-SQL`

---

## Desenvolvimento

O projeto foi realizado durante o curso da Trybe e os seguintes requisitos precisariam ser cumpridos: 

  - [X]  1 - Exiba apenas os nomes dos produtos da tabela 'products'
  
  - [X]  2 - _xiba os dados de todas as colunas da tabela 'products'
  
  - [X]  3 - Escreva uma query que exiba os valores da coluna que contém a primary key da tabela 'products'
  
  - [X]  4 - Conte quantos registros existem na coluna 'product_name' da tabela 'products'
  
  - [X]  5 - Monte uma query que exiba os dados da tabela 'products' a partir do quarto registro até o décimo terceiro
  
  - [X]  6 - Exiba os dados das colunas 'product_name' e 'id' da tabela 'products' de maneira que os resultados estejam em ordem alfabética dos nomes
  
  - [X]  7 - Mostre apenas os ids dos 5 últimos registros da tabela 'products' ordenados por 'id'
  
  - [X]  8 - Faça uma consulta que retorne três colunas, respectivamente, com os nomes 'A', 'Trybe' e 'eh', e com valores referentes a soma de '5 + 6', a string 'de', a soma de '2 + 8'

  - [X]  9 - Mostre todos os valores da coluna 'notes' da tabela 'purchase_orders' que não são nulos

  - [X]  10 - Mostre todos os dados da tabela 'purchase_orders' em ordem decrescente ordenados por 'created_by' em que o 'created_by' é maior ou igual a 3

  - [X]  11 - Exiba os dados da coluna 'notes' da tabela 'purchase_orders' em que seu valor de 'Purchase generated based on Order' é maior ou igual a 30 e menor ou igual a 39

  - [X]  12 - Mostre os resultados da coluna 'submitted_date' da tabela 'purchase_orders' em que a 'submitted_date' é do dia 26 de abril de 2006

  - [X]  13 - Mostre o resultado da coluna 'supplier_id' da tabela 'purchase_orders' em que o 'supplier_id' seja 1 ou 3

  - [X]  14 - Mostre os resultados da coluna 'supplier_id' da tabela 'purchase_orders' em que o 'supplier_id' seja maior ou igual a 1 e menor ou igual 3

  - [X]  15 - Mostre somente as horas, sem os minutos e os segundos, da coluna 'submitted_date' de todos registros da tabela 'purchase_orders'

  - [X]  16 - Exiba os resultados da coluna 'submitted_date' da tabela 'purchase_orders' que estão entre '2006-01-26 00:00:00' e '2006-03-31 23:59:59'

  - [X]  17 - Mostre os registros das colunas 'id' e 'supplier_id' da tabela 'purchase_orders' em que os 'supplier_id' sejam tanto 1, ou 3, ou 5, ou 7

  - [X]  18 - Mostre todos os registros da tabela 'purchase_orders' que tem o valor na coluna 'supplier_id' igual a 3 e o valor na coluna 'status_id' igual a 2

  - [X]  19 - Mostre a quantidade de pedidos que foram feitos na tabela 'orders' pelo 'employee_id' igual a 5 ou 6, e que foram enviados através do método coluna 'shipper_id' igual a 2

  - [X]  20 - Adicione à tabela 'order_details' um registro com 'order_id': 69, 'product_id': 80, 'quantity': 15.0000, 'unit_price': 15.0000, 'discount': 0, 'status_id': 2, 'date_allocated': NULL, 'purchase_order_id': NULL e 'inventory_id': 129

  - [X]  21 - Adicione com um único 'INSERT', duas linhas à tabela 'order_details' com os mesmos dados do requisito 20

  - [X]  22 - Atualize os dados na coluna 'discount' da tabela 'order_details' para 15

  - [X]  23 - Atualize os dados da coluna 'discount' da tabela 'order_details' para 30, onde o valor na coluna 'unit_price' seja menor que 10.0000

  - [X]  24 - Atualize os dados da coluna 'discount' da tabela 'order_details' para 45, onde o valor na coluna 'unit_price' seja maior que 10.0000 e o id seja um número entre 30 e 40

  - [X]  25 - Delete todos os dados na coluna 'unit_price' da tabela 'order_details' em que o valor seja menor que 10.0000

  - [X]  26 - Delete todos os dados na coluna 'unit_price' da tabela 'order_details' em que o valor seja maior que 10.0000

  - [X]  27 - Delete todos os dados da tabela 'order_details'
