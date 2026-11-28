# Remise à niveau : mathématiques, physique, électrotechnique

Ce dépôt est mon carnet de travail. J'y consigne, exercice par exercice, ma remise à niveau en mathématiques, en physique et en électrotechnique, dans le cadre de ma réorientation vers le génie électrique.

Les résolutions sont les miennes, erreurs comprises. Quand je me trompe, je garde l'erreur et j'ajoute ma correction. L'historique des commits montre le rythme du travail.

## Objectifs

1. **Retrouver la fluidité en calcul algébrique.** Je suis les cours d'Yvan Monka (maths-et-tiques.fr) : lecture de la notion, vidéo, puis exercices.
2. **Apprendre l'électricité**, avec les cours de Fabrice Sincère.

## Plan

Pour passer au chapitre suivant, je dois réussir les exercices corrigés sans regarder le cours.

### Phase 1 : algèbre de 4e et de 3e

**Bases de calcul, en parallèle**

- Tables de multiplication
- Calcul mental
- Division euclidienne

**Monka 4e, chapitres retenus**

- Nombres relatifs
- Fractions
- Puissances
- Calcul littéral
- Équations
- Proportionnalité

**Monka 3e, l'algèbre**

- Calculs numériques
- Développements
- Factorisations
- Équations
- Notion de fonction
- Fonctions affines

**Monka 2nde, un seul chapitre**

- Systèmes d'équations et droites

Je laisse de côté pour l'instant les probabilités, les statistiques, la géométrie (Thalès, triangles semblables, transformations) et l'espace. L'arithmétique (divisibilité, nombres premiers) ne fait pas partie du plan : je la travaille par goût.

### Phase 2 : électricité, chapitres 1 et 2 de Fabrice Sincère

- Chapitre 1 : introduction
- Chapitre 2 : régime continu

En parallèle : le reste du programme de 2nde chez Monka (calcul littéral, fractions, puissances et racines, équations et inéquations, fonctions de référence).

### Phase 3 : préparation au courant alternatif, mécanique de base

- Théorème de Pythagore (4e)
- Cosinus (4e), puis trigonométrie (3e)
- Vecteurs (2nde)
- Mécanique de base (niveau lycée)
- Cercle trigonométrique et radians (1re)
- Nombres complexes (Terminale, option maths expertes)

### Phase 4 : le cœur du métier

- Mécanique de rotation
- Électrotechnique, chapitre 1 : machine à courant continu
- Électricité, chapitre 3 : régime sinusoïdal
- Électrotechnique, chapitre 2 : puissances en régime sinusoïdal
- Électrotechnique, chapitre 3 : systèmes triphasés
- Électrotechnique, chapitre 5 : transformateur
- Électrotechnique, chapitres 6 et 7 : champ magnétique tournant, machine synchrone triphasée

## Méthode

1. **Pour chaque chapitre** : cours, vidéo, exercices. Chaque erreur relevée est conservée avec ma correction.
2. **Bilan de fin de chapitre** : exercices inédits, ajoutés à la fin du fichier du chapitre.

## Organisation du dépôt

```
maths/algebre/
  01-nombres-relatifs/
    exercices.md
    brouillons/
  02-fractions/
    exercices.md
    brouillons/
  03-puissances/
    exercices.md
    brouillons/
journal.md
```

Chaque chapitre a son dossier. `brouillons/` contient les photos de mes feuilles manuscrites, et le fichier `.md` leur transcription. `journal.md` résume chaque jour de travail : notions vues, erreurs marquantes, points à travailler.

## Progression

| Notion | Statut | Journal |
|---|---|---|
| Nombres relatifs | Terminé | [20/11](journal.md#2026-11-20), [21/11](journal.md#2026-11-21), [23/11](journal.md#2026-11-23), [24/11](journal.md#2026-11-24) |
| Fractions | Terminé | [21/11](journal.md#2026-11-21), [23/11](journal.md#2026-11-23), [24/11](journal.md#2026-11-24), [25/11](journal.md#2026-11-25) |
| Divisibilité et nombres premiers | En cours | [21/11](journal.md#2026-11-21) |
| Puissances | En cours | [26/11](journal.md#2026-11-26), [27/11](journal.md#2026-11-27) |

Statuts possibles : À faire, En cours, Terminé.

## Modèle d'exercice

```markdown
### Exercice N : titre court

**Source :** Yvan Monka, chapitre, numéro de l'exercice
**Date :** AAAA-MM-JJ
**Brouillon :** [photo](brouillons/nom-du-fichier.jpg)

#### Énoncé

Énoncé court.

#### Résolution

Étapes de calcul en LaTeX :

$$
(x+3)(x-2) = x^2 - 2x + 3x - 6
$$

#### Résultat

Résultat final.

#### Erreur et correction

(Section présente uniquement si une erreur a été relevée.)
- **Erreur :** ligne concernée et nature de l'erreur.
- **Correction :** ma correction.
- **À retenir :** ce que je dois surveiller la prochaine fois.
```
