# Análise de Evasão de Clientes — Telecom X

##  Sobre o Projeto

Este projeto tem como objetivo analisar os dados da empresa fictícia **Telecom X**, a fim de identificar padrões e variáveis associadas à **evasão de clientes (churn)**.

##  Objetivo da Análise

A Telecom X vem enfrentando um aumento na taxa de cancelamento de contratos por parte dos clientes. O objetivo desta análise é:

- Investigar as principais causas da evasão.
- Identificar os perfis de clientes mais propensos ao churn.
- Propor ações baseadas em dados para reduzir a perda de clientes.

---

##  Etapas do Projeto

### 1. Importação e Limpeza dos Dados
- Leitura do dataset com 21 colunas e mais de 7 mil registros.
- Tratamento de valores ausentes e conversão de tipos incorretos (ex: `TotalCharges`).
- Criação de colunas auxiliares, como faixas de tempo de contrato.

### 2. Análise Exploratória de Dados (EDA)
- Análise descritiva das variáveis numéricas e categóricas.
- Cálculo de correlação entre variáveis (inclusive variáveis booleanas).
- Visualizações com Seaborn e Matplotlib:
  - Boxplots
  - Histogramas com separação por churn
  - Gráficos de barras e mapas de calor

### 3. Conclusões e Insights
- Clientes com contratos do tipo `Month-to-month` apresentam maior taxa de churn.
- Novos clientes (com pouco tempo de contrato) tendem a cancelar com mais frequência.
- A falta de fidelização nos primeiros meses é um fator crítico.

### 4. Recomendações
- Implementar **benefícios progressivos** para novos clientes.
- Estimular a migração para contratos mais longos (anual ou bienal).
- Monitorar os primeiros meses de uso para ações proativas de retenção.
- Avaliar métodos de pagamento e serviços combinados como fatores de fidelização.

