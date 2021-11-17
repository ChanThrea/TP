GITHUB
======

## Présentation
### GitHub

* Plateforme collaborative* pour les dev, plus grand stockage de travaux collaboratifs au monde. En lui-même il n'est rien d'autre qu'un réseau social comme Facebook.
Vous y construisez un  profil, vous y déposez des projets à partager et vous vous connectez avec d'autres utilisateurs, vous pouvez même les suivre.
Même si la plupart des autres utilisateurs y déposent des projets de programmation ou de code, rien ne vous empêche d'y placer des textes ou type de fichiers dans vos répertoires de projet.

### Git
git est un *logiciel de contrôle de version*, ce qui signifie qu'il gère les modifications d'un projet sans écraser n'importe quelle parie du projet.

## Lexique de Git et Github
### Vocabulaire
**ligne de commande**: En gros, le programme de l'ordinateur que nous utilisons pour entrer des commandes Git.
On dit quon travaille en "ligne de commande" pour désigner le fait d'intéragir avec un système informatique, et non à l'aide d'une interface graphique.
Les commandes tapées dans le terminal sont interprêtées par un Shell.
[Doc: Journal du net](https://www.journaldunet.fr/webtech/dictionnaire-du-webmastering/1445276-commande-informatique-définition-précise-et-exemples/)

**Dépot**: C'est un répertoire ou de l'espace de stockage, où vos projets peuvent vivre.
Les utilisateurs de GitHub raccourcissent ça en _"repo"_ pour _"repository"_. Il peut être un espace de stockage sur GitHub ou un atre hébergeur en ligne. A l'intérieur d'un dépôt, vous pouvez conserver des fichiers de codes, des fichiers texte et des images.

**Contrôle de version**: Fondamentalement l'objectif pour lequel Git a été conçu. Quand vous avez un fichier Word, vous l'écrasez à chaque fois que vous sauvegardez. Avec Git, vous n'êtes pas obligé de faire ça. Git conserve des "instantannées" de chaque point de l'historique d'un projet, de sorte à ne jamais rien perdre ou écraser.

**Commit**: C'est la commande qui donne à Git toute sa puissance. Quand vous committez, vous prenez un instantané, une photo de votre dépôt à ce stade vous donnant un point de contrôle que vous pouvez ensuite réévaluer ou simplement restaurer votre projet à cette version.
Il est nécessaire de rappeler que le nom de vos commits doivent être parlant afin de vous remémorer où en était le projetà ce stade.

**Branche**: Permet à plusieurs personnes de travailler en même temps sur le même projet. Habituellemment, elle se débranche du projet principal avec les propres versions complètes et font des modofications dessus.
Après avoir terminer, ils refusionnent cette branche avec la branche master, le répertoire principal du projet.

### Commandes spécifiques Git
**git init**: Initialise un nouveau dépôt git.
**git config**: Raccourci de configuration, ceci est tout particulièrement utile quand vous paramétrez Git pour le première fois (identifiant mot de passe)
**git help**: Oublié une commande ? Pour afficher les 21 commandes de git.
**git status**: Vérifie le statut de votre repository. Il permet de voir les fichiers et quelles sont les modifications à commiter sur quelle branche ou repo vous êtes en train de travailler.
**git add**: Cette commande n'ajoute pas des fichiers dans votre repository. Au lieu de cela, cela porte de nouveaux fichiers à l'attestion de git. Après avoir ajouter les fichiers peuvent être commités.
**git commit**: Après avoir effectué toutes sortes de modification vous committez pour sauvegarder votre travail. La sauvegarde s'effectueen local avec un messagede votre choix.
**git branch**: C'est une branche qui vous permet d'effectuer des modifications de votre côté.
**git checkout**: C'est la ligne de commande qui permet de naviguer d'une branche à l'autre.
**git merge**:  Le merge fusionne votre branch avec la branch master.
**git push**: Avec git push vous pouvez sauvegarder vos données en ligne sur GitHub, à utiliser après le commit.
**git pull**: Permet d'importer le travail d'une autre branch sur la votre.
**git clone**: Duplique un repository existant de github pour l'avoir en local.
