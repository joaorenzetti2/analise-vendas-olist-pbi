# Dashboard de Vendas E-commerce (Olist) - Power BI

Este projeto foi desenvolvido para demonstrar habilidades em tratamento, modelagem e visualização de dados.

## 🚀 Objetivo
Analisar o desempenho de vendas, logística e comportamento de clientes do e-commerce brasileiro (Dataset Olist), fornecendo insights sobre faturamento, ticket médio e distribuição geográfica

## 🛠️ Tecnologias e Ferramentas
* **Power BI:** Construção do dashboard e medidas DAX
* **Power Query (M):** ETL e limpeza de dados
* **Modelagem:** Star Schema (Esquema Estrela)
* **Dataset:** [Olist Brazilian E-Commerce](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

## 📋 Processo de Desenvolvimento

### 1. Tratamento de Dados (ETL)
No Power Query, realizei as seguintes etapas:
* Padronização de tipos de dados (Datas e Valores monetários)
* Tratamento de valores nulos em colunas de entrega
* Criação de colunas condicionais para categorização de pagamentos
* Criação de uma tabela **dCalendario** customizada para análises temporais

### 2. Modelagem de Dados
Utilizei o conceito de **Star Schema**, conectando tabelas de dimensões (Clientes, Produtos, Calendário) à tabela fato (Vendas) através de relacionamentos 1:N

### 3. Métricas Criadas (DAX)
* **Total de Vendas:** Soma do preço dos itens vendidos
* **Total de Pedidos:** Contagem distinta de IDs de pedidos
* **Ticket Médio:** Razão entre o faturamento total e o número de pedidos

## 📊 Visualização
<img width="1411" height="792" alt="dashboard" src="https://github.com/user-attachments/assets/902eba85-ce4c-435d-8ffe-e43441056efd" />
