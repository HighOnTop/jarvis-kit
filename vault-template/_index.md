# Index du vault (pour Jarvis)

Ce fichier dit à Jarvis où ranger les choses. Il n'est pas fait pour la navigation : pour ça, ouvre [[🏠 Accueil]].

> `/installer` adapte ce tableau à ta vie. Si tu ajoutes ou renommes un dossier à la main, mets cette page à jour (ou demande à Jarvis de le faire).

## Dossiers et leur rôle

| Dossier | Rôle | Jarvis peut écrire ? |
|---|---|---|
| `0. TODO.md` | Ta to-do unique. La section « 📥 À trier » reçoit les tâches ajoutées par Jarvis ; le reste, c'est toi qui le ranges | Oui, **seulement dans « 📥 À trier »** |
| `1. Perso` | Vie perso : maison, recettes, voyages, santé, finances perso | Oui |
| `2. Projets` | Un sous-dossier par projet (pro, perso, side project), avec `État.md` et `Journal.md` | Oui, dans le sous-dossier du projet |
| `3. Études-Travail` | Cours (un dossier par matière) ou travail (un dossier par mission ou client) | Oui, dans le bon sous-dossier |
| `4. Archives` | Ce qui est terminé ou en pause | Seulement pour y déplacer un projet, à ta demande |
| `5. Modèles` | Modèles de notes | Non |
| `🏠 Accueil.md` | Ta page d'accueil | Non |

## Règles

- Un dossier nommé `KEYS`, `secret` ou `privé` est **interdit en lecture et en écriture**. Mieux : ne mets aucun mot de passe dans le vault.
- Ne jamais réécrire une note entière. Dans un fichier « état », remplacer la ligne concernée. Dans un fichier « journal », ajouter une entrée datée à la fin.
- Format d'une entrée de journal : `- [AAAA-MM-JJ] Résumé en 2 à 4 lignes, centré sur la décision ou l'avancement.`
- En cas de doute sur le bon dossier, **demander** plutôt que deviner.
- Ne jamais créer de dossier sans accord.
- Ne jamais toucher `.obsidian/`.
