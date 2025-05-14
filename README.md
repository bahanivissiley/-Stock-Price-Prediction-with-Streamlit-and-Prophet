# 📈 Stock Price Prediction with Streamlit and Prophet  

Ce projet est une application interactive de prédiction des prix des actions développée avec **Streamlit**, utilisant les bibliothèques **yfinance** pour récupérer les données financières et **Prophet** pour les prévisions.  

## 🚀 Fonctionnalités  
- **Sélection des actions** : Choisissez parmi plusieurs grandes entreprises (AAPL, GOOG, MSTF, AMZN, TSLA, META, NFLX).  
- **Période de prévision** : Réglez la période de prévision de 1 à 4 ans.  
- **Visualisation des données** :  
  - Affichage des données brutes (dernières valeurs de la série).  
  - Graphique interactif des prix d'ouverture et de clôture des actions.  
- **Prédictions de prix** :  
  - Génération des prévisions à l'aide de l'algorithme Prophet.  
  - Affichage des composantes de la prévision (tendance, saisonnalité).  

## 💻 Technologies utilisées  
- **Streamlit** pour l'interface utilisateur interactive.  
- **yfinance** pour la récupération des données boursières.  
- **Prophet** pour la modélisation et la prévision.  
- **Plotly** pour la visualisation interactive des données.  

## 🌟 Comment lancer l'application  
1. Installez les dépendances :  
   ```bash  
   pip install streamlit yfinance prophet plotly  
