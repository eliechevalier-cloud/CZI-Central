# 🏷️ Configuration des Labels GitHub

Ce document explique comment configurer les labels personnalisés pour le repository CZI-Central.

## Labels à Créer

Les labels suivants doivent être créés manuellement dans les paramètres GitHub du repository.

### 1. 🔴 design
- **Nom** : `design`
- **Description** : Travail de création et design de maillots
- **Couleur** : `#d73a4a` (rouge)

### 2. 🔵 production
- **Nom** : `production`
- **Description** : Tâches de production et coordination fournisseurs
- **Couleur** : `#0075ca` (bleu)

### 3. 🟡 marketing
- **Nom** : `marketing`
- **Description** : Actions et campagnes marketing
- **Couleur** : `#fbca04` (jaune)

### 4. 🟢 web
- **Nom** : `web`
- **Description** : Site web et e-commerce
- **Couleur** : `#0e8a16` (vert)

### 5. 🟠 urgent
- **Nom** : `urgent`
- **Description** : Priorité haute, action immédiate requise
- **Couleur** : `#ff9500` (orange)

### 6. 🟣 idée
- **Nom** : `idée`
- **Description** : Propositions, brainstorming et innovations
- **Couleur** : `#7057ff` (violet)

## Comment Créer les Labels

### Via l'Interface GitHub

1. Allez sur le repository : https://github.com/eliechevalier-cloud/CZI-Central
2. Cliquez sur l'onglet **Issues**
3. Cliquez sur **Labels** (à côté de Milestones)
4. Pour chaque label ci-dessus :
   - Cliquez sur **New label**
   - Entrez le **Nom**
   - Entrez la **Description**
   - Entrez le code **Couleur** (avec le #)
   - Cliquez sur **Create label**

### Via GitHub CLI (gh)

Si vous avez GitHub CLI installé, vous pouvez créer tous les labels avec ces commandes :

```bash
# design (rouge)
gh label create design --description "Travail de création et design de maillots" --color "d73a4a" --repo eliechevalier-cloud/CZI-Central

# production (bleu)
gh label create production --description "Tâches de production et coordination fournisseurs" --color "0075ca" --repo eliechevalier-cloud/CZI-Central

# marketing (jaune)
gh label create marketing --description "Actions et campagnes marketing" --color "fbca04" --repo eliechevalier-cloud/CZI-Central

# web (vert)
gh label create web --description "Site web et e-commerce" --color "0e8a16" --repo eliechevalier-cloud/CZI-Central

# urgent (orange)
gh label create urgent --description "Priorité haute, action immédiate requise" --color "ff9500" --repo eliechevalier-cloud/CZI-Central

# idée (violet)
gh label create idée --description "Propositions, brainstorming et innovations" --color "7057ff" --repo eliechevalier-cloud/CZI-Central
```

## Utilisation des Labels

### Dans les Issue Templates

Les issue templates sont déjà configurés avec les labels par défaut :
- **Nouveau Design** → label `design`
- **Tâche Production** → label `production`
- **Action Marketing** → label `marketing`
- **Idée** → label `idée`

### Labels Additionnels

Vous pouvez combiner plusieurs labels sur une même issue :
- `design` + `urgent` : Design urgent à valider
- `production` + `urgent` : Problème production critique
- `marketing` + `web` : Campagne nécessitant intégration web
- `idée` + `design` : Idée de nouveau design

## Labels GitHub par Défaut

Vous pouvez conserver ou supprimer les labels GitHub par défaut selon vos besoins :
- `bug`
- `documentation`
- `duplicate`
- `enhancement`
- `good first issue`
- `help wanted`
- `invalid`
- `question`
- `wontfix`

## Vérification

Une fois les labels créés, vérifiez qu'ils apparaissent bien :
1. Dans la liste des labels (Issues → Labels)
2. Lors de la création d'une nouvelle issue
3. Dans les filtres de recherche d'issues

## Support

Si vous avez des questions sur la configuration des labels, créez une issue avec le label `question`.
