# TPs NLP - Insaf El Korachi

Ce dépôt regroupe les travaux pratiques réalisés dans le cadre du module de **Traitement Automatique du Langage Naturel (NLP)**.  
Les notebooks couvrent plusieurs étapes importantes du NLP : extraction de texte, nettoyage, structuration de données, vectorisation, clustering, recherche d'information et systèmes RAG.

## Objectifs du dépôt

- Appliquer un pipeline NLP complet sur des textes réels.
- Traiter des documents en langue arabe et des données multilingues.
- Transformer des textes non structurés en données exploitables.
- Utiliser des méthodes classiques comme Regex, TF-IDF et KMeans.
- Explorer des architectures RAG pour l'analyse et la détection de phishing.

## Structure du projet

```text
TPs_NLP/
|-- TP1/
|   `-- devoir-nlp-version-final.ipynb
|-- TP2/
|   `-- devoir-week2-INSAF-ELKORACHI-IASD.ipynb
|-- TP3/
|   |-- data.csv
|   |-- devoir-week3-insaf-el-korachi.ipynb
|   `-- week3-insaf-elkorachi.ipynb
|-- TP4/
|   |-- professional_phishing_rag_dataset.csv
|   |-- Rapport_Week_4_Insaf_El_Korachi.pdf
|   `-- week4 NLP El korachi Insaf.ipynb
`-- README.md
```

## Contenu des travaux pratiques

### TP1 - Pipeline NLP sur un document PDF arabe

Ce travail applique un pipeline NLP à un texte arabe extrait depuis un fichier PDF.

Principales étapes :

- extraction du texte avec `pdfplumber` et `PyMuPDF` ;
- correction de certains problèmes liés à l'extraction PDF ;
- nettoyage et normalisation du texte arabe ;
- tokenisation ;
- suppression des mots vides ;
- stemming léger ;
- représentation vectorielle avec TF-IDF.

### TP2 - Structuration du Code de la route

Ce notebook traite un texte juridique arabe lié au Code de la route afin de produire des données structurées.

Principales étapes :

- extraction et nettoyage des articles ;
- détection d'informations importantes avec des expressions régulières ;
- identification des infractions, catégories, amendes et points retirés ;
- classification des paragraphes ;
- vectorisation TF-IDF ;
- clustering avec KMeans ;
- analyse des groupes obtenus.

### TP3 - Données structurées et analyse NLP

Ce dossier contient un dataset CSV ainsi que deux notebooks de travail autour de l'analyse et de la structuration de données textuelles.

Fichier principal :

- `data.csv` : données structurées issues du traitement NLP, avec des colonnes comme `article_id`, `infraction_desc`, `categorie_vehicule`, `amende_fixe`, `points_retrait`, `mots_cles` et `type_paragraphe`.

### TP4 - Détection de phishing avec RAG

Ce travail porte sur la création d'un système de détection et d'analyse de phishing basé sur différentes architectures RAG.

Fichiers principaux :

- `professional_phishing_rag_dataset.csv` : dataset synthétique/professionnel contenant des messages légitimes et frauduleux ;
- `week4 NLP El korachi Insaf.ipynb` : notebook principal ;
- `Rapport_Week_4_Insaf_El_Korachi.pdf` : rapport du travail.

Architectures et techniques utilisées :

- Baseline LLM ;
- Classic RAG ;
- Rerank RAG ;
- Hybrid RAG ;
- Multi-hop RAG ;
- Graph RAG ;
- Agentic RAG ;
- interface interactive avec Gradio.

## Technologies utilisées

- **Langage** : Python
- **Environnement** : Jupyter Notebook / Kaggle / Google Colab
- **Traitement de données** : Pandas, NumPy
- **NLP** : Regex, tokenisation, stopwords, stemming, TF-IDF
- **Machine Learning** : Scikit-learn, KMeans
- **Extraction PDF** : pdfplumber, PyMuPDF
- **Recherche et RAG** : FAISS, BM25, reranking, retrieval
- **Interface** : Gradio

## Installation

Cloner le dépôt :

```bash
git clone https://github.com/Insaf-elkorachi/TPs_NLP.git
cd TPs_NLP
```

Créer un environnement virtuel :

```bash
python -m venv .venv
```

Activer l'environnement :

```bash
# Windows
.venv\Scripts\activate

# Linux / macOS
source .venv/bin/activate
```

Installer les bibliothèques selon le TP à exécuter :

```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
pip install pdfplumber pymupdf
pip install gradio faiss-cpu rank-bm25
```

## Utilisation

Lancer Jupyter Notebook :

```bash
jupyter notebook
```

Puis ouvrir le notebook souhaité dans le dossier correspondant :

- `TP1/devoir-nlp-version-final.ipynb`
- `TP2/devoir-week2-INSAF-ELKORACHI-IASD.ipynb`
- `TP3/devoir-week3-insaf-el-korachi.ipynb`
- `TP4/week4 NLP El korachi Insaf.ipynb`

Certains notebooks ont été conçus ou exécutés sur Kaggle/Colab. Il peut donc être nécessaire d'adapter les chemins des fichiers avant l'exécution locale.

## Auteur

**Insaf El Korachi**  
Module : Natural Language Processing  
Profil GitHub : [Insaf-elkorachi](https://github.com/Insaf-elkorachi)

## Remarque

Ce dépôt est réalisé dans un cadre académique. Les datasets et notebooks servent à expérimenter différentes méthodes de traitement du langage naturel et de recherche d'information.
