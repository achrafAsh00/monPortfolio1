## Étape 3 : Comprendre l'état "Untracked"

### Pourquoi Git voit les fichiers mais ne les "connaît" pas encore ?
Après avoir ajouté du contenu dans les fichiers via VS Code, la commande `git status` affiche les fichiers en rouge. Cela signifie qu'ils sont dans le **Working Directory** (répertoire de travail) mais qu'ils sont **Untracked** (non suivis).

### Le rôle de l'index
Pour que Git commence à versionner ces lignes de code, je dois les déplacer vers la **Staging Area** (l'index). C'est l'étape de préparation avant la création d'une version permanente.

**Observation :**
Les fichiers sont détectés par Git grâce au dossier caché `.git`, mais ils ne font pas encore partie de l'historique du projet.