---
description: Ajouter une ou plusieurs tâches dans la to-do du vault
argument-hint: "[la tâche, en langage naturel]"
---

# /todo

Tâche à ajouter : $ARGUMENTS

1. Si rien n'est donné après `/todo`, demande : « Qu'est-ce que tu dois faire ? »
2. Ouvre `0. TODO.md` à la racine du vault (chemin dans `context/CONTEXT.md`).
3. Ajoute chaque tâche **en bas de la section « 📥 À trier »**, au format `- [ ] tâche`. Si une date ou une échéance est mentionnée, mets-la au début : `- [ ] 📅 ven 14/11 : tâche`.
4. Reformule seulement pour rendre la tâche claire et actionnable (commence par un verbe), sans changer le sens.
5. Confirme en une ligne : « ✅ Ajouté à ta to-do : … »

## Règles

- N'écris **que** dans « 📥 À trier ». Le reste du fichier, c'est la personne qui le range.
- Ne coche ni ne supprime jamais une tâche sans qu'on te le demande.
- Si la section « 📥 À trier » n'existe pas, crée-la tout en haut du fichier, sous le titre.
