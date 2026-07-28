🧠 Modelagem Preditiva de Tumores Mamários com Redes Neurais (MLP)

Este projeto apresenta o desenvolvimento de um modelo de Machine Learning baseado em Redes Neurais Artificiais para a classificação de tumores mamários em benignos e malignos, utilizando o conjunto de dados Wisconsin Diagnostic Breast Cancer.

O objetivo é avaliar o desempenho de diferentes arquiteturas de redes neurais na tarefa de classificação binária, analisando métricas de desempenho relevantes para aplicações médicas, como Acurácia, Precisão, Recall, F1-Score e AUC-ROC.


Objetivos:

Desenvolver modelos de Redes Neurais Artificiais para classificação de tumores mamários.
Comparar diferentes arquiteturas MLP.
Avaliar o impacto da profundidade da rede no desempenho do modelo.
Aplicar boas práticas de pré-processamento e validação para evitar overfitting.
Demonstrar a aplicação de Inteligência Artificial como ferramenta de apoio ao diagnóstico médico.

Base de Dados:

O projeto utiliza o Wisconsin Diagnostic Breast Cancer (WDBC), disponível na biblioteca scikit-learn.
Características do conjunto de dados:
569 amostras
30 atributos numéricos extraídos de exames de Punção Aspirativa por Agulha Fina (FNA)
Classificação binária:
Benigno
Maligno

⚙️ Metodologia

O pipeline desenvolvido inclui:

Divisão estratificada dos dados (80% treino e 20% teste)
Padronização dos atributos com StandardScaler
Construção de três arquiteturas MLP com diferentes números de camadas e neurônios
Regularização utilizando Dropout
Treinamento com:
Otimizador Adam
Função de perda Binary Crossentropy
Early Stopping
Avaliação no conjunto de teste

📈 Métricas Avaliadas
Foram utilizadas as seguintes métricas:

Acurácia
Precisão
Recall (Sensibilidade)
F1-Score
AUC-ROC

Além disso, foram geradas visualizações como:
Matriz de Confusão
Curva ROC
Curva Precision-Recall


🛠️ Tecnologias Utilizadas
Python
NumPy
Pandas
Matplotlib
Scikit-learn
TensorFlow / Keras
Google Colab

📁 Estrutura do Projeto
├── notebook.ipynb       
├── README.md              
├── images/                 
│   ├── matriz_confusao.png
│   ├── curvas_ROC_e_Recall.png


Resultados:
Os experimentos demonstraram que todas as arquiteturas apresentaram elevado desempenho na classificação dos tumores. O modelo intermediário (MLP_B) obteve o melhor equilíbrio entre capacidade de generalização e custo computacional, alcançando valores elevados de Acurácia, Recall e AUC-ROC, mostrando o potencial das Redes Neurais como ferramenta de apoio ao diagnóstico médico.

🎓 Projeto Acadêmico

Este projeto foi desenvolvido para a disciplina de Sistemas Inteligentes II, com foco na aplicação de Redes Neurais Artificiais em problemas de classificação na área da saúde.
