### LES MOTS CLEFS

Dans le langage de programmation Java , un mot-clé est l’un des 51 mots réservés qui ont une **signification prédéfinie** dans le langage; 

pour cette raison, les programmeurs **ne peuvent pas utiliser de mots-clés comme noms** de variables , de méthodes , de classes ou comme tout autre identifiant.

Chaque mots-clés JAVA a une signification particulière.

Exemple de mots clefs: 

* if
* boolean
* do
* etc ...

------------------------
------------------------

### L'INSTRUCTION ET LE BLOC D'INSTRUCTION

Une instruction permettent de **lancer des actions** (un test, une boucle, ...).
Elle demande directement à l'ordinateur de faire quelque chose

le bloc d’instructions peut contenir une seule ou plusieurs instructions.

	{
    System.out.print( «Veuillez renseigner votre nom : « );
    String nom = System.console().readline();
    System.out.println( «Votre nom est : « + nom );
	}
<<<<<<< HEAD
<<<<<<< HEAD
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
=======
* "Bank" est donc une class.
>>>>>>> origin/lucas
=======

Une instruction se termine toujours avec ;
>>>>>>> origin/Trystan
