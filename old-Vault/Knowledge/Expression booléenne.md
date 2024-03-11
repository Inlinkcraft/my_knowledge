---
type: Knowledge
class: Mathématique pour informaticien
id: MAT-1919
chapiter: Chapitre-1
title: Expression booléenne 
tags: Knowledge/MAT-1919/Chapitre-1/Expression_booléenne 
created: 2024-01-15 13:52
sr-due: 2024-02-19
sr-interval: 21
sr-ease: 250
---
# Expression booléenne 
----
Question ou liaison de plusieurs questions qui se répondent par une [[Valeur booléenne|valeur booléenne]].

> [!Note]
> Une expression booléenne accorde aucune importance au sens.

## Expression booléenne atomique
---
Une expression booléenne atomique est la forme la plus simple d'une expression booléenne. Elle ne contient qu'une seule et unique expression.

> [!Exemple]
> `Cinq est un nombre impair` : ✔
> `J'habite à Chicoutimi (et) la capital de ma province est la ville de quebec` : ❌
> Dans le deuxième cas l'expression est formé de deux expression booléenne atomique et d'un [[#Combinaison d'expression atomique|agent de liaison]].
### Combinaison d'expression atomique
----
**ET** : `J'habite a Chicoutimi (et) la capital de ma province est la ville de Québec`
Le "et" va venir lier les deux expression de façons a ce que les deux expression soit vrai pour que l'énoncé soit vrai

**Ou** : `Mon prénon contient la lettre "P" (ou) Mon prénon contient la lettre "S"`
Le "ou" va venir lier les deux expression de façons a ce que une des deux expressions doit vrai pour que l'énoncé soit vrai

**Si-Alors** : `(Si) j'habite a Chicoutimi, (alors) la capital de ma province Québec`
Le "si-alors" va venir lier les deux expression de façons a ce que la première expression doit être vrai pour que la deuxième soit vrai

## Dépendance aux contexte
----
Une expression booléenne qui est dépendante sur le context auras une variable libre présente dans sont expression:

> [!Exemple]
> - $x \le 7$
> - La Capitale de ma province est la ville de Québec

## Related Subjects
----
#### flashcard 
----
- Qu'est ce qu'un expression booléenne ?:: Question ou liaison de plusieurs questions qui se répondent par une [[Valeur booléenne|valeur booléenne]]
<!--SR:!2024-05-21,80,270-->
-  Une expression booléenne accorde-t-elle une importance au sens ?::Non
<!--SR:!2024-05-12,71,270-->
- Qu'est ce qu'une expression booléenne atomique ?::Une expression booléenne atomique est la forme la plus simple d'une expression booléenne. Elle ne contient qu'une seule et unique expression.
<!--SR:!2024-04-17,46,270-->
- Est ce que `Cinq est un nombre impair` est une expression booléenne atomique ?::Oui
<!--SR:!2024-04-24,53,270-->
- Est-ce que `J'habite à Chicoutimi et la capital de ma province est la ville de quebec` est une expression booléenne atomique ?::Non
<!--SR:!2024-05-20,79,270-->
- Qu'est ce que **ET** ?::Le "et" va venir lier les deux expression de façons a ce que les deux expression soit vrai pour que l'énoncé soit vrai
<!--SR:!2024-05-24,83,270-->
- Qu'est ce que **Ou** ?::Le "ou" va venir lier les deux expression de façons a ce que une des deux expressions doit vrai pour que l'énoncé soit vrai
<!--SR:!2024-05-08,67,270-->
- Qu'est ce que **Si-Alors** ?::Le "si-alors" va venir lier les deux expression de façons a ce que la première expression doit être vrai pour que la deuxième soit vrai
<!--SR:!2024-04-12,41,250-->
- Qu'est ce qu'est la dépendance aux contexte pour une expression booléenne ?:: Une expression booléenne qui est dépendante sur le context auras une variable libre présente dans sont expression:
<!--SR:!2024-03-29,27,230-->