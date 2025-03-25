# Projet ACP - Analyse des Performances des Athlètes

## 🔬 Description
Ce projet applique une **Analyse en Composantes Principales (ACP)** sur les performances des athlètes de décathlon lors des **Jeux Olympiques de 2004** et de l'événement **Décastar 2004**. L'objectif est de réduire la dimensionnalité des données tout en conservant l'essentiel de la variance afin d'identifier des profils types d'athlètes et de visualiser les corrélations entre les épreuves.

---

## 🔧 Prérequis
- Python 3.x
- Jupyter Notebook
- Bibliothèques : `pandas`, `numpy`, `matplotlib`, `seaborn`, `sklearn`

Installez les dépendances avec :
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## 🔍 Installation
1. Clonez le référentiel :
```bash
git clone https://github.com/ihssane2002/Projet-AI_ACP.git
```
2. Accédez au projet :
```bash
cd Projet-AI_ACP
```
3. Lancez le notebook :
```bash
jupyter notebook Projet AI_PCA.ipynb
```

---

## 📉 Utilisation
1. **Chargement des données** : Importation des performances des athlètes depuis un fichier CSV.
2. **Exploration des données** : Analyse descriptive des variables (classement, points, épreuves).
3. **Standardisation** : Centrage et normalisation des données pour rendre les variables comparables.
4. **Réalisation de l'ACP** : Application de l'ACP pour réduire la dimensionnalité et capturer les axes de variations les plus significatifs.
5. **Visualisation des Résultats** : Graphiques de variance expliquée, valeurs propres et projection des athlètes dans le nouvel espace de dimension réduite.
6. **Interprétation** : Identification de profils d'athlètes et analyse des corrélations entre les performances.

---

## 📊 Résultats
- **Variance Expliquée** : Les 5 premières composantes principales expliquent **81.56%** de la variance totale.
- **Profils Identifiés** :
  - *Athlètes Hautement Performants* : Excellents dans plusieurs épreuves, dominent le classement.
  - *Athlètes Polyvalents* : Performances homogènes dans plusieurs disciplines.
  - *Athlètes avec Potentiel d'Amélioration* : Lacunes identifiées dans certaines épreuves, mais un bon potentiel de progression.
- **Corrélations** : Des liens significatifs ont été détectés entre certaines épreuves, comme le sprint et le saut en longueur.

---

## 👨‍💼 Auteur
- **Ihssane BAMMAD**





