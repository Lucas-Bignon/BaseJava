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

## FINISH

