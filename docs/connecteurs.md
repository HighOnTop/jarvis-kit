# Brancher tes mails et ton agenda

Les connecteurs permettent à Jarvis de lire tes mails et ton agenda (pour `/morning`, ou quand tu lui demandes « j'ai quoi demain ? »). Ils se branchent sur ton **compte Claude**, pas dans ce dossier : une fois branchés, ils marchent dans Claude Code comme sur claude.ai.

Temps : 2 minutes par connecteur.

---

## Gmail et Google Agenda

1. Va sur **claude.ai** et connecte-toi avec le même compte que dans Claude Code.
2. Ouvre les **Paramètres**, puis la section **Connecteurs**.
3. Cherche **Gmail**, clique sur **Connecter**, choisis ton compte Google et accepte les autorisations.
4. Fais pareil avec **Google Calendar**.
5. Reviens dans VS Code et **redémarre la session Claude Code** (ferme et rouvre le panneau).
6. Vérifie : tape `/mcp`. Gmail et Google Calendar doivent apparaître dans la liste.
7. Teste : « Quels sont mes 3 derniers mails ? »

## Outlook (Microsoft 365)

Même chemin : **Paramètres > Connecteurs > Microsoft 365**.

⚠️ **Compte d'école ou d'entreprise** : l'administrateur informatique doit souvent approuver l'application avant que tu puisses la connecter. Si tu vois un message du type « approbation de l'administrateur requise », ce n'est pas un bug : écris au service informatique de ton école ou de ton entreprise et demande-leur d'approuver l'application Claude sur votre compte Microsoft.

---

## Ce que Jarvis fait (et ne fait pas) avec

- Il **lit** pour te résumer et te conseiller.
- Il ne **répond à aucun mail**, n'en supprime aucun et ne touche pas à ton agenda **sans que tu le lui demandes**. Et même là, il te montre le brouillon avant d'envoyer.
- Tu peux débrancher un connecteur à tout moment dans les mêmes paramètres.

---

## Bonus : Claude in Chrome

L'extension Chrome de Claude permet à Jarvis d'agir dans ton navigateur : remplir un formulaire, comparer des prix, récupérer une info sur un site où tu es connecté.

1. Installe l'extension **Claude** (éditeur : Anthropic) depuis le Chrome Web Store.
2. Connecte-toi avec ton compte Claude dans l'extension.
3. Dans Claude Code, vérifie avec `/mcp` qu'elle apparaît.

Conseil : demande-lui de travailler dans un nouvel onglet, et garde un œil sur ce qu'il fait les premières fois. Il agit avec tes comptes connectés.
