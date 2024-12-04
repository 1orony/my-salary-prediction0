# **Prédiction de Salaire**  

Ce projet est une application de machine learning qui prédit les salaires en fonction de variables telles que l'expérience, la localisation, le niveau d'éducation et d'autres facteurs pertinents. Il utilise un pipeline complet de science des données, allant de la préparation des données au développement et à l'évaluation des modèles prédictifs.

---

## **📋 Fonctionnalités**
- Nettoyage et prétraitement des données.  
- Sélection des caractéristiques les plus pertinentes.  
- Développement de modèles prédictifs.  
- Évaluation des modèles à l'aide de métriques comme RMSE, MAE et R².  
- Interface simple pour saisir de nouvelles données et prédire les salaires.  

---

## **🛠 Technologies Utilisées**
- **Langage:** Python  
- **Bibliothèques Principales :**  
  - Pandas, NumPy (Manipulation des données)  
  - Scikit-learn (Modèles de machine learning)  
  - Matplotlib, Seaborn (Visualisation des données)  
- **Environnement de Développement:** Jupyter Notebook ou tout IDE compatible Python.  

---

## **📂 Structure du Projet**
```plaintext
prediction-de-salaire/
│
├── data/
│   ├── raw/         # Données brutes
│   ├── processed/   # Données prétraitées
│
├── notebooks/
│   ├── exploration.ipynb  # Analyse exploratoire des données
│   ├── model_training.ipynb  # Entraînement du modèle
│
├── src/
│   ├── preprocess.py  # Fonctions de prétraitement
│   ├── models.py      # Définition des modèles et fonctions associées
│   ├── utils.py       # Fonctions utilitaires
│
├── requirements.txt  # Dépendances du projet
├── README.md         # Documentation du projet
└── main.py           # Script principal pour exécution
```

---

## **🚀 Comment Exécuter**
### Prérequis :
1. **Python** 3.8 ou supérieur.  
2. Installer les dépendances :  
```bash
pip install -r requirements.txt
```

### Étapes :
1. Cloner ce dépôt :  
```bash
git clone <URL_DU_DEPOT>
cd prediction-de-salaire
```
2. Exécuter le notebook `notebooks/exploration.ipynb` pour l'analyse et la visualisation des données.  
3. Lancer `notebooks/model_training.ipynb` pour entraîner et évaluer le modèle.  
4. Utiliser le script `main.py` pour réaliser des prédictions.  

---

## **📊 Évaluation du Modèle**
Métriques utilisées pour évaluer les performances du modèle :  
- **Erreur Absolue Moyenne (MAE) :** Quantifie l'erreur moyenne absolue des prédictions.  
- **Erreur Quadratique Moyenne (MSE/RMSE) :** Pénalise davantage les grandes erreurs.  
- **R² :** Mesure dans quelle proportion le modèle explique la variabilité des données.  

Les résultats finaux du modèle sont disponibles dans le notebook d'entraînement.  

---

## **🔮 Prochaines Étapes**
- Implémentation d’une API pour des prédictions en temps réel.  
- Entraînement avec des données supplémentaires pour améliorer la précision.  
- Intégration avec des frameworks frontend pour développer une interface utilisateur.  

---

## **👩‍💻 Contribution**
Les contributions sont les bienvenues !  
1. Faites un fork du dépôt.  
2. Créez une branche :  
```bash
git checkout -b ma-fonctionnalite
```
3. Commitez vos modifications :  
```bash
git commit -m "Ajout de ma fonctionnalité"
```
4. Envoyez-les pour révision :  
```bash
git push origin ma-fonctionnalite
```

---

## **📄 Licence**
Ce projet est sous licence MIT. Consultez le fichier `LICENSE` pour plus d'informations.  

---

**Développé avec 💻 et ☕ par Ronaldo.**
