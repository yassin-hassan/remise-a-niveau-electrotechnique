# Remise à niveau : mathématiques, physique, électrotechnique

Ce dépôt est mon carnet de travail. J'y consigne, exercice par exercice, ma remise à niveau en mathématiques, en physique et en électrotechnique, dans le cadre de ma réorientation vers le génie électrique.

Les résolutions sont les miennes, erreurs comprises. Quand je me trompe, je garde l'erreur et j'ajoute ma correction. L'historique des commits montre le rythme du travail.

La première étape est l'algèbre. Je suis les cours d'Yvan Monka (maths-et-tiques.fr) : lecture de la notion, vidéo, puis exercices.

## Méthode

1. **Pour chaque chapitre** : cours, vidéo, exercices. Chaque erreur relevée est conservée avec ma correction.
2. **Bilan de fin de chapitre** : exercices inédits, chronométrés.

## Organisation du dépôt

```
maths/algebre/
  01-nombres-relatifs/
    exercices.md
    brouillons/
  02-<chapitre>/
    ...
```

Chaque chapitre a son dossier. `brouillons/` contient les photos de mes feuilles manuscrites, et le fichier `.md` leur transcription.

## Progression

| Chapitre | Statut | Exercices | Bilan (score) | Bilan (temps) | Date de fin |
|---|---|---|---|---|---|
| Nombres relatifs (rappel 4e) | Terminé | 2 | | | 2026-11-20 |

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
