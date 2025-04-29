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

## Relatório de Análise para Decisão de Venda da Loja

Após a análise detalhada das informações fornecidas sobre as lojas da rede Alura Store, com base no faturamento total, vendas por categoria, média de avaliação, produtos mais e menos vendidos e custo médio de frete, o objetivo é determinar qual loja apresenta o menor desempenho e deve ser considerada para venda.

**<u>Faturamento Total:</u>**<br>

O faturamento total de cada loja é um dos principais indicadores de performance. As lojas estão organizadas conforme o faturamento total:

Loja 1: R$ 1.534.509,12

Loja 2: R$ 1.488.459,06

Loja 3: R$ 1.464.025,03

Loja 4: R$ 1.384.497,58<br><br>

![Faturamento](/faturamento.png)

A **Loja 4** apresenta o menor faturamento total, com R$ 1.384.497,58, o que pode indicar uma performance abaixo das outras lojas.<br><br>

**<u>Vendas por Categoria de Produto</u>**<br><br>

Analisando as categorias de produto mais vendidas em cada loja, verificamos a quantidade de unidades vendidas para as principais categorias:<br><br>


Loja 1: A maior venda foi de móveis (465 unidades), seguida de eletrônicos (448 unidades).

Loja 2: A maior venda foi de móveis (442 unidades), seguida de eletrônicos (422 unidades).

Loja 3: A maior venda foi de móveis (499 unidades), seguida de eletrônicos (451 unidades).

Loja 4: A maior venda foi de móveis (480 unidades), seguida de eletrônicos (451 unidades).

![Vendas por categoria](/vendascategoria.png)

A **Loja 4** tem um desempenho de vendas um pouco abaixo em várias categorias, especialmente em eletrodomésticos e instrumentos musicais, se comparada às outras lojas, que mostram mais equilíbrio nas vendas.<br><br>

**<u>Média de Avaliação</u>**<br><br>

A média de avaliação dos clientes é uma métrica importante para entender a satisfação dos consumidores:<br><br>


Loja 1: Média de 3.98

Loja 2: Média de 4.04

Loja 3: Média de 4.05

Loja 4: Média de 3.99<br><br>

A **Loja 3** se destaca com a maior média de avaliação, mostrando um bom nível de satisfação do cliente. A Loja 4, com a menor média de avaliação, pode indicar uma experiência do cliente abaixo das expectativas.<br><br>

**<u>Produtos Mais e Menos Vendidos</u>**<br><br>

Verificando os produtos mais e menos vendidos, observamos:<br><br>

Loja 1: O micro-ondas é o produto mais vendido, com 60 unidades, e o headset o menos vendido, com 33 unidades.<br><br>

Loja 2: O produto mais vendido é "Iniciando em programação" com 65 unidades, e o menos vendido é o jogo de tabuleiro com 32 unidades.<br><br>

Loja 3: O kit banquetas é o produto mais vendido com 57 unidades, e o bloco de montar o menos vendido com 35 unidades.<br><br>

Loja 4: O produto mais vendido é a cama box com 62 unidades, e o menos vendido é a guitarra com 33 unidades.<br><br>

Embora a **Loja 4** tenha um bom desempenho em termos de produtos mais vendidos, o baixo número de vendas de produtos como guitarras pode indicar uma limitação de opções ou demanda para certos produtos.<br><br>

**<u>Custo Médio do Frete</u>**<br><br>

O custo do frete também é uma métrica importante para entender os custos operacionais:<br><br>

Loja 1: R$ 34,69

Loja 2: R$ 33,62

Loja 3: R$ 33,07

Loja 4: R$ 31,28<br><br>

A Loja 4 apresenta o custo médio de frete mais baixo, o que é uma vantagem operacional em termos de custos.<br><br>

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

. Clone ou faça o download deste repositório.

. Abra o notebook AluraStoreBr.ipynb no Google Colab.

. Execute as células do notebook para realizar as análises. A primeira célula 
  carrega os dados e as bibliotecas necessárias.

. Observe os gráficos gerados e os insights nas células subsequentes.<br><br>

Após a execução do notebook, você terá uma visão clara do desempenho das lojas e poderá determinar qual loja deve ser vendida com base nas análises realizadas.
