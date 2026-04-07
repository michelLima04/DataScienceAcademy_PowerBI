# 📊 Laboratório Prático 2 - Dashboard de Vendas, Custo, Margem de Lucro e KPI

Este projeto faz parte do portfólio prático desenvolvido durante o curso **Microsoft Power BI Para Business Intelligence e Data Science** (Data Science Academy).

## 🎯 Objetivo do Projeto e Desafio Técnico
Diferente de análises com fonte de dados única, o objetivo deste projeto foi atuar em todo o processo de *Business Intelligence*: desde a extração e integração dos dados até a modelagem relacional e a criação de cálculos avançados. 

Para a elaboração deste painel, foram aplicados os seguintes conceitos técnicos:
* **Integração de Múltiplas Fontes:** Importação e união de 4 arquivos `.csv` distintos.
* **Modelagem de Dados:** Construção do modelo relacional (esquema estrela/star schema), estabelecendo relacionamentos de `1:*` (um-para-muitos) entre as tabelas Dimensão (`Clientes`, `Pedidos`, `Produtos`) e a tabela Fato (`Vendas`).
* **Introdução ao DAX:** Criação de colunas e métricas calculadas diretamente no Power BI, como o cálculo de **Lucro** e **Margem de Lucro**.

## ❓ Perguntas de Negócio Respondidas
Com o modelo de dados consolidado, o dashboard interativo foi projetado para responder às seguintes questões estratégicas:
1. Qual foi o total de valor de venda considerando cada modo de envio dos pedidos?
2. Quais mercados tiveram o maior custo médio de envio dos produtos vendidos?
3. A empresa atingiu a meta de manter uma média de 350 para o valor de venda mensal? *(Acompanhamento de KPI com base em filtro de Ano e Mês)*
4. Qual categoria de produto apresentou o maior lucro médio?
5. Qual foi o comportamento da margem de lucro ao longo do tempo?

## 📸 Visualização do Projeto

**Dashboard Finalizado:**
<img width="1253" height="703" alt="dashboard" src="https://github.com/user-attachments/assets/486bba3f-3b2e-415c-8844-d16025697700" />

**Estrutura de Modelagem de Dados:**
<img width="1030" height="657" alt="tabelas" src="https://github.com/user-attachments/assets/cea3fd27-d8fb-4222-83d4-82930f5622b6" />

**Arquivos de Fonte de Dados**

<img width="364" height="224" alt="arquivos" src="https://github.com/user-attachments/assets/84499c51-e28b-445c-9122-3a78ca9b1f43" />

---
*Desenvolvido por Michel.*
