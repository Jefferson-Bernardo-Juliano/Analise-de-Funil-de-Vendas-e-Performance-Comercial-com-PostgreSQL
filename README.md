# 📊 Análise de Funil de Vendas e Performance Comercial com PostgreSQL

## 📌 Visão Geral
Este projeto tem como objetivo analisar o **funil de vendas** e o **desempenho comercial** de uma empresa a partir de dados de visitas, clientes, produtos e pagamentos, utilizando **PostgreSQL** como principal ferramenta de análise.

A análise é totalmente orientada a SQL, explorando métricas essenciais para tomada de decisão, como **receita**, **taxa de conversão**, **ticket médio** e **comportamento temporal e geográfico dos clientes**.

---

## 🎯 Objetivos do Projeto
- Analisar a evolução mensal de:
  - Leads
  - Vendas
  - Receita
  - Taxa de conversão
  - Ticket médio
- Avaliar a performance comercial por **estado** 
- Identificar padrões de acesso por:
  - Dia da semana
  - Períodos do mês
- Entender o comportamento do cliente ao longo do funil de vendas

---

## 🛠️ Tecnologias Utilizadas
- **PostgreSQL**
- **SQL Avançado**
  - CTEs (`WITH`)
  - `JOINs`
  - Funções de agregação (`COUNT`, `SUM`, `AVG`)
  - Funções de data (`DATE_TRUNC`, `EXTRACT`)
  - `CASE WHEN`
- **Análise de Dados**

---

## 🗂️ Estrutura do Banco de Dados
As análises foram realizadas a partir das seguintes tabelas:

- **sales.funnel**  
  Dados de visitas, leads e conversões
- **sales.customers**  
  Informações demográficas dos clientes
- **sales.products**  
  Informações dos produtos
- **sales.payments**  
  Dados financeiros e de receita

---

## 📈 Principais Análises

### 📅 Análise Mensal
- Total de visitas
- Total de vendas
- Receita mensal
- Taxa de conversão (%)
- Ticket médio

> Permite avaliar o crescimento do negócio e a eficiência do funil de vendas ao longo do tempo.

---

### 🌍 Análise Geográfica
- Quantidade de visitas por estado
- Ranking de estados e cidades com maior volume de acessos

> Apoia decisões estratégicas de marketing e expansão regional.

---

### ⏱️ Análise Temporal
- Distribuição de visitas por dia da semana
- Identificação de períodos com maior volume de acessos

> Auxilia na definição de campanhas e ações comerciais mais eficientes.

---


## 🚀 Principais Insights
- Identificação de meses com maior volume de vendas e conversão
- Estados e cidades com maior potencial comercial
- Dias da semana mais estratégicos para ações de marketing
- Melhor compreensão do comportamento do cliente no funil
