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
##### Résultats finaux
###### MSE
* **Moyenne** : 0.13873392219344774
* **Variance** : 2.7876201898140933e-07

#### conv_autoencoder-2.pth

* **Jeu de données** : images virtuelles, 10 000 éléments
* **Taille des images** : 256*256
* **Transformations** : CenterCrop, Resize, Normalize
* **Tailles des lots de données** : 128
* **Nombre de génération** : 100
* **Fonction coût**: MSELoss
* **Optimisateur** : Adam, weight_decay = 1e-5
* **Taux d'apprentissage** : 1e-3
##### Résultats finaux
###### MSE
* **Moyenne** : 0.004974390162775914
* **Variance** : 4.62117756500811e-08

#### conv_autoencoder-3.pth

* **Jeu de données** : images réelles masqued, 194 éléments
* **Taille des images** : 256*256
* **Transformations** : CenterCrop, Resize, Normalize
* **Tailles des lots de données** : 128
* **Nombre de génération** : 100
* **Fonction coût**: MSELoss
* **Optimisateur** : Adam, weight_decay = 1e-5
* **Taux d'apprentissage** : 1e-3

##### Résultats finaux
###### MSE
* **Moyenne** : 0.01516372427965204
* **Variance** : 1.8457829094184494e-07

#### conv_autoencoder-4.pth

* **Jeu de données** : images réelles, 389 éléments
* **Taille des images** : 256*256
* **Transformations** : CenterCrop, Resize, Normalize
* **Tailles des lots de données** : 128
* **Nombre de génération** : 100
* **Fonction coût**: MSELoss
* **Optimisateur** : Adam, weight_decay = 1e-5
* **Taux d'apprentissage** : 1e-3

##### Résultats finaux
###### MSE
* **Moyenne** : 0.04658940608302752
* **Variance** : 9.142156281887687e-08

#### conv_autoencoder-5.pth

* **Jeu de données** : images réelles masquées, 389 éléments
* **Taille des images** : 256*256
* **Transformations** : CenterCrop, Resize, Normalize
* **Tailles des lots de données** : 128
* **Nombre de génération** : 100
* **Fonction coût**: MSELoss
* **Optimisateur** : Adam, weight_decay = 1e-5
* **Taux d'apprentissage** : 1e-3

##### Résultats finaux
###### MSE
* **Moyenne** : 0.01578084727904449
* **Variance** : 1.4966934534295013e-06

#### conv_autoencoder-6.pth

* **Jeu de données** : images réelles masquées, 389 éléments
* **Taille des images** : 256*256
* **Transformations** : CenterCrop, Resize, Normalize, RandomHorizontalFlip, RandomVerticalFlip
* **Tailles des lots de données** : 128
* **Nombre de génération** : 100
* **Fonction coût**: MSELoss
* **Optimisateur** : Adam, weight_decay = 1e-5
* **Taux d'apprentissage** : 1e-3

##### Résultats finaux
###### MSE
* **Moyenne** : 0.013455323680924872
* **Variance** : 1.1636956767513199e-06
