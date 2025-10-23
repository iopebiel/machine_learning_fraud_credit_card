# modelos fraudes cartão de crédito

## Logistic Regression LR
- Scikit Learn -> cuml.linear_model.LogisticRegression
- CuML RAPIDS -> sklearn.linear_model.LogisticRegression

## Random Forest RF
- Scikit Learn -> sklearn.ensemble.RandomForestClassifier
- CuML RAPIDS  -> cuml.ensemble.RandomForestClassifier

## FeedFoward Neural Network FNN
- biblioteca Torch
- MLP com dropout e EarlyStopping de monitoramento de perda na validação


## Base de dados e Preparação
fonte: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud
- Aplicação do SMOTE-ENN (sobreamostragem e subamostrem) em conjuntos novos de treinamento com proporções 10:90 e 50:50