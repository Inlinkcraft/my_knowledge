---
type: Knowledge
class: Mathématique pour informaticien
id: MAT-1919
chapiter: Chapitre-3
title: Démonstration par cas 
tags: Knowledge/MAT-1919/Chapitre-3/Démonstration_par_cas 
created: 2024-02-19 16:00
---
# Démonstration par cas 
----
Démonstration par cas est une démonstration qui divise en plusieurs sous groupe le prédicat afin de les démontré individuellement souvent utilisé lorsque le prédicat contient $\land$.

## Procédure
---
Le prédicat est séparer afin de couvrir l'**entièreté** des valeur possible.

> [!Example]
> $\text{Cas 1: } x \mod 3 = 1$
> $\text{Cas 2: } \lnot(x \mod 3 = 1)$
> ou encore :
> $\text{Cas 1: } x^2 - 3x < 13$
> $\text{Cas 2: } x^2 - 3x \ge 13$

Les cas doivent être affiché clairement et l'utilisation d'indentation peut aider à la lecture de la démonstration :

> [!Example]
> $\lnot(\exists m \in \mathbb{N} | m > m^2)$
>
> $$
> \begin{array}{llr}
> 	\text{Par la lois de De Morgan} & (\forall m \in \mathbb{N} | \lnot(m > m^2)) & \\
> 	\text{Soit} & m \in \mathbb{N} & \langle \text{On veut montrer} m \le m^2 \rangle \\
> 	\text{Distinguons deux cas :} & & \\
> 	\textbf{    Cas 1:} & m = 0 & \\
> 	\text{        On a bien} & m \le m^2, \text{ puisque } 0 \le 0^2 & \langle \text{Cas 1 démontré}\rangle \\
> 	\textbf{    Cas 2:} & m \in \mathbb{N}^* & \\
> 	\text{        Alors on a} & m \ge 1 & \langle \text{Par la définition de} \mathbb{N}^* \rangle \\
> 	\text{        Donc} & m \times m \ge 1 \times m & \langle \text{Car } m > 0 \rangle \\
> 	\text{        Ce qui équivalent à} & m \ge m^2 & \langle \text{Cas 2 démontré}\rangle \\
> 	\text{Puisque } & \mathbb{N}^* \cup \{0\} \mathbb{N} = & \\
> \end{array}
> $$
> **C.Q.F.D**

De plus:
> [!Note]
> **Cas de $\land$**
> Les deux cas doivent vrai soit $P$ et $Q$ doivent être démontré
> **Cas de $\lor$**
> Cas 1 $P$ est vrai, Cas 2 $P$ est faut et on veux montré que $Q$ est vrai

## Related Subjects
----
#### flashcard 
----
- Qu'elle est la seul condition d'une démonstration pas cas ?::Le prédicat est séparer afin de couvrir l'**entièreté** des valeur possible.
<!--SR:!2024-03-05,3,250-->
- Comment démontré un prédicat qui contient un $\land$ ?::Les deux cas doivent vrai soit $P$ et $Q$ doivent être démontré
<!--SR:!2024-03-05,3,250-->
- Comment démontré un prédicat qui contient un $\lor$ ?::Cas 1 $P$ est vrai, Cas 2 $P$ est faut et on veux montré que $Q$ est vrai
<!--SR:!2024-03-05,3,250-->