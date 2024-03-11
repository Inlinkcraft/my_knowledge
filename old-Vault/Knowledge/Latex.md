---
type: Knowledge
class: Design-1 (méthodologie)
id: GEL-1001
title: Latex 
tags: Knowledge/GEL-1001/Latex 
created: 2024-01-18 21:51
sr-due: 2024-02-18
sr-interval: 20
sr-ease: 250
---
# Latex 
----
C’est un outil de typographie professionnelle.

## Quand est-ce qu'on doit utilisé Latex
----
Si 2 des 5 critère ont des réponse positive, vous devriez considérer Latex comme outil pour votre travail
1. Est-ce que le document est long (>5 pages) ?
2. Est-ce que votre document devra évoluer dans le temps ?
3. Est-ce que le but de votre document est d'être présenté à d'autre pour expliquer ou convaincre ?
4. Est ce que plusieurs personnes doivent collaborer au document ?
5. Avez-vous des besoins particulier (modularité, mise en page particulière, style, alignement, document standardisé, etc)

## Structure et conventions
----
La structure générale d'un ficher Latex est comme suit :
```Latex
\documentclass[option]{class}
	% Préambule et option du docuent
\begin{document}
	% Tous ce qui se trouve dans le document
\end
```

### Type de document (documentclass)
----
Quelque type commun
- `book`: Livre
- `report`: Rapport
- `article`: Article
- `ULrapport`: Format de rapport ( filière Design )
	- Disponible sur le site web "Comprehensive TeX Archive Network (CTAN)"
- `ulthese`: Format des thèse de l'Université Laval
	- Disponible sur le site web de la Faculté des études supérieures et postdoctorales (FESP)

### Section d'un document
----
Un document est composé de plusieurs sections hiérarchiques
	Chapitres, sections, sous-sections, paragraphes, etc.

Exemple de section
```Latex
\part{titre}
\chapter{titre}
\section{titre}
\subsection{titre}
\subsubsection{titre}
\paragraph{titre}
\subparagraph{titre}
```

> [!info] Table des matière
> Chaque section apparait dans la table des matières sauf les version "\*"

#### Label
----
Chaque section peut être identifier par un label
```Latex
\label{section_name}
```

#### Référence
----
Chaque section peut être alors référencé:
```Latex
\ref{section_name}
```


### Modularité
----
L'inclusion de fichier se fait comme suit:
```Latex
\input{file}
\input{folder/file}
```

## Related Subjects
----
#### Links
----
- [Overleaft](https://www.overleaf.com)
