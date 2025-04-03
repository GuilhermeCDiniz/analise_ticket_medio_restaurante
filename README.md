# 🍔 Análise de Ticket Médio e Segmentação de Clientes com RFM

Este projeto utiliza **Python + Estatística** para analisar o **ticket médio de um restaurante**, identificar padrões de consumo e propor **estratégias para aumentar o faturamento** com base em segmentações inteligentes.

---

## 📌 Objetivo

Responder perguntas de negócio com base em dados de vendas:
- Qual o ticket médio por dia, semana e mês?
- Como ele varia por horário e dia da semana?
- Quais produtos contribuem para um ticket mais alto?
- Clientes recorrentes gastam mais que os novos?
- A campanha na 3ª semana do mês teve impacto?
- Quais oportunidades existem para **upsell e cross-sell**?

---

## 🛠️ Tecnologias Utilizadas

- 📊 **Pandas** e **NumPy** – tratamento e manipulação de dados
- 📈 **Matplotlib** e **Seaborn** – visualizações
- 📐 **Scipy.stats** – testes estatísticos
- 🎯 **RFM Scoring** – segmentação de clientes
- 🧠 **Estatística Descritiva** – medidas como média, desvio padrão, quartis

---

## 🔍 Análises Realizadas

### 1️⃣ Estatística Descritiva do Ticket Médio
Visualização da distribuição do ticket médio com:
- Histograma
- Boxplot
- Curva de Densidade

### 2️⃣ Análises Segmentadas
- Ticket médio por **método de pagamento**, **horário** e **dia da semana**
- Verificação do impacto da campanha com **teste de hipótese (T-Test)**

### 3️⃣ Segmentação com RFM (Recência, Frequência, Valor)
Cada cliente recebeu um **score de 3 a 15** e foi classificado como:
- **Cliente VIP**
- **Cliente Leal**
- **Cliente Regular**
- **Cliente em Risco**

Com isso, conseguimos personalizar ações de marketing e fidelização 🎯

### 4️⃣ Estratégias de Upsell e Cross-Sell
- Identificação de **produtos frequentemente comprados juntos**
- Sugestões práticas de combos para aumentar o ticket médio

---

## 💡 Principais Insights

- O ticket médio varia significativamente por método de pagamento e horário
- A campanha analisada **não teve impacto estatístico**
- Clientes **VIP representam uma fatia pequena, mas lucrativa**
- **Produtos combinados** geram grandes oportunidades de upsell

---

## ✅ Resultados Esperados

Com as estratégias sugeridas:
- Aumentar o ticket médio por cliente
- Reter clientes fiéis
- Reativar clientes inativos
- Melhorar as campanhas futuras com base em dados

---

## 🧠 Como Rodar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/nome-do-repo.git
   cd nome-do-repo
