# Lab activity 7 - Réseau de neurones artificiels 

!!! Noté !!!

## Introduction


### Rendu

### Membre de l'équipe

- Ibrahim 
- Chelson SUPREME
- Lucas GAIO DOS SANTOS

### A faire

- Modéliser ANN
- Utiliser Keras et TensorFlow


1. Charger les données ;
2. Inspecter et nettoyer les données ;
3. Encoder de façon catégoriel ;
4. Diviser les données en entrainement et test ;
5. StandarScaler pour standardiser ;
6. Utiliser keras.models pour initialiser ANN en faisant par couche ;
7. Ajouter la couche d'entrée et la première couche cachée en utilidant la méthode add() ;
8. Ajouter une deuxième couche cachée composée de 6 unités ;
9. Ajouter la couche de sortie avec une unité binaire, et ne pas oublier l'activation sigmoïde fonction à utiliser ;
10. Configurer le modèle d'apprentissage, via la méthode de comilation ;
11. Ajouster le modèle et appliquer la validation croisée avec une taille de lot de 10. Répéter 50 ou 100 fois (époque = 50 ou 100) ;
12. Faire des prédictions ;
13. Evaluer le modèle à l'aide de la matrice de confusion et du rapport de classification ;
14. Prédire si le client avec les informations suivantes quittera la banque ou non : Géographie : France • Pointage de crédit : 600 • Sexe : Homme • Âge : 40 • Ancienneté : 3 • Solde : 60000 • Nombre de produits : 2 • Possède un crédit carte : Oui • Est membre actif : Oui • Salaire estimé : 50000
15. Utiliser des modèles Keras séquentiels dans le cadre du flux de trvail Scikit-Learn via le wrappers trouvés dans la bibliothèque Keras. Suivre les instruction données dans le notebook Python pour comprendre comment utiliser KerasClassifier à partir de keras.wrappers.scikit_learn.

```classifier.add(Dense(units = 6, kernel_initializer = 'uniform', activation = 'relu', input_dim = 11))```

- Uiliser Dense() pour créer une couche Dense.
- 