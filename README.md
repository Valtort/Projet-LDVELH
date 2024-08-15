# Projet: Livre dont vous êtes le héros
Ce petit projet permet de jouer à un livre dont vous êtes le héros.

## Compilation
> [!NOTE]
>Une compilation classique avec gcc suffit.

## Informations générales

Vous retrouverez les fichiers livre.txt écrit par mon professeur d'informatique ainsi que le fichier multiverse.txt co-écrit avec Corentin, un ancien élève de MPI*, ceux-ci contiennent des livres jouables avec le programme.

![image](https://github.com/user-attachments/assets/cf822eb5-8142-42d6-8cae-551bce6e6eb4)

*Exemple de LDVELH assez court*


## Formes des fichiers textes

1. Un fichier .txt correspondant à un livre jouable est de la forme : 

  - Entier qui indique le nombre de pages.

  - Suivi d'autant de pages qu'indiqué.

    - Chaques pages sont de la formes : 

    - Entier qui indique le nombre de choix.

    - Texte de la page actuelle.

    - Suivi d'autant de choix qu'indiqué.

      - Chaques choix sont de la formes :

      - Texte qui décrit le choix.

      - Page à laquelle mène ce choix.

--------------------------------

![image](https://github.com/user-attachments/assets/06473e11-8d1b-4084-8a25-50c0d512a4af)

*Petit exemple de fichier texte correspondant à un LDVELH*


## Execution du programme

Quand on exécute le programme, on doit donner le nom du livre .txt.

## Ce que ce projet m'a apporté

J'ai appris à écrire un LDVLEH.

## Difficultés rencontrées

Une seule difficulté a été rencontrée : il faut être très rigoureux lors de la rédaction du .txt, si un seul espace se glisse après le chiffre indiquant le nombre de choix, tout le programme est décalé.
