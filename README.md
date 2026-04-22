# Travaux Pratiques - Traitement du Langage Naturel (NLP)

Ce dépôt contient l'ensemble des travaux pratiques réalisés dans le cadre du module de **NLP (Natural Language Processing)**. L'objectif de ces TPs est de maîtriser les différentes étapes de la chaîne de traitement du texte, de l'analyse lexicale aux modèles de deep learning.

## Contenu du dépôt

Le projet est structuré par étapes progressives, couvrant les concepts fondamentaux et avancés du NLP :

### 1. Prétraitement du texte (Text Preprocessing)
* Nettoyage des données (suppression des caractères spéciaux, ponctuation).
* Tokenisation (mots et phrases).
* Suppression des mots vides (Stopwords).
* Normalisation : Lemmatisation et Racinisation (Stemming).

### 2. Représentation Vectorielle (Word Embeddings)
* Implémentation de modèles classiques : **Bag of Words (BoW)** et **TF-IDF**.
* Exploration de modèles statiques : **Word2Vec** (Skip-gram, CBOW), **GloVe** ou **FastText**.

### 3. Analyse de Sentiment et Classification
* Utilisation d'algorithmes de Machine Learning (Naïve Bayes, SVM, Random Forest).
* Évaluation des performances (Matrice de confusion, F1-score, Précision, Rappel).

### 4. Modèles de Langage et Deep Learning (Optionnel/À adapter selon vos dossiers)
* Réseaux de neurones récurrents (**RNN**, **LSTM**, **GRU**).
* Introduction aux **Transformers** et utilisation de modèles pré-entraînés via Hugging Face.

## Technologies et Bibliothèques utilisées

* **Langage :** Python 3.x
* **NLP :** NLTK, Spacy, TextBlob
* **Machine Learning :** Scikit-learn
* **Deep Learning :** TensorFlow / Keras ou PyTorch
* **Analyse de données :** Pandas, NumPy
* **Visualisation :** Matplotlib, Seaborn

## Installation et Utilisation

1.  **Cloner le dépôt :**
    ```bash
    git clone [https://github.com/Insaf-elkorachi/TPs_NLP.git](https://github.com/Insaf-elkorachi/TPs_NLP.git)
    cd TPs_NLP
    ```

2.  **Installer les dépendances :**
    ```bash
    pip install -r requirements.txt
    ```

3.  **Lancer les Notebooks :**
    Vous pouvez ouvrir les fichiers `.ipynb` via Jupyter Notebook ou Google Colab pour voir les résultats et exécuter le code.

## Auteur
* **Insaf Elkorachi** - [Profil GitHub](https://github.com/Insaf-elkorachi)

---
*Projet réalisé dans un cadre académique.*
