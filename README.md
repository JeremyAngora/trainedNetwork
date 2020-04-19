# Trained neural networks

Ce dépôt contient des réseaux de neurones entraînés pour le projet Dolos

##Auto encodeurs


###conv_autoencoder-1.pth

**Jeu de données** : images réelles (v1 simples 400 images)
**Taille des images** : 256*256
**Transformations** : CenterCrop, Resize, Normalize
**Tailles des lots de données** : 128
**Nombre de génération** : 100
**Fonction coût**: MSELoss
**Optimisateur** : Adam, weight_decay = 1e-5
**Taux d'apprentissage** : 1e-3
