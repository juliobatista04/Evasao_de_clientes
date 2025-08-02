# 📊 Análise de Evasão de Clientes (Churn)

Este projeto tem como objetivo analisar os fatores que influenciam a **evasão de clientes** em uma base de dados de uma empresa de serviços. Através de visualizações gráficas, estatísticas descritivas e análise de correlação, buscamos identificar padrões que possam ajudar na retenção de clientes.

---

## 📌 Objetivos

- Analisar a distribuição de cancelamentos por **gênero** e **forma de pagamento**.
- Investigar o impacto de **variáveis numéricas** (como tempo de contrato e total gasto) na evasão.
- Explorar a **correlação** entre variáveis para identificar fatores críticos.
- Criar visualizações **profissionais e interpretáveis** para comunicação dos insights.

---

## 📊 Principais Análises Realizadas

### 1. 📌 Evasão por Gênero
- Visualização com barras horizontais e contagem total por gênero.
- Homens apresentam taxa de evasão maior que mulheres.

### 2. 💳 Evasão por Forma de Pagamento
- Clientes com **cheque eletrônico** apresentaram maior índice de churn.

### 3. 📈 Distribuição de Variáveis Numéricas
- Análise com **boxplot** e **violin plot** para:
  - Tempo de contrato (`meses_contrato`)
  - Faturamento total (`faturamento_total`)
- Clientes que saíram tendem a ter contratos mais curtos e menor faturamento acumulado.

### 4. 🔄 Correlação entre Variáveis
- Cálculo da matriz de correlação.
- Principais correlações negativas com evasão:
  - `tempo de contrato` (-0.34)
  - `suporte técnico`, `segurança online`, `dependentes`
- Correlações positivas com evasão:
  - `contas_diarias` e `fatura_online`

---

## 🧰 Tecnologias Utilizadas

- **Python 3.11+**
- **Pandas**
- **Matplotlib & Seaborn** (para gráficos)
- **Jupyter Notebook** (ambiente de desenvolvimento)

---

## 🧠 Insights Relevantes

- Clientes com contratos curtos e poucos serviços contratados são mais propensos a cancelar.
- Foco em clientes com fatura online e débito automático pode melhorar retenção.
- Recursos como segurança online e suporte técnico estão associados à permanência.

---

## 🚀 Próximos Passos

- Construção de modelos preditivos (classificação).
- Implementação de dashboards interativos com Streamlit ou Power BI.
- Ações para retenção baseadas em segmentação de clientes.

---

## 📎 Créditos

Projeto desenvolvido por **Julio**, desenvolvedor com foco em Ciência de Dados.


