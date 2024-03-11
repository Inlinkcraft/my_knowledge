---
type: Knowledge
class: Ordinateur, structure et application
id: GIF-1001
chapiter: Chapitre-1
title: Binaire 
tags: Knowledge/GIF-1001/Chapitre-1/Binaire 
created: 2024-01-22 20:41
sr-due: 2024-02-25
sr-interval: 27
sr-ease: 270
---
# Binaire 
----
Système numérique de base 2.

## Nomenclature
---
Le bit sera toujours préfixé de "0b" lorsque celui-ci sera écrit

## Conversion entre le binaire et le décimal
----
### Non-Signé
----
#### Binaire à décimal
----
Chaque bit est multiplier par la puissance de 2 correspondante

| Chiffre binaire | ... | 1 | 0 | 0 | 1 | 1 | 0 | 1 |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | ---- |
| Puissance | ... | $2^6$ | $2^5$ | $2^4$ | $2^3$ | $2^2$ | $2^1$ | $2^0$ |
| Valeur | ... | 64 | 32 | 16 | 8 | 4 | 2 | 1 |
| Résultat |  | 64 | 0 | 0 | 8 | 4 | 0 | 1 |
Donc 0b1001101 = 64+0+0+8+4+0+1 = 77

#### Décimal à binaire
----
Partant du bit le plus significatif descendre toute les possibilité en soustrayant l'équivalent du bit

| Puissance | ... | $2^6$ | $2^5$ | $2^4$ | $2^3$ | $2^2$ | $2^1$ | $2^0$ |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | ---- |
| Valeur | ... | 64 | 32 | 16 | 8 | 4 | 2 | 1 |
$77 \ge 64$ = vrai  : 77 - 64 = 13 : 1
$13 \ge 32$ = faux : 13                 : 0
$13 \ge 16$ = faux : 13                 : 0
$13 \ge 8$   = vrai  : 13 - 8 = 5     : 1
$5 \ge 4$     = vrai  : 5 - 4 = 1       : 1
$1 \ge 2$     = faux : 1                   : 0
$1 \ge 1$     = vrai  : 1 - 1 = 0       : 1

Donc la réponse est 0b1001101

#### Carry
----
Le carry est la situation qui survient lorsque le résultat des deux nombre additionné utilise une représentation avec un plus grand nombre de bit que ceux additionner

### Signé
----
#### Binaire à décimal (2em complément)
----
Chaque bit est multiplier par la puissance de 2 correspondante et pennant en compte que le MSB est négatif

| Chiffre binaire | ... | 1 | 0 | 0 | 1 | 1 | 0 | 1 |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | ---- |
| Puissance | ... | $-2^6$ | $2^5$ | $2^4$ | $2^3$ | $2^2$ | $2^1$ | $2^0$ |
| Valeur | ... | -64 | 32 | 16 | 8 | 4 | 2 | 1 |
| Résultat |  | -64 | 0 | 0 | 8 | 4 | 0 | 1 |
Donc 0b1001101 = -64+0+0+8+4+0+1 = -52

#### Décimal à binaire
----
Calculer le nombre binaire normalement comme pour [[#Décimal à binaire|le cas non-signer]] ensuite:
- Inversé toute les bits
- Ajouté 1

Pour calculer -5 en binaire
	5 en binaire est 0b101
	Inversé toute les bits on obtient 0b010
	On ajoute 1 on obtient 0b011 soit -5

#### Overflow
----
L'overflow est la situation qui survient lorsque le résultat des deux nombre additionné utilise une représentation avec un plus grand nombre de bit que ceux additionner donc le bit est perdu et il a overflow


## Related Subjects
----
#### flashcard 
----
- Qu'elle est la base du binaire ?::2
<!--SR:!2024-02-08,10,250-->
- Qu'elle est le préfixe utilisé pour le binaire ?::0b
<!--SR:!2024-02-06,8,250-->
- Comment convertissons un chiffre binaire non-signé en décimal ?::Chaque bit est multiplier par la puissance de 2 correspondante
<!--SR:!2024-02-08,6,210-->
- Comment convertissons un chiffre décimal en chiffre binaire non-signé ?::Partant du bit le plus significatif descendre toute les possibilité en soustrayant l'équivalent du bit
<!--SR:!2024-02-10,8,210-->
- Comment convertissons un chiffre binaire signé en décimal ?::Chaque bit est multiplier par la puissance de 2 correspondante et pennant en compte que le MSB est négatif
<!--SR:!2024-02-08,6,210-->
- Comment convertissons un chiffre décimal en chiffre binaire non-signé ?::Calculer le nombre binaire normalement comme pour [[#Décimal à binaire|le cas non-signer]] ensuite ont inversé toute les bits et on ajoute 1
<!--SR:!2024-02-11,9,210-->
- Qu'est ce qu'un carry ?::Le carry est la situation qui survient lorsque le résultat des deux nombre additionné utilise une représentation avec un plus grand nombre de bit que ceux additionner
<!--SR:!2024-02-03,5,230-->
- Qu'est ce qu'un overflow ?::L'overflow est la situation qui survient lorsque le résultat des deux nombre additionné utilise une représentation avec un plus grand nombre de bit que ceux additionner donc le bit est perdu et il a overflow
<!--SR:!2024-02-09,7,210-->