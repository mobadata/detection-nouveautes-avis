# Projet : Détection de Nouveautés dans les Avis Clients

Ce projet vise à identifier les thèmes qui apparaissent ou disparaissent dans les avis clients Amazon, pour mieux comprendre leurs besoins et améliorer leur satisfaction.

## Objectifs

- Extraire les sujets les plus fréquents dans les avis
- Suivre l’évolution de ces sujets dans le temps
- Identifier les nouveautés dans les attentes clients

## Outils utilisés

- Python (Pandas, Numpy)
- BERTopic (pour extraire les thèmes)
- UMAP + HDBSCAN (clustering)
- NLTK et SpaCy (traitement de texte)
- Google Colab + Google Drive

## Structure du projet

- `data/` → les données brutes Amazon
- `notebooks/` → les notebooks d’analyse
- `outputs/` → les résultats (thèmes, graphiques)
- `requirements.txt` → les librairies à installer
- `.pre-commit-config.yaml` → vérification automatique du code

## Auteur

Projet réalisé par Moussa BA.