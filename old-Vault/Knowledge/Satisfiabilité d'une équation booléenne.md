---
type: Knowledge
class: Mathématique pour informaticien
id: MAT-1919
chapiter: Chapitre-1
title: Satisfiabilité d'une équation booléenne
tags: Knowledge/MAT-1919/Chapitre-1/Satisfiabilité_dune_équation_booléenne
created: 2024-01-24 19:21
sr-due: 2024-02-09
sr-interval: 11
sr-ease: 249
---
# Satisfiabilité d'une équation booléenne
----
Champ encore très actif des mathématiques booléenne car énormément de problème si réduise

## Définition
---
Si pour une seul ou plusieurs valeur de $p, q, r, \dots$ l'[[Expression booléenne|expression booléenne]] est vrai, alors l'[[Expression booléenne|expression booléenne]] est dite satisfaite. Par contre si pour toute valeurs de  $p, q, r, \dots$ l'[[Expression booléenne|expression booléenne]] est fausse, alors l'[[Expression booléenne|expression booléenne]] est dite insatisfaite.

## Forme normal conjonctive (CNF)
----
### Literal
----
Une variable booléenne ou la négation de celle-ci

### Clause
----
[[Disjonction]] de littéraux

### CNF
----
[[Conjonction]] de clause
$$\Phi_c := (x_1 \lor x_2) \land (\lnot x_1 \lor x_2) \land \dots$$
> [!info]
> Il suffit qu'une seul clause soit fausse pour que l'expression soit insatifiable

## Related Subjects
----
#### flashcard 
----
- Qu'est ce que la satisfiabilités d'une équation booléenne ?::Si pour une seul ou plusieurs valeur de $p, q, r, \dots$ l'[[Expression booléenne|expression booléenne]] est vrai, alors l'[[Expression booléenne|expression booléenne]] est dite satisfaite. Par contre si pour toute valeurs de  $p, q, r, \dots$ l'[[Expression booléenne|expression booléenne]] est fausse, alors l'[[Expression booléenne|expression booléenne]] est dite insatisfaite.
<!--SR:!2024-03-05,3,229-->
- Qu'est ce qu'un literal ?::Une variable booléenne ou la négation de celle-ci
<!--SR:!2024-03-14,12,249-->
- Qu'est ce qu'une clause ?::[[Disjonction]] de littéraux
<!--SR:!2024-03-05,3,229-->
- Qu'est ce que la forme normal conjonctive (CNF) ?::[[Conjonction]] de clause
<!--SR:!2024-03-06,4,229-->
- Qu'elle est la propriété des CNF ?::Il suffit qu'une seul clause soit fausse pour que l'expression soit insatifiable
<!--SR:!2024-03-15,13,249-->