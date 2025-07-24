# 🍄 Classificação de Cogumelos Venenosos com MLP

Este repositório contém o trabalho final da disciplina de Deep Learning do programa **Tomorrow/UFBA**, cujo objetivo é aplicar uma rede neural do tipo **MLP (Perceptron Multicamadas)** para classificar se cogumelos são venenosos ou comestíveis, com base em suas características visuais e estruturais.

🔗 [Notebook no Google Colab](https://colab.research.google.com/github/GustavoCruzzz/TrabalhoFinal_DeepLearning_TomorrowUfba/blob/main/TrabalhoFinal_DP_Tomorrow_UFBA.ipynb)

---

## 📊 Objetivo

Desenvolver e treinar uma MLP capaz de identificar cogumelos venenosos utilizando um dataset clássico de aprendizado supervisionado, com dados categóricos e rotulados.

---

## 🧠 Tecnologias e Ferramentas

- Python 3.8+
- TensorFlow 
- Pandas
- Numpy
- Scikit-learn
- Seaborn / Matplotlib

---

## 🔎 Sobre o Dataset

- **Origem**: UCI Machine Learning Repository – [Mushroom Dataset](https://archive.ics.uci.edu/ml/datasets/mushroom)
- **Tamanho**: 8124 instâncias
- **Classes**: 
  - `e` – comestível (edible)
  - `p` – venenoso (poisonous)
- **Atributos**: 22 atributos categóricos (como cor do chapéu, odor, formato do caule etc.)

---

## 🧪 Pipeline do Projeto

1. **Importação e visualização dos dados**
2. **Pré-processamento**
   - Conversão de atributos categóricos (Label Encoding / One-Hot Encoding)
   - Remoção de colunas irrelevantes
3. **Divisão em treino e teste**
4. **Construção da MLP**
   - Camadas densas com funções de ativação ReLU e Sigmoid
   - Regularização e dropout
5. **Treinamento e validação**
6. **Avaliação com métricas**
   - Acurácia, matriz de confusão e curva ROC
7. **Conclusões e observações**

---

## 📈 Resultados Esperados

- Alta acurácia (>95%) na detecção de cogumelos venenosos.
- Classificação eficaz mesmo em presença de atributos ruidosos.
- Generalização avaliada em conjunto de teste.

---
