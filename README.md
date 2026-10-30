# Anti-Dream

> Skill OpenCode de garde-fous contre les hallucinations et les dérives de contexte — vérifier avant d'affirmer, marquer les incertitudes.

**ID** : `anti-dream` · **Portée** : globale (`~/.config/opencode/skills/`) · **Langue** : FR

## Ce que fait le skill

Feuille de route de discipline chargée dans le contexte du modèle :

1. **Ancrage aux sources** : lire avant d'affirmer, jamais d'inventer (noms, URLs, versions), distinguer *lu* / *sourcé* / *supposé*
2. **Anti-dérive** : reformuler la tâche, s'arrêter sur ambiguïté, détecter la dérive, ne pas deviner les objectifs implicites
3. **Vérification des sorties** : relire/exécuter le code, sourcer chiffres et versions
4. **Format d'honnêteté** : table de formulations (*« à confirmer »*, *« non vérifié »*)
5. **Déclenchement prioritaire** : questions factuelles, migrations, tâches longues

## Structure

```text
anti-dream/
├── SKILL.md                    # Règles anti-hallucination / focus
└── references/
    └── checklist.md            # Checklist 4 blocs à passer avant livraison
```

## Déclenchement

- **Automatique** : questions factuelles, APIs, versions, tâches longues
- **Manuel** : `@anti-dream`
- À combiner avec `pre-ship-review` (règle « aucune case cochée sans preuve »)

## Vérification

- [ ] Chaque fait sourcé ou marqué d'incertitude
- [ ] Code testé ou mentionné *« non testé »*
- [ ] Toujours sur la tâche initiale

## Skills liés

- `debug-methodique` (hypothèses validées par observation), `opti-skill` (économie sans perdre la fiabilité)
