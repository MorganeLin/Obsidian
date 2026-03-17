## VIM
### Raccourcis Vim 

Pour faciliter les raccourcis Vim il est important de configurer son [[vim.rc]]
#####  Pour se déplacer 
Mettre avant le nombre de chiffre souhaité

	gg - pour aller au début du fichier
	G - pour aller à la fin du fichier 
	j - pour aller vers le bas
	k - pour aller vers le haut
	h - pour aller vers la gauche
	l  - pour aller vers la droite
	$ - pour aller à la fin d'une phrase
	e - pour aller à la fin d'un mot
	0 - pour aller au début de la phrase
	
##### Commandes insert

	a - pour faire insert vers la droite
	Shift + o - insert vers le haut
	 o - insert vers le bas

##### Outils entre les parenthèses

	c i ( - changer ce qu'il y a à l'intérieur de la brackets 
	d i ( - supprimer ce qu'il y a entre parenthèses
	y i ( - copier ce qu'il y a entre parenthèses

##### Quelques commandes pour le tree

	:E - Pour ouvrir le tree de l'emplacement du fichier
	:15 le - Pour ouvrir le tree afin de naviguer entre les fichiers
	:Vsplit (le nom du fichier) - scinder l'écran en deux avec le fichier actuel et le fichier mentionné   