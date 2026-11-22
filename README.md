# 📊 E-Commerce Analytics: Olist Brazilian Market

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Data Science](https://img.shields.io/badge/Data_Science-150458?style=for-the-badge&logo=data-science&logoColor=white)
![DAX](https://img.shields.io/badge/DAX-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)

## 📌 Visão Geral do Projeto
Este projeto de Ciência de Dados analisa o comportamento operacional e financeiro do e-commerce brasileiro utilizando o banco de dados público da **Olist** (via Kaggle). O objetivo foi aplicar o ciclo completo de análise de dados — da extração e limpeza à visualização executiva — estruturando mais de 20 KPIs estratégicos em um dashboard interativo no Power BI.

Projeto desenvolvido como requisito prático para a disciplina de Ciência de Dados do **Centro Universitário de Brasília (CEUB)**.

## 🛠️ Ferramentas e Tecnologias
* **Microsoft Power BI:** Construção do dashboard e arquitetura de visualização em 3 níveis (Executiva, Analítica, Exploratória).
* **Power Query (M):** Processamento de ETL, tratamento de valores nulos e padronização de tipos de dados.
* **Linguagem DAX:** Modelagem de dados e criação de métricas dinâmicas (Inteligência de Tempo, Cálculos Iterativos e Formatação Condicional).

## 🗂️ Arquitetura de Dados (Pipeline)
Foram utilizados dois datasets principais integrados via relacionamento relacional (`order_id`):
1. `olist_orders_dataset`: Histórico de status, carimbos de tempo e logística.
2. `olist_order_payments_dataset`: Transações financeiras, parcelamentos e meios de pagamento.

**Volume Analisado:** ~99,4 mil pedidos validados, totalizando R$ 16,0 Milhões em receita.

## 📈 Estrutura do Dashboard

### 1. Visão Executiva (Estratégico)
Foco em faturamento, ticket médio e comportamento macro de pagamentos.
![Visão Executiva](Executivo.png)

### 2. Visão Analítica (Tático e Correlações)
Detalhamento de gargalos logísticos, taxas de conversão por status e análise de regressão linear (Ticket Médio vs. Volume).
![Visão Analítica](Analitico.png)

### 3. Visão Exploratória (Causa Raiz)
Análise profunda com uso de Árvore Hierárquica em 4 níveis (Status > Pagamento > Parcelas > Ano) e gráfico de cascata para variação mensal.
![Visão Exploratica](Exploratico.png)

## 💡 Principais Insights Extraídos
1. **Dependência do Crédito:** O cartão de crédito representa **78,3%** do faturamento total (R$ 12,1 Mi), apontando para a necessidade de estratégias focadas em limite e parcelamento (com destaque para o volume de compras em 10x).
2. **Eficiência Logística:** O índice de confiabilidade operacional é altíssimo, com **97,02%** de taxa de entrega (96,5 mil pacotes) e cancelamentos controlados abaixo de 0,7%.
3. **Comportamento de Compra:** A análise de correlação demonstra que picos de Ticket Médio (acima de R$ 160) tendem a comprimir o volume de pedidos, sugerindo oportunidades para campanhas de *cross-selling* voltadas a equilibrar ambas as métricas.

## 🚀 Como Executar o Projeto
1. Clone este repositório: `git clone https://github.com/vrsmarcos26/ecommerce-analytics-powerbi-olist.git`
2. Certifique-se de ter o [Microsoft Power BI Desktop](https://powerbi.microsoft.com/desktop/) instalado (versão gratuita).
3. Abra o arquivo `Projeto_CD.pbix`.
4. Os datasets já estão embarcados no modelo. Basta navegar pelas abas inferiores para interagir com o dashboard.<img width="1442" height="816" alt="Executivo" src="https://github.com/user-attachments/assets/822fa4ef-b6c1-4d56-bf65-5ec0845dd481" />


---
**Autor:** Marcos Vinícius  
*Acesse o arquivo PDF anexo neste repositório para conferir o relatório completo de apresentação do projeto.*
