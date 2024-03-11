---
type: Knowledge
class: Mathématique pour informaticien
id: MAT-1919
chapiter: Chapitre-2
title: Ensemble
tags: Knowledge/MAT-1919/Chapitre-2/Ensemble
created: 2024-01-24 19:36
sr-due: 2024-02-10
sr-interval: 12
sr-ease: 250
---
# Ensemble
----
Un ensemble est une structure de donnée.

## Définition
----
### Définition par extension
----
$$A := \{1, 2, 3, 4, 5\}$$

### Définition par comprehension
----
$$S := \{ f(x) | R(x) \}$$
$f(x)$ : décrit les élément de l'ensemble
$R(x)$ : restreint le contenue de S

> [!Info]
> \* : Exclut le 0 d'un ensemble numérique

## Notation abrégé d'un ensemble
----
Un ensemble qui est définie par compréhension peut être définie de façons abrégé. Pour ce faire on établit un type a "$x$":
$$\{x \in \mathbb{T} \ | \ \text{condition}\} \to A:=\{x \in \mathbb{N} \ | \ 1 \le x \le 5\}$$

## L'ensemble vide
----
L'esemble vide est un ensemble qui ne contiens aucun élément celui-ci se note : $\emptyset$

> [!Attention]
> $$\{\emptyset\} \not = \emptyset \qquad \text{et} \qquad \emptyset \in \{\emptyset\} \implies \{\{\}\}$$

## Cardinalité d'un ensemble
----
La cordialité d'un ensemble est simplement le nombre d'élément présent dans un ensemble et est obtenue en entourant un ensemble de | E |

**Exemple**
$$|\mathbb{B}| = 2 \qquad \text {car} \qquad \mathbb{B} = \{V, F\}$$

> [!Note]
> $$|\emptyset| = 0$$
> $$|\{\emptyset\}| = 1$$

## Opérateur d'appartenance ($\in$)
----
Permet de spécifier qu'une variable, numéro ou autre appartient a un ensemble
$$5 \in \mathbb{N} \qquad \text{vs} \qquad -5 \not \in \mathbb{N}$$

## Égalité entre ensemble
----
Un ensemble est équivalent a un autre ensemble si le deuxième ensemble si contient aux moins un de tous les élément du premier ensemble
$$S=T := (\forall e \ | \ e \in S \Leftrightarrow e \in T)$$

## Related Subjects
----
#### flashcard 
----
- Qu'est ce qu'un ensemble ?::Un ensemble est une structure de donnée.
<!--SR:!2024-03-16,14,230-->
- Qu'est ce que la définition par extension ?::$E := \{\}$
<!--SR:!2024-03-06,4,230-->
- Qu'est ce que la définition par compréhension ?::$S := \{ f(x) | R(x) \}$
<!--SR:!2024-03-06,4,230-->
- Qu'elle est le symbole d'appartenance ?::$\in$
<!--SR:!2024-03-25,23,250-->
- A quoi sert le symbole d'appartenance ?::Permet de spécifier qu'une variable, numéro ou autre appartient a un ensemble
<!--SR:!2024-03-19,17,250-->
- Qu'elle est la définition textuelle de l'égalité d'ensemble ?::Un ensemble est équivalent a un autre ensemble si le deuxième ensemble si contient aux moins un de tous les élément du premier ensemble
<!--SR:!2024-03-20,18,250-->
- Qu'elle est la définition mathématique de l'égalité d'ensemble ?::$S=T := (\forall e \ | \ e \in S \Leftrightarrow e \in T)$
<!--SR:!2024-03-07,5,230-->
- Qu'elle est la notation abrégé d'un ensemble ?::$\{x \in \mathbb{T} \ | \ \text{condition}\}$
<!--SR:!2024-03-08,6,230-->
- Qu'elle est le symbole d'un ensemble vide ?::$\emptyset$
<!--SR:!2024-03-31,29,270-->
- Est-ce que $\{\emptyset\} = \emptyset$ ?::Non
<!--SR:!2024-04-08,37,270-->