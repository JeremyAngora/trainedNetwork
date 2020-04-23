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
* **Moyenne** : 0.03890876242880776
* **Variance** : 4.052118552826295e-05  

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
* **Moyenne** : 0.01301718304809081
* **Variance** : 6.594012461948263e-05

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
* **Moyenne** : 0.022096401391947854
* **Variance** : 1.8770773028205295e-05

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
* **Moyenne** : 0.01936398114133728
* **Variance** : 3.251132711535617e-05

#### conv_autoencoder-7.pth

* **Jeu de données** : images réelles masquées, 662 éléments
* **Taille des images** : 256*256
* **Transformations** : CenterCrop, Resize, Normalize,
* **Tailles des lots de données** : 128
* **Nombre de génération** : 100
* **Fonction coût**: MSELoss
* **Optimisateur** : Adam, weight_decay = 1e-5
* **Taux d'apprentissage** : 1e-3

##### Résultats finaux
###### MSE
* **Moyenne** : 0.01640854784353672
* **Variance** : 3.3630212934014234e-05

#### conv_autoencoder-8.pth

* **Jeu de données** : images réelles , 662 éléments
* **Taille des images** : 256*256
* **Transformations** : CenterCrop, Resize, Normalize,
* **Tailles des lots de données** : 128
* **Nombre de génération** : 100
* **Fonction coût**: MSELoss
* **Optimisateur** : Adam, weight_decay = 1e-5
* **Taux d'apprentissage** : 1e-3

##### Résultats finaux
###### MSE
* **Moyenne** : 0.017418385803434855
* **Variance** : 0.0007574164846972581
