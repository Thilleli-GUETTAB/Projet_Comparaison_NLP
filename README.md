# Projet_Comparaison_NLP

### Description du projet

Ce projet vise à développer un système complet de traitement automatique du langage naturel (NLP) intégrant l’ensemble de la chaîne de traitement, depuis le nettoyage des textes jusqu’à la classification, l’extraction d’informations et la génération de résumés.
Le système repose sur une comparaison de modèles séquentiels classiques (LSTM) et de Transformers (BERT, DistilBERT), avec une évaluation approfondie des performances et des coûts computationnels.

Le projet est réalisé dans un cadre académique et s’appuie exclusivement sur des datasets et modèles reconnus.

### Objectifs

Nettoyer et analyser linguistiquement un corpus de documents textuels

Apprendre et visualiser des embeddings (Word2Vec, GloVe)

Implémenter des modèles de classification séquentiels (LSTM bidirectionnel)

Fine-tuner des modèles Transformers (BERT, DistilBERT)

Extraire des informations clés (entités nommées, mots-clés)

Générer des résumés extractifs et abstractifs

Comparer les modèles selon des métriques quantitatives et temporelles

Proposer une interface interactive via Streamlit

### Corpus utilisé

Dataset : BBC News

Langue : Anglais

Nombre total de documents : 600

Thématiques :

- Politique : 200 documents

- Sport : 200 documents

- Technologie : 200 documents

Les 200 premiers articles de chaque thématique ont été sélectionnés afin de garantir :

- un équilibre parfait des classes

- une reproductibilité totale des expériences

### Prérequis et installation
Installation des dépendances
**pip install -r requirements.txt**

### Glove Embedding
Les embeddings de mots GloVe utilisés dans ce projet correspondent au modèle GloVe 6B en dimension 100, mis à disposition par le Stanford NLP Group.
link : ** https://nlp.stanford.edu/projects/glove/**
