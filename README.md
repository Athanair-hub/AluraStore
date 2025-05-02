# Análise de Vendas e Desempenho de Lojas - Alura Store

## Propósito da Análise

O objetivo desta análise é ajudar o Sr. João a decidir qual loja da sua rede Alura Store vender para iniciar um novo empreendimento.
Através de dados de vendas, avaliações e desempenho de 4 lojas fictícias da Alura Store, foram realizadas análises para identificar a loja com menor eficiência, a qual deve ser vendida.
Para isso, diversas métricas foram analisadas, incluindo faturamento, categorias mais vendidas, avaliação dos clientes, produtos mais e menos vendidos e frete médio.

## Estrutura do Projeto e Organização dos Arquivos

Este repositório contém o notebook que realiza a análise, bem como o código necessário para gerar insights e gráficos sobre o desempenho das lojas.
A estrutura do projeto é organizada da seguinte forma:<br><br>


-> Importação dos dados

1. Análise do faturamento

2. Vendas por Categoria

3. Média de Avaliação das Lojas

4. Produtos Mais e Menos Vendidos

5. Frete Médio por Loja<br><br>

## Relatório de Análise para Decisão de Venda da Loja<br><br>

Após a análise detalhada das informações fornecidas sobre as lojas da rede Alura Store, com base no faturamento total, vendas por categoria, média de avaliação, produtos mais e menos vendidos e custo médio de frete, o objetivo é determinar qual loja apresenta o menor desempenho e deve ser considerada para venda.<br><br>

## Relatório de Análise Comparativa – Lojas da Allure Store<br><br>

**<h3>Objetivo:**<br><br>

Auxiliar o Sr. João na decisão de venda de uma das quatro lojas da Allure Store, com base em indicadores de desempenho. <br><br>

O critério definido é desempenho geral mais fraco.<br><br>

**<h3>Indicadores Avaliados:**<br><br>

- Faturamento total

- Categorias mais vendidas

- Produto mais vendido

- Produto menos vendido

- Avaliação média dos clientes

- Frete médio

- Local de compra mais frequente

- Tipo de pagamento mais comum

- Desempenho por ano e mês (vendedores e local)<br><br>

**<h3>Faturamento Total**<br><br>

 Loja   |  Faturamento Total<br>
 -------|-------------------
Loja 1	| R$ 1.616.347,09
Loja 2 | R$ 1.567.773,22
Loja 3	| R$ 1.542.047,69
Loja 4	| R$ 1.458.253,46 🔻

<br><br> ![Faturamento](/imagens/faturamento.png)        

<br>**Análise:**<br><br>

A **Loja 4** tem o menor faturamento total entre todas as lojas. Isso é um indicativo de menor desempenho financeiro em relação às demais lojas.<br><br>

**<h3>Avaliação Média dos Clientes**<br><br>

Loja | Avaliação Média
-----|----------------
Loja 1 | 3.98 🔻
Loja 2	| 4.04
Loja 3	| 4.05
Loja 4	| 4.00

<br><br> ![Avaliação Média](/imagens/mediaavaliacao.png)

<br>**Análise:**<br><br>

A **Loja 1** apresenta a menor média de avaliação dos clientes, o que sugere que a experiência de compra pode não ser tão satisfatória quanto nas outras lojas.<br><br>

**<h3>Frete Médio**<br><br>

Loja | Frete Médio
-----|------------
Loja 1	| R$ 34,69 🔻
Loja 2	| R$ 33,62
Loja 3	| R$ 33,07
Loja 4	| R$ 31,28

<br><br> ![Frete Médio](/imagens/fretemedio.png)

<br>**Análise:**<br><br>

A **Loja 4** possui o menor frete médio, o que pode ser considerado uma vantagem em termos de custo logístico, mas isso não compensa o desempenho em outras áreas.<br><br>

**<h3>Categorias Mais Vendidas por Loja**<br><br>

Loja | Top Categoria | Quantidade
-----|---------------|------------
Loja 1	| Eletrônicos | 469
Loja 2	| Brinquedos |440
Loja 3	| Móveis	| 453
Loja 4	| Móveis	| 480

<br><br> ![Categorias mais vendidas](/imagens/vendascategorialoja.png)

<br>**Análise:**<br><br>

A **Loja 4** lidera nas vendas de móveis, mas isso não se traduz em um faturamento superior. Apesar de ser a líder em sua categoria, a Loja 4 não lidera em termos financeiros.

**<h3>Produtos Mais e Menos Vendidos**<br><br>

**Produtos Mais Vendidos (Top 10 de Todas as Lojas)**<br><br>

Produto | Quantidade
--------|------------
Cômoda	| 210
Carrinho controle remoto | 206
Micro-ondas | 206
Bateria | 203
Cama king | 201
Secadora de roupas | 200
Modelagem preditiva | 200
Jogo de panelas | 200
Cama box | 199
Blocos de montar | 199

<br><br> ![Produtos mais vendidos](/imagens/maisvendidosloja1.png)

<br><br> ![Produtos mais vendidos](/imagens/maisvendidosloja2.png)

<br><br> ![Produtos mais vendidos](/imagens/maisvendidosloja3.png)

<br><br> ![Produtos mais vendidos](/imagens/maisvendidosloja4.png)

<br>**Análise:**<br><br>

Os produtos mais vendidos mostram uma tendência clara de alta demanda em itens como móveis e eletrodomésticos. A Cômoda e o Carrinho controle remoto estão entre os produtos de maior destaque.<br><br>

**Produtos Menos Vendidos (Top 10 de Todas as Lojas)**

Produto	| Quantidade
--------|-------------
Panela de pressão |	172
Smartwatch | 172
Jogo de copos | 169
Poltrona | 168
Assistente virtual | 167
Ciência de dados com python | 166
Guitarra | 165
Mochila	| 163
Headset | 158
Celular ABXY | 157

<br><br> ![Produtos menos vendidos](/imagens/menosvendidosloja1.png)

<br><br> ![Produtos menos vendidos](/imagens/menosvendidosloja2.png)

<br><br> ![Produtos menos vendidos](/imagens/menosvendidosloja3.png)

<br><br> ![Produtos menos vendidos](/imagens/menosvendidosloja4.png)

<br>**Análise:**<br><br>

Os produtos menos vendidos incluem itens como Smartwatch e Poltrona, com vendas notavelmente mais baixas. Esses produtos podem estar passando por menos procura no mercado.<br><br>

**Local com Mais Compras (por ano)**<br><br>

Todas as lojas têm São Paulo (SP) como principal local de compras em todos os anos e meses, indicando um padrão uniforme de operação geográfica. Isso não mostra grandes diferenças entre as lojas em termos de distribuição geográfica das vendas.<br><br>

**Tipo de Pagamento Mais Utilizado (por ano e mês)**<br><br>

Em todas as lojas, o cartão de crédito é o tipo de pagamento mais utilizado. Isso também indica um padrão semelhante de consumo entre as lojas, com a preferência dos clientes pelo pagamento parcelado.<br><br>

**Vendedor com Mais Vendas por Ano**<br><br>

Loja 4 (Exemplo)

Ano | Top Vendedor
----|---------------
2020 | João Souza
2021 | Mariana Ferreira
2022 | Felipe Santos
2023 | Felipe Santos

<br>**Análise:**<br><br>

A **Loja 4** apresenta uma variação de vendedores ao longo dos anos, com uma leve repetição de Felipe Santos como vendedor de destaque em 2022 e 2023, o que sugere uma estabilidade recente.<br><br>


**Resumo Geral Comparativo**

Indicador	| Loja 1 | Loja 2 | Loja 3 | Loja 4 | Pior Desempenho
----------|--------|--------|--------|--------|-------------------
Faturamento Total|R$1.616.347|R$1.567.773|R$1.542.047|R$1.458.253|Loja 4
Avaliação Média |	3.98 |	4.04 |	4.05 |	4.00 |	Loja 1
Frete Médio |	R$ 34,69 |	R$ 33,62 |	R$ 33,07 |	R$ 31,28 |	Loja 1
Estabilidade em Vendas |	OK |	OK |	OK |	🔻 Variável |	Loja 4
Crescimento | 2023 |	Estável |	Estável |	Estável |	🔻 Reduzido |	Loja 4


<br>**Recomendação Final**<br><br>

**Vender a Loja 4**<br><br>

**Justificativas:**<br><br>

Menor faturamento absoluto: A Loja 4 apresenta o menor faturamento total, o que indica um desempenho financeiro mais fraco.<br><br>

Desempenho de vendas mais fraco em 2023: O desempenho da Loja 4 foi mais fraco em termos de crescimento e estabilidade nas vendas.<br><br>

Menor estabilidade nos rankings de vendedores: A variação na liderança dos vendedores da Loja 4 sugere menos estabilidade no time de vendas.<br><br>

Avaliação de clientes e frete não compensam a baixa performance: Embora a Loja 4 tenha o frete mais baixo, sua avaliação de clientes e o desempenho geral não são suficientes para compensar o menor faturamento.<br><br>

Potencial menor de crescimento: Com um desempenho de vendas reduzido e instabilidade em 2023, a Loja 4 apresenta um potencial de crescimento menor em comparação com as outras lojas.<br><br>

Essa análise indica que a Loja 4 deve ser vendida para focar em opções com melhor desempenho financeiro e potencial de crescimento.<br><br>


**<u>Análise Conclusiva</u>**<br><br>

Apesar da Loja 4 ter o custo médio de frete mais baixo e um desempenho razoável em algumas categorias de vendas, ela apresenta o menor faturamento total e a menor média de avaliação dos clientes. Além disso, a Loja 4 tem um desempenho inferior em várias categorias de produto, especialmente quando comparada à Loja 3, que apresenta o melhor desempenho de avaliação e faturamento.<br><br>

A Loja 4 parece ser a que apresenta maior risco para o negócio no momento, tanto em termos de faturamento quanto de satisfação do cliente. Embora o custo de frete seja favorável, a menor avaliação e o menor faturamento total indicam que ela é a candidata mais provável para venda.<br><br>

**<u>Recomendação</u>**<br><br>

Com base em uma análise combinada dos dados de faturamento, avaliação dos clientes e desempenho geral, recomenda-se que a **Loja 4** seja a loja a ser vendida para possibilitar o investimento em um novo empreendimento.


## Instruções para Executar o Notebook

Para executar o notebook e reproduzir a análise, siga os passos abaixo:

### Pré-requisitos

- Ter o Python 3 instalado no seu ambiente.
- Instalar as bibliotecas necessárias com o comando:
  
  ```bash
  pip install pandas matplotlib numpy

**<u>Passos</u>**<br><br>

- Clone ou faça o download deste repositório.

- Abra o notebook AluraStoreBr.ipynb no Google Colab.

- Execute as células do notebook para realizar as análises. A primeira célula 
  carrega os dados e as bibliotecas necessárias.

- Observe os gráficos gerados e os insights nas células subsequentes.<br><br>

Após a execução do notebook, você terá uma visão clara do desempenho das lojas e poderá determinar qual loja deve ser vendida com base nas análises realizadas.
