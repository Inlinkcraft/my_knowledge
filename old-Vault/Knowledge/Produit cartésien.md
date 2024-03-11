---
type: Knowledge
class: Mathématique pour informaticien
id: MAT-1919
chapiter: Chapitre-4
title: Produit cartésien
tags: Knowledge/MAT-1919/Chapitre-4/Produit_cartésien 
created: 2024-02-19 17:28
---
# Produit cartésien 
----
Le produit cartésien met en relation deux [[Ensemble|ensemble]].

## Définition
----
La définition du produit cartésien est:
$$S \times T := \{\langle a, b\rangle | a \in S \land b \in T\}$$
> [!Note]
> Le produit cartésien n'est pas une opération symétrique

## Propriété
----
### 1.4.3-a
----
$$S \times T = T \times S \qquad \Leftrightarrow \qquad S=\emptyset \lor T = \emptyset \lor S = T$$
### 1.4.3-b : Distributivité sur l'union
----
$$S \times (T \cup U) = (S \times T) \cup (S \times U)$$
### 1.4.3-c : Distributivité sur l'intersection
----
$$S \times (T \cap U) = (S \times T) \cap (S \times U)$$
### 1.4.3-d : Distributivité sur la différence
----
$$S \times (T \backslash U) = (S \times T) \backslash (S \times U)$$
### 1.4.3-e
----
$$S \subseteq U \land T \subseteq V \Rightarrow S \times T \subseteq S \times U$$
### 1.4.3-f
----
$$S \times T \subseteq S \times U \Rightarrow S = \emptyset \lor T \subseteq U$$
### 1.4.3-g
----
$$(S \cap T) \times (U \cap V) = (S \times U) \cap (T \times V)$$
### 1.4.3-h
----
$$|S \times T| = |S| \cdot |T| \qquad \text{Si S et T sont des ensemble fini} $$
## Related Subjects
----
#### flashcard 
----
- Que fait le produit cartésien ?::Le produit cartésien met en relation deux [[Ensemble|ensemble]].
<!--SR:!2024-03-03,1,230-->
- Qu'elle est la définition du produit cartésien ?::$S \times T := \{\langle a, b\rangle | a \in S \land b \in T\}$
<!--SR:!2024-03-03,1,230-->
- Le produit cartésien est une opération symétrique ?::Faux
<!--SR:!2024-03-03,1,230-->
- Qu'elle est la propriété 1.4.3-a ?::$S \times T = T \times S \qquad \Leftrightarrow \qquad S=\emptyset \lor T = \emptyset \lor S = T$
<!--SR:!2024-03-05,3,250-->
- Qu'elle est la propriété 1.4.3-b : Distributivité sur l'union ?::$S \times (T \cup U) = (S \times T) \cup (S \times U)$
<!--SR:!2024-03-05,3,250-->
- Qu'elle est la propriété 1.4.3-c : Distributivité sur l'intersection ?::$S \times (T \cap U) = (S \times T) \cap (S \times U)$
<!--SR:!2024-03-05,3,250-->
- Qu'elle est la propriété 1.4.3-d : Distributivité sur la différence ?::$S \times (T \backslash U) = (S \times T) \backslash (S \times U)$
<!--SR:!2024-03-03,1,230-->
- Qu'elle est la propriété 1.4.3-e ?::$S \subseteq U \land T \subseteq V \Rightarrow S \times T \subseteq S \times U$
<!--SR:!2024-03-03,1,230-->
- Qu'elle est la propriété 1.4.3-f ?::$S \times T \subseteq S \times U \Rightarrow S = \emptyset \lor T \subseteq U$
<!--SR:!2024-03-05,3,250-->
- Qu'elle est la propriété 1.4.3-g ?::$(S \cap T) \times (U \cap V) = (S \times U) \cap (T \times V)$
<!--SR:!2024-03-05,3,250-->
- Qu'elle est la propriété 1.4.3-h ?::$|S \times T| = |S| \cdot |T| \qquad \text{Si S et T sont des ensemble fini}$
<!--SR:!2024-03-03,1,230-->