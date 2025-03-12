# Extração e Análise de Dados

Este repositório contém os códigos e análises realizados como parte de um projeto de iniciação científica na área de Engenharia da Computação. O projeto teve como objetivo a extração e análise de dados de dois bancos de dados distintos: um sobre a quantidade de leitos no Brasil e outro sobre a série histórica do preço da gasolina no país. Todos os dados são disponéveis publicamento nos sites oficiais do Governo Federal.

## Série Histórica do Preço da Gasolina no Brasil

### Contexto
Pela Lei nº 9478/1997, artigo 8º, a Agência Nacional do Petróleo (ANP) registra os preços de combustíveis automotivos e GLP P13 (gás liquefeito de petróleo envasilhado em botijões de 13 quilos) por meio de uma pesquisa semanal de preços. Essa iniciativa gera um conjunto de dados abertos e disponíveis desde 2004 até o primeiro semestre de 2023 sobre a variação do preço desses produtos no Brasil.

### Metodologia
A análise se baseou em métodos estatísticos como testes de normalidade, análise de tendência, testes de estacionariedade e comparação de médias. Para isso, foram utilizadas as bibliotecas Python, Pandas, Matplotlib e Seaborn. Os dados foram adquiridos através do sistema de dados abertos do governo, e após a identificação e correção de erros, foram realizadas análises para avaliar a normalidade, tendência e estacionariedade dos dados.

### Resultados
A análise revelou que os preços da gasolina, diesel e GLP P13 não são normalmente distribuídos, apresentam tendência de aumento ao longo do tempo e são estacionários. Observou-se um aumento significativo nos preços ao longo dos anos, com picos em 2022 devido à recuperação da demanda global pós-pandemia e à guerra na Ucrânia. A gasolina manteve-se acima do preço do dólar, enquanto o diesel acompanhou o dólar com maior frequência, e o GLP P13 apresentou menor relação com o dólar, mas com aumentos significativos em 2021 e 2022.

### Conclusão
Este estudo contribui para a compreensão dos fatores que influenciam os preços dos combustíveis no Brasil e seus impactos na economia e na sociedade. Recomenda-se a formulação de políticas públicas para proteger os consumidores e promover a competitividade do setor.

## Quantidade de Leitos no Brasil

### Contexto
O projeto também analisou a quantidade de leitos no Brasil, utilizando dados extraídos do sistema de dados abertos do governo federal. O objetivo foi verificar a distribuição e a quantidade de leitos, incluindo leitos do SUS, ao longo dos anos.

### Metodologia
Após a extração dos dados no formato CSV, foram realizadas análises utilizando Python e a biblioteca Pandas. Foram identificados e corrigidos erros nos arquivos referentes aos anos de 2018 e 2023. Para visualização dos dados, foram criados gráficos geográficos do país, divididos por estados federativos, utilizando as bibliotecas Matplotlib e Seaborn.

### Resultados
A análise mostrou uma diminuição na quantidade de leitos em alguns estados ao longo do tempo. Foram realizadas análises estatísticas, incluindo média, desvio-padrão, correlação linear e regressão linear, utilizando as bibliotecas Pandas e Scikit-Learn. Os resultados foram apresentados por meio de gráficos, facilitando a visualização e compreensão dos dados.

### Conclusão
Este estudo fornece insights sobre a distribuição e a quantidade de leitos no Brasil, destacando a necessidade de políticas públicas para melhorar a infraestrutura de saúde no país.

## Ferramentas Utilizadas
- **Python**: Linguagem de programação principal utilizada para análise e manipulação de dados.
- **Pandas**: Biblioteca utilizada para manipulação e análise de dados.
- **Matplotlib e Seaborn**: Bibliotecas utilizadas para visualização de dados.
- **Scikit-Learn**: Biblioteca utilizada para análise de regressão linear.

## Como Executar o Projeto
1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/extracao-analise-dados.git
