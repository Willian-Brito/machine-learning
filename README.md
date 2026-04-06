# 🧠 Machine Learning
**Machine Learning (ML)** é uma área da **Inteligência Artificial** que permite que sistemas aprendam padrões a partir de dados e tomem decisões ou façam previsões sem serem explicitamente programados para cada regra. Em vez de regras fixas, você fornece dados + objetivo → o modelo aprende a “função”.

## 📚 Abordagens
<img src="doc/img/aprendizados.png">

### 🕵🏻 1. Aprendizado Supervisionado

Você tem dados rotulados (entrada + resposta correta).

**👉 Objetivo:** aprender a mapear entrada → saída

<img src="doc/img/aprendizado-supervisionado.png" />

#### Tipos principais:
- **Classificação →** prever categorias **Ex:** spam vs não spam
- **Regressão →** prever valores contínuos **Ex:** preço de casa

#### Algoritmos comuns:
- Regressão Linear
- Regressão Logística
- Árvores de Decisão
- Random Forest
- Gradient Boosting (XGBoost, LightGBM)
- SVM (Support Vector Machine)
- Redes Neurais

#### 📌 Exemplo prático:
Prever se um cliente vai cancelar **(classificação)** ou prever faturamento **(regressão)**

### 🙈 2. Aprendizado Não Supervisionado
Você tem dados sem rótulos.

**👉 Objetivo:** encontrar padrões escondidos

<img src="doc/img/aprendizado-nao-supervisionado.png">

#### Tipos principais:
- **Clusterização →** agrupar dados similares
- **Detecção de Anomalias →** encontrar comportamentos fora do padrão
- **Redução de Dimensionalidade →** simplificar dados
- **Sistemas de Recomendação** (em parte)

#### Algoritmos comuns:
- K-Means
- DBSCAN
- Hierarchical Clustering
- PCA (Principal Component Analysis)
- Autoencoders

#### 📌 Exemplo:
Segmentação de clientes por comportamento


### 🫣 3. Aprendizado Semi-Supervisionado

#### Mistura de:

- poucos dados rotulados
- muitos dados não rotulados

👉 Muito usado quando rotular dados é caro (ex: imagens médicas)

### 🎰 4. Aprendizado por Reforço (Reinforcement Learning)
Um agente aprende interagindo com o ambiente.

<img src="doc/img/aprendizado-por-reforco.png">

#### 👉 Conceitos-chave:
- Estado
- Ação
- Recompensa

#### Algoritmos comuns:
- Q-Learning
- Deep Q-Network (DQN)
- Policy Gradient
- Actor-Critic

#### 📌 Exemplo:
- Jogos (tipo AlphaGo)
- Robótica
- Sistemas de decisão

### 🤔 Quando usar cada abordagem?
- **Supervisionado →** quando você tem histórico com respostas
- **Não supervisionado →** quando quer descobrir padrões
- **Reforço →** quando há tomada de decisão sequencial
- **Semi-supervisionado →** quando rótulos são escassos

### 💡 Resumão rápido
- **Supervisionado:** aprende com resposta
- **Não supervisionado:** encontra padrões
- **Reforço:** aprende por tentativa e erro
- Algoritmos variam conforme problema

## ⚛ Tipos de Algoritmos (organizado por função)

<img src="doc/img/algoritmos-3.png">

### 📊 Classificação

#### Prever classes/categorias:
- Logistic Regression
- Decision Tree
- Random Forest
- SVM
- KNN (K-Nearest Neighbors)
- Naive Bayes
- Redes Neurais (MLP, CNN)

### 📈 Regressão

#### Prever valores contínuos:
- Linear Regression
- Ridge / Lasso
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting

### 🧠 Clusterização

#### Agrupar dados:
- K-Means
- DBSCAN
- Hierárquico

### 🚨 Detecção de Anomalias

#### Identificar outliers:
- Isolation Forest
- One-Class SVM
- LOF (Local Outlier Factor)

### 🎯 Sistemas de Recomendação

#### Sugerir itens:
- Filtragem colaborativa
- Filtragem baseada em conteúdo
- Matrix Factorization

#### 📌 Exemplo:
Netflix, Amazon, Spotify

### 🧬 Algoritmos Bio-inspirados

#### Inspirados na natureza:
- Algoritmos Genéticos
- Particle Swarm Optimization
- Ant Colony Optimization

### 🔽 Redução de Dimensionalidade

#### Simplificar dados:
- PCA
- t-SNE
- UMAP



## 🚀 Pipeline típico de Machine Learning
1. Coleta de dados
1. Limpeza e tratamento
1. Feature engineering
1. Treinamento do modelo
1. Avaliação
1. Deploy
1. Monitoramento

