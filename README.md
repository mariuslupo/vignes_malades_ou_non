
# Classification des maladies des vignes 🍇

Ce projet utilise des algorithmes d'apprentissage automatique pour classifier l'état de santé des vignes (malades ou non) à partir d'images. Il vise à aider les viticulteurs ou les chercheurs à détecter les maladies des vignes rapidement et efficacement.

## 📌 Objectif

Développer un modèle capable de distinguer entre plusieurs états de santé des vignes :
- **Black Measles**
- **Healthy**
- **Leaf blight**
- **Black rot**

Avec un modèle actuel atteignant une précision globale de **86%**, ce projet constitue une base pour des améliorations futures dans le domaine de la détection des maladies agricoles.

## 🗂️ Contenu du projet

1. **Notebook principal** :
   - Chargement et exploration des données.
   - Prétraitement des images.
   - Entraînement d'un modèle de classification.
   - Évaluation des performances à l'aide d'une matrice de confusion.

2. **Matrice de confusion** :
   Visualisation des performances du modèle avec une matrice qui montre les erreurs de classification.

3. **Fichiers et données** (non incluses dans ce dépôt pour des raisons de taille) :
   - Images des différentes catégories.
   - Données prétraitées pour entraîner le modèle.

## 📊 Résultats

- **Précision globale** : 86%
- Les catégories les mieux classées : 
  - **Healthy** : 82 images correctement classées.
  - **Leaf blight** : 71 images correctement classées.
- Améliorations nécessaires pour différencier les catégories similaires comme **Black Measles** et **Black rot**.

![Matrice de confusion](./confusion_matrice.png)

## 🚀 Comment exécuter le projet ?

### Prérequis

- Python 3.8 ou supérieur
- Bibliothèques nécessaires :
  - `numpy`
  - `pandas`
  - `matplotlib`
  - `opencv-python`
  - `scikit-learn`

### Étapes

1. Clonez ce dépôt :
   ```bash
   git clone https://github.com/votre-utilisateur/votre-projet.git
   cd votre-projet
   ```

2. Installez les dépendances

3. Lancez le notebook :
   ```bash
   jupyter notebook Vignes_malades_ou_non.ipynb
   ```

## 🌱 Pistes d'amélioration

- Ajouter des données supplémentaires pour équilibrer les classes.
- Utiliser des modèles plus avancés comme les réseaux de neurones convolutionnels (CNN).
- Tester des techniques d'augmentation des données pour rendre le modèle plus robuste.

## ✨ Avenir du projet

Ce projet peut être intégré dans un système automatisé de surveillance des vignes, permettant aux viticulteurs d'identifier rapidement les maladies et de prendre des décisions éclairées pour protéger leur production.

