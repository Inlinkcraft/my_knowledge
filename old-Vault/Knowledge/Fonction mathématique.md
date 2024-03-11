---
type: Knowledge
class: Mathématique pour informaticien
id: MAT-1919
chapiter: Chapitre-4
title: Fonction mathématique 
tags: Knowledge/MAT-1919/Chapitre-4/Fonction_mathématique 
created: 2024-02-26 16:41
---
# Fonction mathématique 
----
Une fonction est une [[Relations|relation]] est [[Famille de relation#1.4.16-a Totalité|total]] et [[Famille de relation#1.4.16-c Déterministe|déterministe]].

## Notation
----
Une fonction peut être noté de plusieurs façons soit:
### Classique
----
$$f(x) = y := \langle x, y \rangle \in f$$
> [!note]
> Ici $f$ est une [[Relations|relation]]

### Règle de correspondance
----
$$
\begin{array}{cccc}
	f: & \mathbb{R} & \rightarrow & \mathbb{R} \\
	   & x & \mapsto & x^2 \\
\end{array} \quad := \quad f = \{\langle x, y \rangle \in \mathbb{R}^2 | y= x^2 \}
$$
> [!Note]
> Par la règle de correspondance il est possible d'assumé directement que la relation $f$ est [[Famille de relation#1.4.16-a Totalité|total]] et [[Famille de relation#1.4.16-c Déterministe|déterministe]]


## Propriété
----
### 1.4.19-a : Définition équivalente d'une fonction surjective
----
$$(\forall b \in T | (\exists a \in S | a f b))$$
### 1.4.19-b : Définition équivalente d'une fonction surjective
----
$$(\forall b \in T | (\exists a \in S | f(a)=b))$$

### 1.4.20-a: Définitions équivalente d'une fonction injective
----
$$(\forall a \in S, a' \in S, b \in T | a f b \land a' f b \Rightarrow a = a')$$
### 1.4.20-b: Définitions équivalente d'une fonction injective
----
$$(\forall a \in S, a' \in S | f(a) = f(a') \Rightarrow a = a')$$
### 1.4.20-c: Définitions équivalente d'une fonction injective
----
$$(\forall a \in S, a' \in S | a \not = a' \Rightarrow f(a) \not = f(a'))$$
## Related Subjects
----
#### Links
----
- [[Fonction programmation]]
#### flashcard 
----
- Qu'elle est la définition classique d'une fonction ?::$f(x) = y := \langle x, y \rangle \in f$
<!--SR:!2024-03-05,3,250-->
- Qu'est ce que la règle de correspondance ?::$\begin{array}{cccc} f: & \mathbb{R} & \rightarrow & \mathbb{R} \\ & x & \mapsto & x^2 \\ \end{array} \quad := \quad f = \{\langle x, y \rangle \in \mathbb{R}^2 | y= x^2 \}$
<!--SR:!2024-03-05,3,250-->
- Qu'est t-il possible d'assumer si la fonction est écrite selon la règle de correspondance ?::il est possible d'assumé directement que la relation $f$ est [[Famille de relation#1.4.16-a Totalité|total]] et [[Famille de relation#1.4.16-c Déterministe|déterministe]]
<!--SR:!2024-03-05,3,250-->
- Définition équivalente d'une fonction surjective ?::$(\forall b \in T | (\exists a \in S | a f b)) \ \text{ou} \ (\forall b \in T | (\exists a \in S | f(a)=b))$
<!--SR:!2024-03-05,3,250-->
- Qu'elle est la définitions équivalente d'une fonction injective ?::$(\forall a \in S, a' \in S, b \in T | a f b \land a' f b \Rightarrow a = a')  \ \text{ou} \  (\forall a \in S, a' \in S | f(a) = f(a') \Rightarrow a = a')  \ \text{ou} \  (\forall a \in S, a' \in S | a \not = a' \Rightarrow f(a) \not = f(a'))$
<!--SR:!2024-03-05,3,250-->