# 💳 Credit Card Fraud Detection using Machine Learning

Projeto de **Machine Learning supervisionado** para detecção de fraudes em transações de cartão de crédito.

O objetivo deste projeto é construir e comparar diferentes modelos de classificação capazes de identificar **transações fraudulentas**, utilizando técnicas clássicas de machine learning com a biblioteca **scikit-learn**.

---

# 📌 Contexto

Fraudes em cartões de crédito representam um problema significativo para instituições financeiras e empresas de pagamento digital.

Com o crescimento das transações online, torna-se cada vez mais necessário desenvolver sistemas automatizados capazes de detectar padrões suspeitos em grandes volumes de dados.

Neste projeto, aplicamos algoritmos de **machine learning supervisionado** para classificar transações como:

- **0 → Transação legítima**
- **1 → Fraude**

O sistema desenvolvido pode ser utilizado como **ferramenta de apoio à detecção de fraudes em sistemas financeiros**.

---

# 📊 Dataset

O dataset utilizado é o **Credit Card Fraud Detection Dataset**, contendo transações realizadas por portadores de cartão de crédito na Europa.

Características do dataset:

- **284.807 transações**
- **30 features numéricas**
- **Classificação binária**
- **Dataset altamente desbalanceado**

As variáveis `V1` até `V28` foram obtidas através de **PCA (Principal Component Analysis)** para anonimização dos dados.

Fonte do dataset:

https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

---

# 🧠 Modelos Utilizados

Durante o projeto foram treinados e avaliados diferentes modelos de classificação:

### 🔹 Perceptron
Classificador linear utilizado como **modelo baseline**, permitindo analisar a separabilidade linear do problema.

### 🔹 Decision Tree
Modelo baseado em regras condicionais que divide o espaço de dados em regiões associadas às classes.

### 🔹 Random Forest
Modelo ensemble que combina múltiplas árvores de decisão para melhorar desempenho e reduzir overfitting.

---

# ⚙️ Técnicas Utilizadas

O projeto inclui diversas técnicas importantes de machine learning:

- **Data preprocessing**
- **StandardScaler**
- **Train/Test Split**
- **Cross Validation**
- **Grid Search para otimização de hiperparâmetros**
- **PCA (Principal Component Analysis)**
- **Feature Importance**
- **Avaliação de métricas de classificação**

---

# 📏 Métricas de Avaliação

Os modelos foram avaliados utilizando:

- **Accuracy**
- **Precision**
- **Recall**
- **F1 Score**

Essas métricas são essenciais em problemas de detecção de fraude, onde o custo de erros pode ser elevado.

---

# 📈 Resultados

A comparação entre os modelos mostrou que:

- Modelos lineares simples possuem limitações para capturar padrões complexos.
- Árvores de decisão oferecem maior interpretabilidade.
- **Random Forest apresentou o melhor desempenho geral**, capturando relações não lineares entre as variáveis.

---

# 🧪 Estrutura do Projeto
