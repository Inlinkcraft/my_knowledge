---
type: Knowledge
class: Mathématique pour informaticien
id: MAT-1919
chapiter: Chapitre-1
title: Succession d'équivalences
tags: Knowledge/MAT-1919/Chapitre-1/Succession_déquivalences
created: 2024-01-23 22:36
sr-due: 2024-02-06
sr-interval: 8
sr-ease: 230
---
# Succession d'équivalences
----
## Méthodologie de la démonstration
----
### Entête
----
- Définir les variable utilisé dans le problème
- Définir l'expression que nous cherchons a démontré
- Nommer la méthode utilisé
### Développement
----
$$
\begin{align}
	& \text{Équation initial} & \\ \\
	& \Leftrightarrow \langle \text{Def/Prop x.x - Nom de la proposition} \ [\text{Substitution ex:} \ p:= \lnot p]\rangle \\
	& \qquad \text{Nouvelle équation} \\ \\
	& \Leftrightarrow \langle \text{Def/Prop x.x - Nom de la proposition} \ [\text{Substitution ex:} \ p:= \lnot p]\rangle \\
	& \qquad \text{Nouvelle équation} \\ \\
	& \Leftrightarrow \langle \text{Def/Prop x.x - Nom de la proposition} \ [\text{Substitution ex:} \ p:= \lnot p]\rangle \\
	& \qquad \text{Nouvelle équation} \\ \\
	& \qquad\vdots \\ \\
	& \text{Équation final} & \\ \\
\end{align}
$$
### Conclusion
---
- Conclusion version descriptive écrite aux long énonçant le résultat
- Et/Ou : **C.Q.F.D** ou $\square$

## Règle de substitution
----
Chaque bloc d'une [[Expression booléenne|expression booléenne]] peut être substituer dans la proposition ou définition:
$[p := \lnot p]$ dans $\lnot p \lor q$ nous permet d'appliquer la [[Disjonction#1.1.7-D Commutativité|sa commutativité]]
$$\lnot p \lor q \Leftrightarrow q \lor \lnot p$$

## Règle d'équivalence
----
Si un bloc d'une [[Expression booléenne|expression booléenne]] est remplaçable par un bloc équivalent il est possible de le faire:
$$q \lor \lnot p \Leftrightarrow \lnot(\lnot q) \lor p$$
> [!Info]
> Le reste de l'expression se doit de resté fixe

## Related Subjects
----
#### Links
----
- [[Opérateur booléens]]
#### flashcard 
----
- Qu'elle sont les 3 aspect d'une entête dans la démonstration booléenne ?::Définir les variable utilisé dans le problème, Définir l'expression que nous cherchons a démontré, Nommer la méthode utilisé
<!--SR:!2024-03-04,2,190-->
- Quoi devons nous mettre avant chaque étape d'une succession d'équivalence ?::Le nom ou le numéro de la proposition ou définition utilisé ainsi que les substitution utilisé
<!--SR:!2024-03-05,3,210-->
- Que doit-t-on mettre a la fin de chaque succession d'équivalence ?::Une description du résultât, **CQFD** ou $\square$
<!--SR:!2024-03-14,12,230-->
- Qu'elle est la règle de substitution ?::Chaque bloc d'une [[Expression booléenne|expression booléenne]] peut être substituer par une variable booléenne afin d'appliquer différente définition ou proposition.
<!--SR:!2024-03-06,4,190-->
- Qu'est ce que la règle d'équivalence  ?::Si un bloc d'une [[Expression booléenne|expression booléenne]] est remplaçable par un bloc équivalent il est possible de le faire.
<!--SR:!2024-03-03,1,170-->