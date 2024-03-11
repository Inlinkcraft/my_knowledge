---
type: Knowledge
class: Mathématique pour informaticien
id: MAT-1919
chapiter: Chapitre-1
title: Lois de Morgan 
tags: Knowledge/MAT-1919/Chapitre-1/Lois_de_Morgan 
created: 2024-01-16 20:11
sr-due: 2024-02-07
sr-interval: 9
sr-ease: 230
---
# Lois de Morgan 
----
Propriété utiliser avec divers type d'[[Expression booléenne|expression booléenne]]

## Propriété booléenne
----
Par définition:
$$\lnot \ (p \land q) \Leftrightarrow \lnot \ p \lor \lnot \ q$$
$$\lnot \ (p \lor q) \Leftrightarrow \lnot \ p \land \lnot \ q$$

## Propriété Quantificateur
----
Par définition:
[[Quantificateur universelle]]:
$$\lnot (\forall  \in T \ | \ P(x)) \Leftrightarrow (\exists  \in T \ | \ \lnot P(x))$$
[[Quantificateur existentiel]]:
$$\lnot (\exists  \in T \ | \ P(x)) \Leftrightarrow (\forall  \in T \ | \ \lnot P(x))$$

## Propriété Ensembliste
----
Par définition:
$$(S \cap T)^c = S^c \cup T^c$$
$$(S \cup T)^c = S^c \cap T^c$$
## Related Subjects
----
#### Links
----
- [[Opérateur booléens]]
- [[Opérateur Ensembliste]]
#### flashcard 
----
- Qu'elle est la [[Lois de Morgan]] booléenne ?:: $\lnot \ (p \land q) \Leftrightarrow \lnot \ p \lor \lnot \ q \qquad \text{ou} \qquad \lnot \ (p \lor q) \Leftrightarrow \lnot \ p \land \lnot \ q$
<!--SR:!2024-04-15,44,250-->
- Qu'elle est la [[Lois de Morgan]] du Quantificateur ?::
<!--SR:!2024-03-03,1,220-->
$\lnot (\forall  \in T \ | \ P(x)) \Leftrightarrow (\exists  \in T \ | \ \lnot P(x))\qquad \text{ou} \qquad \lnot (\exists  \in T \ | \ P(x)) \Leftrightarrow (\forall  \in T \ | \ \lnot P(x))$
- Qu'elle est la [[Lois de Morgan]] de l'Ensemble ?::$(S \cap T)^c = S^c \cup T^c \qquad \text{ou} \qquad (S \cup T)^c = S^c \cap T^c$
<!--SR:!2024-03-03,1,220-->