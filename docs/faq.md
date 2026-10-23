# FAQ

**Jarvis a oublié ce qu'on a fait hier.**
Tape `/prime` en début de session. S'il manque quelque chose, c'est que ça n'a pas été écrit : pense à `/sync-obsidian` en fin de session, ou dis-lui « note ça ».

**Il ne peut pas écrire dans mon vault.**
Le vault est hors du dossier du kit. Vérifie que son chemin est dans `.claude/settings.local.json` (section `additionalDirectories`), ou tape `/add-dir <chemin du vault>` pour la session en cours.

**J'ai déplacé ou renommé mon vault.**
Dis-le à Jarvis : il met à jour le chemin dans `context/CONTEXT.md` et dans `.claude/settings.local.json`.

**J'ai réorganisé mes dossiers Obsidian.**
Demande-lui de mettre à jour `_index.md` à la racine du vault, sinon il rangera aux anciens endroits.

**Il range une note au mauvais endroit.**
Corrige-le une fois (« non, les notes de sport vont dans 1. Perso/Sport ») et demande-lui de l'ajouter dans `_index.md`.

**Je peux l'utiliser sur un autre ordi ?**
Oui : copie ce dossier et ton vault, ou synchronise-les (iCloud, Google Drive, Obsidian Sync). Ne passe jamais par un dépôt GitHub **public**.

**Combien ça coûte ?**
L'abonnement Claude (Pro minimum pour Claude Code). Obsidian est gratuit. Wispr Flow a une offre gratuite limitée.

**Mes données partent où ?**
Tes fichiers restent sur ton ordi. Ce que Jarvis lit pendant une session (ton contexte, les notes qu'il ouvre, tes mails si tu le lui demandes) est envoyé à Claude pour qu'il puisse te répondre. C'est pour ça qu'on ne met jamais de mot de passe dans le vault.

**Je veux repartir de zéro.**
Supprime `context/CONTEXT.md` et `context/HISTORY.md`, puis relance `/installer`. Ton vault n'est pas touché.
