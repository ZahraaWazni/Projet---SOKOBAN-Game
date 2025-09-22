# Sokoban - Partie 2 

Deuxième partie du TP noté du jeu Sokoban.


## Compilation

Pour compiler le jeu Sokoban, il faut entrer la commande suivante:

```
make
```
Pour obtenir plus d'infos de compilation, il est possible d'entrer :

```
make help
```

### Utilisation de l'exécutable

Pour lancer le jeu, après avoir compiler il faut entrer la commande suivante :

```bash 
./bin/main level/<niveau voulu>.txt [--console] # en mode console
# ou
./bin/main level/<niveau voulu>.txt --sdl2 # en mode sdl2
```

### Comment jouer

Pour jouer le jeu, utiliser les touches suivantes:

```
I: se deplacer en haut
J: se deplacer à gauche
K: se deplacer en bas 
L: se deplacer à droite
Q: quitter le jeu
```

### Auteurs

- Zahraa WAZNI
- Zoé PURSON-PASQUALINI

### Version 

```bash
# ligne de commande
gcc -v
# -> gcc version 9.4.0 (Ubuntu 9.4.0-1ubuntu1~20.04.1)

# ligne de commande
gcc -dM -E - < /dev/null | grep __STDC_VERSION__
# -> define __STDC_VERSION__ 201710L
```

### Captures d'images

#### Console

![Console](Screenshots/console.gif)

#### SDL2

![SDL2](Screenshots/sdl2.gif)


### To do

- Ajouter des textures
- Ajouter du son
- Donner la possibilité à l'utilisateur de choisir les niveaux
- Ajouter plus de niveaux
