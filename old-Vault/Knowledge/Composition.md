---
type: Knowledge
class: Mathématique pour informaticien
id: MAT-1919
chapiter: Chapitre-4
title: Composition 
tags: Knowledge/MAT-1919/Chapitre-4/Composition 
created: 2024-02-26 15:09
---
# Composition 
----
La composition est un opérateur pour les [[Relations|relations]].

## Définition $\circ$
----
La composition met en "Lie" deux ou plus [[Relations|relations]] en elle
$$\mathcal{R} \circ \mathcal{L} := \{\langle a, c\rangle \in S \times U |(\exists b \in T |\langle a , b \rangle \in \mathcal{R} \land \langle b, c \rangle \in \mathcal{L})\}$$

## Propriété
----
### 1.4.8-a : Élément neutre
----
$$I_S \circ \mathcal{R} = \mathcal{R} \circ I_T = \mathcal{R}$$
### 1.4.8-b : Élément absorbant
----
$$\emptyset \circ \mathcal{R} = \mathcal{R} \circ \emptyset = \emptyset$$
### 1.4.8-c : Associativité
----
$$(\mathcal{R} \circ \mathcal{R}_1) \circ \mathcal{L} = \mathcal{R} \circ (\mathcal{R}_1 \circ \mathcal{L})$$
### 1.4.8-d : Monotonie
----
$$\mathcal{R} \subseteq \mathcal{R}_1 \Rightarrow \mathcal{R} \circ \mathcal{L} \subseteq \mathcal{R}_1 \circ \mathcal{L}$$
### 1.4.18-a: Composition total
----
$$\mathcal{R} \text{ et } \mathcal{L} \text{ sont totaux} \Rightarrow \mathcal{R} \circ \mathcal{L} \text{ est total}$$
### 1.4.18-b: Composition déterministes
----
$$\mathcal{R} \text{ et } \mathcal{L} \text{ sont déterministe} \Rightarrow \mathcal{R} \circ \mathcal{L} \text{ est déterministe}$$

### 1.4.18-c: Composition injectifs
----
$$\mathcal{R} \text{ et } \mathcal{L} \text{ sont injectif} \Rightarrow \mathcal{R} \circ \mathcal{L} \text{ est injectif}$$
### 1.4.18-d: Composition surjectifs
----
$$\mathcal{R} \text{ et } \mathcal{L} \text{ sont surjectif} \Rightarrow \mathcal{R} \circ \mathcal{L} \text{ est surjectif}$$

## Related Subjects
----
#### flashcard 
----
- Qu'elle est le symbole de la composition ?::$\circ$
<!--SR:!2024-03-05,3,250-->
- Qu'elle est la définition de la composition ?::$\mathcal{R} \circ \mathcal{L} := \{\langle a, c\rangle \in S \times U |(\exists b \in T |\langle a , b \rangle \in \mathcal{R} \land \langle b, c \rangle \in \mathcal{L})\}$
<!--SR:!2024-03-05,3,250-->
- Qu'est ce que l'élément neutre de la composition ?::$I_S \circ \mathcal{R} = \mathcal{R} \circ I_T = \mathcal{R}$
<!--SR:!2024-03-05,3,250-->
- Qu'est ce que l'élément absorbant de la composition ?::$\emptyset \circ \mathcal{R} = \mathcal{R} \circ \emptyset = \emptyset$
<!--SR:!2024-03-05,3,250-->
- Qu'est ce que l'associativité de la composition ?::$(\mathcal{R} \circ \mathcal{R}_1) \circ \mathcal{L} = \mathcal{R} \circ (\mathcal{R}_1 \circ \mathcal{L})$
<!--SR:!2024-03-05,3,250-->
- Qu'est ce que la monotonie de la composition ?::$\mathcal{R} \subseteq \mathcal{R}_1 \Rightarrow \mathcal{R} \circ \mathcal{L} \subseteq \mathcal{R}_1 \circ \mathcal{L}$
<!--SR:!2024-03-05,3,250-->
- Qu'est ce que la composition total ?::$\mathcal{R} \text{ et } \mathcal{L} \text{ sont totaux} \Rightarrow \mathcal{R} \circ \mathcal{L} \text{ est total}$
<!--SR:!2024-03-05,3,250-->
- Qu'est ce que la composition déterministes ?::$\mathcal{R} \text{ et } \mathcal{L} \text{ sont déterministe} \Rightarrow \mathcal{R} \circ \mathcal{L} \text{ est déterministe}$
<!--SR:!2024-03-05,3,250-->
- Qu'est ce que la composition injectives ?::$\mathcal{R} \text{ et } \mathcal{L} \text{ sont injectif} \Rightarrow \mathcal{R} \circ \mathcal{L} \text{ est injectif}$
<!--SR:!2024-03-05,3,250-->
- Qu'est ce que la composition surjective ?::$\mathcal{R} \text{ et } \mathcal{L} \text{ sont surjectif} \Rightarrow \mathcal{R} \circ \mathcal{L} \text{ est surjectif}$
<!--SR:!2024-03-05,3,250-->