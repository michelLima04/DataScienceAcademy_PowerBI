# 📊 Dashboard de Análise de Dados de RH (Recursos Humanos)

Este projeto foi desenvolvido como parte do curso Microsoft Power BI Para Business Intelligence e Data Science da plataforma Data Science Academy. Este é o Mini-Projeto 3, focado em uma breve introdução à análise de dados de RH (Recursos Humanos).

## 🎯 Objetivo do Projeto
O grande desafio deste projeto foi atuar com foco no *back-end* da ferramenta, priorizando a organização de cálculos e a modelagem de dados antes da etapa visual. O objetivo central foi estruturar um ambiente analítico de Recursos Humanos robusto, utilizando a linguagem **DAX** para a criação de métricas totalmente customizadas.

Além da extração de inteligência, o projeto exigiu a aplicação de funcionalidades específicas do Power BI, como a criação de colunas condicionais e tabelas de medidas dedicadas. Isso simula um cenário corporativo onde a performance, a estruturação técnica e a organização do cálculo são tão importantes quanto o design do painel final.

## 📂 Fonte de Dados
Para a elaboração deste projeto, foi utilizado o dataset:
* **DatasetRH.csv**: Um arquivo de dados brutos contendo os registros do setor de recursos humanos, com informações demográficas dos funcionários, dados salariais, funções desempenhadas, indicadores de horas extras e histórico de envolvimento no trabalho.

O arquivo serviu como base fundamental para todo o processo de estruturação do *back-end*, permitindo a modelagem de dados, parametrização de regras de negócio e a criação de medidas complexas.

## ⚙️ Estrutura Analítica e DAX
Para a elaboração deste projeto analítico de *People Analytics*, o foco estrutural envolveu:

* **Tabela de Medidas:** Isolamento e organização das medidas DAX em uma tabela dedicada, garantindo escalabilidade e facilidade de manutenção para o relatório.
* **Colunas Condicionais:** Criação de regras de negócio complexas. O principal exemplo foi a parametrização do tempo desde a última promoção, estipulando que se o funcionário tiver 5 anos ou mais desde a última promoção, a mesma deve ser considerada. Caso contrário, não é considerada.
* **Funções DAX:** Uso de funções de agregação e filtro de contexto (como `COUNTROWS` e `CALCULATE`) para a criação de indicadores dinâmicos.

## ❓ Perguntas de Negócio Respondidas
O painel de RH foi estruturado para responder ativamente às seguintes perguntas de negócio estipuladas:

* Qual o total de funcionários atualmente na empresa?
* Qual o tempo médio de experiência dos funcionários (em anos)?
* Qual o total e percentual de funcionários do gênero masculino e feminino?
* Qual a média salarial mensal?
* Qual o total de funcionários por função?
* Qual o percentual de funcionários disponíveis para fazer hora extra?
* Qual o nível de envolvimento dos funcionários no trabalho considerando 4 categorias: Ruim, Baixo, Médio e Alto?
* Qual o total e o percentual de funcionários que devem receber promoção? (Cálculo realizado no back-end para fins de auditoria interna).

## 📸 Visualização do Projeto
<img width="1251" height="704" alt="miniProjeto03" src="https://github.com/user-attachments/assets/5754cda9-c1d7-430f-bead-73c18966930a" />

---
*Desenvolvido por Michel Urban Rosendo de Lima.*
