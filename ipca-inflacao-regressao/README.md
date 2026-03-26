# IPCA - Inflação Anualizada, Volatilidade e Regressão

## Sobre o projeto
Projeto desenvolvido para analisar a dinâmica da inflação brasileira a partir da série mensal do IPCA.

O trabalho combina visualização de dados, estatística descritiva e regressão linear para investigar o comportamento da inflação e buscar variáveis capazes de explicar sua variação.

## Objetivo
Construir uma análise aplicada do IPCA com três etapas principais:
1. cálculo da inflação anualizada a partir da variação mensal;
2. cálculo da volatilidade da inflação por meio do desvio padrão em janela móvel de 12 meses;
3. estimação de uma regressão para explicar a variação do IPCA com base em variáveis macroeconômicas.

## Metodologia
- Leitura e tratamento da base de dados em Python
- Conversão da coluna de datas para índice temporal
- Cálculo da inflação anualizada a partir do IPCA mensal
- Cálculo do desvio padrão móvel de 12 meses
- Construção de gráficos para análise visual
- Estimação de modelo OLS com variáveis explicativas selecionadas

## Variáveis utilizadas
- IPCA
- Selic
- GDP
- PO
- Taxa de desemprego

## Tecnologias utilizadas
- Python
- pandas
- matplotlib
- statsmodels
- Jupyter Notebook

## Resultados
O projeto gera:
- gráfico da inflação anualizada;
- gráfico da volatilidade da inflação em janela móvel de 12 meses;
- regressão linear para explicar a variação do IPCA;
- interpretação inicial dos coeficientes estimados e sua aderência à teoria econômica.

## Observações
O modelo econométrico foi construído com foco prático e exploratório, buscando identificar relações entre inflação e variáveis macroeconômicas relevantes.

## Como rodar
1. Instalar as dependências do projeto
2. Ajustar o caminho da base de dados
3. Executar o notebook
