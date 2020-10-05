# JAVA 
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

----------------------------------
-----------------------------

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

### EVALUATION
================

#### Évaluation d'exécution

On doit résoudre cette tâche conformément à la description de la tâche, en utilisant le language demandé par le compilateur exemple une
syntaxe en **LUA** ne peut pas s'executer dans un programme **JAVA**.


#### Évaluation de TaskRuntime

On doit démontrer la capacité d'un langage pour les programmes à exécuter du code écrit dans le langage fourni au moment de l'exécution.
On y retrouve les expression et instruction **autorisé** par le programme, pour aller plus loin les environnements, les arguments
et l'environnement lexical (utf-8,etc...). Si il y a une erreur de syntaxe, d'indentation ou autres une erreur runtime apparait :/ .

![Exemple](https://www.google.com/url?sa=i&url=https%3A%2F%2Fairbrake.io%2Fblog%2Fwhat-is%2Fruntime-error&psig=AOvVaw3vzvLs2hWMFzn09vyK0KN_&ust=1601991283114000&source=images&cd=vfe&ved=0CAIQjRxqFwoTCOiop9_InewCFQAAAAAdAAAAABAD)


De plus le programme  est évalué pour savoir l'autorisation certe mais la restriction aussi ! Comme pour restreindre la limitation des ressource 
pour le programme ou une fonctions. Pour finir il évalue aussi compatibilité entre les différentes bibliothèque / plateforme / language.

La seule méthode pour résoudre les problèmes reste de debogguer via print par exemple ^^.

![Exemple](https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww3.ntu.edu.sg%2Fhome%2Fehchua%2Fprogramming%2Fjava%2FJ1a_Introduction.html&psig=AOvVaw2mXbqJt_OA0-4vjlGVDsR2&ust=1601985100387000&source=images&cd=vfe&ved=0CAIQjRxqFwoTCOjjmN2xnewCFQAAAAAdAAAAABAK)

-----------------------
------------------------------

### LES ASSIGNATIONS

Elles sont les valeurs associer a une variable.

exemple : 

	const string Lucas = "The rock" + "rocky"
	System.out.println(Lucas) // print : The rock rocky

-----------------------------
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

Une instruction se termine toujours avec ;

----------------------------
----------------------------------

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

### CONDITIONS

On appelle structure conditionel les instructions qui permettent de tester si une condition est vraie ou non. Ces structures conditionnelles 
peuvent être associées à des structures qui se répètent suivant la réalisation de la condition, on appelle ces structures des structures de boucle

#### La notion de bloucle

* L'instruction if :

L'instruction if est la structure de test la plus basique, on la retrouve dans tous les langages (avec une syntaxe différente...). Elle permet 
d'exécuter une série d'instructions si jamais une condition est réalisée.

![Exemple](https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.tutoderien.com%2Fcondition-if-dans-java-ou-comment-dire-au-code-quoi-faire%2F&psig=AOvVaw0w175GusxGjByY91eO8CpA&ust=1601987675696000&source=images&cd=vfe&ved=0CAIQjRxqFwoTCOin7qm7newCFQAAAAAdAAAAABAD)


* L'instruction if ... else :

L'instruction if dans sa forme basique ne permet de tester qu'une condition, or la plupart du temps on aimerait pouvoir choisir les instructions à 
exécuter en cas de non réalisation de la condition...
L'expression if ... else permet d'exécuter une autre série d'instruction en cas de non-réalisation de la condition.

![Exemple](https://www.google.com/imgres?imgurl=https%3A%2F%2Fwww.homeandlearn.co.uk%2Fjava%2Fimages%2Fcon_logic%2Fif_elseIF_statement.gif&imgrefurl=https%3A%2F%2Fwww.homeandlearn.co.uk%2Fjava%2Fjava_if_else_statements.html&tbnid=e4j9ygX0rE4u-M&vet=12ahUKEwj-nd3iup3sAhVGgRoKHVFlAm4QMygBegUIARCjAQ..i&docid=Ea7IiPHPG7YyXM&w=460&h=279&q=structure%20if%20do%20java&ved=2ahUKEwj-nd3iup3sAhVGgRoKHVFlAm4QMygBegUIARCjAQ)


* La boucle for :

L'instruction for permet d'exécuter plusieurs fois la même série d'instructions: c'est une boucle!
Dans sa syntaxe, il suffit de préciser le nom de la variable qui sert de compteur (et éventuellement sa valeur de départ, la condition sur la variable 
pour laquelle la boucle s'arrête (basiquement une condition qui teste si la valeur du compteur dépasse une limite) et enfin une instruction qui incrémente
 (ou décrémente) le compteur.

![Exemple](https://www.google.com/imgres?imgurl=https%3A%2F%2Fi.ytimg.com%2Fvi%2FOKiXQXRQQ58%2Fmaxresdefault.jpg&imgrefurl=https%3A%2F%2Fwww.youtube.com%2Fwatch%3Fv%3DOKiXQXRQQ58&tbnid=HOImxNUeDWPjWM&vet=12ahUKEwjFqpyLu53sAhUCw4UKHSl5CecQMygAegUIARCpAQ..i&docid=Yti2SOZZqxmY0M&w=1280&h=720&q=boucle%20for%20java&ved=2ahUKEwjFqpyLu53sAhUCw4UKHSl5CecQMygAegUIARCpAQ)


* Les boucles :
 
Elles sont des structures qui permettent d'exécuter plusieurs fois la même série d'instructions jusqu'à ce qu'une condition ne soit plus réalisée...
On appelle parfois ces structures instructions répétitives ou bien itérations.
La façon la plus commune de faire une boucle, est de créer un compteur (une variable qui s'incrémente, c'est-à-dire qui augmente de 1 à chaque tour 
de boucle) et de faire arrêter la boucle lorsque le compteur dépasse une certaine valeur.

![Exemple](https://www.google.com/url?sa=i&url=http%3A%2F%2Fwww.moserware.com%2F2008%2F02%2Ffor-loops-using-i-i-enumerators-or-none.html&psig=AOvVaw1zKkuJK6QgfpuIxAxmk4gj&ust=1601990055721000&source=images&cd=vfe&ved=0CAIQjRxqFwoTCKDDrpXEnewCFQAAAAAdAAAAABAD)

------------------
--------------------

### BOUCLE AVANCE

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

------------------------
-----------------------

### PARAMETRE

La notion de classe paramétrée est présente dans Java depuis la version 5.0. On appelle cela des classes généric.
Cette notion a été empruntée au langage C++ et permet, entre autre, de spécialiser les classes en fonction d'objet et de les manipuler 
avec des parametres c'est le principe de base de la POO.

Ainsi, nous pouvons avoir une liste de chaînes de caractères ou une liste de personnes. Nous avons besoin des mêmes opérations sur les deux listes : 
ajouter, rechercher, retirer. Nous ne voulons cependant pas mélanger les personnes et les chaînes de caractères.Cette paramétrisation simplifie la vie du programmeur 
en lui garantissant que les collections ne contiennent que des objets d’un type donné.

La paramétrisation est réalisée en spécifiant le type des objets manipulés. Il est nécessaire de préciser 
ce type lors de la déclaration de la référence et lors de la création de l’objet.

![Exemple](https://www.google.com/imgres?imgurl=https%3A%2F%2Frmdiscala.developpez.com%2Fcours%2FLesChapitres.html%2FJava%2FCours3%2Fclassembre2.png&imgrefurl=https%3A%2F%2Frmdiscala.developpez.com%2Fcours%2FLesChapitres.html%2FJava%2FCours3%2FChap3.1.htm&tbnid=fvgAFwwzsNXDCM&vet=12ahUKEwim5YnYxp3sAhUBVhoKHRDHCwkQMygEegUIARCYAQ..i&docid=rFF4TWau_VRO5M&w=512&h=298&q=parametre%20de%20classe%20java&ved=2ahUKEwim5YnYxp3sAhUBVhoKHRDHCwkQMygEegUIARCYAQ)

--------------------
-------------------
*Merci de votre attention
* Realisé par le boss Trystan, le roi romain, le dieu amin, et DarkLucas44HackeurX°9DDOSMASTER the best kikkoo of world.