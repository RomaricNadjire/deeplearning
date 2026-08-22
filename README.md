# Deep Learning from scratch (NumPy)

Projet réalisé en suivant la série de tutoriels **Deep Learning** de la chaîne YouTube [Machine Learnia](https://www.youtube.com/@MachineLearnia).

L'objectif est de comprendre et d'implémenter, sans framework de deep learning (uniquement avec `numpy`), les bases des réseaux de neurones : neurone artificiel, descente de gradient, rétropropagation, et réseaux profonds.

## Contenu

| Notebook | Description |
|---|---|
| [01_premier_neurone.ipynb](01_premier_neurone.ipynb) | Implémentation d'un neurone artificiel (régression logistique) : modèle, fonction coût (log loss), descente de gradient, sur un dataset généré avec `make_blobs`. |
| [02_application_catdog.ipynb](02_application_catdog.ipynb) | Application du neurone artificiel à un problème de classification d'images (chat vs chien). |
| [03_ann_2couches.ipynb](03_ann_2couches.ipynb) | Réseau de neurones à 2 couches (ANN) : propagation avant, rétropropagation, mise à jour des paramètres, sur un dataset `make_circles`. |
| [04_ann_profond.ipynb](04_ann_profond.ipynb) | Généralisation à un réseau de neurones profond avec un nombre arbitraire de couches. |

Le fichier [utilities.py](utilities.py) contient les fonctions utilitaires (chargement des données depuis `datasets/`).

## Données

Le dossier `datasets/` contient les fichiers `trainset.hdf5` et `testset.hdf5` utilisés par le notebook `02_application_catdog.ipynb`.

## Installation

```bash
pip install numpy matplotlib scikit-learn h5py tqdm
```

## Utilisation

Ouvrir les notebooks avec Jupyter :

```bash
jupyter notebook
```
