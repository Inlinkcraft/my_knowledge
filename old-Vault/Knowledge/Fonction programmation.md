---
type: Knowledge
class: Programmation Avancé c++
id: GIF-1003
chapiter: Chapitre-1
title: Fonction
tags: Knowledge/GIF-1003/Chapitre-1/Fonction_programmation
created: 2024-01-24 20:33
sr-due: 2024-02-10
sr-interval: 12
sr-ease: 270
---
# Fonction programmation
----
Block de code qui est réutilisable a plusieurs reprise a divers endroit, permet une optimisation et simplification du code.

## C++
----
### Fonction
----
```C++
// déclaration
type nom_de_la_fonction(type arg); // Dans le .h
//implémentation
type nom_de_la_fonction(type arg){ // Dans le .cpp
	[code];
	return
}
```

#### Argument de la fonction
----
##### Par copie
---
Lorsque la fonction est utilisé comme suit:
```C++
type nom_de_la_fonction(type arg){ // Dans le .cpp
	[code];
	return
}
```
Les argument seront copier et modifiable seulement dans la fonction

##### Par référence
----
Si on veut éviter la copie de l'objet il est possible d'utiliser la référence soit le symbole `&` avant la déclaration de l'argument:
```C++
type nom_de_la_fonction(type &arg){ // Dans le .cpp
	[code];
	return
}
```

##### Par pointeur
----
Finalement pour éviter la copie il est possible d'utilisé un [[Pointeur|pointeur]] pour avoir une référence indirecte à l'objet:
```C++
type nom_de_la_fonction(type* arg){ // Dans le .cpp
	[code];
	return
}
```

## Related Subjects
----
#### Links
----
- [[Fonction mathématique]]
#### flashcard 
----
- Qu'est ce qu'une fonction ?:: Block de code qui est réutilisable a plusieurs reprise a divers endroit, permet une optimisation et simplification du code.
<!--SR:!2024-02-06,8,270-->
- Qu'elle est la syntaxe de la déclaration d'une fonction en C++ ?:: `type nom_de_la_fonction(type arg);`
<!--SR:!2024-02-06,8,270-->
- Ou est écrite la déclaration de la fonction ?::Dans le .h
<!--SR:!2024-02-07,9,270-->
- Qu'elle est l'implémentation d'une fonction en C++ ?::`type nom_de_la_fonction(type arg){[code]; return}`
<!--SR:!2024-02-07,9,270-->
- Ou est écrite l'implémentation de la fonction en C++ ?:: Dans le .cpp
<!--SR:!2024-02-06,8,270-->
- Qu'elle sont les 3 type principal d'argument pour une fonction ?:Copie, Pointeur, Référence