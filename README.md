# assma
Ce projet à été réalisé sous netbeans,


Le programme permet de charger un fichier .txt puis d'effectuer l'une des 3 analyses ( lexicale, syntaxique ou semantique )

Nous détaillons de façon générale la manière dont nous avons realiser chacune de ces 3 fonctions d'analyses.

Analyse lexicale : 

On va lire le fichier .txt préalablement charger avec le boutton charger un fichier, 
à chaque itération on va stocker la ligne courante dans un tableau de caracteres puis on va tester individuellement chaque caractere pour voir ci ce dernier fait partie de notre alaphabet, si oui alors on va l'ajouter dans notre variable mot, l'analyse lexicale d'un mot contenu dans notre buffer via une succession de if et de case jusqu'a ce que l'on traite tout les cas possible puis on va repeter le processus precedant jusqu'a ce que l'on finisse de parcourir l'ensemble du fichier.

Analyse Syntaxique :

dans un premier temps,
 on va réutiliser le code que l'on a précédement utiliser pour l'analyse lexicale sauf que cette fois, lors de l'analyse du mot, on va attribué à chaque cas possible un nombre ou une lettre qui nous servira plus tard pour l'analyse syntaxique, on stockera le nombre ou la lettre en question dans une variable que l'on a nommé "i", ce processus va se repeter jusqu'a ce qu'on analyse tout les mots d'une ligne puis on va vérifier la syntaxe de la ligne en question grace à notre variable syntax en effectuant une serie de tests,

Analyse Semantique : 

on va réutiliser le code precedement utilisé pour l'analyse syntaxique sauf que cette fois, au moment de l'analyse du mot, on va en plus de la variable syntax, egalement utiliser une variable "i" dans laquelle on stockera la traduction java du mot analtysé, ainsi a la fin de l'analyse de chaque ligne on aura dans notre variable 

puis comme precedement, on va effectuer des tests sur un ensemble de conditions pour chaque cas possible, si tout est bon, on aura un return en sortie.
le binome:
ben ahmed daho asmaa
kerroumi fatima zohra
