# 📊 Mini Projeto 04 - Desconstruindo o Dashboard e Resolvendo Problemas na Área de Logística

Este projeto foi desenvolvido como parte do curso Microsoft Power BI Para Business Intelligence e Data Science da plataforma Data Science Academy. O Mini-Projeto 4 focou em um cenário altamente realista: a auditoria e refatoração de um painel de indicadores com problemas críticos.

## 🎯 Objetivo do Projeto
O grande diferencial deste projeto não foi apenas construir um painel do zero, mas atuar de forma crítica sobre um Dashboard previamente construído (e repleto de erros técnicos e visuais). O objetivo central foi **desconstruir** o trabalho antigo, identificar problemas analíticos que poderiam levar a diretoria a tomar decisões equivocadas, e reconstruir a interface e o *back-end* para entregar informações logísticas de forma clara, precisa e profissional.

A prioridade foi o desenvolvimento do senso crítico analítico, provando que ferramentas de *self-service BI* exigem conhecimento em regras de negócio e boas práticas de UI/UX de dados para não gerarem prejuízos.

## 📂 Fonte de Dados
Para a elaboração e correção deste projeto, foi utilizado o dataset:
* **dataset.xlsx**: Um arquivo de dados transacionais contendo informações de entregas logísticas, detalhando os canais de distribuição, equipes de entrega responsáveis, datas, vendedores, cidades destino e o status final de cada entrega (No Prazo, Atrasado, Antecipado).

## ⚙️ Estrutura Analítica e Correções (Back-end)
Neste projeto, a atuação técnica consistiu na refatoração e ajuste do ambiente analítico:

* **Auditoria Visual e de Negócio:** Substituição de gráficos inadequados (como o uso excessivo de gráficos de pizza ou linhas que distorciam a proporção) por visuais que respeitam as melhores práticas (barras horizontais, tabelas bem formatadas e gráficos de área/linha limpos).
* **Correção de Filtros e Contexto (DAX):** Ajuste de medidas DAX e aplicação correta de filtros de contexto. Um exemplo prático foi isolar o conceito de "Entregas com Atraso" na tabela de cidades, corrigindo rótulos que antes causavam dupla interpretação.
* **Clareza de Informação (UI/UX):** Padronização de cores, nomenclaturas de eixos e títulos, garantindo que o cérebro do tomador de decisão interprete o KPI instantaneamente.

## ❓ Perguntas de Negócio Respondidas
O painel foi reestruturado para responder de forma correta, sem margem para erros, aos 6 KPIs essenciais solicitados pela diretoria de Logística:

1. Qual o Total de Entregas no Prazo por Canal de Entrega?
2. Qual o Percentual de Entregas Antecipadas por Equipe de Entrega?
3. Qual o Total de Entregas realizadas por Mês (sazonalidade)?
4. Qual o Total de Entregas de Produtos atrelados aos Top 5 Vendedores?
5. Qual o Total de Entregas com Atraso ranqueadas por Cidade?
6. Qual o Percentual Geral de Entregas agrupadas por Status de Entrega?

## 📸 Visualização do Projeto (Evolução)

**1. Dashboard Antigo (Com erros analíticos e visuais):**
<img width="1247" height="700" alt="Antes" src="https://github.com/user-attachments/assets/b56bf5d2-dedb-44cc-a0a7-afb367644f79" />

**2. Dashboard Novo (Refatorado e Validado):**
<img width="1207" height="673" alt="Depois" src="https://github.com/user-attachments/assets/dacf23f1-40a1-4ca1-ac20-d53f3884079d" />

---
*Desenvolvido por Michel Urban Rosendo de Lima.*
