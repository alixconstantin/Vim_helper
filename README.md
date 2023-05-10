##Commandes de navigation :
 
h, j, k, l : se déplacer à gauche, en bas, en haut et à droite respectivement. 
w : aller au début du mot suivant. 
b : aller au début du mot précédent. 
0 : aller au début de la ligne. 
$ : aller à la fin de la ligne. 
gg : aller au début du fichier. 
G : aller à la fin du fichier. 
Ctrl + f : avancer d'une page. 
Ctrl + b : reculer d'une page. 
 
 
 
##Commandes d'édition : 
 
i : passer en mode insertion avant le curseur. 
a : passer en mode insertion après le curseur. 
o : ouvrir une nouvelle ligne en dessous de la ligne actuelle et passer en mode insertion.
O : ouvrir une nouvelle ligne au-dessus de la ligne actuelle et passer en mode insertion.
u : annuler la dernière modification.
Ctrl + r : refaire la dernière modification annulée.
dd : supprimer la ligne actuelle.
dw : supprimer le mot actuel.
x : supprimer le caractère sous le curseur.



##Commandes de recherche et de remplacement :

/mot : rechercher 'mot' dans le fichier.
n : aller à l'occurrence suivante de la recherche.
N : aller à l'occurrence précédente de la recherche.
:%s/ancien/nouveau/g : remplacer toutes les occurrences de 'ancien' par 'nouveau' dans le fichier.
:%s/ancien/nouveau/gc : remplacer toutes les occurrences de 'ancien' par 'nouveau' dans le fichier avec une confirmation.



##Commandes d'enregistrement et de sortie :

:w : enregistrer le fichier.
:q : quitter Vim.
:wq ou :x : enregistrer et quitter Vim.
:q! : quitter Vim sans enregistrer.



##Commandes de fenêtres :

:split ou :sp : diviser la fenêtre horizontalement.
:vsplit ou :vs : diviser la fenêtre verticalement.
Ctrl + w suivi de h, j, k, l : naviguer entre les fenêtres.



##Commandes visuelles :
v : passer en mode visuel pour sélectionner du texte.
V : sélectionner des lignes entières.
y : copier la sélection.
p : coller après le curseur.

