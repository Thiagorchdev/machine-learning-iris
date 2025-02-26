🌿 Projeto de Machine Learning com o Dataset Iris
📌 Introdução
Este projeto utiliza Aprendizado de Máquina para classificar flores do gênero Iris com base em suas características físicas. Foram aplicadas técnicas de clusterização e classificação para análise dos dados.

📊 Dataset
O conjunto de dados Iris contém 150 amostras de flores distribuídas em três espécies:

Setosa
Versicolor
Virginica
Cada amostra possui quatro características preditivas:

Comprimento da sépala (sepal_length)
Largura da sépala (sepal_width)
Comprimento da pétala (petal_length)
Largura da pétala (petal_width)
🔍 Coleta de Dados
Os dados foram carregados diretamente da biblioteca seaborn usando:

import seaborn as sns
iris = sns.load_dataset('iris')
🏗 Modelagem
Foram aplicadas duas abordagens principais:

1️⃣ Clusterização (K-Means) → Para agrupar as flores sem utilizar rótulos.
2️⃣ Classificação (Random Forest) → Para prever a espécie da flor com base em seus atributos.

📌 Algoritmos Utilizados
K-Means Clustering
Random Forest Classifier
📈 Avaliação do Modelo
O modelo de classificação foi avaliado utilizando:
✅ Acurácia → Mede o percentual de previsões corretas.
✅ Matriz de Confusão → Mostra os acertos e erros por categoria.

Acurácia do modelo: 98%

🔥 Matriz de Confusão
![image](https://github.com/user-attachments/assets/18304d00-d576-4b68-b004-0f686b38767d)


📊 Visualizações
Foram gerados gráficos para melhor compreensão dos dados e do modelo:
✅ Pairplot com clusters identificados
✅ Gráficos de dispersão das variáveis preditivas

📂 Como Rodar o Projeto
Para executar o projeto localmente, siga os passos:

1️⃣ Clone o repositório:

git clone https://github.com/Thiagorchdev/machine-learning-iris.git
cd iris-ml-classification
2️⃣ Instale as dependências:

pip install -r requirements.txt
3️⃣ Execute o notebook ou script Python:

python main.py
📜 Conclusões
O modelo apresentou excelente desempenho na classificação das espécies de Iris. A clusterização também identificou padrões naturais entre as flores, confirmando a separação em três grupos.

🛠 Tecnologias Utilizadas
Python 3.x
Pandas, NumPy, Seaborn, Matplotlib
