# 🎬 Analiza sentymentu recenzji filmowych z ML

Projekt demonstruje klasyfikację sentymentu recenzji filmowych (pozytywny/negatywny) za pomocą uczenia maszynowego na przykładowym zbiorze 50K recenzji z IMDB.

**Zbiór danych**: [IMDB Dataset of 50K Movie Reviews](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)

## 🛠️ Technologie
- Python 3.x
- scikit-learn (Logistic Regression, Naive Bayes, Linear SVM)
- pandas, numpy  
- TF-IDF wektoryzacja tekstu

## 📊 Wyniki
| Model              | Accuracy |
|--------------------|----------|
| Logistic Regression| 89.0%   |
| Naive Bayes        | 85.9%   |
| Linear SVM         | 88.2%   |

## 📝 Opis
Model przetwarza surowy tekst recenzji: preprocessuje dane, stosuje TF-IDF do wektoryzacji, a następnie trenuje klasyfikatory.

**Pliki**:

- [notebook.ipynb](sentiment_analysis_ML.ipynb) - Google Colab notebook
