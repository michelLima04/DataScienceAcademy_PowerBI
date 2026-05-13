# 📊 Mini Projeto 05 - Dashboard de Análise Financeira e Inteligência Artificial

Este projeto foi desenvolvido como parte do curso Microsoft Power BI Para Business Intelligence e Data Science da plataforma Data Science Academy. O foco deste 5º Mini-Projeto foi a área de **Finanças**, com ênfase na preparação avançada de dados (ETL) e no uso de Inteligência Artificial nativa do Power BI.

## 🎯 Objetivo do Projeto
O objetivo central foi atuar em um cenário corporativo altamente realista: receber dados financeiros brutos, organizados de forma não-analítica (formato de tabela de apresentação), e transformá-los em um ambiente de inteligência que permita à diretoria acompanhar a saúde financeira da empresa. O painel final entrega o controle de receitas, despesas, margem de lucro e identifica os segmentos mais críticos da operação para embasar o planejamento estratégico.

## 📂 Fonte de Dados e Desafio de ETL
Para a elaboração deste projeto, foi utilizado o dataset:
* **DadosFinanceiros.xlsx**: Um arquivo de dados brutos que simulava um problema comum no dia a dia das empresas. A planilha foi preenchida com o layout de "colunas de datas" (uma coluna para o tipo de custo/receita, outra para o componente, e diversas colunas estendidas lateralmente para cada data).

Para que o Power BI pudesse ler e calcular as métricas corretamente, foi necessário aplicar técnicas de manipulação e limpeza no **Power Query**, realizando o pivoteamento (Unpivot / Transformar Colunas em Linhas) para normalizar a base de dados.

## ⚙️ Estrutura Analítica e Diferenciais Técnicos
Além do pesado tratamento de dados no *back-end*, o projeto se destacou pela aplicação de boas práticas visuais e analíticas:

* **IA e Principais Segmentos:** Utilização do visual avançado de IA (*Principais Influenciadores / Segmentos*) para localizar e classificar automaticamente os segmentos onde as receitas e despesas são maiores ou menores.
* **Hierarquia Dinâmica (Matriz):** Criação de uma matriz financeira com *drill-down*, permitindo que o gestor desça o nível da informação de "Tipo" (Receitas/Despesas) para "Componentes" (Marketing, Salários, Impostos, etc.) e valide os valores ano a ano.
* **UI/UX e Limpeza Cognitiva:** Aplicação do conceito de "Data Ink Ratio" (Proporção de Tinta de Dados). Rótulos redundantes de eixos (X e Y) foram removidos para evitar a poluição visual, e os cartões de KPIs foram configurados com títulos personalizados, tornando a leitura direta e limpa.

## ❓ Perguntas de Negócio Respondidas
O painel financeiro foi estruturado para responder com exatidão às seguintes necessidades de negócio:

1. Qual o Total exato de Receitas e o Total de Despesas?
2. Qual a Margem de Lucro global da operação?
3. Qual o Total de Receitas destrinchado por Componente (Vendas, Licenciamento, etc.)?
4. Qual o Total de Despesas por Componente e como elas se comportam visualmente em relação à linha de Média de Despesas?
5. Como é a distribuição de Receitas e Despesas cruzadas por Componente e Ano?
6. **(IA)** Quais são os segmentos ocultos onde a probabilidade do valor financeiro ser baixo/alto é maior?

## 📸 Visualização do Projeto
<img width="1240" height="700" alt="img_MiniProjeto05" src="https://github.com/user-attachments/assets/7e7f8006-1b3c-4328-a974-ec6ced0beaab" />

---
*Desenvolvido por Michel Urban Rosendo de Lima.*
