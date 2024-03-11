---
type: Knowledge
class: Programmation Avancé c++
id: GIF-1003
chapiter: Chapitre-1
title: Compilateur 
tags: Knowledge/GIF-1003/Chapitre-1/Compilateur_vs_Interpréteur
created: 2024-01-17 20:13
sr-due: 2024-02-06
sr-interval: 4
sr-ease: 230
---
# Compilateur vs Interpréteur 
----
## Compilateur
----
Un compilateur va venir compiler le code en language machine
```mermaid
graph TD; 
	id1(Code C++ text)-->id2(Compilateur Window); 
	id1(Code C++ text)-->id3(Compilateur Mac); 
	id1(Code C++ text)-->id4(Compilateur Linux); 
	id2(Compilateur Window)-->id5(Executable Window); 
	id3(Compilateur Mac)-->id6(Executable Mac); 
	id4(Compilateur Linux)-->id7(Executable Linux); 
```
Exemples:
- GNU compilateur collection (UNIX, Windows, DOS, etc)
- Microsoft visual c++ (Windows)
- Borland c++
- ...

## Compilateur - Interpréteur
----
Version de chacun qui porte des compromis
```mermaid
graph TD;
	id1(Code Java Text) --> id2(Compilateur)
	id2(Compilateur) --> id3(Byte code)
	subgraph Interpréteur
	id3(Byte code) --> id4(Machine virtuel);
	end
	id4(Machine virtuel) --> id5(Execution);
```

## Interpréteur
----
Un interpréteur vient abstraire l'execution de la machine virtuelle
```mermaid
graph TD;
	id1(Code Pyhton text) --> id2(Compilateur);
	subgraph Interpréteur
	id2(Compilateur) --> id3(Byte code);
	id3(Byte code) --> id4(Machine virtuel);
	end
	id4(Machine virtuel) --> Execution;
```


## Related Subjects
----
#### flashcard 
----
- Qu'est ce qu'un compilateur ?::Un compilateur va venir compiler le code en language machine
<!--SR:!2024-02-09,7,190-->
- Qu'elle est la limitation d'un compilateur ?::Le compilateur compile le code pour une seul et unique machine
<!--SR:!2024-02-23,21,250-->
- Qu'elle est le processus compilateur ?::Code->Compilateur->Executable
<!--SR:!2024-02-15,17,250-->
- Qu'est ce qu'un interpréteur ?::Un interpréteur vient abstraire l'execution de la machine virtuelle
<!--SR:!2024-02-07,5,170-->
- Qu'elle est le processus de l'interpréteur ?::Code->Interpréteur:(Compilateur->Byte code->Machine virtuel)->Execution
<!--SR:!2024-02-10,8,210-->
- Qu'est ce qu'un compilateur-interpréteur ?::Version mixte du compilateur et de l'interpréteur qui offre quelque possibilité supplémentaire aux profit de compromis
<!--SR:!2024-02-12,10,190-->
- Qu'elle est le processus du compilateur-interpréteur ?::Code->compilateur->Byte code->Interpréteur:(Machine virtuel)->Execution
<!--SR:!2024-02-10,12,230-->