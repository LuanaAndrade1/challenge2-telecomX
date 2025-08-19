Análise de Evasão de Clientes – Telecom X

Descrição do Projeto

Este projeto tem como objetivo analisar os dados de clientes da Telecom X para identificar padrões de evasão (churn). Através da exploração, limpeza e visualização dos dados, buscamos entender os fatores que influenciam a permanência ou cancelamento dos clientes, oferecendo insights estratégicos para reduzir a evasão.

Tecnologias Utilizadas

Python 3.x

Pandas

Matplotlib / Seaborn

Google Colab


Estrutura do Projeto

notebook.ipynb – Notebook principal com todo o passo a passo da análise.

README.md – Documentação do projeto.

dados/ (opcional) – Pasta para armazenar arquivos .csv ou JSON baixados da API.


Passos do Projeto

1. Importação dos Dados

Conexão com a API da Telecom X.

Conversão do JSON em DataFrame do Pandas.



2. Exploração Inicial

Visualização das colunas e tipos de dados.

Identificação das variáveis mais relevantes para análise de churn.



3. Identificação de Problemas nos Dados

Verificação de valores ausentes, duplicados e inconsistências.



4. Tratamento e Limpeza dos Dados

Correção de erros e ajustes necessários para garantir integridade dos dados.



5. Criação de Colunas Derivadas

Criação da coluna Contas_Diarias a partir do faturamento mensal, oferecendo uma visão detalhada do comportamento diário dos clientes.



6. Análise Descritiva

Cálculo de métricas como média, mediana e desvio padrão.



7. Análise de Churn

Visualização da proporção de clientes que permaneceram e que cancelaram.



8. Análise de Variáveis Categóricas

Exploração da evasão por gênero, tipo de contrato, método de pagamento e outros fatores.



9. Análise de Variáveis Numéricas

Comparação de métricas como “total gasto” e “tempo de contrato” entre clientes que cancelaram e que não cancelaram.



10. Relatório Final

Introdução, metodologia, limpeza de dados, análise exploratória, conclusões, insights e recomendações.



Como Executar

1. Abra o Google Colab.


2. Faça upload do notebook (.ipynb) ou abra o projeto diretamente no Colab.


3. Execute as células na ordem apresentada para reproduzir a análise.



Conclusões e Insights

O projeto fornece uma visão detalhada sobre os fatores que influenciam a evasão de clientes.

Identificação de padrões importantes para tomada de decisão e estratégias de retenção.
