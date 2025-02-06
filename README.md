# miage-fdd-tp2-clustering

## Analyse des données

#### Quel est le nombre d'instances (lignes en BDD, individus en statistiques) ?

Il y a environ 150 lignes.

#### Quels sont les attributs (colonnes en BDD, variables en statistiques) et leurs types ?

Il y a 4 attributs :
- sepal-length --> Type : Numérique (quantitative continue)
- sepal-width --> Type : Numérique (quantitative continue)
- petal-length --> Type : Numérique (quantitative continue)
- petal-width --> Type : Numérique (quantitative continue)
- iris --> Type : qualitative
#### Quels sont les couples d'attributs fortement corrélés ?

- Petal length ↔ Petal width : +0.963
- Petal length ↔ Sepal length : +0.872
- Petal width ↔ Sepal length : +0.818

#### Parmi les mesures fournies par le widget "Feature Statistics", comment est calculée la colonne "center", et la colonne "dispersion" ?

La colonne center est en réalité la colonne médianne.
Pour la variable sepal-length, la médianne est de 5,8.

Et pour la dispersion, c'est l'écart-type. L'objectif est de calculer la dispersion autour de la moyenne.
La moyenne est de 1,199. La dispersion est de 0.635 --> indique que les valeurs de petal width s’écartent en moyenne de 0.635 par rapport à la moyenne.
Donc l'écart-type = dispersion.
