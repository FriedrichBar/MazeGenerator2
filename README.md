# Translation in english coming soon

# Projet Labyrinthe Maze Runner

## Promotion Cybersécurité du Logiciel 2020-2023

## Fonctionnement

`python3 ProjetLabyrinthe.py`

Le programme renvoie une image du labyrinthe nommée Labyrinthe.png.

Il va ensuite visualiser le labyrinthe après Dijkstra et l'enregistre également sous le nom CarteLabyrinthe.png.

Enfin, il renvoie une dernière image, SolutionLabyrinthe.png qui affiche le chemin solution depuis une cellule sélectionnée aléatoirement, et affiche dans la console la taille du chemin solution depuis cette cellule.

## Benchmark

Le programme de benchmark est inclus dans l'archive zip. Pour l'exécuter, il suffit de faire `python3 benchmark.py`.

|Taille du Labyrinthe|Nombre de répétition|Moyenne|
|--------------------|--------------------|-------|
|         8          |          10        |  10.0 |
|        16          |          10        |  30.2 |
|        32          |          10        |  101.5|
|        64          |          10        |  490.6|
|        128         |          10        |  798.3|
|        256         |          10        | 3691.0|
|        512         |          10        |13842.3|

## Autheur

Friedrich Bär