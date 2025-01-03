# analyse_phd

## Contexte
Ce projet analyse les soutenances de thèses en France en utilisant des données relatives à la période entre 1985 et 2020. Le fichier **Analyse_Phd.Rmd** est un document R Markdown qui présente des étapes de nettoyage, d'exploration et de visualisation des données.

## Objectifs
Les principaux objectifs de cette analyse sont :
1. Identifier et quantifier les données manquantes dans le jeu de données.
2. Analyser les tendances des soutenances par année, mois et langue.
3. Visualiser les proportions de thèses soutenues en français et en anglais entre 2001 et 2018.
4. Examiner les évolutions des soutenances le 1er janvier sur plusieurs années.

## Contenu
Le fichier **Analyse_Phd.Rmd** contient les sections suivantes :

1. **Introduction** : Contexte et objectifs de l'analyse.
2. **Nettoyage des données** :
   - Identification des valeurs manquantes.
   - Traitement des données aberrantes.
3. **Exploration des données** :
   - Calcul des proportions et des tendances.
   - Comparaison des soutenances selon différents critères (langue, mois, jour).
4. **Visualisation** :
   - Graphiques créés avec `ggplot2` et `pheatmap` pour représenter les données.
5. **Conclusions** : Résumé des résultats et perspectives futures.

## Prérequis
Avant d'exécuter le fichier R Markdown, assurez-vous que votre environnement de travail est configuré correctement :

1. **Langage** : R (version 4.0 ou ultérieure).
2. **Packages R requis** :
   - `tidyverse`
   - `ggplot2`
   - `pheatmap`
   - `dplyr`
   - `lubridate`
3. **Fichier de données** : Assurez-vous que le fichier source contenant les données est accessible et correctement nommé.

## Instructions d'exécution
1. Ouvrez le fichier **Analyse_Phd.Rmd** dans RStudio.
2. Installez les packages manquants avec `install.packages()` si nécessaire.
3. Exécutez l'ensemble du document en cliquant sur le bouton **Knit** pour générer un rapport en format HTML ou PDF.

## Résultats attendus
- Un rapport contenant :
  - Des statistiques descriptives sur les soutenances de thèses.
  - Des visualisations des tendances temporelles et linguistiques.
  - Une analyse des données manquantes.

## Auteur
Anna

## Licence
Ce projet est distribué sous la licence [choisir la licence appropriée, ex. MIT, GPL, etc.].

