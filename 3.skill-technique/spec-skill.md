# Spécification Technique : Skill `skill-creator`

## 1. Fiche d'Identité
- **Nom du Skill :** `skill-creator`
- **Type :** Méta-Outillage & Génération Déterministe
- **Cible :** Agent `AgentDev` (Google Antigravity, GitHub Copilot)
- **Version cible :** `1.5.0`
- **Inspiration :** `anthropic/claude-plugins-official` (pattern `plugin-dev`)

## 2. Contrat d'Interface

### Entrées attendues :
- **Intention utilisateur :** Demande de création ou audit d'un skill (ex: *« Crée le skill alpine-components pour la gestion de modales et menus »*).
- **Paramètres :**
  - Domaine / Techno (ex: Alpine.js, Laravel).
  - Brique métier visée.
  - Pattern architectural (ex: `feature-dev`, `domain-guidance`).

### Sorties produites :
- Arborescence sous `.agent/skills/[nom-norme]/` :
  - `SKILL.md` rigoureusement structuré en 10 rubriques.
  - En-tête YAML valide (sans préfixe `lab-*`).
  - Sous-dossiers éventuels `resources/` (snippets et règles) et `docs/`.
- Résultat du linter `validate-skills.cjs` avec statut vert (0 erreur).

## 3. Matrice des 10 Rubriques Imposées
1. `# 1. Mission`
2. `# 2. Déclenchement & Limites`
3. `# 3. Entrées & Ressources à Charger`
4. `# 4. Contraintes & Règles Inviolables`
5. `# 5. Procédure Pas-à-Pas`
6. `# 6. Gestion des Ambiguïtés & Décisions`
7. `# 7. Format de Sortie & Livrables`
8. `# 8. Contrôle Qualité (Checklist Binaire)`
9. `# 9. Gestion des Erreurs Fréquentes`
10. `# 10. Exemples Concrets (Few-Shot)`

