Architecture des dossiers et fichiers linux :

Pour afficher les premiers et principaux répertoires de linux, il suffit de tapper la commande suivante : tree -d -L 1

tree = le format que l'on veut afficher 

-d = Ceci va permettre d'afficher uniquement les dossiers et non les fichiers

-L (nombre_que_l'on_veut)= Le nombre que l'on va choisir derrière est décisif dans le résultat que nous allons obtenir, ce sera le nombre de "branche" de l'arbre afficher dans chaque dossier principaux

Nous avons donc grâce à la commande tree -d -L 1, le résultat suivant qui nous donne les répertoires principaux :


![alt text](https://github.com/kevinguyodo/linux/blob/main/Cours%20linux%201.PNG?raw=true)

Dès à présent, je veux en connaître davantage sur la composition de ses répertoires, pour cela j'ai uniquement à changer le chiffre de ma commande pour m'afficher plus de "branche".

J'exécute donc la commande suivante tree -d -L 2, et j'ai donc les résultats suivant :

Ceci est le résultat pour les trois premiers principaux répertoires: 

![alt text](https://github.com/kevinguyodo/linux/blob/main/bin%20boot%20dev.PNG?raw=true)

Nous avons ensuite, le répertoire ce nommant : etc 

Celui-ci est composé de trop de dossier pour que ce soit afficher en une image, il est composé notament de dossier se nommant : ssh, python, vim, terminfo, security ...

Puis nous avons ensuite : 

![alt text](https://github.com/kevinguyodo/linux/blob/main/Cours%20linux%202.PNG?raw=true)

Mais encore nous avons un grand répertoire nommé : proc

Mais il est doté de trop de dossiers, or tous ont pour nom des chiffres sauf 12 d'entre-eux.


Et en fin nous avons : 

![alt text](https://github.com/kevinguyodo/linux/blob/main/Cours%20linux%203.PNG?raw=true)


![alt text](https://github.com/kevinguyodo/linux/blob/main/Cours%20linux%204.PNG?raw=true)

Et nous pouvons voir qu'il y a en tout 434 répertoires en affichant uniquement que deux branches de l'architecture de Linux



Histoire linux :

Dates clés

En 1991 à l’initiative d’un étudiant d’Helsinki : Linus Torvalds. En août 1991, il poste sur un forum un message dans lequel il déclare travailler au développement d’un système d’exploitation libre.

En 1992, le noyau Linux passe ainsi sous GPL, la licence Open Source définie par une figure du logiciel libre, Richard Stallman.

1993 est l’année d’une autre grande étape de l’histoire du kernel selon la Linux Fondation. Créée à l’initiative de Patrick Volkerding, Slackware a été la première distribution Linux à bénéficier d’une large adoption.

1996 création du logo de linux que l'on connait tous le fameux manchot. L'idée de se logo est tiré d'une anecdote de vie de Linus Torvalds.

1998 linux prend un gros coup de pouce suite a l'adoption du système par les géants du secteur informatique.

2010 importaion de linux sur les mobiles. Si Google n’est pas la première entreprise à avoir porté Linux sur téléphone mobile, elle est néanmoins la première à en avoir autant répandu l’usage grâce à la plate-forme Android
