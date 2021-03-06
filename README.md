## La théorie (MLC, Libre Office)
  - Le fonctionnement d'un modèle de prédiction
    * apprentissage
    * validation
    * prédiction
  - Les différents types de prédiction
    * régression linéaire
    * classification
  - Le principe des datasets et leurs features
    * leur pertinence
    * le traîtement des données
    * leur exploitation
    * les différents types de modèles
        + modèle classique
        + ensemble
        + régression linéaire
        + deep net
  - Les metrics qui servent à l'évaluation d'un modèle
    * Probability / Confidence
    * MAE / MAPE
    * Accuracy
    * AUC
    * Recoil
    * Confusion matrix, Cost matrix
    * Log loss
    * MSE
    * Gradient Descent / RMSE


## La pratique (BigML, Jupyter Notebooks, Python, Kaggle, Versionning)
  - ### Le workflow sur BigML
    * création de sources
    * création de datasets
        + train
        + validation
        + train full
        + test
    * réaliser une prédicition et son évaluation à l'aide des metrics
        + en régression linéaire avec *HousePrices*
        + en classification avec *GiveMeSomeCredit*
    * utilisation de l'OptiML
    * BigML via Web UI / via API

    ### Les Jupyter Notebooks
    * la mise en place d'un environnement Jupyter
        + via **Docker** *(docker-compose.yml, Dockerfile)*
        + via **Anaconda** *(Anaconda Navigator, conda, environment.yml)*
        + les *"good practices"* sous Jupyter
            - filenaming
            - séparer les actions en modules
            - diaporamas avec RISE
    * les API (BigML, Kaggle)
        + authentification
        + préparation
        + prédiction
        + évaluation
    * le module Pandas
        + création et import de *DataFrames*
        + modification et export de *DataFrames* **(.apply, .to_csv)**
        + sélection et manipulation de *DataFrames* **(.loc, .iloc, slices, jointures)**

    ### Python
    * Machine Learning
        * Sci-kit learn
          + pipelines
          + Normalisation, Standardisation, Scaling, One Hot Encoding...
          + les modèles et leurs hyperparamètres
          + évaluations
        * XGBoost
        * Keras with TensorFlow
          + structures de Neural Networks
          + initialisation des poids (en cours)
    * Visualisation
        * matplotlib
        * seaborn
        * plotly dash
    
    ### Kaggle
    * comprendre les enjeux et les données d'un challenge
    * participer à une compétition
    * évaluer la qualité des prédictions en fonction du résultat

    ### Versionning
    * Git
    * GitHub
        + Perso
        + Classroom

    ### Computer Vision
    * Traîtement de l'image
        * opencv (color schemes, cropping, resizing)
        * ImageDataGenerator
        * NumPy shape
    * Classification
        + Haar cascades
        + CNN
          - Convolution2D
          - MaxPooling
        + Transfer Learning (VGG16)

    ### NLP
    * Faut que j'me replonge dedans mais y'en a dans le projet du boulot

    ### Cloud
    * Pipelines Azure
        + Datasets
        + Experiments
        + Estimators
        + Runs
        + Environments
        + Compute Targets
        + AutoML
    * Azure Speech (Cognitive Services)
        + Speech-to-text
        + Traduction

    ### Gestion de projet
    * Cadrage
        + Architecture fonctionnelle
        + Architecture technique
        + Retro planning
    * Trello
        + User Stories
        + Liens entre les cartes
    
    ### Développement Web
    * Node.JS
        + Architecture serveur
        + Protocole WebSocket
        + SDK Azure Cognitive Services
        + Mise en production dans le cloud Azure
    * MongoDB
        + Création d'un cluster et de collections
        + Librairie mongoose
    * jQuery
