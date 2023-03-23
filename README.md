# Student-Analysis

### Visão geral
Este projeto é uma análise de dados que visa classificar a adaptabilidade dos alunos em educação online. O dataset utilizado foi obtido a partir do Kaggle, [link para o dataset](https://www.kaggle.com/datasets/mdmahmudulhasansuzan/students-adaptability-level-in-online-education).

### Dependências
As seguintes bibliotecas do Python são necessárias para executar o código:
* pandas
* numpy
* scipy
* matplotlib
* scikit-learn

### Como usar
O arquivo students_adaptability_level_online_education.ipynb contém o código completo utilizado neste projeto, desde a leitura dos dados até a criação do modelo de classificação. Basta abrir este arquivo no Jupyter Notebook ou no Google Colab e executar cada célula sequencialmente para reproduzir os resultados obtidos.

### Resultados
Utilizamos o GridSearchCV para encontrar os melhores parâmetros para o modelo de classificação DecisionTreeClassifier. Após o treinamento do modelo, obtivemos as seguintes métricas:

Dados do treino:

              precision    recall  f1-score   support

           0       1.00      1.00      1.00       204
           1       1.00      1.00      1.00       276

    accuracy                           1.00       480
    macro avg      1.00      1.00      1.00       480
    weighted avg   1.00      1.00      1.00       480

Dados do teste:

              precision    recall  f1-score   support

           0       0.92      0.93      0.92        28
           1       0.96      0.96      0.96        68

    accuracy                           0.95        96
    macro avg      0.94      0.94      0.94        96
    weighted avg   0.95      0.95      0.95        96

    Acuracidade:  0.9479166666666666

A acurácia do modelo foi de 0.9479, o que indica que ele é capaz de classificar com precisão se um aluno é ou não adaptável à educação online.
