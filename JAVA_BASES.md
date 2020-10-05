i# JAVA 
------------------------
------------------------
## INTRODUCTION

Java est un langage POO. C'est un Langage compilé ce qui signifie qu'on peut le compiler afin de voir si notre code est correct, auquel cas voir ou sont les erreurs. 
- System.out.println permet de print le résultat sur le terminal 

------------------------
------------------------
### VARIABLES

Elles servent à stocker une information. Les variables sont mises en mémoire dans la ram de l'ordi. Il existe plusieurs types de variables pour plusieurs types d'informations : 
 
* Integer = nombre entier (1,5,22,540566) 
* Double = nombre décimaux (3.5, 22.45)
* String = texte
* Boolean = true/false
* Char = un seul character (a, !)

Une variable se décompose comme telle :

int numbers  --> int étant le **type**, **numbers** étant le nom de la var

------------------------
------------------------


### OPERATORS 

Les operators servent à additionner/soustraire/multiplier etc des statements notamment des variables.
Il existe donc plusieurs operators :

* (+ - == / *)
* le % qui est le modulo, c'est le reste de la division entre 2 nbx (7%3 = 1 car 3x2=6 + 1 = 7. on prend tjrs le reste de la division du 2eme nombre --> 12%5 = 5x2 =10 donc il reste 2)
* == veut dire egale  
* != veut dire l'inverse  
* .equals() permet de savoir si un string est egale à un autre (ex: person1.equals(person2) = est ce que la var string "person1" est = à la var person2 , true / false)

------------------------
------------------------


### CLASS

Une class permet de ... C'est obligatoire en Java de déclarer une class pour que le code soit fonctionnel. 

* statement = état (solde d'un compte bancaire) 
* behavior = comportement (retrait/depot sur le compte bancaire)

exemple de class :


public class Bank {

	String countName;
	double soldeCount;
	int numberOfCount;
	

	public Bank(String name, double solde, int number) {
		countName = name;
		soldeCount = solde;
		numberOfCount = number;
	}
* "Bank" est donc une class.

<<<<<<< HEAD
### CONDITIONS 

La condition permet d'éxécuter une fonction/donner un résultat si un paramètre est validé.

### BOUCLE / LOOP

la boucle permet d'éxécuter une fonction tant qu'un paramètre/condition est remplit. 
=======
------------------------
------------------------

### LA BOUCLE

Une boucle est un outil de programmation qui permet aux développeurs de répéter le même bloc de code jusqu'à ce qu'une certaine condition soit remplie.
Elle permet d'éviter les répétitions dans notre code et de gagner du temps.
Il existe 3 type de boucles :

*while loops
*for loops
*for-each loops


#### While

la boucle While ne fonctionnera que si la condition est vraie. 
Elle continuera à faire tourner le code encore et encore jusqu'à ce que la condition soit évaluée comme fausse.
exemple de While : 

	makeHamburguer = 10
	while (makeHamburguer > 10) {

  // code to run

}

 Cependant, une boucle while continuera à faire tourner le code encore et encore jusqu'à ce que la condition soit évaluée comme fausse. 
Ainsi, le bloc de code se répétera jusqu'à ce que makeHamberguer soit inférieure ou égale à 10.

#### FOR

 elle nous aident à incrémenter notre compteur:


ex : 

	for (int i = 0; i < 5; i++) {

  // code that will run

}

initialisation du compteur de variable ( i=0) ensuite la conditions (i<5) et i++ pour mettre en place le compteur ( de combien montes la variable a chaque tour de la boucle)

#### FOR-EACH
Les boucles for-each vous permettent de passer directement en boucle chaque élément d'une liste d'éléments (comme un tableau ou une ArrayList) et d'effectuer une action avec chaque élément. 
exemple :

	for (String inventoryItem : inventoryItems) {

  	System.out.println(inventoryItem);
	}
On peut lire le ":" comme "dans" inventoryItems.

------------------------
------------------------

### LE COMMENTAIRE

Les commentaires en Java permette de mieux se retrouvé dans nos projets et de rendre notre code plus lisible, ils sont ignoré par la console exprés.

exemple:

commentaire d'une ligne:

	// ceci est un commentaire
	System.out.println("Hello World");
le commentaire sur l'exemple ci dessus conscerne qu'une ligne grâce a "//"

commentaire de plusieur ligne:

	/* Ceci est un commentaire de plusieurs lignes 
	sur Java  */
	System.out.println("Hello World");

------------------------
------------------------

### LES ASSIGNATIONS

Elles sont les valeurs associer a une variable.

exemple : 

	const string Lucas = "The rock" + "rocky"
	System.out.println(Lucas) // print : The rock rocky
>>>>>>> origin/Amin
