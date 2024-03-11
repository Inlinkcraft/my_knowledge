---
type: Knowledge
class: Mathématique pour informaticien
id: MAT-1919
chapiter: Chapitre-1
title: Conjonction
tags: Knowledge/MAT-1919/Chapitre-1/Conjonction
created: 2024-01-22 21:51
sr-due: 2024-02-21
sr-interval: 23
sr-ease: 268
---
# Conjonction ($\land$) : ET
----
## Définition
----
Les deux valeur de la conjonction doivent être vrai pour que le résultat soit vrai
$$
\begin{array}{cc|c|c}
	p & q & p \land q & q \land p \\
\hline
V & V & V & V\\
V & F & F & F\\
F & V & F & F\\
F & F & F & F\\
\end{array}
$$
> [!info] Similarité arithmétique
> $$1 \times 1 = 1$$
> $$1 \times 0 = 0$$

## Propriété (1.1.6)
----
### 1.1.6-A : Élément neutre
----
$$p \land Vrai \Leftrightarrow p$$
### 1.1.6-B : Élément absorbant
----
$$p \land Faux \Leftrightarrow Faux$$
### 1.1.6-C : Idempotence
----
$$p \land p \Leftrightarrow p$$

### 1.1.6-D : Commutativité
----
$$p \land q \Leftrightarrow q \land p $$

### 1.1.6-E : Associativity
----
$$(p \land q) \land r \Leftrightarrow p \land (q \land r)$$

### 1.1.6-F : Distributivité
----
$$(p \lor q) \land r \Leftrightarrow (p \land r) \lor (q \land r)$$


## Related Subjects
----
#### Links
----
- [[Opérateur booléens]]
#### flashcard 
----
- Qu'elle est le symbole de la conjonction ?::$\land$
<!--SR:!2024-04-18,47,250-->
- Qu'elle est la table de la conjonction ?::$\begin{array}{cc|c|c} p & q & p \land q & q \land p \\ \hline V & V & V & V\\ V & F & F & F\\ F & V & F & F\\ F & F & F & F\\ \end{array}$
<!--SR:!2024-04-02,31,230-->
- Qu'elle est l'élément neutre de la conjonction ?::$p \land Vrai \Leftrightarrow p$
<!--SR:!2024-03-19,17,267-->
- Qu'elle est l'élément absorbant de le conjonction ?::$p \land Faux \Leftrightarrow Faux$
<!--SR:!2024-03-20,18,247-->
- Qu'elle est l'idempodance de la conjonction ?::$p \land p \Leftrightarrow p$
<!--SR:!2024-03-13,11,247-->
- Qu'elle est la commutativité de la conjonction ?::$p \land q \Leftrightarrow q \land p$
<!--SR:!2024-03-15,13,227-->
- Qu'elle est l'assosiabilité de la conjonction ?::$(p \land q) \land r \Leftrightarrow p \land (q \land r)$
<!--SR:!2024-03-08,6,207-->
- Qu'elle est la distributivité de la conjonction ?::$(p \lor q) \land r \Leftrightarrow (p \land r) \lor (q \land r)$
<!--SR:!2024-03-04,2,187-->