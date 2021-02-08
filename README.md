# Maximização de vendas com ML

## Problema:

A empresa quer lançar um novo produto. Assim, ela fez um projeto piloto com 
2240 clientes aleatórios, para estudar as características dos clientes que estão dispostos a comprar o novo produto.

## Objetivo:

Construir um modelo preditivo que irá maximizar os lucros da venda desse produto. O modelo permitirá que a empresa escolha os clientes com maior probabilidade decomprar a oferta, deixando de fora os não respondentes, tornando a próxima campanha altamenterentável.


## Metadados: Separei os metadados em 3 categoriais, apenas por didática.

#### Características Sociodemográficas:

* Education: Nível de educação;
* Marital: Estado Civíl;
* Kidhome: número de crianças pequenas na casa do cliente;
* Teenhome: número de adolescentes na casa do cliente;
* Year_Birth
* Income: renda familiar anual do cliente;

#### Relações com a plataforma:

* Complain(reclamação): 1, se o cliente reclamou no último 2 anos;
* DtCustomer: data de inscrição do cliente na empresa;
* MntFishProducts: valor gasto em produtos pesqueiros nos últimos 2 anos;
* MntMeatProducts: valor gasto em produtos em carne nos últimos 2 anos;
* MntFruits: valor gasto em frutas nos últimos 2 anos;
* MutSweetProducts: valor gasto em doces nos últimos 2 anos;
* MntWines: valor gasto em vinhos nos últimos 2 anos;
* MntGoldProds: amount spent on gold products in the last 2 years;
* NumDealsPurchases: número de compras feitas com desconto;
* NumCatalogPurchases: número de compras feitas usando o catálogo;
* NumStorePurchases: número de compras feitas diretamente nas lojas;
* NumWebPurchases: número de compras feitas através do site da empresa;
* NumWebVisitsMonth: número de visitas ao site da empresa no último mês;
* Recency: número de dias desde a última compra;

#### Relações com as campanhas:

* AccepetedCmp1: 1, se o cliente aceitou a primeira campanha. Senão, 0;
* AccepetedCmp2: 1, se o cliente aceitou a segunda campanha. Senão, 0;
* AccepetedCmp3: 1, se o cliente aceitou a terceira campanha. Senão, 0;
* AccepetedCmp4: 1, se o cliente aceitou a quarta campanha. Senão, 0;
* AccepetedCmp5: 1, se o cliente aceitou a quinta campanha. Senão, 0;
* Response(Target): 1, se o cliente aceitou a oferta na última campanha. Senão, 0;
