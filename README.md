# Análise de Vendas e Desempenho de Lojas - Alura Store

## Propósito da Análise

O objetivo desta análise é ajudar o Sr. João a decidir qual loja da sua rede Alura Store vender para iniciar um novo empreendimento. 
Através de dados de vendas, avaliações e desempenho de 4 lojas fictícias da Alura Store, foram realizadas análises para identificar a loja com menor eficiência, a qual deve ser vendida. 
Para isso, diversas métricas foram analisadas, incluindo faturamento, categorias mais vendidas, avaliação dos clientes, produtos mais e menos vendidos e frete médio.

## Estrutura do Projeto e Organização dos Arquivos

Este repositório contém o notebook que realiza a análise, bem como o código necessário para gerar insights e gráficos sobre o desempenho das lojas. 
A estrutura do projeto é organizada da seguinte forma:

. ├── analysis_notebook.ipynb # Notebook principal com a análise de dados e gráficos ├── data/ │ ├── loja_1.csv # Dados da Loja 1 │ ├── loja_2.csv # Dados da Loja 2 │ ├── loja_3.csv # Dados da Loja 3 │ └── loja_4.csv # Dados da Loja 4 ├── images/ # Imagens dos gráficos gerados └── README.md # Este arquivo


- **analysis_notebook.ipynb**: Contém a análise das lojas, incluindo gráficos de barras, pizza e linha, além de cálculos detalhados sobre o desempenho de cada loja.
- **data/**: Contém os arquivos CSV com os dados de cada loja (Loja 1, Loja 2, Loja 3, Loja 4).
- **images/**: Diretório para armazenar as imagens dos gráficos gerados, que são incluídas no relatório final.

## Exemplos de Gráficos e Insights Obtidos

Durante a análise, diversos gráficos foram gerados para comparar o desempenho das lojas. Aqui estão alguns exemplos:

### 1. **Gráfico de Barras - Faturamento Total por Loja**

Este gráfico exibe o faturamento total das quatro lojas, permitindo uma comparação visual entre elas.

![Faturamento Total por Loja](images/faturamento_barras.png)

### 2. **Gráfico de Pizza - Média de Avaliação por Loja**

Este gráfico mostra a média de avaliação dos clientes para cada loja.

![Média de Avaliação por Loja](images/avaliacao_pizza.png)

### 3. **Gráfico de Barras - Produto Mais Vendido e Menos Vendido por Loja**

Este gráfico compara o produto mais vendido e o menos vendido de cada loja.

![Produto Mais e Menos Vendido por Loja](images/produtos_vendidos.png)

## Instruções para Executar o Notebook

Para executar o notebook e reproduzir a análise, siga os passos abaixo:

### Pré-requisitos

- Ter o Python 3 instalado no seu ambiente.
- Instalar as bibliotecas necessárias com o comando:
  
  ```bash
  pip install pandas matplotlib numpy

Passos
Clone ou faça o download deste repositório.

Abra o notebook analysis_notebook.ipynb no Google Colab.

Execute as células do notebook para realizar as análises. A primeira célula carrega os dados e as bibliotecas necessárias.

Observe os gráficos gerados e os insights nas células subsequentes.

Após a execução do notebook, você terá uma visão clara do desempenho das lojas e poderá determinar qual loja deve ser vendida com base nas análises realizadas.

Se tiver alguma dúvida ou encontrar algum problema, sinta-se à vontade para abrir uma issue ou fazer um pull request!
