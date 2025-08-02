# Diallo-Moussa
utils de visualisation pédagogique des réseaux de neurones (Perceptron, MLP, CNN) développés durant mon stage M1 Mapi3  ontient le rapport de stage, les diapositives de soutenance, et les implémentations Python avec visualisations interactives des mécanismes d'apprentissage."
# 🧠 Projet de Visualisation des Réseaux de Neurones

<div align="center">
  <img src="images/network_visualization.gif" alt="Demo" width="600"/>
</div>

## 📌 Description du Projet
**Outils interactifs** pour visualiser le fonctionnement interne des réseaux de neurones développés durant mon stage M1 MAPI3 (TER à l'IRIT)  (Université Toulouse III).

## 🛠️ Technologies Utilisées
- ![Python](https://img.shields.io/badge/Python-3.8+-blue?logo=python)
- ![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange?logo=tensorflow)
- ![Matplotlib](https://img.shields.io/badge/Matplotlib-3.5+-blue?logo=python)
- ![Scikit-learn](https://img.shields.io/badge/scikit--learn-1.0+-blue?logo=scikitlearn)

## 📂 Structure des Fichiers
```bash
.
├── code/
│   ├── perceptron/          # Visualisation convergence
│   │   ├── train.py         # Algorithme d'apprentissage
│   │   └── visualize.py     # Animations interactives
│   ├── mlp/                 # Réseaux multicouches
│   │   ├── model.py         # Architecture MLP
│   │   └── boundaries.py    # Frontières de décision
│   └── cnn/                 # Réseaux convolutionnels
│       ├── reconstruction.py # Reconstruction d'images
│       └── filters.py       # Visualisation des filtres
├── docs/
│   ├── Rapport_Stage.pdf    # Version complète
│   └── Soutenance.pdf       # Présentation Beamer
└── assets/                  # Images et visualisations
