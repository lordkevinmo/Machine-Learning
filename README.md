# Machine-Learning
J'ai hébergé ici les projets que j'ai eu a effectué lors du cours d'introduction au machine learning de Andrew Ng proposé par l'Université de Standford via la plateforme Coursera. Lien du cours : https://www.coursera.org/learn/machine-learning

Le langage de programmation utilisé est MatLab/Octave.

Le dépôt contient 8 répertoires nommés ex1 ... ex8.

# Description du contenu des répertoires

# ex1 - Projet sur la Régression Linéaire Simple (Simple Linear Regression or Linear Regression with One variable) et sur la Régression Linéaire Multiple (Multiple Linear Regression or Linear Regression with multiple variables)

# Contexte : 
1 .Supposons que vous soyez le PDG d'une franchise de restaurant et que vous envisagiez différentes villes pour ouvrir un nouveau point de vente. La chaîne a déjà des restaurants dans différentes villes et vous disposez de données sur les bénéfices et les populations des villes. Vous souhaitez utiliser ces données pour vous aider à sélectionner la ville à développer.

2. Supposons que vous vendiez votre maison et que vous souhaitiez savoir quel serait le bon prix du marché. Une façon de procéder consiste à collecter d’abord des informations sur les maisons vendues récemment et à créer un modèle de prix de l’habitation.

# Objectifs : 

- Prédiction des prix d'une maison en fonction de sa surface en mètre carré (MLR)
- Prédiction de la bonne ville à choisir par un chef de franchise pour la création d'une nouvelle filiale en fonction de la population de la ville et des bénéfices des habitants.


# ex2 - Regression Logistique et régularisation (Logistic Regression and Regularization)

# Contexte :

Supposons que vous êtes l’administrateur d’un département universitaire et que vous souhaitez déterminer les chances d’admission de chaque candidat sur la base des résultats obtenus aux deux examens. Vous disposez de données historiques de demandeurs précédents que vous pouvez utiliser comme ensemble de formation pour la régression logistique. Pour chaque exemple de formation, vous avez les scores du candidat à deux examens et la décision d’admission.


# Objectifs

- Construction d'un modèle de classification qui estime la probabilité d'admission d'un candidat sur la base des notes obtenues à deux 
examens.



# ex3 - Méthode un-contre-tous et réseau de neurone pour reconnaître un chiffre écrit à la main (One-vs-all Logistic regression and Artificial Neural Network to recognize hand-written digits)

# Contexte :

1. Extension de la mise en œuvre précédente de la régression logistique et application de la classification un-contre-tous au jeu de données. Implémentation d'une classification un-contre-tous en formant plusieurs classificateurs de régression logistique régularisés, un pour chacune des classes K de notre ensemble de données pour reconnaître les chiffres manuscrits.

2. Implémenter un réseau de neurones pour reconnaître les chiffres manuscrits en utilisant le même ensemble d'apprentissage que précédemment. Le réseau de neurones sera capable de représenter des modèles complexes qui forment des hypothèses non linéaires. Les paramètres du réseau de neurones ont été déjà formé.


# Objectifs

- Implémenter l'algorithme de propagation par anticipation afin d'utiliser nos pondérations pour la prédiction.


# ex4 - Apprentissage de réseau neuronal (Neural Network Learning with feedforward with and without regularization, backpropagation and prediction)

# Contexte :

Implémentation de l'algorithme de rétropropagation pour apprendre les paramètres du réseau de neurones précédents.


# ex5 - Regression linéaire régularisée et variance (Regularized Linear Regression and Bias-Variance)

# Contexte :

1. Implémenter une régression linéaire régularisée pour prédire la quantité d'eau sortant d'un barrage en utilisant le changement de niveau d'eau dans un réservoir.

2. Passer en revue certains diagnostics d'algorithmes d'apprentissage de débogage et examiner les effets entre le biais et la variance.



# ex6 - Machines à vecteurs de support et classification de spam avec SVM (Support Vector Machines & Spam Classification with SVMs) 

# Contexte :

Utiliser des machines à vecteurs de support (SVM) avec divers exemples de jeux de données 2D. Expérimenter avec ces jeux de données vous aidera à mieux comprendre le fonctionnement des SVM et l'utilisation d'un noyau gaussien avec des SVM.


# Objectifs 
Utiliser des machines à vecteurs de support pour créer un classificateur de courrier indésirable.


# ex7 - Analyse en composante principale et regroupement des K-Moyens (Principle Component Analysis and K-Means Clustering)

# Contexte :

1. Nous allons implémenter l'algorithme K-Moyens et l'utiliser pour la compression d'image. Nous commencerons d'abord par un exemple de jeu de données 2D qui nous aidera à mieux comprendre le fonctionnement de l'algorithme K-Moyens. Après cela, nous utiliserons l'algorithme K-Moyens pour la compression d'image en réduisant le nombre de couleurs d'une image à celles qui sont les plus courantes dans cette image.

2. Nous utiliserons l'analyse en composantes principales (ACP) pour effectuer la réduction de la dimensionnalité. Nous allons d’abord expérimenter avec un exemple de jeu de données 2D pour mieux comprendre le fonctionnement de la PCA, puis l’utiliser sur un plus grand jeu de données de 5 000 images image de face.


# Objectifs

- Implémentation de l'algorithme de regroupement des K-moyens et application pour compresser une image;
- Utilisation de l'analyse en composantes principales pour trouver une représentation en basse dimension des images de visage.



# ex8 - Détection d'anomalie et filtrage collaboratif (Anomaly Detection and Collaborative Filtering)

# Contexte :

1. Vous allez implémenter un algorithme de détection d'anomalie pour détecter un comportement anormal sur les ordinateurs serveurs. Les fonctionnalités mesurent le débit (Mo/s) et la latence (ms) de la réponse de chaque serveur. Pendant que vos serveurs fonctionnaient, vous avez collecté m = 307 exemples de comportement, et vous disposez ainsi d'un ensemble de données non étiqueté {x (1), ..., x (m)}. Vous soupçonnez que la grande majorité de ces exemples sont des exemples «normaux» (non anormaux) de serveurs fonctionnant normalement, mais il peut également y avoir des exemples de serveurs agissant de manière anormale dans cet ensemble de données.
Vous utiliserez un modèle gaussien pour détecter des exemples anormaux dans votre jeu de données. Vous commencerez d'abord par un jeu de données 2D qui vous permettra de visualiser ce que fait l'algorithme. Sur cet ensemble de données, vous allez adapter une distribution gaussienne, puis trouver des valeurs qui ont une probabilité très faible et qui peuvent donc être considérées comme des anomalies. Ensuite, vous appliquerez l'algorithme de détection d'anomalie à un jeu de données plus volumineux comportant de nombreuses dimensions.

2. La matrice Y (une matrice num movie × num users) stocke les notes y (i, j) (de 1 à 5). La matrice R est une matrice d'indicateurs à valeurs binaires, où R (i, j) = 1 si l'utilisateur j a attribué une cote au film i et R (i, j) = 0 sinon. Le filtrage collaboratif a pour objectif de prédire les classements des films que les utilisateurs n’ont pas encore classés, c’est-à-dire les entrées avec R (i, j) = 0. Nous pourrons ainsi recommander les films dont les classements prédits sont les plus élevés à l'utilisateur.


# Objectifs

- Implémenter l'algorithme de détection d'anomalie et l'avons appliqué pour détecter les serveurs défaillants sur un réseau.
- Utiliser le filtrage collaboratif pour créer un système de recommandation pour les films.
