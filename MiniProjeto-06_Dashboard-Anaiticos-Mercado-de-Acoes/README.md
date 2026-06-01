# 📊 Mini-Projeto 06 - Dashboard Analítico do Mercado de Ações com Narrativa Inteligente

Este projeto foi desenvolvido como parte do curso Microsoft Power BI Para Business Intelligence e Data Science da plataforma Data Science Academy[cite: 2]. O foco deste 6º Mini-Projeto foi o mercado financeiro (ações), com ênfase na análise de séries temporais e na aplicação de Inteligência Artificial para geração de insights[cite: 2].

## 🎯 Objetivo do Projeto
O objetivo central foi atuar como um analista de dados financeiros, recebendo uma base de dados real do mercado de ações e construindo um painel interativo para monitoramento de ativos[cite: 2]. O dashboard entrega o controle do volume negociado e das variações de preço (abertura, fechamento, máximas e mínimas), gerando explicações textuais automatizadas sobre as tendências do período[cite: 2].

## 📂 Fonte de Dados e Desafio de Negócio
Para a elaboração deste projeto, foram utilizados dados reais extraídos publicamente do portal da **Nasdaq** (`https://www.nasdaq.com`)[cite: 2]. 
* O dataset contempla a cotação diária (uma série temporal) de 5 grandes corporações globais: **IBM, Microsoft, Oracle, Tesla e Walmart**[cite: 2].

## ⚙️ Estrutura Analítica e Diferenciais Técnicos
O projeto se destacou pela aplicação de boas práticas visuais e uso de recursos avançados do Power BI:

* **Time Intelligence (Inteligência de Tempo):** Aplicação de funções e recursos de manipulação de datas para avaliar o comportamento do mercado acionário ao longo do tempo[cite: 2].
* **Inteligência Artificial (Narrativa Inteligente):** Implementação de um visual de IA que gera resumos automáticos em texto para explicar características, inclinações e tendências nos dados (ex: altas e quedas de volume ou valores de fechamento)[cite: 2].
* **UI/UX e Executividade:** Criação de uma interface *Dark Theme* (Azul Marinho) com cartões em contraste, garantindo conforto visual e mantendo o foco analítico nos gráficos através de um excelente *Data-Ink Ratio*.

## 🚀 Principais Funcionalidades e Respostas de Negócio
O painel financeiro foi estruturado para responder dinamicamente às seguintes necessidades:

1. **Volume Negociado:** Gráfico de área demonstrando o total de volume de ações negociadas ao longo do tempo (com linha de tendência), permitindo analisar o fluxo geral ou de uma empresa específica[cite: 2].
2. **Variação MoM (Month-over-Month):** Análise visual da variação da média do valor de fechamento (Close) das ações mês a mês[cite: 2], permitindo comparar a volatilidade e performance entre as 5 corporações.
3. **Detalhamento Tabular (Matriz):** Tabela financeira consolidando os valores médios de *Open* (abertura), *High* (mais alto), *Low* (mais baixo), *Close* (fechamento) e Volume de ações por ano e mês[cite: 2].
4. **Contexto Narrativo Automatizado:** Caixa de texto gerada por IA que acompanha os filtros aplicados e redige *insights* automáticos sobre quedas e aumentos percentuais no período selecionado[cite: 2].

## 📸 Visualização do Projeto

### Dashboard Analítico do Mercado de Ações
<img width="1291" height="712" alt="Print_Mini-Projeto06" src="https://github.com/user-attachments/assets/ff0b6e21-3048-46c3-9d1d-fec89a770723" />

## 🛠️ Técnicas Utilizadas

* **ETL (Extração, Transformação e Carga):** Importação e modelagem de dados de séries temporais reais do mercado de ações.
* **DAX & Time Intelligence:** Manipulação de medidas de tempo para consolidação de médias mensais (*MoM*).
* **Inteligência Artificial Nativa:** Configuração do visual de Narrativa Inteligente (*Smart Narrative*) para *storytelling* de dados automático.
* **Design de Interfaces (UI/UX):** Aplicação de paleta de cores voltada para o mercado financeiro (*Dark Mode*), alinhamento em blocos, hierarquia tipográfica e filtros em dropdown (*Mês* e *Empresa*) para otimização de espaço em tela.

---
*Desenvolvido por Michel Urban Rosendo de Lima.*
