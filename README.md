# Remise à niveau : mathématiques, physique, électrotechnique

Ce dépôt est mon carnet de travail. J'y consigne, exercice par exercice, ma remise à niveau en mathématiques, en physique et en électrotechnique, dans le cadre de ma réorientation vers le génie électrique.

Les résolutions sont les miennes, erreurs comprises. Quand je me trompe, je garde l'erreur et j'ajoute ma correction. L'historique des commits montre le rythme du travail.

## Objectifs

1. **Retrouver la fluidité en calcul algébrique.** Je suis les cours d'Yvan Monka (maths-et-tiques.fr) : lecture de la notion, vidéo, puis exercices.
2. **Apprendre l'électricité**, avec les cours de Fabrice Sincère.

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
journal.md
```

Chaque chapitre a son dossier. `brouillons/` contient les photos de mes feuilles manuscrites, et le fichier `.md` leur transcription. `journal.md` résume chaque jour de travail : notions vues, erreurs marquantes, points à travailler.

## Progression

| Notion | Statut | Journal |
|---|---|---|
| Nombres relatifs | Terminé | [20/11](journal.md#2026-11-20), [21/11](journal.md#2026-11-21), [23/11](journal.md#2026-11-23) |
| Fractions | En cours | [21/11](journal.md#2026-11-21) |
| Divisibilité et nombres premiers | En cours | [21/11](journal.md#2026-11-21) |

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
