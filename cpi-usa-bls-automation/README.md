# CPI USA - BLS Automation

## Sobre o projeto
Projeto desenvolvido para automatizar a coleta e análise dos dados do Consumer Price Index (CPI) dos Estados Unidos utilizando a API do Bureau of Labor Statistics (BLS).

O objetivo foi construir um pipeline replicável para monitoramento da inflação americana, com geração automática de gráficos e tabelas para análise macroeconômica.

## Objetivo
Automatizar a coleta, tratamento e visualização das principais séries do CPI dos EUA, permitindo acompanhamento rápido da dinâmica inflacionária.

## Metodologia
- Consumo dos dados via API do BLS
- Tratamento das séries temporais
- Cálculo de variações mensais e interanuais
- Organização das séries em DataFrame
- Geração automática de gráficos
- Exportação dos resultados em relatório HTML

## Séries analisadas
- All items
- Core CPI (All items less food and energy)
- Food
- Energy
- Apparel
- Education and communication
- Other goods and services
- Medical care
- Recreation
- Transportation

## Tecnologias utilizadas
- Python
- pandas
- requests
- matplotlib
- seaborn
- Jupyter Notebook

## Resultados
O script gera automaticamente:
- Gráficos históricos das séries do CPI
- Comparação entre núcleos de inflação
- Métricas de variação mensal
- Métricas de variação interanual
- Relatório consolidado em HTML

## Fonte dos dados
U.S. Bureau of Labor Statistics (BLS)
https://www.bls.gov/

## Como rodar
1. Instalar as dependências
2. Inserir token da API do BLS
3. Executar o notebook
4. O relatório será gerado automaticamente
