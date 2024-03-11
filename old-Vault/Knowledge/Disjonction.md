---
type: Knowledge
class: Mathématique pour informaticien
id: MAT-1919
chapiter: Chapitre-1
title: Disjonction
tags: Knowledge/MAT-1919/Chapitre-1/Disjonction
created: 2024-01-22 21:52
sr-due: 2024-02-22
sr-interval: 24
sr-ease: 269
---
# Disjonction ($\lor$) : OU
----
## Definition
----
Les deux valeur de la disjonction doit avoir une valeur vrai pour que le résultat soit vrai
$$
\begin{array}{cc|c|c}
	p & q & p \lor q & q \lor p\\
\hline
V & V & V & V\\
V & F & V & V\\
F & V & V & V\\
F & F & F & F\\
\end{array}
$$
> [!info] Similarité arithmétique
> $$1 + 1 = 2$$
> $$1 + 0 = 1$$
> $$0 + 0 = 0$$

## Propriété (1.1.7)
----
### 1.1.7-A : Élément neutre
----
$$p \lor Faux \Leftrightarrow p$$
### 1.1.7-B : Élément absorbant
----
$$p \lor Vrai \Leftrightarrow Vrai$$
### 1.1.7-C : Idempotence
----
$$p \lor p \Leftrightarrow p$$

### 1.1.7-D : Commutativité
----
$$p \lor q \Leftrightarrow q \lor p $$

### 1.1.7-E : Associativity
----
$$(p \lor q) \lor r \Leftrightarrow p \lor (q \lor r)$$

### 1.1.7-F : Distributivité
----
$$(p \land q) \lor r \Leftrightarrow (p \lor r) \land (q \lor r)$$



## Related Subjects
----
#### Links
----
- [[Opérateur booléens]]
#### flashcard 
----
- Qu'elle est le symbole de la disjonction ?::$\lor$
<!--SR:!2024-04-19,48,250-->
- Qu'elle est la table de la disjonction ?::$\begin{array}{cc|c|c} p & q & p \lor q & q \lor p\\ \hline V & V & V & V\\ V & F & V & V\\ F & V & V & V\\ F & F & F & F\\ \end{array}$
<!--SR:!2024-06-04,94,270-->
- Qu'elle est l'élément neutre de la disjonction ?::$p \lor Faux \Leftrightarrow p$
<!--SR:!2024-03-05,3,229-->
- Qu'elle est l'élément absorbant de le disjonction ?::$p \lor Vrai \Leftrightarrow Vrai$
<!--SR:!2024-03-18,16,269-->
- Qu'elle est l'idempodance de la disjonction ?::$p \lor p \Leftrightarrow p$
<!--SR:!2024-03-17,15,269-->
- Qu'elle est la commutativité de la disjonction ?::$p \lor q \Leftrightarrow q \lor p$
<!--SR:!2024-03-05,3,229-->
- Qu'elle est l'assosiabilité de la disjonction ?::$(p \lor q) \lor r \Leftrightarrow p \lor (q \lor r)$
<!--SR:!2024-03-14,12,249-->
- Qu'elle est la distributivité de la disjonction ?::$(p \land q) \lor r \Leftrightarrow (p \lor r) \land (q \lor r)$
<!--SR:!2024-03-08,6,209-->