# 📊 Desafio Telecom X – Análise de Evasão de Clientes

Este repositório contém o notebook **`Challege_TelecomX_2.ipynb`**, que realiza uma análise detalhada da evasão de clientes (**churn**) de uma empresa fictícia do setor de telecomunicações, chamada **Telecom X**. O objetivo principal é entender os fatores que influenciam o cancelamento de serviços por parte dos clientes e propor soluções baseadas em dados.

---

## 📁 Arquivo Principal

- **`Challege_TelecomX_2.ipynb`**  
  Contém todo o pipeline de análise, desde a extração dos dados até a geração de insights e recomendações.

---

## 🧱 Estrutura do Projeto

O notebook é dividido nas seguintes seções:

### 1. **Introdução**
Explica o objetivo da análise, a relevância do problema de churn e o contexto do desafio.

### 2. **ETL (Extração, Transformação e Carga)**
- Extração de dados via API no formato JSON.
- Normalização de colunas aninhadas (`customer`, `internet`, `account`).
- Tratamento de dados inconsistentes, como strings vazias e tipos incorretos.
- Criação de novas variáveis como `account_Charges.Daily`.

### 3. **Análise Exploratória de Dados (EDA)**
- Análise estatística descritiva das variáveis numéricas.
- Estudo de variáveis categóricas com relação ao churn.
- Gráficos de boxplot, barras e heatmap para visualização de padrões.

### 4. **Principais Resultados**
- Churn mais frequente em contratos mensais e pagamentos via `Electronic check`.
- Menor churn entre clientes com serviços de segurança e suporte técnico.
- Gastos totais e tempo de contrato menores entre clientes que evadem.
- Forte correlação entre `customer_tenure` e `account_Charges.Total`.

### 5. **Conclusões e Recomendações**
- Estimular contratos de longo prazo.
- Oferecer valor agregado (ex.: suporte técnico, segurança).
- Reavaliar experiência dos clientes com fatura online e débito eletrônico.
- Fundamento pronto para criação de modelos preditivos.

---

## 📌 Tecnologias Utilizadas

- **Linguagem:** Python 3.x  
- **Bibliotecas:** `pandas`, `numpy`, `requests`, `json`, `matplotlib`, `seaborn`  
- **Ambiente:** Google Colab / Jupyter Notebook

---

## 🧠 Requisitos para Execução

Para rodar o notebook localmente, certifique-se de ter:

- Python 3.x instalado
- Jupyter ou Google Colab configurado
- As bibliotecas listadas instaladas (`pip install -r requirements.txt`)

---

## 📚 Referências

- Desafio fictício proposto para prática de análise de dados.
- Dados no formato JSON com estrutura hierárquica simulando API.

---

## 👤 Autor

**Marcone Tenório da Silva**  
Projeto desenvolvido como parte do processo de aprendizagem em **Ciência de Dados** com foco em **Engenharia de Dados e Modelagem Preditiva**.

---

## 📬 Contato

Caso queira contribuir ou discutir melhorias, entre em contato pelo GitHub ou outro canal informado.

---
