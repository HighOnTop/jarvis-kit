---
description: Le point du matin (mails, agenda, focus du jour)
---

# /morning

Remplace 15 minutes de scroll par 30 secondes de lecture utile.

1. Utilise le contexte (`context/CONTEXT.md`) et `0. TODO.md` du vault pour savoir ce qui compte.
2. **Mails** (si un connecteur Gmail ou Outlook est branché) : regarde les mails reçus depuis hier soir. Garde seulement ceux qui demandent une action ou concernent un projet en cours. Ignore les newsletters et les pubs.
3. **Agenda** (si un connecteur Google Agenda ou Outlook est branché) : les événements d'aujourd'hui.
4. Réponds dans ce format, une page maximum :

```
☀️ Bonjour [prénom]. [jour et date]

📬 Mails de ce matin
- [Expéditeur] : [ce qu'il veut, en une ligne] → [action suggérée]

📅 Aujourd'hui
- [heure] [événement]

✅ À faire
- [2 ou 3 tâches de la to-do les plus urgentes]

🎯 Focus du jour
[une phrase : LA chose à faire aujourd'hui, en croisant agenda, mails et projets]
```

## Règles

- Si un connecteur n'est pas branché, saute la section sans le mentionner. Si aucun n'est branché, une seule ligne à la fin : « Branche Gmail et Agenda (voir `docs/connecteurs.md`) pour que je lise tes mails et ton agenda. »
- Ne réponds à aucun mail et ne modifie aucun événement sans qu'on te le demande.
- Pas plus de 5 mails. S'il y en a plus d'importants, dis combien.
