# 📊 Mini Projeto 02 - Dashboard Comercial de Performance de Vendas

Este projeto foi desenvolvido com foco em Business Intelligence, aplicando conceitos avançados de UI/UX corporativo e design de interfaces para análise de dados.

## 🎯 Objetivo do Projeto
Muito além da criação de gráficos, o objetivo central deste projeto foi atuar simulando uma demanda real de diretoria: transformar dados comerciais brutos em uma interface intuitiva com "cara de sistema" (*app-like*). A meta foi estruturar um ambiente analítico limpo que direcione o olhar do gestor para os KPIs essenciais, identificando os motores de venda, a distribuição geográfica do faturamento e o fluxo de saída de produtos, facilitando assim a tomada de decisão estratégica rápida e assertiva.

## 📂 Fonte de Dados
Para a elaboração deste projeto, foi utilizado o dataset:
* **Dados_Comerciais.xlsx**: Um arquivo transacional bruto contendo registros de vendas, segmentações de clientes (Doméstico, Corporativo, Industrial), hierarquia de produtos (categorias e fabricantes), dados de lojas/vendedores e localizações geográficas.

O arquivo passou por um processo de modelagem de dados e tratamento no **Power Query**, garantindo a integridade dos relacionamentos, seguido pela criação de medidas dinâmicas utilizando a linguagem **DAX**.

## ❓ Possíveis Perguntas de Negócio que podem ser Respondidas
Como é comum em cenários reais de B.I., as perguntas não vieram prontas. O dashboard foi estruturado através de engenharia reversa para responder às seguintes questões vitais para a operação comercial:
* Qual é o faturamento total da companhia e qual a sua proporção entre os diferentes segmentos de atuação?
* Quais fabricantes e categorias de produtos compõem a curva de maior volume de receita?
* Quais são as características exatas (segmento, categoria, etc.) que mais impulsionam o aumento ou a queda do valor de venda (Inteligência Artificial)?
* Como se comporta o fluxo cruzado de distribuição entre os tipos de produtos vendidos e os diferentes pontos de venda (lojas)?
* Qual é o desempenho individual da equipe de vendedores e como essas vendas estão distribuídas geograficamente pelo país?

## ⚙️ Funcionalidades e Estrutura Analítica
Para evitar a sobrecarga cognitiva e garantir uma navegação imersiva, o painel foi construído utilizando um *Design System* padronizado (paleta em Azul Marinho, fundo Cinza e destaques em Verde), dividido em **1 Menu Principal de Navegação (com botões de *hover*)** e **4 Visões Estratégicas**:

1. **Visão de Detalhamento Geral:** Focada na visão macro do negócio, destacando o Big Number financeiro e o ranqueamento de categorias.
2. **Visão de Principais Influenciadores:** Focada no uso de Inteligência Artificial nativa do Power BI para encontrar padrões ocultos e correlações de vendas.
3. **Visão de Vendas por Categoria e Pontos:** Focada na análise complexa de fluxo de dados através do gráfico avançado de *Sankey*.
4. **Visão de Performance por Região:** Focada na performance da equipe de vendas atrelada a uma visualização geográfica limpa e contrastante.

## 📸 Visualização do Projeto

**1. Capa e Navegação (Menu Principal):**
<img width="1217" height="686" alt="Indice" src="https://github.com/user-attachments/assets/9aa235ef-a713-4880-8495-6b83ed8fb404" />

**2. Visão Detalhamento Geral:**
<img width="1220" height="688" alt="pag1" src="https://github.com/user-attachments/assets/77c7af2c-7cce-4181-818d-e3e645170a76" />

**3. Visão Principais Influenciadores:**
<img width="1218" height="685" alt="pag2" src="https://github.com/user-attachments/assets/87ade4fe-5945-45e0-bfc0-df8e989c92c2" />

**4. Visão Vendas Por Categoria e Pontos (Sankey):**
<img width="1214" height="685" alt="pag3" src="https://github.com/user-attachments/assets/ce76c2b5-6581-418a-be2a-91a32cf722c2" />

**5. Visão Performance por Região (Mapa):**
<img width="1219" height="685" alt="pag4" src="https://github.com/user-attachments/assets/8c6a886f-a6e3-49dd-902e-cb92060e488f" />

---
*Desenvolvido por Michel Urban Rosendo de Lima.*
