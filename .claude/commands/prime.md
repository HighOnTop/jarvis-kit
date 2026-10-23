---
description: Démarrer une session avec tout le contexte chargé
---

# /prime

1. `context/CONTEXT.md` est déjà chargé via `CLAUDE.md`. Lis aussi `context/HISTORY.md` (les 3 dernières entrées suffisent).
2. Si un vault est configuré, lis son `_index.md`, `0. TODO.md`, et les fichiers `État.md` des projets modifiés depuis la dernière entrée de `HISTORY.md`.
3. Réponds dans ce format, court :

```
Salut [prénom]. Où on en est :

**En ce moment** : [1 à 2 lignes sur la situation]
**Tes projets actifs** : [une ligne par projet, avec sa prochaine étape]
**Dernière session** : [ce qui a été fait ou décidé]
**À ne pas oublier** : [échéances proches, tâches en retard, s'il y en a]

On fait quoi aujourd'hui ?
```

4. **N'agis pas** : attends qu'on te dise quoi faire.

Si deux fichiers se contredisent (par exemple un projet « en pause » dans `CONTEXT.md` mais « en cours » dans le vault), signale-le en une ligne à la fin et propose de corriger.
