---
type: Knowledge
class: Ordinateur, structure et application
id: GIF-1001
chapiter: Chapitre-1
title: IEEE754
tags: Knowledge/GIF-1001/Chapitre-1/IEEE754
created: 2024-01-29 14:49
sr-due: 2024-02-08
sr-interval: 6
sr-ease: 248
---
# IEEE754
----
Protocole pour représenté un nombre décimal rationnelle en [[Binaire|binaire]] avec une bonne précision 

## IEEE754 (32bits) $\to$ Decimal
----
**Étape-1:**
Couper le chiffre binaire afin d'avoir 1 bit de signe suivis de 8 bit qui représenterons l'exposant et le reste qui sera la mantisse

**Étape 2:**
Convertir l'exposant en chiffre décimal

**Étape 3:**
Convertir la mantisse en chiffre décimal

**Étape 4:**
Convertir les valeur sous la forme de l'équation mathématique suivante et calculer
$$1.\text{mantisse} \times 2^{(exposant - 127)}$$
### Exemple
----
Convertir $\text{0x41A0000}$ en décimal
$$\text{0x41A0000} \to 01000001000110100000000000000000$$
$$0 \quad 10000010 \quad 00110100000000000000000$$
$$\text{0b0} \to +$$
$$\text{0b10000010} \to 130 - 127 \to 3$$
$$\text{.00110100000000000000000} \to 0.203125$$
$$+1.203125 \times 2^3 = 9.625$$

## Décimal $\to$ IEEE754 (32bits)
****
**Étape-1:**
Convertir le chiffre en binaire selon un chiffre non-signé

**Étape 2:**
Déplacer la virgule afin d'obtenir un seul "1" a gauche de la virgule et compter le nombre de déplacement

**Étape 3:**
additionner 127 au nombre de déplacement de la virgule

**Étape 4:**
Convertir le signe, exposant et mantisse en binaire

### Exemple
----
Convertir 12.5 sur 32bit IEEE754:Hex
$$12 \to 1100$$
$$0.5 \to 100 \dots$$
$$1100.1000\dots \to 1.1001000\dots \to \text{l'exposant est } 3 + 127 = 130 \to 10000010$$
Donc
$$0 \quad 10000010 \quad 10010000000000000000000$$
$$\text{0x41480000}$$
## Related Subjects
----
#### flashcard 
----
- Qu'est ce que IEEE754 ?::Protocole pour représenté un nombre décimal rationnelle en [[Binaire|binaire]] avec une bonne précision
<!--SR:!2024-02-06,4,248-->
- Comment convertir de décimal à IEEE754(32bits) ?::**Étape-1:** Convertir le chiffre en binaire selon un chiffre non-signé **Étape 2:** Déplacer la virgule afin d'obtenir un seul "1" a gauche de la virgule et compter le nombre de déplacement **Étape 3:** additionner 127 au nombre de déplacement de la virgule **Étape 4:** Convertir le signe, exposant et mantisse en binaire
<!--SR:!2024-02-03,1,228-->
- Comment convertir de IEEE754(32bits) en décimal ?::**Étape-1:** Couper le chiffre binaire afin d'avoir 1 bit de signe suivis de 8 bit qui représenterons l'exposant et le reste qui sera la mantisse **Étape 2:** Convertir l'exposant en chiffre décimal **Étape 3:** Convertir la mantisse en chiffre décimal **Étape 4:** Convertir les valeur sous la forme de l'équation mathématique suivante et calculer
<!--SR:!2024-02-06,4,248-->
- Comment se nomme les chiffre qui suivent la virgule ?::Mantisse
<!--SR:!2024-02-10,8,268-->