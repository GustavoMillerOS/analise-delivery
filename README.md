# 🍔 Desafio de Análise de Dados: Delivery de Refeições

Este repositório contém a resolução do desafio técnico de análise de dados de um delivery, utilizando **Python**, **Pandas** e **NumPy**.

## 🎯 Objetivos do Projeto
O projeto consistiu em processar e analisar dois conjuntos de dados (`pedidos.csv` e `cardapio.csv`) para gerar insights sobre faturamento, comportamento de compra e saúde financeira do negócio.

## 🛠️ O que foi desenvolvido:
* **EDA e Limpeza:** Identificação de nulos e tratamento de dados ausentes (preenchimento da `Quantidade` pela média).
* **Feature Engineering:** Cálculo de receita por item e extração de períodos temporais (mês/ano).
* **Integração de Dados:** Realização de um `Left Merge` para enriquecer a base de pedidos com as categorias do cardápio.
* **Análise Estatística:** Uso de NumPy para calcular **Ticket Médio** e **Percentis** de preços e volumes.
* **Filtros Avançados:** Segmentação de pedidos de alto volume na categoria "Salgados".

## 📈 Principais Indicadores (KPIs)
* **Receita Total: R$ 122,652.59
* **Ticket Médio: R$ 285.24
* **Top Categoria: Salgados

## 💻 Como visualizar
Você pode acessar o código completo através do arquivo `.ipynb` neste repositório ou abrir diretamente no Google Colab.
