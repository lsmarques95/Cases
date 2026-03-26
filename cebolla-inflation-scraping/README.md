# Cebolla Inflation Forecast - Web Scraping + Econometrics

## Sobre o projeto
Projeto desenvolvido para coletar dados de preços da cebola (Cebolla Bola) a partir do sistema SNIIM e construir um modelo econométrico para prever a inflação quinzenal do produto.

O trabalho combina web scraping com Selenium, tratamento de séries temporais e regressão linear.

## Objetivo
Construir um pipeline completo para:
- coletar dados automaticamente do site
- calcular inflação quinzenal
- estimar modelo econométrico de previsão

## Metodologia

### Web Scraping
- Coleta de dados com Selenium
- Navegação automática pelas páginas
- Extração das variáveis:
  - Fecha
  - Presentación
  - Precio Frec
- Construção de DataFrame com os dados raspados

### Tratamento dos dados
- Conversão da data para formato temporal
- Agrupamento quinzenal
- Cálculo da inflação quinzenal
- Separação por tipo de apresentação

### Modelo econométrico
- Regressão linear sem intercepto
- Variável dependente: inflação quinzenal
- Variáveis explicativas: inflação por tipo
- Estimação com OLS (statsmodels)

## Tecnologias utilizadas
- Python
- Selenium
- pandas
- numpy
- statsmodels
- matplotlib
- Jupyter Notebook

## Resultados
O projeto gera:
- base raspada automaticamente
- série de inflação quinzenal
- regressão linear
- coeficientes estimados
- métricas de ajuste do modelo

## Fonte dos dados
Sistema Nacional de Información e Integración de Mercados (SNIIM)
https://www.economia-sniim.gob.mx/
