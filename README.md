# **Uber Hot-Zone Recommender**

## **Description**
Ce projet vise à réduire les temps d’attente des utilisateurs Uber en recommandant aux chauffeurs les zones à forte demande ("hot-zones"). À l'aide de techniques de clustering et de visualisation, nous identifions les zones stratégiques pour optimiser la disponibilité des chauffeurs à différents moments de la journée.

---

## **Fonctionnalités**
- Identification des "hot-zones" dans New York City à partir des données de trajets Uber.  
- Comparaison de deux algorithmes de clustering : **KMeans** et **DBScan**.  
- Cartes interactives visualisant les "hot-zones" par jour de la semaine.  
- Approche évolutive pour généraliser à d'autres périodes et villes.

---

## **Prérequis**
- Python 3.8+  
- Librairies :  
  - `pandas`  
  - `numpy`  
  - `scikit-learn`  
  - `plotly`  

---

## **Utilisation**
1. **Données** : Téléchargez les données de trajets Uber pour New York City ici : [Uber Trip Data](#).  
2. **Exécution** : Lancez le script principal pour générer les "hot-zones" :  
   ```bash
   python main.py
   ```  
3. **Résultats** :  
   - Consultez les visualisations dans le répertoire `outputs/`.  
   - Analysez les performances des algorithmes comparés.  

---

## **Livrables**
- Carte interactive des "hot-zones".  
- Comparaison des résultats entre **KMeans** et **DBScan**.  

---

## **Améliorations futures**
- Extension des analyses à d'autres villes et horaires.  
- Ajout de données en temps réel et de facteurs externes (météo, événements).  
- Optimisation des algorithmes pour améliorer la précision.
