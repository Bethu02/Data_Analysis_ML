# Data_Analysis_ML

## Contenu du Repository

- `data/` : Dossier contenant les jeux de données utilisés dans le projet, notamment `chiens.csv`, `voitures.csv`, `simu.txt` et `xsimutest`.
- `notebooks/` : Contient les scripts Python ou R pour l'analyse des données, la régression binaire, l'ACP, la classification et l'ACM.
- `Rapport/` : Inclut le rapport final du projet en format PDF.

## Résumé du Projet

### 1. Régression Binaire

- Objectif : Déterminer le meilleur modèle possible pour modéliser P(Y | X1, X2) à partir du fichier `simu.txt`.
- Outil : Utilisation de méthodes de régression logistique / machine learning pour prédire les valeurs de Y.

Nous modélisons la probabilité de la variable binaire Y en fonction des variables explicatives X1 et X2 en utilisant une approche de régression binaire. L'objectif est de prédire Y pour de nouvelles observations à partir du fichier `xsimutest`.

### 2. Analyse en Composantes Principales (ACP)

- Analyse des données du fichier `voitures` pour effectuer une ACP.
- Objectifs : Interprétation des axes principaux, représentation des individus sur le premier plan factoriel.

Nous effectuons une ACP sur les données de différents types de voitures pour comprendre les principales variations et caractéristiques. Cette analyse nous aide à interpréter les relations entre les variables et à visualiser les données dans un espace réduit.

### 3. Classification

- Réalisation de classifications avec la méthode des k-means et interprétation des résultats.
- Classification hiérarchique avec la méthode de Ward et interprétation du dendrogramme.

Nous explorons les données des voitures à l'aide de techniques de classification, notamment k-means et la méthode hiérarchique de Ward, pour identifier des groupes similaires et interpréter leur composition.

### 4. Analyse des correspondances multiples

- Analyse des correspondances multiples des données du fichier `chiens`.
- Objectif : Décrire les différentes races de chiens en fonction de leurs caractéristiques.

À travers une analyse des correspondances multiples basée sur les caractéristiques des races de chiens, nous cherchons à comprendre comment ces races se regroupent selon différentes caractéristiques et fonctions.

## Instructions d'Exécution

Les scripts (R et Python) et notebooks sont fournis afin de lancer l'exécution. La prédiction des valeurs de Y via la régression binaire se trouve dans le dossier `exo1/` du dossier `notebooks/`.

## Membres de l'Équipe

Ce projet a été un effort collaboratif de Bethuel ASSE, Roland DUTAUZIET et Maeva N'Guessan. Chaque membre a contribué à différents aspects du projet, de l'analyse des données à la rédaction du rapport final en passant par les codes.


Pour toute question ou commentaire, n'hésitez pas à me contacter via mon adresse mail bethuelasse9@gmail.com.
