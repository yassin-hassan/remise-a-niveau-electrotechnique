# Instructions pour Claude dans ce dépôt

Ce dépôt documente ma remise à niveau en mathématiques et en électrotechnique, en vue d'un BTS Électrotechnique en apprentissage. Il est public et sera montré à des écoles et des employeurs (Enedis, RTE, EDF...). Tout son contenu doit refléter MON travail.

## Règles

1. **Ne jamais résoudre un exercice à ma place.** Ne donne pas la solution, même partielle, sauf si je te le demande explicitement avec le mot « SOLUTION ».
2. **Mise en forme uniquement.** Quand je te donne une photo ou un brouillon de ma résolution, transcris-la fidèlement en Markdown avec LaTeX (`$...$`, `$$...$$`) en suivant le modèle d'exercice du README. Ne corrige pas mes erreurs dans la transcription.
3. **Vérification.** Après la transcription, signale les erreurs éventuelles (ligne concernée, type d'erreur) sans donner la correction. Je corrigerai moi-même, puis tu ajouteras une section « Erreur et correction » rédigée à partir de MA correction.
4. **Journal hebdomadaire.** Quand je dis « journal », rédige l'entrée de la semaine dans `journal/` à partir des commits de la semaine (`git log --since="1 week ago"`) et de mes notes : notions vues, nombre d'exercices, difficultés, objectifs de la semaine suivante. Ton factuel, sans enjoliver.
5. **Tableau de progression.** Mets à jour le tableau du README quand je termine une notion.
6. **Langue :** français. Pas d'emojis, pas de formules creuses.
7. **Commits :** propose un message de commit court en français (ex. `maths: équations, exercices 1 à 8`), mais laisse-moi valider avant de committer. N'ajoute jamais de ligne `Co-Authored-By` ni aucune mention de Claude dans les commits.
8. **Nouveau chapitre.** Quand je commence un nouveau chapitre, crée son dossier numéroté à la suite des autres (ex. `maths/algebre/03-puissances/`), avec un `exercices.md` (titre, source, date) et un dossier `brouillons/` (avec un `.gitkeep` tant qu'il est vide). Ajoute-le à l'arborescence de la section « Organisation du dépôt » du README.
9. **Nouveau brouillon.** Quand j'ajoute un brouillon dans un dossier `brouillons/`, sans attendre que je le demande : retire du fichier toute donnée de localisation (GPS), renomme-le au format `AAAA-MM-JJ-sujet.pdf`, transcris-le dans le `exercices.md` du chapitre (règle 2), puis vérifie-le (règle 3).
