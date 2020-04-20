# Trained neural networks

Ce dépôt contient des réseaux de neurones entraînés pour le projet Dolos

## Auto encodeurs

### Auto encodeurs convolutifs
#### conv_autoencoder-1.pth

* **Jeu de données** : images réelles, 194 éléments
* **Taille des images** : 256*256
* **Transformations** : CenterCrop, Resize, Normalize
* **Tailles des lots de données** : 128
* **Nombre de génération** : 100
* **Fonction coût**: MSELoss
* **Optimisateur** : Adam, weight_decay = 1e-5
* **Taux d'apprentissage** : 1e-3

#### conv_autoencoder-2.pth

* **Jeu de données** : images virtuelles, 10 000 éléments
* **Taille des images** : 256*256
* **Transformations** : CenterCrop, Resize, Normalize
* **Tailles des lots de données** : 128
* **Nombre de génération** : 100
* **Fonction coût**: MSELoss
* **Optimisateur** : Adam, weight_decay = 1e-5
* **Taux d'apprentissage** : 1e-3

#### conv_autoencoder-3.pth

* **Jeu de données** : images réelles masqued, 194 éléments
* **Taille des images** : 256*256
* **Transformations** : CenterCrop, Resize, Normalize
* **Tailles des lots de données** : 128
* **Nombre de génération** : 100
* **Fonction coût**: MSELoss
* **Optimisateur** : Adam, weight_decay = 1e-5
* **Taux d'apprentissage** : 1e-3
