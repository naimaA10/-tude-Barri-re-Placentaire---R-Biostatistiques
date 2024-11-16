# Projet - Étudier le phénomène du passage de la barrière placentaire par de petits composés

## Description du projet

Ce projet a pour objectif d'analyser et de prédire la capacité de médicaments à traverser la barrière placentaire en utilisant des données massives. Il repose sur l'utilisation de méthodes d'analyse multivariée appliquées à un jeu de données contenant des médicaments et leurs descripteurs physico-chimiques. Le but est de déterminer si la structure chimique des médicaments peut prédire leur clairance à travers la barrière placentaire.

## Installation et exécution

### Prérequis

- **R** (version 4.1.2, "Bird Hippie") ou supérieure.
- **RStudio** (recommandé pour une utilisation optimale).

### Lancer le script

1. Téléchargez le fichier `ADM_projet.Rmd` (script RMarkdown).
2. Ouvrez **RStudio** et chargez le fichier `ADM_projet.Rmd`.
3. Exécutez le script pour analyser les données et générer un rapport.

### Packages nécessaires :

```r
install.packages(c("ggplot2", "cluster", "factoextra", "rpart", "caret", "dplyr"))
```

## Méthodes utilisées

Le projet utilise des **méthodes d’analyse multivariée** pour prédire la clairance des médicaments, telles que :
- **Classification K-means** et **hiérarchique** (non supervisées).
- **Régression linéaire multiple** et **arbres de classification (rpart)** (supervisées).

Les résultats sont visualisés à l'aide de graphiques et d'analyses détaillées, disponibles dans le rapport généré.
