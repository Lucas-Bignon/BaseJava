
L'évaluation :
================

### Évaluation d'exécution

On doit résoudre cette tâche conformément à la description de la tâche, en utilisant le language demandé par le compilateur exemple une
syntaxe en **LUA** ne peut pas s'executer dans un programme **JAVA**.


### Évaluation de TaskRuntime

On doit démontrer la capacité d'un langage pour les programmes à exécuter du code écrit dans le langage fourni au moment de l'exécution.
On y retrouve les expression et instruction **autorisé** par le programme, pour aller plus loin les environnements, les arguments
et l'environnement lexical (utf-8,etc...). Si il y a une erreur de syntaxe, d'indentation ou autres une erreur runtime apparait :/ .

![Exemple](https://www.google.com/url?sa=i&url=https%3A%2F%2Fairbrake.io%2Fblog%2Fwhat-is%2Fruntime-error&psig=AOvVaw3vzvLs2hWMFzn09vyK0KN_&ust=1601991283114000&source=images&cd=vfe&ved=0CAIQjRxqFwoTCOiop9_InewCFQAAAAAdAAAAABAD)


De plus le programme  est évalué pour savoir l'autorisation certe mais la restriction aussi ! Comme pour restreindre la limitation des ressource 
pour le programme ou une fonctions. Pour finir il évalue aussi compatibilité entre les différentes bibliothèque / plateforme / language.

La seule méthode pour résoudre les problèmes reste de debogguer via print par exemple ^^.

![Exemple](https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww3.ntu.edu.sg%2Fhome%2Fehchua%2Fprogramming%2Fjava%2FJ1a_Introduction.html&psig=AOvVaw2mXbqJt_OA0-4vjlGVDsR2&ust=1601985100387000&source=images&cd=vfe&ved=0CAIQjRxqFwoTCOjjmN2xnewCFQAAAAAdAAAAABAK)




La condition :
=================


On appelle structure conditionel les instructions qui permettent de tester si une condition est vraie ou non. Ces structures conditionnelles 
peuvent être associées à des structures qui se répètent suivant la réalisation de la condition, on appelle ces structures des structures de boucle

## La notion de bloucle

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



## Les boucles :
 
Elles sont des structures qui permettent d'exécuter plusieurs fois la même série d'instructions jusqu'à ce qu'une condition ne soit plus réalisée...
On appelle parfois ces structures instructions répétitives ou bien itérations.
La façon la plus commune de faire une boucle, est de créer un compteur (une variable qui s'incrémente, c'est-à-dire qui augmente de 1 à chaque tour 
de boucle) et de faire arrêter la boucle lorsque le compteur dépasse une certaine valeur.

![Exemple](https://www.google.com/url?sa=i&url=http%3A%2F%2Fwww.moserware.com%2F2008%2F02%2Ffor-loops-using-i-i-enumerators-or-none.html&psig=AOvVaw1zKkuJK6QgfpuIxAxmk4gj&ust=1601990055721000&source=images&cd=vfe&ved=0CAIQjRxqFwoTCKDDrpXEnewCFQAAAAAdAAAAABAD)




Les paramètres :
==================


La notion de classe paramétrée est présente dans Java depuis la version 5.0. On appelle cela des classes généric.
Cette notion a été empruntée au langage C++ et permet, entre autre, de spécialiser les classes en fonction d'objet et de les manipuler 
avec des parametres c'est le principe de base de la POO.

Ainsi, nous pouvons avoir une liste de chaînes de caractères ou une liste de personnes. Nous avons besoin des mêmes opérations sur les deux listes : 
ajouter, rechercher, retirer. Nous ne voulons cependant pas mélanger les personnes et les chaînes de caractères.Cette paramétrisation simplifie la vie du programmeur 
en lui garantissant que les collections ne contiennent que des objets d’un type donné.

La paramétrisation est réalisée en spécifiant le type des objets manipulés. Il est nécessaire de préciser 
ce type lors de la déclaration de la référence et lors de la création de l’objet.

![Exemple](https://www.google.com/imgres?imgurl=https%3A%2F%2Frmdiscala.developpez.com%2Fcours%2FLesChapitres.html%2FJava%2FCours3%2Fclassembre2.png&imgrefurl=https%3A%2F%2Frmdiscala.developpez.com%2Fcours%2FLesChapitres.html%2FJava%2FCours3%2FChap3.1.htm&tbnid=fvgAFwwzsNXDCM&vet=12ahUKEwim5YnYxp3sAhUBVhoKHRDHCwkQMygEegUIARCYAQ..i&docid=rFF4TWau_VRO5M&w=512&h=298&q=parametre%20de%20classe%20java&ved=2ahUKEwim5YnYxp3sAhUBVhoKHRDHCwkQMygEegUIARCYAQ)
