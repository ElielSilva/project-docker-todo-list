
# Projeto mysql-all-for-one
esse projeto tem como objetivo desmostrar os conhecimento basicos de SQL adquiridos durante o curso de Desenvolvedor Web na TRYBE

## quais arquivos foram desenvolvidos por mim
- desafio1.sql (Exibe apenas os nomes dos produtos na tabela products)
- desafio2.sql (Exibe os dados de todas as colunas da tabela products)
- desafio3.sql (exibe os valores da coluna que representa a primary key da tabela products)
- desafio4.sql (Conta quantos registros existem na coluna product_name da tabela products)
- desafio5.sql (exibe os dados da tabela products a partir do quarto registro até o décimo terceiro)
- desafio6.sql (Exibe os dados das colunas product_name e id da tabela products de maneira que os resultados estão em ordem alfabética dos nomes)
- desafio7.sql (Mostra apenas os ids dos 5 últimos registros da tabela products (com ordernação baseada na coluna id)).
- desafio8.sql(Faz uma consulta que retorna três colunas, respectivamente, com os nomes 'A', 'Trybe' e 'eh', e com valores referentes a soma de '5 + 6', a string 'de', a soma de '2 + 8')
-desafio9.sql  (Mostra todos os valores de notes da tabela purchase_orders que não são nulos)
- desafio10.sql (Mostra todos os dados da tabela purchase_orders em ordem decrescente, ordenados por created_by em que o created_by é maior ou igual a 3)
- desafio11.sql (Exibe os dados da coluna notes da tabela purchase_orders em que seu valor de Purchase generated based on Order é maior ou igual a 30 e menor ou igual a 39)
- desafio12.sql (Mostra as submitted_date de purchase_orders em que a submitted_date é do dia 26 de abril de 2006)
- desafio13.sql (Mostra o supplier_id das purchase_orders em que o supplier_id seja 1 ou 3)
- desafio14.sql (Mostra os resultados da coluna supplier_id da tabela purchase_orders em que o supplier_id seja maior ou igual a 1 e menor ou igual 3)
- desafio15.sql (Mostra somente as horas (sem os minutos e os segundos) da coluna submitted_date de todos registros da tabela purchase_orders)
- desafio16.sql (Exibe a submitted_date das purchase_orders que estão entre 2006-01-26 00:00:00 e 2006-03-31 23:59:59)
- desafio17.sql (Mostra os registros das colunas id e supplier_id das purchase_orders em que os supplier_id sejam tanto 1, ou 3, ou 5, ou 7)
- desafio18.sql (Mostra todos os registros de purchase_orders que tem o supplier_id igual a 3 e status_id igual a 2)
- desafio19.sql (Mostra a quantidade de pedidos que foram feitos na tabela orders pelo employee_id igual a 5 ou 6, e que foram enviados através do método(coluna) shipper_id igual a 2)
- desafio20.sql (Adiciona à tabela order_details um registro com order_id: 69, product_id: 80, quantity: 15.0000, unit_price: 15.0000, discount: 0, status_id: 2, date_allocated: NULL, purchase_order_id: NULL e inventory_id: 129)
- desafio21.sql (Adiciona com um único INSERT, duas linhas à tabela order_details com os mesmos dados do desafio20.sql)
- desafio22.sql (Atualiza os dados de discount do order_details para 15)
- desafio23.sql (Atualiza os dados da coluna discount da tabela order_details para 30, onde o valor na coluna unit_price seja menor que 10.0000)
- desafio24.sql (Atualiza os dados da coluna discount da tabela order_details para 45, onde o valor na coluna unit_price seja maior que 10.0000 e o id seja um número entre 30 e 40)
- desafio25.sql (Deleta todos os dados em que a unit_price da tabela order_details seja menor que 10.0000)
- desafio26.sql (Deleta todos os dados em que a unit_price da tabela order_details seja maior que 10.0000)
- desafio20.sql (Deleta todos os dados da tabela order_details)

## quais arquivos/pastas foram desenvolvidos pela Trybe
- .editorconfig
- .eslintignore
- .eslintrc.json
- .gitignore
- docker-compose.yml
- est.config.js
- northwind.sql
- package.json

## Instalação
requer [Node.js](https://nodejs.org/) v10+ rodando e o [docker](https://www.docker.com/).

baixe o repositorio e instale as dependencias.

```sh
git clone git@github.com:ElielSilva/mysql-all-for-one.git
cd mysql-all-for-one
npm i
```

## testando

rodar o docker, entre no conteiner, entre no mysql
```sh
docker-compose up -d
```
 entre no conteiner
```sh
docker exec -it db
```
entre no mysql, a senha é passaword 
```sh
mysql -u root -p
```
depois só copiar e colar, e da ENTER pra executar a query

