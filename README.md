# jarvis-kit

Ton assistant IA personnel, façon Jarvis d'Iron Man : **Claude Code** comme cerveau, **Obsidian** comme mémoire, **Wispr Flow** pour lui parler.

Le problème de l'IA, c'est qu'elle oublie tout d'une conversation à l'autre. Ce kit lui greffe une mémoire : un dossier de contexte sur toi, et un vault Obsidian qu'elle lit et qu'elle range pour toi. Tu lui parles normalement, elle sait qui tu es, sur quoi tu bosses, et elle classe tout au bon endroit.

> Kit gratuit, licence MIT. Il accompagne la vidéo YouTube « Mon Jarvis connecté à Obsidian » de la chaîne Alexandre Lagarde.

---

## Ce qu'il te faut

| Outil | À quoi il sert | Prix |
|---|---|---|
| **VS Code** | L'endroit où tu parles à Jarvis | Gratuit |
| **Claude Code** (extension VS Code) | Le cerveau | Abonnement Claude Pro minimum |
| **Obsidian** | La mémoire, lisible par toi | Gratuit (Sync et Publish sont des options payantes, pas nécessaires) |
| **Wispr Flow** | La dictée vocale partout sur ton ordi | Offre gratuite limitée, version Pro payante |

Ça marche sur **Mac et Windows**.

---

## Installation (environ 30 minutes)

1. Télécharge ce dossier (bouton vert « Code », puis « Download ZIP ») et dézippe-le où tu veux, par exemple dans `Documents/jarvis`.
2. Ouvre VS Code, puis **Fichier > Ouvrir le dossier** et choisis ce dossier.
3. Installe l'extension **Claude Code** et connecte-toi avec ton compte Claude.
4. Dans la fenêtre Claude Code, tape :

```
/installer
```

Jarvis s'occupe du reste : il vérifie ton installation, t'aide à installer Obsidian et Wispr Flow, te pose des questions pour bien te connaître, construit ton vault Obsidian à ton image et te fait une mini-formation.

---

## Les commandes

| Commande | Ce qu'elle fait |
|---|---|
| `/installer` | L'installation guidée, à lancer une seule fois |
| `/prime` | Démarre une session : Jarvis charge ton contexte |
| `/morning` | Ton point du matin : mails, agenda, focus du jour |
| `/todo` | Ajoute une tâche à ta to-do Obsidian |
| `/update` | Met à jour ton contexte quand ta vie change |
| `/sync-obsidian` | En fin de session, range dans Obsidian tout ce qu'on s'est dit |

Mais le plus important : **tu n'as pas besoin de commandes.** Parle-lui normalement. « Remets au propre mes notes de cours », « note que j'ai un rendez-vous jeudi », « reprends le projet où on s'était arrêté » : il comprend.

---

## Les connecteurs (optionnel, mais c'est là que ça devient magique)

Pour que `/morning` lise tes mails et ton agenda, connecte Gmail et Google Agenda à ton compte Claude. Le guide pas à pas est dans [docs/connecteurs.md](docs/connecteurs.md).

---

## ⚠️ Sécurité : à lire avant de partager quoi que ce soit

Après l'installation, ce dossier contient **ta vie** : qui tu es, tes projets, tes objectifs.

- **Ne publie jamais ton dossier Jarvis** (GitHub public, Drive partagé, zip envoyé à un pote). Le `.gitignore` exclut déjà tes fichiers perso, mais ne compte pas que là-dessus.
- **Ne mets jamais de mots de passe ni de clés d'API** dans Obsidian ou dans `context/`. Jarvis lit ces fichiers à chaque session : tout ce qui y est écrit passe dans la conversation. Utilise un gestionnaire de mots de passe.
- Si tu veux partager ton Jarvis avec quelqu'un, partage **ce kit vierge**, pas ton dossier.

---

## Structure

```
jarvis-kit/
├── CLAUDE.md                 # La personnalité et les règles de Jarvis (rempli par /installer)
├── context/
│   ├── CONTEXT.md            # Qui tu es, ce que tu fais, tes objectifs
│   ├── HISTORY.md            # Le journal de vos sessions
│   └── import/               # Dépose ici les documents à analyser
├── vault-template/           # Le squelette Obsidian que /installer adapte à ta vie
├── docs/                     # Guides (connecteurs, FAQ)
└── .claude/commands/         # Les commandes de Jarvis
```

---

Licence MIT. Fais-en ce que tu veux, améliore-le, partage-le.
