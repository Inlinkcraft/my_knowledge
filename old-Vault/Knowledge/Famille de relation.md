---
type: Knowledge
class: Mathématique pour informaticien
id: MAT-1919
chapiter: Chapitre-4
title: Famille de relation 
tags: Knowledge/MAT-1919/Chapitre-4/Famille_de_relation 
created: 2024-02-26 15:50
---
# Famille de relation 
----
Regroupement de [[Relations|relations]] selon différente propriété

## Propriété
----
### 1.4.14-a: Réflexif
----
$$\mathcal{R} := (\forall a \in S | a \mathcal{R} a)$$
### 1.4.14-b: Irréflexif
----
$$\mathcal{R} := (\forall a \in S | \lnot (a \mathcal{R} a))$$
### 1.4.14-c: Symétrique
----
$$\mathcal{R} := (\forall a \in S, b \in S | a \mathcal{R} b \Rightarrow b\mathcal{R}a)$$
### 1.4.14-d: Asymétrique
----
$$\mathcal{R} := (\forall a \in S, b \in S | a \mathcal{R} b \Rightarrow \lnot(b \mathcal{R} a))$$
### 1.4.14-e: Antisymétrique
----
$$\mathcal{R} := (\forall a \in S, b \in S | a \mathcal{R} b \land b \mathcal{R} a \Rightarrow a = b)$$
### 1.4.14-f: Transitif
----
$$\mathcal{R} := (\forall a \in S, b \in S, c \in S| a\mathcal{R}b \land b \mathcal{R} c \Rightarrow a \mathcal{R} c)$$
### 1.4.16-a: Totalité
----
$$\mathcal{R} := (\forall a \in S | (\exists b \in T | a \mathcal{R} b))$$
### 1.4.16-b: Subjectivité
----
$$\mathcal{R} = (\forall b \in T | (\exists a \in S | a \mathcal{R} b))$$
### 1.4.16-c: Déterministe
----
$$\mathcal{R} := (\forall a \in S, b \in T, b' \in T | a\mathcal{R}b \land a \mathcal{R} b' \Rightarrow b = b')$$
### 1.4.16-d: Injectif
----
$$\mathcal{R} := (\forall a \in S, a' \in S, b \in T |a \mathcal{R} b \land a' \mathcal{R} b \Rightarrow a = a')$$
### 1.4.16-e: Bijectif
----
$$\mathcal{R} := \mathcal{R} \text{ est injectif et surjectif}$$

## Related Subjects
----
#### flashcard 
----
- Qu'est ce qu'une relation réflexive ?::$\mathcal{R} := (\forall a \in S | a \mathcal{R} a)$
<!--SR:!2024-03-05,3,250-->
- Qu'est ce qu'une relation irréflexive ?::$\mathcal{R} := (\forall a \in S | \lnot (a \mathcal{R} a))$
<!--SR:!2024-03-05,3,250-->
- Qu'est ce qu'une relation symétrique ?::$\mathcal{R} := (\forall a \in S, b \in S | a \mathcal{R} b \Rightarrow b\mathcal{R}a)$
<!--SR:!2024-03-05,3,250-->
- Qu'est ce qu'une relation asymétrique ?::$\mathcal{R} := (\forall a \in S, b \in S | a \mathcal{R} b \Rightarrow \lnot(b \mathcal{R} a))$
<!--SR:!2024-03-05,3,250-->
- Qu'est ce qu'une relation antisymétrique ?::$\mathcal{R} := (\forall a \in S, b \in S | a \mathcal{R} b \land b \mathcal{R} a \Rightarrow a = b)$
<!--SR:!2024-03-05,3,250-->
- Qu'est ce qu'une relation transitive ?::$\mathcal{R} := (\forall a \in S, b \in S, c \in S| a\mathcal{R}b \land b \mathcal{R} c \Rightarrow a \mathcal{R} c)$
<!--SR:!2024-03-05,3,250-->
- Qu'est ce que la totalité d'une relation ?::$\mathcal{R} := (\forall a \in S | (\exists b \in T | a \mathcal{R} b))$
<!--SR:!2024-03-05,3,250-->
- Qu'est ce que la subjectivité d'une relation ?::$\mathcal{R} = (\forall b \in T | (\exists a \in S | a \mathcal{R} b))$
<!--SR:!2024-03-05,3,250-->
- Qu'est ce qu'une relation déterministe ?::$\mathcal{R} := (\forall a \in S, b \in T, b' \in T | a\mathcal{R}b \land a \mathcal{R} b' \Rightarrow b = b')$
<!--SR:!2024-03-05,3,250-->
- Qu'est ce qu'une relation injective ?::$\mathcal{R} := (\forall a \in S, a' \in S, b \in T |a \mathcal{R} b \land a' \mathcal{R} b \Rightarrow a = a')$
<!--SR:!2024-03-05,3,250-->
- Qu'est ce qu'une relation bijective ?::$\mathcal{R} := \mathcal{R} \text{ est injectif et surjectif}$
<!--SR:!2024-03-05,3,250-->