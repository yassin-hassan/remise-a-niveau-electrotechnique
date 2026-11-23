# Remise à niveau : mathématiques, physique, électrotechnique

Ce dépôt est mon carnet de travail. J'y consigne, exercice par exercice, ma remise à niveau en mathématiques, en physique et en électrotechnique, dans le cadre de ma réorientation vers le génie électrique.

Les résolutions sont les miennes, erreurs comprises. Quand je me trompe, je garde l'erreur et j'ajoute ma correction. L'historique des commits montre le rythme du travail.

## Objectifs

1. **Retrouver la fluidité en calcul algébrique.** Je suis les cours d'Yvan Monka (maths-et-tiques.fr) : lecture de la notion, vidéo, puis exercices.
2. **Apprendre l'électricité**, avec les cours de Fabrice Sincère.

## Plan

Pour passer au chapitre suivant, je dois réussir les exercices corrigés sans regarder le cours.

### Phase 1 : algèbre de 4e et de 3e (4 à 6 semaines)

**Bases de calcul, en parallèle**

- **Tables de multiplication** : entraînement quotidien, surtout les tables de 6 et de 7.
- **Calcul mental.**
- **Division euclidienne** posée.

**Monka 4e, chapitres retenus**

- **Nombres relatifs** : additions et soustractions, règle des signes (y compris sur les fractions), calculs avec des relatifs.
- **Fractions** : simplification, mise au même dénominateur, additions et soustractions, multiplications, inverse, divisions, calculs mêlés, problèmes.
- **Puissances** : notation, puissances de 10, préfixes de nano à giga, écriture scientifique. Les préfixes (mA, kΩ, µF, MW) sont omniprésents en électricité.
- **Calcul littéral** : exprimer en fonction de, distributivité, développer, factoriser (niveaux 1 et 2), réduire.
- **Équations** : vérifier une solution, mettre en équation, résoudre.

**Monka 3e, l'algèbre**

- **Calculs numériques** : révision des relatifs, des fractions et des puissances, puissances d'exposant négatif, notation scientifique.
- **Développements** : distributivité simple et double, identité remarquable $(a-b)(a+b) = a^2 - b^2$.
- **Factorisations** : facteur commun, $a^2 - b^2$, identités remarquables.
- **Équations** : équations avec fractions, équation-produit, $x^2 = a$, mise en équation.
- **Notion de fonction** : tableau de valeurs, image, antécédent, représentation graphique, lecture graphique.
- **Fonctions affines** : reconnaître une fonction affine, la représenter, déterminer une fonction linéaire graphiquement, déterminer une fonction affine à partir de deux nombres et de leurs images.

**Monka 2nde, un seul chapitre**

- **Systèmes d'équations et droites** : méthodes par substitution et par combinaison linéaire, problèmes. L'interprétation graphique vient en complément.

Je laisse de côté pour l'instant les probabilités, les statistiques, la proportionnalité, la géométrie (Thalès, triangles semblables, transformations) et l'espace. L'arithmétique (divisibilité, nombres premiers) ne fait pas partie du plan : je la travaille par goût.

### Phase 2 : électricité, chapitres 1 et 2 de Fabrice Sincère (6 à 8 semaines)

**Chapitre 1, introduction**

- Courant électrique, loi des nœuds (1re loi de Kirchhoff).
- Tension électrique, loi des mailles (2e loi de Kirchhoff).
- Loi d'Ohm, résistance, résistivité.
- Puissance, énergie, effet Joule.
- QCM : lois des mailles et des nœuds, puissance, multimètre.

**Chapitre 2, régime continu**

- Dipôles passifs, associations en série et en parallèle.
- Diviseur de tension, diviseur de courant, théorème de Millman.
- Dipôles actifs : modèles de Thévenin et de Norton.
- Théorème de superposition.
- Dipôles non linéaires et linéarisation (fonctions affines).
- Exercices 2-01 à 2-31. Ceux sur les circuits linéaires en régime continu (2-10, 2-17 à 2-21, 2-25, 2-26) demandent de résoudre des systèmes d'équations, vus en phase 1.

En parallèle : le reste du programme de 2nde chez Monka (calcul littéral, fractions, puissances et racines, équations et inéquations, fonctions de référence).

### Phase 3 : préparation au courant alternatif

Le chapitre 3 de Sincère (régime sinusoïdal) utilise les vecteurs de Fresnel et les nombres complexes. Avant de l'aborder :

- Théorème de Pythagore (4e).
- Cosinus (4e), puis trigonométrie : cosinus, sinus, tangente (3e).
- Vecteurs (2nde).
- Cercle trigonométrique et radians (1re).
- Nombres complexes (Terminale, option maths expertes). C'est la partie la plus longue, à planifier en détail le moment venu.

### Phase 4 : le cœur du métier

- **Électricité, chapitre 3** : régime sinusoïdal, impédance, puissance.
- **Électrotechnique, chapitre 2** : puissances active, réactive et apparente, théorème de Boucherot, facteur de puissance.
- **Électrotechnique, chapitre 3** : systèmes triphasés, couplages étoile et triangle. C'est la base des réseaux électriques.
- **Électrotechnique, chapitre 5** : transformateur, et son rôle dans le transport et la distribution de l'énergie.

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
| Fractions | En cours | [21/11](journal.md#2026-11-21), [23/11](journal.md#2026-11-23) |
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
