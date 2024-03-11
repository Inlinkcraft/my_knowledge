---
type: Knowledge
class: Mathématique pour informaticien
id: MAT-1919
chapiter: Chapitre-3
title: Démonstration d'un quantificateur existentiel 
tags: Knowledge/MAT-1919/Chapitre-3/Démonstration_dun_quantificateur_existentiel 
created: 2024-02-17 21:43
---
# Démonstration d'un quantificateur existentiel 
----
Démonstration d'un expression qui contient un [[Quantificateur existentiel|quantificateur existentiel]]

### Étape 1
----
Un choix est fait intelligemment de façons à associer à la variable $x$ un valeur qui existe de telle sorte que le prédicat soit satisfait. 

### Étape 2
----
Prouver le prédicat en utilisant la variable $x$

> [!Exemple]
> $(\exists x \in ]0, 1] | x^2 - 3x + 2 = 0)$
> $$
> \begin{array}{llr}
> 	\text{Soit} & P(x) = x^2 - 3x + 2 = 0 \\
> 	\text{Posons que} & x = 1 & \langle \text{car} \ x \ \text{existe et appartien à} \ ]0, 1] \rangle \\
> 	 & & \langle \text{Démontrons} \ P(x) \rangle \\
> 	\text{Comme} & 1^2 -3 \times 1 + 2 = 0 & \langle \text{Le prédicat est respecté} \rangle \\
> \end{array}
> $$
> **C.Q.F.D**

## Related Subjects
----
#### flashcard 
----
- Que doit-on absolument faire aux début d'une [[Démonstration d'un quantificateur existentiel]] ?:: Posé une variable valide pour le prédicat qui existe et qui appartient à l'intervalle.
<!--SR:!2024-03-05,3,250-->