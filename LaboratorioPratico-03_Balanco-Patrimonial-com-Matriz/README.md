# 📊 Lab 3 - Balanço Patrimonial e Resumo Executivo em Power BI

Este projeto foi desenvolvido como uma expansão do Lab 3 do curso Microsoft Power BI Para Business Intelligence e Data Science da plataforma Data Science Academy. O foco deste laboratório foi a área de **Contabilidade e Finanças**, com ênfase na modernização de relatórios contábeis tradicionais.

## 🎯 Objetivo do Projeto
O objetivo central foi atuar em um cenário de controladoria: receber dados financeiros brutos e transformá-los em um ambiente de inteligência interativo. O projeto vai além do desafio original (criar um balanço patrimonial com visual de matriz), entregando uma aplicação analítica completa com múltiplas páginas que permite à diretoria ter uma visão rápida e executiva da saúde financeira da instituição, além do detalhamento contábil profundo.

## 📂 Fonte de Dados e Desafio de ETL
Para a elaboração deste projeto, foi utilizado o dataset:
* **Lab3-Dataset.xlsx**: Um arquivo com os dados contábeis distribuídos em um formato de colunas anuais (2019 a 2023), simulando uma exportação comum de sistemas ERP ou planilhas de controle manual.

Para que o modelo relacional funcionasse corretamente e permitisse a inteligência de tempo no Power BI, foi necessário aplicar pesadas técnicas de transformação no **Power Query**, especificamente o pivoteamento (Unpivot / Transformar Colunas em Linhas) das colunas de anos, convertendo a base para um formato tabular normalizado.

## ⚙️ Estrutura Analítica e Diferenciais Técnicos
Além do tratamento de dados no *back-end*, o projeto se destacou pela aplicação de boas práticas visuais e cálculos avançados:

* **Inteligência de Tempo Customizada (DAX):** Uso de DAX avançado para calcular a variação YoY (Ano a Ano) e buscar valores de anos anteriores dinamicamente, adequando-se à estrutura dos dados sem depender de uma tabela de calendário padrão.
* **UI/UX e Limpeza Cognitiva:** Aplicação do conceito de "Data Ink Ratio" (Proporção de Tinta de Dados). Eixos Y foram removidos de gráficos de barras para evitar poluição visual, e a semântica de cores foi rigidamente aplicada (verde e vermelho exclusivos para indicar crescimento ou queda na Variação YoY).
* **Navegação de Aplicação (App-like Experience):** Implementação de botões de *Page Navigation* para que o usuário transite fluidamente entre a visão executiva e o detalhamento da matriz.

## 🚀 Principais Funcionalidades e Telas
O painel financeiro foi estruturado nas seguintes visões estratégicas:

1. **Dados Gerais (Dashboard Executivo):** Visão macro com KPIs de Total de Ativos, liquidez e variação percentual anual.
2. **Balanço Patrimonial (Detalhamento Contábil):** Visão analítica profunda utilizando o visual de matriz com hierarquias e barras de dados dinâmicas.

## 📸 Visualização do Projeto

### 1. Balanço Patrimonial
<img width="1208" height="675" alt="lab3_1" src="https://github.com/user-attachments/assets/cfe73f63-ebbf-4311-b6e3-d7d7eb8f4621" />

### 2. Dados Gerais
<img width="1204" height="669" alt="lab3_2" src="https://github.com/user-attachments/assets/7a1a28ed-f02e-4351-a1ad-85ee290405bc" />

## 🛠️ Técnicas Utilizadas

* **ETL (Extração, Transformação e Carga):** Limpeza de dados e aplicação de *Unpivot* para normalização de bases temporais.
* **Modelagem de Dados:** Estruturação de modelo relacional (Fato/Dimensão) entre tabelas contábeis e plano de contas.
* **DAX (Data Analysis Expressions):** Medidas para manipulação de contexto de filtro (`CALCULATE`) e métricas de variação percentual (`DIVIDE`).
* **Visualização de Dados & UI/UX:** Aplicação de *Data-Ink Ratio*, hierarquia visual, estilização de *Cards* com sombras e bordas (estilo Web App), formatação condicional e navegação entre páginas.

---
*Desenvolvido por Michel Urban Rosendo de Lima.*
