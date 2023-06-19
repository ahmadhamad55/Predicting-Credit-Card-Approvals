# Predicting-Credit-Card-Approvals
<p align="center">
  <img src="https://github.com/ahmadhamad55/Predicting-Credit-Card-Approvals/blob/main/credit_card%20(1).jpg"  width="400" height="300">
</p>

### English version
Commercial banks receive a lot of applications for credit cards. Many of them get rejected for many reasons, like high loan balances, low income levels, or too many inquiries on an individual's credit report, for example. Manually analyzing these applications is mundane, error-prone, and time-consuming (and time is money!). Luckily, this task can be automated with the power of machine learning and pretty much every commercial bank does so nowadays. In this notebook, we will build an automatic credit card approval predictor using machine learning techniques, just like the real banks do.

We'll use the Credit Card Approval dataset from the UCI Machine Learning Repository. The structure of this notebook is as follows:
* First, we will start off by loading and viewing the dataset.
* We will see that the dataset has a mixture of both numerical and non-numerical features, that it contains values from different ranges, plus that it contains a number of missing entries.
* We will have to preprocess the dataset to ensure the machine learning model we choose can make good predictions.
* After our data is in good shape, we will do some exploratory data analysis to build our intuitions.
* Finally, we will build a machine learning model that can predict if an individual's application for a credit card will be accepted.

### Version Française
Les banques commerciales reçoivent de nombreuses demandes de cartes de crédit. Beaucoup d'entre elles sont rejetées pour diverses raisons, telles que des soldes de prêts élevés, des niveaux de revenus faibles ou trop d'enquêtes sur le rapport de crédit d'un individu, par exemple. Analyser manuellement ces demandes est fastidieux, sujet aux erreurs et prend beaucoup de temps (et le temps, c'est de l'argent !). Heureusement, cette tâche peut être automatisée grâce à la puissance de l'apprentissage automatique, et pratiquement toutes les banques commerciales le font de nos jours.

Dans ce notebook, nous allons construire un prédicteur automatique d'approbation de cartes de crédit en utilisant des techniques d'apprentissage automatique, tout comme le font les vraies banques. Nous utiliserons le jeu de données "Credit Card Approval" du référentiel UCI Machine Learning. La structure de ce notebook est la suivante :

* Nous commencerons par charger et visualiser le jeu de données.
* Nous verrons que le jeu de données contient à la fois des caractéristiques numériques et non numériques, qu'il contient des valeurs provenant de différentes plages, ainsi qu'un certain nombre d'entrées manquantes.
* Nous devrons prétraiter le jeu de données pour nous assurer que le modèle d'apprentissage automatique que nous choisirons peut faire de bonnes prédictions.
* Une fois que nos données seront en bon état, nous effectuerons une analyse exploratoire des données pour développer nos intuitions.
* Enfin, nous construirons un modèle d'apprentissage automatique capable de prédire si la demande d'un individu pour une carte de crédit sera acceptée.
