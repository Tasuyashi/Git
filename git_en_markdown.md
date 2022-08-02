## *GitHub*

## 1Présentation
### 1.1 GitHub

*Plateforme colleborative* Pour dev, plus grand espace de stockage de travaux collaborative dans dans le monde! GitHub en lui-même n'est plus qu'un reseau social comme FB. Vous construisez un profil, vous y deposez des projet à partager et vous vous connectez avec d'autre utilisateur en suivant leurs comptes. Meme si la plupart des utilisateurs y deposent des project de programmes ou de code, rien no vous empeche d'y placer des textes ou tout type de fichier à présenter dans vos repertoires de projets


### 1.2 Git
Git est un *logiciel de controle de de version*, ce qui signifie qu'il gere les modification d'un projet sans écraser n'importe qu'elle partie de projet.

## 2 Git et GitHub
### 2.1 Vocabulaire
**ligne de commande**: En gros : le programme de l'ordinateur que nous utilisons pour entrer des commande Git. Dans le monde UNIX, on dit qu'on travaille en "ligne de commande" pour désigner le fait d'interagir avec un systéme informatique en entrant des lignes d'instructions textuelles dans un terminal, et non à l'aide d'une interface grafique.
Les commandes tapées dans le terminal sont interprétées par un shell.
 Journal du Net.
  https://www.journaldunet.fr/web-tech/dictionnaire-du-webmastering/1445276-commande-informatique-definition-precise-et-exmples/

  **Depot**: Un repertoire ou de l'espace de stockage ou vos projets peuvent vivre; les utlisateurs de GitHub raccourcissent en "repo" pour "repository". Li peut être un espace de stokage sue GitHunb ou un autre hebergeur en ligne. A l'interieur d'un depot, vous pouvez conserver des fichiers de codes, des fichiers txt des images.

  **Controle de version**: Fondamamentalement, l'objectif pour lequel Git a été concu. Quand vous avez un fichier Wourd, vous l'écrasez à chaque foit que vous sauvegardez plusieurs version. Avec Git, vous n'est plus obliger de faire ça. Git conserve des "instantanes" de chaque point dans l'historique d'un projet, de sorte que vous ne pouvez jamais le perdre ou l'écraser.

  **Commit** C'est la commmande qui donne à Git toute puissanc. quand vous comttez, vous prenez un instantaneée, une photo de votre depot à ce stade vous donnant point de contrôle que vous pouvez ensuite réévaluer ou tout simplement restaurer votre projet à cette version. il est nécessaair de rappler que le nom de vos commits doivent-être pralant afin de savoir à quel stade du projet celui-ci a été fait.

  **Branche**: Comment plusieurs personnes travaillant sur un projet en même temps sans que Git ne s'embrouille? Habituellement, elle se debranchent du projet principal avec leur propres version complètes, des modification qu'elles on chacune produites de leur cote. Aprés avoir terminer, il est temps de fusionner cette branche pour la ramener vers la branche master, le repertoire principal du projet;

  ### 2.2 Commandes specifiques Git 

  **git init**: Initialise un nouveau depost git jusqu'a ce que vous executiez les commandes Git qui suivent.

  **git config** Raccourci de configuration, ceci est tout particuliérement utile quand
  vous paramétrez Git pour la premier fois identifiant et mail d'utilisateut.

  **git help**: oublie une commande? pour afficher les 21 commande de git; 

  **git status**: Verifie le status de votre repo. Voir les fichiers et quelle sont sont les modifications à commiter et sur quelle branche ou repo vous étes en train de travailler.

  **git add**: Ceci n'ajouter pas des fichiers dans votre repo, Au lieu de cela, cela apporte de nouveaux fichiers à l'attestation de Git. Aprés avoir ajouter des fichiers, ils sont inclus dans les instantanes du depot Git.

  **git commit**: La commande la importante de Git. Aprs avoir effectue toute sorte de modification vous entrez ça afin de prendre instantanes du depot. le mettre en mémoire. On écrit ca sous la forme de git comit -m 'votre message' Le -m indique que la section suivente de la comande devrait être lu comme un message.

  **git branche**: Vous travaillez avec plusieurs collaborateurs et vous voulez produire des modification de votre cote? cette commande vous permet de construire une nouvelle branche, ou une chronologie de commits, des modifications et des ajouts de fichiers qui sont competement les votre titre va aprés la command. Si vous vouliez construire une nouvelle branche appellée 'Tatsuya' vous saisiriez git branche Tatsuya.

  **git checkout**: C'est une commande navigation qui permet de vous deplacer vers le repertoire que vous vouliez verifier. vous utiliser cette commande sous la forme de git checkout master pour regarder la branche master, ou checkout Tatsuya pour regarder une autre branche.


  **git merge**: Lorsque vous avez fini de travailler sur une branche, vous pouvez fusionner vos modification vers la branche master, qui est visible pour tous les collaborteur. Git merge Tatsuya prendrait toutes les modification que vous avez apportées à la branche Tatsuya eet les ajoutera à la brnche master.

  **git pus**: Si vous travaillez sur votre ordinateur ordinateur en local et vous voulez que vos commits soient visibles aussi en ligne sur GitHub, vous pushez les modification vers GitHub avec cette commande.

  **git pull**: Si vous travaillez en local et que vous voulez la version la plus e jour se votre repo pour travailler dessus, vous pouvez les modification provvenant de GitHub avec cette commande.

  **git clone**: Permet de dupliquer, cloner un esistant sur GitHub pour l'avoir en local.La commande git clone doit être suivit de url de repo correspondant qui copie depuis GitHub direct. 