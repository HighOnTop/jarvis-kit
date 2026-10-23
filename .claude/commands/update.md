---
description: Mettre à jour le contexte quand quelque chose a changé
---

# /update

1. Si la conversation en cours contient déjà des changements (nouveau projet, décision, résultat, changement de situation), pars de là. Sinon, demande en une question : « Qu'est-ce qui a changé depuis la dernière fois ? »
2. Relis `context/CONTEXT.md` et repère ce qui est devenu faux ou incomplet.
3. Présente le plan avant d'écrire :

```
Je mets à jour :
- CONTEXT.md, [section] : [avant] → [après]
- HISTORY.md : nouvelle entrée « [titre] »
Ça te va ?
```

4. Après accord, écris. Dans `HISTORY.md`, ajoute en haut (sous l'en-tête) :

```
## AAAA-MM-JJ

### [Titre court]
- [ce qui a changé ou a été décidé]
```

5. Confirme en une ligne ce qui a été modifié.

## Règles

- Remplace les infos devenues fausses, n'empile pas l'ancienne et la nouvelle version.
- Garde `CONTEXT.md` synthétique. Si une section devient trop longue, propose d'en faire une note dans le vault.
- Ne touche jamais à `CLAUDE.md` : il reste générique.
