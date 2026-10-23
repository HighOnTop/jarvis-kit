---
description: Ranger dans le vault Obsidian tout ce qui s'est dit pendant la session
---

# /sync-obsidian

Tu as toute la conversation en mémoire : sers-t'en pour figer dans le vault ce qui a été fait, décidé ou reste à faire.

## Étapes

1. **Lis `_index.md`** à la racine du vault (chemin dans `context/CONTEXT.md`) pour savoir quel dossier sert à quoi et où tu as le droit d'écrire.
2. **Liste ce qui mérite d'être gardé** depuis le début de la session (ou depuis le dernier `/sync-obsidian`) : décisions, avancées, infos nouvelles, tâches à faire. Ignore la technique sans impact (« j'ai renommé une variable »).
3. **Pour chaque sujet, trouve le bon endroit** : le dossier du projet, la matière, la note perso concernée. Pas de dossier qui corresponde ? **Demande**, ne crée rien tout seul.
4. **Lis avant d'écrire.** Ouvre les notes existantes (`État.md`, `Journal.md`, la note de cours…) pour ne rien dupliquer ni écraser.
5. **Écris** :
   - Fichier « état » : remplace les lignes devenues fausses, ajoute ce qui manque.
   - Fichier « journal » : ajoute une entrée datée à la fin, `- [AAAA-MM-JJ] résumé en 2 à 4 lignes`.
   - Tâches : dans « 📥 À trier » de `0. TODO.md` uniquement.
6. Si quelque chose a changé dans la vie ou les projets de la personne, mets aussi à jour `context/CONTEXT.md` et ajoute une ligne dans `context/HISTORY.md`.
7. **Résume** ce que tu as écrit et où, en une ligne par note.

## Règles

- Si rien de notable ne s'est passé, dis-le et n'écris rien.
- Jamais de mots de passe, clés ou codes dans le vault, même s'ils ont été donnés pendant la session.
- Jamais dans un dossier `KEYS`, `secret` ou `privé`, ni dans `.obsidian/`.
- Ne réécris jamais une note entière.

## Limite

Il n'existe pas de marqueur du dernier `/sync-obsidian`. Dans une nouvelle session, fie-toi à ce qui est déjà écrit dans les notes plutôt que de supposer ce qui a été synchronisé ou non.
