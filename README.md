🍷 Classificação de Vinhos com Machine Learning
Este repositório contém um código para a classificação de vinhos, utilizando Aprendizado de Máquina com a biblioteca scikit-learn. O modelo foi treinado com o conjunto de dados wine disponível no sklearn.datasets, aplicando Support Vector Machine (SVM) e técnicas de pré-processamento para otimizar a precisão da classificação.

📊 Descrição do Projeto
O objetivo deste projeto é classificar diferentes tipos de vinho com base em suas características químicas. Para isso, foram aplicadas as seguintes etapas:

✔ Carregamento dos dados: load_wine do sklearn.datasets.
✔ Pré-processamento: Normalização dos dados com StandardScaler.
✔ Divisão do conjunto de dados: Separação em treino e teste (train_test_split).
✔ Treinamento do modelo: Algoritmo SVM (Support Vector Machine).
✔ Otimização dos hiperparâmetros: GridSearchCV.
✔ Avaliação do modelo: Relatórios de classificação e matriz de confusão.

🛠 Tecnologias Utilizadas
Python 🐍
scikit-learn (Machine Learning)
NumPy (Manipulação de arrays)
Pandas (Análise e manipulação de dados)
Matplotlib e Seaborn (Visualização de dados)
