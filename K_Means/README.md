# 🌸 Clusterização de Flores Iris com K-Means

## 📌 Descrição do Projeto

Este projeto tem como objetivo aplicar o algoritmo **K-Means** para realizar a **clusterização do famoso dataset Iris**, que contém medidas de flores de três espécies diferentes:

- Iris-setosa
- Iris-versicolor
- Iris-virginica

O objetivo é verificar se o algoritmo consegue **agrupar as flores automaticamente** apenas com base nas características numéricas, sem usar os rótulos das espécies.

---

## 📊 Sobre o Dataset

O dataset contém as seguintes colunas:

- SepalLength → Comprimento da sépala
- SepalWidth → Largura da sépala
- PetalLength → Comprimento da pétala
- PetalWidth → Largura da pétala
- Species → Espécie da flor (usada apenas para validação)

Exemplo dos dados:

| SepalLength | SepalWidth | PetalLength | PetalWidth | Species |
|------------|------------|-------------|------------|----------|
| 5.1 | 3.5 | 1.4 | 0.2 | Iris-setosa |

---

## 🧠 O que foi feito no projeto

- Análise exploratória dos dados
- Limpeza e verificação de valores nulos
- Seleção apenas das colunas numéricas
- Normalização dos dados
- Aplicação do método do cotovelo (Elbow Method)
- Cálculo do Silhouette Score
- Treinamento do modelo K-Means
- Visualização dos clusters
- Comparação dos clusters com as espécies reais

---

## 🛠️ Tecnologias Utilizadas

- Python
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Jupyter Notebook

---


---

## 📈 Resultados

O modelo conseguiu separar os dados em **3 clusters**, que correspondem de forma muito próxima às três espécies reais de flores, mostrando a eficiência do K-Means para este tipo de problema.

Também foi utilizada uma **tabela de contingência (crosstab)** para comparar:

- Espécies reais
- Clusters gerados pelo modelo

---

## 🎯 Conclusão

Este projeto demonstra como o **K-Means pode ser usado para descobrir padrões e grupos em dados sem rótulos**, sendo uma técnica poderosa de aprendizado não supervisionado.

---

