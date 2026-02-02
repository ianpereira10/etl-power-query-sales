# Projeto de Análise de Dados – ETL com Power Query e Dashboard no Power BI

Este projeto apresenta um processo completo de **ETL (Extract, Transform, Load)** utilizando **Power Query**, seguido da criação de um **dashboard interativo no Power BI** para análise de dados de vendas de jogos.

A base de dados simula um relatório corporativo extraído de um sistema **SAP**, com dados brutos que precisaram passar por tratamento e padronização antes da análise.


## 🎯 Objetivo do Projeto
Transformar dados brutos de vendas em **informações estruturadas e visuais**, permitindo análises como faturamento, estoque e desempenho por região, jogo e console.


## 🔹 Extração (Extract)
- Importação de dados a partir de um arquivo Excel
- Simulação de relatório de vendas extraído do SAP

## 🔹 Transformação (Transform)
As transformações foram realizadas no **Power Query**, utilizando o **Editor Avançado (linguagem M)**, incluindo:
- Promoção de cabeçalhos
- Remoção de registros inválidos
- Padronização de categorias (regiões)
- Separação de colunas (nome do jogo e console)
- Conversão e tratamento de valores monetários
- Tratamento de datas
- Criação de regra de negócio para cálculo de faturamento total

## 🔹 Carga (Load)
- Dataset final estruturado e pronto para análise
- Utilização do dataset no Power BI para construção do dashboard

## 📊 Dashboard no Power BI
O dashboard desenvolvido permite:
- Visualização do **faturamento total**
- Análise de faturamento por **região, jogo e console**
- Cálculo de **preço médio** e **estoque total**
- Aplicação de filtros dinâmicos por:
  - Região
  - Console
  - Status do pedido

## 🛠 Ferramentas Utilizadas
- Power BI  
- Power Query  
- Excel  

## 📈 Resultado
Entrega de um dashboard interativo e uma base de dados tratada, possibilitando **análises claras e suporte à tomada de decisão**.


