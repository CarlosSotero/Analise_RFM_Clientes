## Análise RFM de Clientes

Este repositório contém o código em Python desenvolvido como parte de um desafio do curso de Cientista de Dados da Escola DNC. O objetivo foi calcular as métricas de Recência (R), Frequência (F) e Valor Monetário (M) para os clientes de uma empresa fictícia do ramo de e-commerce.

O que é RFM?
R (Recency): Tempo desde a última compra do cliente (em dias).

F (Frequency): Quantidade de compras realizadas pelo cliente.

M (Monetary): Valor do ticket médio gasto pelo cliente.

O código recebe uma base de dados (arquivo CSV) como entrada e gera um arquivo CSV contendo a identificação dos clientes e as respectivas métricas RFM.

Etapas Realizadas:
Leitura e inspeção dos dados.

Remoção de valores faltantes na identificação do cliente.

Exclusão de preços unitários e quantidades de produtos menores ou iguais a 0.

Verificação e remoção de linhas duplicadas.

Alteração do tipo de dados das colunas CustomerID e InvoiceDate.

Tratamento de outliers:

Quantidade do item na compra superior a 10.000.

Preço unitário maior que 5.000.

Criação de uma coluna adicional com o preço total da compra.

Cálculo da última data de compra.

Plotagem de gráficos:

Top 10 países com maior valor em vendas.

Top 10 produtos mais vendidos.

Valor total de vendas por mês.

Valor total de vendas por mês e país (apenas os 10 principais países).

Cálculo do RFM.

### 📖Aprendizado
Este desafio foi uma oportunidade incrível para aplicar conceitos de data cleaning e data wrangling, além de visualizar dados com gráficos informativos. Estou orgulhoso dos resultados alcançados e confiante de que este é mais um passo importante na minha trajetória rumo à carreira de Cientista de Dados.
