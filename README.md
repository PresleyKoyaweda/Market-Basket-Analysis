# Market Basket Analysis (MBA) - Projet de Détection de Motifs d'Achat et de Cooccurrences de Symptômes

## Présentation

Le Market Basket Analysis (MBA) est une technique de fouille de données pour découvrir des associations entre produits, révélant les comportements d'achat des clients. Le MBA aide à identifier les articles souvent achetés ensemble.

## Objectif

L'objectif de ce projet était de développer un algorithme MBA pour révéler des motifs d'achat dans un ensemble de données de trois millions de transactions de supermarché, puis d'appliquer cet algorithme à des données médicales pour détecter les cooccurrences de symptômes.

## Mise en œuvre

### Développement de l'algorithme MBA

- **Utilisation de l'approche MapReduce avec Apache Spark sur GCP** pour le traitement distribué des données.
- **Analyse des transactions de supermarché** pour identifier les motifs d'achat fréquents.

### Application aux données médicales

- **Filtrage et préparation des données VAERS (1990-2024)**.
- **Adaptation de l'algorithme MBA** pour analyser les données médicales et détecter les cooccurrences de symptômes.
- **Utilisation de Spark SQL** pour manipuler les données et générer des insights médicaux.

## Résultats

### Supermarchés

Les données ont été analysées pour révéler les motifs d'achat fréquents et les associations entre les produits, facilitant ainsi la prise de décision pour les détaillants.

### Médical

L'algorithme a permis de mettre en avant l'apparition de symptômes cooccurrences, ce qui aide à anticiper l'apparition de symptômes et à effectuer les traitements préventifs adéquats.

## Compétences

- Analyse de données
- Apprentissage automatique appliqué
- Apache Spark
- MapReduce
- Python
- Big data
- SQL

## Instructions pour Exécuter le Projet

1. Cloner le dépôt :
   ```bash
   git clone https://github.com/VOTRE_NOM_UTILISATEUR/NOM_DU_DEPOT.git
