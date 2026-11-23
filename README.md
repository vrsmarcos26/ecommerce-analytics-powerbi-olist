# 📊 E-Commerce Analytics: Olist Brazilian Market

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Data Science](https://img.shields.io/badge/Data_Science-150458?style=for-the-badge&logo=data-science&logoColor=white)
![DAX](https://img.shields.io/badge/DAX-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)
![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-181717?style=for-the-badge&logo=github&logoColor=white)

> 🌐 **Acesse a vitrine interativa do projeto:** [vrsmarcos26.github.io/ecommerce-analytics-powerbi-olist](https://vrsmarcos26.github.io/ecommerce-analytics-powerbi-olist/) *(disponível em PT-BR / EN com modo claro e escuro)*

---

## 📌 Visão Geral do Projeto
Este projeto de Ciência de Dados analisa o comportamento operacional, logístico e financeiro do e-commerce brasileiro utilizando o banco de dados público da **Olist** (via Kaggle). O objetivo foi aplicar o ciclo completo da metodologia **KDD (Knowledge Discovery in Databases)** — da extração e limpeza à visualização executiva — estruturando mais de **20 KPIs estratégicos** em um dashboard interativo de 3 camadas no Power BI.

Projeto desenvolvido como trabalho de conclusão da disciplina de Ciência de Dados do **Centro Universitário de Brasília (CEUB)**.

---

## 🛠️ Ferramentas e Metodologia
* **Metodologia KDD:** Seleção, pré-processamento, transformação, mineração de padrões e interpretação de resultados.
* **Microsoft Power BI:** Construção do dashboard e arquitetura de visualização em 3 níveis (*Executiva*, *Analítica* e *Exploratória*).
* **Power Query (M):** Pipeline de ETL, tratamento de valores nulos, tipagem e modelagem relacional.
* **Linguagem DAX:** Criação de medidas dinâmicas, inteligência de tempo, cálculos iterativos e formatação condicional.
* **Front-end (HTML5 / CSS3 / JS):** Página web responsiva (`index.html`) hospedada via GitHub Pages para embarcar o relatório público do Power BI.

---

## 🗂️ Arquitetura de Dados & Estrutura do Repositório

Foram utilizados dois datasets principais integrados via chave relacional (`order_id`):
1. `olist_orders_dataset`: Histórico de status dos pedidos, carimbos de tempo e desempenho logístico.
2. `olist_order_payments_dataset`: Transações financeiras, parcelamentos e meios de pagamento.

**Volume Analisado:** ~99,4 mil pedidos validados, totalizando **R$ 16,0 Milhões** em receita bruta.

```text
ecommerce-analytics-powerbi-olist/
├── Projeto_CD.pbix     # Arquivo fonte do Power BI com dados embarcados e medidas DAX
├── index.html          # Página web executiva (bilíngue PT/EN + Dark/Light mode)
├── Executivo.png       # Captura da camada 1: Visão Executiva
├── Analitico.png       # Captura da camada 2: Visão Analítica
├── Exploratico.png     # Captura da camada 3: Visão Exploratória
├── LICENSE             # Licença do repositório
└── README.md           # Documentação do projeto
