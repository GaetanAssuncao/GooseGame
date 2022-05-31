# GooseGame

1.1 Description et objectifs du projet
Le but de ce travail est de valider un concept de jeu en réseau de type tour à tour. Dans ce projet la 
base de jeu utilisé est le « jeu de l’oie ».
L’idée est d’utiliser ce TPI comme base pour le développement d’outils ludiques pour l’enseignement.

1.2 Déroulement du projet
Il existe deux types d’utilisateurs : les joueurs et le maître du jeu.
Le maître en question peut lancer l’application qui contient le serveur de jeu, une application 
graphique et une page Web. 

Les joueurs pourront scanner un QR-code sur un écran géant à l’aide de leur smartphone. Ils 
accèderont à une page qui demande leur pseudo. Une fois celle-ci remplie ils seront connectés au jeu. 
Sur l’écran géant la liste des joueurs connectés avec leur pseudo sera affichée, et un bouton intitulé 
« Jouer » y figura afin de permettre au maître du jeu de débuter la partie.

Une fois le jeu lancé tous les utilisateurs auront un pion d’une couleur différente. Chacun leurs tours 
les joueurs pourront jouer depuis leur portable en guise de terminal en lançant les dés.

Quelques règles sont en place pour dynamiser le jeu.
Une fois qu’un joueur gagne la partie, un message s’affiche avec le nom du gagnant. Le maître du jeu 
peut choisir de quitter l’application ou de relancer une partie. S’il choisit de relancer la partie tous les 
joueurs seront déconnectés et la page avec le QR-code sera de nouveau affichée à l’écran pour 
permettre de rejoindre la nouvelle partie.
