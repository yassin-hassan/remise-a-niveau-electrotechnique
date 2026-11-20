# Instructions pour Claude dans ce dépôt

Ce dépôt documente ma remise à niveau en mathématiques et en électrotechnique, en vue d'un BTS Électrotechnique en apprentissage. Il est public et sera montré à des écoles et des employeurs (Enedis, RTE, EDF...). Tout son contenu doit refléter MON travail.

## Règles

1. **Ne jamais résoudre un exercice à ma place.** Ne donne pas la solution, même partielle, sauf si je te le demande explicitement avec le mot « SOLUTION ».
2. **Mise en forme uniquement.** Quand je te donne une photo ou un brouillon de ma résolution, transcris-la fidèlement en Markdown avec LaTeX (`$...$`, `$$...$$`) en suivant le modèle d'exercice du README. Ne corrige pas mes erreurs dans la transcription.
3. **Vérification.** Après la transcription, signale les erreurs éventuelles (ligne concernée, type d'erreur) sans donner la correction. Je corrigerai moi-même, puis tu ajouteras une section « Erreur et correction » rédigée à partir de MA correction.
4. **Journal hebdomadaire.** Quand je dis « journal », rédige l'entrée de la semaine dans `journal/` à partir des commits de la semaine (`git log --since="1 week ago"`) et de mes notes : notions vues, nombre d'exercices, difficultés, objectifs de la semaine suivante. Ton factuel, sans enjoliver.
5. **Tableau de progression.** Mets à jour le tableau du README quand je termine une notion.
6. **Langue :** français. Pas d'emojis, pas de formules creuses.
7. **Sécurité :** pour le projet ESP32, ne propose jamais de manipulation sur du 230 V. Uniquement pince ampèremétrique non invasive et très basse tension.
8. **Commits :** propose un message de commit court en français (ex. `maths: équations, exercices 1 à 8`), mais laisse-moi valider avant de committer. N'ajoute jamais de ligne `Co-Authored-By` ni aucune mention de Claude dans les commits.
