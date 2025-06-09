# analyse_donnees
#  Projet d'Analyse de Données Agricoles

Ce projet vise à explorer, visualiser et classifier un jeu de données simulant des exploitations agricoles à travers différentes régions du monde. 

##  Contenu du dépôt

- `Data_Analysis_Project.ipynb` : Notebook Google Colab contenant tout le code Python utilisé pour l’analyse.

##  Objectif du projet

L’objectif est de mettre en œuvre différentes techniques d’analyse de données sur un jeu de données agricole afin de :
- Comprendre les variables influentes (climat, pratiques agricoles…)
- Identifier des groupes d’exploitations similaires
- Mettre en évidence des profils agricoles types selon les régions et cultures

##  Étapes de l’analyse

1. **Prétraitement**
   - Nettoyage des données
   - Imputation conditionnelle des valeurs manquantes
   - Sélection des variables pertinentes

2. **Analyse exploratoire**
   - Statistiques descriptives
   - Visualisation des distributions
   - Analyse croisée de variables quantitatives et qualitatives

3. **Analyse multivariée**
   - **ACP (Analyse en Composantes Principales)** pour extraire les axes principaux de variation
   - **ACM (Analyse des Correspondances Multiples)** pour étudier les relations entre variables qualitatives

4. **Classification**
   - **CAH (Classification Ascendante Hiérarchique)**
   - **K-means** clustering pour regrouper les exploitations en profils homogènes

##  Technologies utilisées

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

##  Résultats clés

- Identification de trois profils d’exploitations agricoles :
  -  Agriculture sobre mais productive
  - Agriculture extensive avec conditions favorables mais faible rendement
  -  Agriculture intensive avec rendement maximal
- Mise en évidence de liens entre les cultures, les régions, et les pratiques agricoles (type d’irrigation, usage des pesticides, etc.)


 Remarque : Ce projet est une illustration pédagogique des méthodes d’analyse de données appliquées à un cas concret du domaine agricole.
