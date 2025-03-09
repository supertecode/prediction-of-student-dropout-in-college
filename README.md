# Student Situation Analysis Project

## 🇺🇸 English

### Overview
This project uses machine learning classification models to predict the current situation of students based on various demographic and academic factors. The goal is to identify patterns that may affect student outcomes and potentially enable early intervention strategies.

### Data Processing
- Data was previously cleaned and processed using Power BI
- Label encoding applied to binary categorical variables: Gender, Public School, Course, Current Student Situation
- One-hot encoding applied to categorical variables without fixed order: City, State, Admission Form, Ethnic Group, Quota Type
- Feature 'id' was dropped from the dataset

### Methodology
#### Data Balancing
- Class imbalance addressed using RandomUnderSampler to balance classes by randomly removing samples from the majority class

#### Models Evaluated
- Random Forest Classifier
- Extra Trees Classifier
- Logistic Regression (with data normalization)

#### Evaluation Methods
- Holdout validation (70% training, 30% testing)
- 5-fold cross-validation

#### Performance Metrics
- Accuracy
- Precision
- Recall
- F1-score
- Confusion matrix

### Visualizations
- Boxplot for ENEM scores
- Confusion matrices for each model

### Dependencies
- pandas
- scikit-learn
- imbalanced-learn
- matplotlib
- seaborn

---

## 🇧🇷 Português

### Visão Geral
Este projeto utiliza modelos de classificação de aprendizado de máquina para prever a situação atual dos alunos com base em diversos fatores demográficos e acadêmicos. O objetivo é identificar padrões que possam afetar os resultados dos estudantes e potencialmente permitir estratégias de intervenção precoce.

### Processamento de Dados
- Dados previamente limpos e processados usando Power BI
- Label encoding aplicado a variáveis categóricas binárias: Sexo, Escola Pública, Curso, Situação Atual do Aluno
- One-hot encoding aplicado a variáveis categóricas sem ordem fixa: Cidade, Estado, Forma de Ingresso, Grupo (Étnico), Tipo de Cota
- A feature 'id' foi removida do dataset

### Metodologia
#### Balanceamento de Dados
- Desbalanceamento de classes tratado utilizando RandomUnderSampler para equilibrar as classes removendo aleatoriamente amostras da classe majoritária

#### Modelos Avaliados
- Random Forest Classifier
- Extra Trees Classifier
- Regressão Logística (com normalização de dados)

#### Métodos de Avaliação
- Validação holdout (70% treinamento, 30% teste)
- Validação cruzada com 5 folds

#### Métricas de Desempenho
- Acurácia
- Precisão
- Recall
- F1-score
- Matriz de confusão

### Visualizações
- Boxplot para as notas do ENEM
- Matrizes de confusão para cada modelo

### Dependências
- pandas
- scikit-learn
- imbalanced-learn
- matplotlib
- seaborn
