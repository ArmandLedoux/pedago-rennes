### Tri à bulles

De gauche à droite :

1. Comparer la premère et la deuxième carte. Les échanger si la première est plus grande que la deuxième.

2. Recommencer en se décalant d'une carte vers la droite

Lorsqu'on arrive tout à droite, si on a inversé au moins une paire de cartes, recommencer l'algorithme depuis le début.


### Tri par insertion

On distingue la table en trois zones : les cartes déjà triées, les cartes non triées et une carte mise à part. Au début toutes les cartes sont non triées.

Tant qu'il y a des cartes non triées : 

1. Prendre une carte non triée au hasard et la mettre à part 
2. Comparer la carte mise à part avec la première carte triée. Si elle est plus petite, l'insérer juste avant.
3. Sinon, recommancer à l'étape 2 en se décalant d'une carte à droite. S'il n'y en a pas, la placer tout à droite

