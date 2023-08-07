# OCR3
OpenClassRooms projet 3: Anticipez les besoins en consommation de bâtiments

### Données
Des relevés minutieux ont été effectués par les agents de la ville en 2016. Voici les  [données](https://s3.eu-west-1.amazonaws.com/course.oc-static.com/projects/Data_Scientist_P4/2016_Building_Energy_Benchmarking.csv) et leur [source](https://data.seattle.gov/dataset/2016-Building-Energy-Benchmarking/2bpz-gwpy).

### Mission   
   1. Réaliser une courte analyse exploratoire (**One hot encoder, transformation et normalisation des variables, imputation des valeures manquante spar KNN**).
   2. Tester différents modèles de prédiction afin de répondre au mieux à la problématique :
      - **Création d'une fonction qui permet de réaliser un K-fold avec grid search pour une optimisation des meilleurs hyperparamètres en choisissant une ou plusieurs métriques de "goodness of fit".**
      - **Cette fonction permet de tester divers algorithmes de régression tels que Random Forest, XGBoost, Ridge, Lasso, Elastic Net et Kernel Ridge.**
      - **Fonction pour visualiser des facteurs et leur importance, que ce soit pour les algorithmes de Random Forest, XGBoost, Ridge, Lasso, Elastic Net et Kernel Ridge..**
        ![image](https://github.com/SebastianSosa/OCR3/assets/22368172/d9508fb8-1dfc-4ec5-a52b-0326429c0308)
        ![image](https://github.com/SebastianSosa/OCR3/assets/22368172/6bd0ed41-1966-4921-abe1-683d99ec663a)
        ![image](https://github.com/SebastianSosa/OCR3/assets/22368172/cb92f9ac-6ee8-4c5b-8188-7c05de1ce5af)


      - **Fonction principale pour réaliser l'ensemble du pipeline de production :**
           ![image](https://github.com/SebastianSosa/OCR3/assets/22368172/915804c3-ec84-40d4-b705-3cfac5655e5c)

### Compétences évaluées

  1. Mettre en place le modèle d'apprentissage supervisé adapté au problème métier
  2. Adapter les hyperparamètres d'un algorithme d'apprentissage supervisé afin de l'améliorer
  3. Transformer les variables pertinentes d'un modèle d'apprentissage supervisé
  4. Évaluer les performances d’un modèle d'apprentissage supervisé
     
### Livrables 

  1.  Un notebook de l'analyse exploratoire mis au propre et annoté.
  2.  Un notebook pour chaque prédiction (émissions de CO2 et consommation totale d’énergie) des différents tests de modèles mis au propre, dans lequel vous identifierez clairement le modèle final choisi.
  3. Un support de présentation pour la soutenance.
