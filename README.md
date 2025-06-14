# Prédiction du Prix du Bitcoin avec Analyse Multi-Approche

---

##  Objectif du Projet

Ce projet vise à **prédire le prix du Bitcoin** en combinant deux grandes familles d’approches :

1. **Approches classiques** : ARIMA, SARIMA, et autres modèles statistiques pour les séries temporelles.
2. **Approches modernes** : Modèles de **deep learning** (LSTM, GRU, etc.) pour capter les relations non linéaires.

---

## Application Interactive avec Streamlit

Une **interface graphique** a été développée avec **Streamlit** pour permettre :

- La **visualisation des données historiques** du Bitcoin
- Le **lancement des modèles de prédiction**
- L’**affichage des résultats des modèles** (prévisions, courbes, erreurs)
- Un **chatbot intégré** capable de répondre aux questions sur les données, les prédictions, ou même des éléments éducatifs sur le Bitcoin et les techniques utilisées

---

## Démarche Générale

1. **Collecte et préparation des données**
2. **Exploration et analyse des corrélations**
3. **Modélisation** :
   - ARIMA/SARIMA pour les tendances saisonnières
   - LSTM ou GRU pour les dynamiques à long terme
4. **Création de l'application Streamlit**
5. **Intégration d’un chatbot (basé sur NLP)** pour interagir avec les utilisateurs

---

## Données Utilisées

Les données contiennent les variables suivantes :

- `date` : Date de la mesure
- `open`, `high`, `low`, `close` : Prix du Bitcoin
- `volume` : Volume de transactions
- `RSI` : Indicateur technique (Relative Strength Index)
- `volatility` : Mesure de la variation
- `fear_index` : Indice de sentiment de peur
- `active_addresses` : Nombre d’adresses Bitcoin actives
- `individual_daily_tx` : Nombre de transactions journalières individuelles
- `total_daily_tx` : Nombre total de transactions journalières

---

## 🖥️ Technologies Utilisées

| Catégorie         | Outils / Librairies                      |
|------------------|------------------------------------------|
| Programmation    | Python                                   |
| Modélisation     | statsmodels, scikit-learn, TensorFlow    |
| Visualisation    | Matplotlib, Seaborn, Plotly              |
| Interface UI     | Streamlit                                |
| Traitement texte | NLTK, spaCy, Transformers (pour chatbot) |

---

## 🧪 Structure du Projet
