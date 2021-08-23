# Habilidades
Nesse projeto, você será capaz de:

- Entender o que são bancos de dados, e como a linguagem de consulta estruturada (SQL) é usada;
- Compreender o que é uma query SQL e quais são seus tipos de comando
- Gerar valores com `SELECT`, selecionar colunas individualmente com `SELECT`
- Renomear e gerar colunas em uma consulta com `AS`
- Concatenar colunas e valores com `CONCAT`
- Remover dados duplicados em uma consulta com `DISTINCT`
- Contar a quantidade de resultados em uma consulta com `COUNT`
- Limitar a quantidade de resultados em uma consulta com `LIMIT`
- Pular resultados em uma consulta com `OFFSET`
- Ordernar os resultados de uma consulta com `ORDER BY`
- Filtrar resultados de consultas com o `WHERE`
- Utilizar operadores booleanos e relacionais em consultas
- Criar consultas mais dinâmicas e maleáveis com `LIKE`
- Fazer consultas que englobam uma faixa de resultados com `IN` e `BETWEEN`
- Encontrar e separar resultados que incluem datas.
- Inserir dados em tabelas com `INSERT`
- Atualizar dados em tabelas com `UPDATE`
- Apagar dados em tabelas com `DELETE`

---

# Instalação

- Clone o repositório
- Entre na pasta do repositório que você acabou de clonar
- Instale as dependências:
```bash 
  npm install
```
---

# Requisitos do projeto

Monte queries para encontrar as informações esperadas pelos desafios:

## Lista de Requisitos

## Desafios Iniciais

- [X] 1 - Exiba apenas os nomes do produtos na tabela `products`.

- [X] 2 - Exiba os dados de todas as colunas da tabela `products`.

- [X] 3 - Escreva uma query que exiba os valores da coluna que representa a primary key da tabela `products`.

- [X] 4 - Conte quantos registros existem em `product_name` de `products`.
- [X] 5 - Monte uma query que exiba os dados da tabela `products` a partir do quarto registro até o décimo terceiro, incluindo tanto um quanto o outro. Obs.: não use `where` ou `order by`.

- [X] - Exiba os dados das colunas `product_name` e `id` da tabela `products` de maneira que os resultados estejam em ordem alfabética dos nomes.

- [X] - Mostre apenas os ids dos 5 últimos registros da tabela `products` (a ordernação deve ser baseada na coluna `id`).
- [X] - Faça uma consulta que retorne três colunas. Na primeira coluna, exiba a soma de `5 + 6` (essa soma deve ser realizada pelo SQL). Na segunda coluna deve haver a palavra \"de\". E por fim, na terceira coluna, exiba a soma de `2 + 8` (essa soma deve ser realizada pelo SQL). A primeira coluna deve se chamar \"A\", a segunda coluna deve se chamar \"Trybe\" e a terceira coluna deve se chamar \"eh\". Não use colunas pre-existentes, apenas o que for criado na hora.

---

## Desafios sobre filtragem de dados

- [X] 9 - Mostre todos os valores de `notes` da tabela `purchase_orders` que não são nulos.

- [X] 10 - Mostre todos os dados da tabela `purchase_orders` em ordem decrescente ordenados por `created_by` em que o `created_by` é maior ou igual a 3. E como critério de desempate para a ordenação, ordene também os resultados pelo `id` de forma crescente.

- [X] - Exiba os dados de `notes` da tabela `purchase_orders` em que seu valor de \"Purchase generated based on Order\" está entre 30 e 39, incluindo tanto o valor de 30 quanto de 39.

- [X] - Mostre as `submitted_date` de `purchase_orders` em que a `submitted_date` é do dia 26 de abril de 2006.

- [X] - Mostre o `supplier_id` das `purchase_orders` em que o `supplier_id` seja 1 ou 3.

- [X] - Mostre os `supplier_id` da `purchase_orders` em que o `supplier_id` seja de 1 a 3, incluindo tanto o 1 quanto o 3.

- [X] - Mostre somente as horas (sem os minutos e os segundos) da `submitted_date` de todos registros de `purchase_orders`. Chame essa coluna de `submitted_hour`.

- [X] - Exiba a `submitted_date` das `purchase_orders` que estão entre `2006-01-26 00:00:00` e `2006-03-31 23:59:59`.

- [X] - Mostre os registros das colunas `id` e `supplier_id` das `purchase_orders` em que os `supplier_id` sejam tanto 1, ou 3, ou 5, ou 7.

- [X] - Mostre todos os registros de `purchase_orders` que tem o `supplier_id` igual a 3 e `status_id` igual a 2.

- [X] - Mostre a quantidade de pedidos que foram feitos na tabela `orders` pelo `employee_id` igual a 5 ou 6, e que foram enviados através do método `shipper_id` igual a 2. Chame a coluna de orders_count.

---

## Desafios de manipulação de tabelas

- [X] 20 - Adicione ao `order_details` uma linha com os seguintes dados: `order_id`: 69, `product_id`: 80, `quantity`: 15.0000, `unit_price`: 15.0000, `discount`: 0, `status_id`: 2, `date_allocated`: NULL, `purchase_order_id`: NULL e `inventory_id`: 129. Obs.: o `id` deve ser incrementado automaticamente.

- [X] - Adicione, com um único `INSERT`, duas linhas ao `order_details` com os mesmos dados. Esses dados são novamente `order_id`: 69, `product_id`: 80, `quantity`: 15.0000, `unit_price`: 15.0000, `discount`: 0, `status_id`: 2, `date_allocated`: NULL, `purchase_order_id`: NULL e `inventory_id`: 129 (o `ìd` deve ser incrementado automaticamente).

- [X] - Atualize os dados de `discount` do `order_details` para 15. (Não é necessário utilizar o SAFE UPDATE em sua query).

- [X] - Atualize os dados de `discount` da tabela `order_details` para 30 cuja `unit_price` seja menor que 10.0000. (Não é necessário utilizar o SAFE UPDATE em sua query).

- [X] - Atualize os dados de `discount` da tabela `order_details` para 45 cuja `unit_price` seja maior que 10.0000 e o id seja um número entre 30 a 40. (Não é necessário utilizar o SAFE UPDATE em sua query).

- [X] - Delete todos os dados em que a `unit_price` da tabela `order_details` seja menor que 10.0000.

- [X] - Delete todos os dados em que a `unit_price` da tabela `order_details` seja maior que 10.0000.

- [X] - Delete todos os dados da tabela `order_details`.

---
