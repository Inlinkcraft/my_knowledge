---
type: Knowledge
class: Mathématique pour informaticien
id: MAT-1919
chapiter: Chapitre-3
title: Démonstration d'un quantificateur universelle 
tags: Knowledge/MAT-1919/Chapitre-3/Démonstration_dun_quantificateur_universelle 
created: 2024-02-17 20:56
---
# Démonstration d'un quantificateur universelle 
----
Démonstration d'un expression qui contient un [[Quantificateur universelle|quantificateur universelle]]
## Procédure
----
### Étape 1
----
Définir une variable d'intéret et l'assigner à un ensemble afin de prouver le prédicat

### Étape 2
----
Construire le prédicat à l'aide de ce que nous savons comme vrai

> [!Example]
> $(\forall n \in \mathbb{N} | n^2 + n + 2 > 1)$
> $$
> \begin{array}{llr}
> 	\text{Soit} & P(x) = n^2 + n + 2 > 1 & \\
> 	\text{Soit} & n \in \mathbb{N} & \langle \text{Démontrons} P(x) \rangle \\
> 	\text{On Sait que} & n \ge 0 & \langle \text{car} \ n \in \mathbb{N} \rangle \\
> 	\text{On Sait que} & n^2 \ge 0 & \langle \text{car} \ n \in \mathbb{N} \text{, Arithmétique} \rangle \\
> 	\text{On Sait que} & 2 \ge 1 & \langle \text{prop. Arithmétique} \rangle \\
> 	\text{On Sait que} & n^2 + n \ge 0 + 0 & \langle \text{Arithmétique} \rangle \\
> 	\text{On Sait que} & n^2 + n + 2 \ge 0 + 1 & \langle \text{Arithmétique} \rangle \\
> 	\text{Donc} & n^2 + n + 2 \ge 1 & \langle \text{Arithmétique} \rangle \\
> \end{array}
> $$
> **C.Q.F.D**

## Related Subjects
----
#### flashcard 
----
- Que doit-on absolument faire aux début d'une [[Démonstration d'un quantificateur universelle]] ?:: Posé le prédicat et une variable significative
<!--SR:!2024-03-06,4,270-->