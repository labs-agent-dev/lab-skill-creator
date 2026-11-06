# Travail à Réaliser : 3. Skill Technique (Résultat Final du Lab)

Ce dossier accueille la spécification et la conception du skill technique final de ce lab : **`skill-creator`**.

---

## 🎯 Objectif Technique
Concevoir la spécification formelle de `skill-creator`, la compétence qui permet à notre équipe et à l'agent `AgentDev` de générer et maintenir tous les skills techniques du projet fil rouge.

## 📋 Travail Concret à Réaliser par l'Apprenant
1. **Rédiger `spec-skill.md` :**
   - Définir le contrat d'interface de `skill-creator`.
   - Spécifier les entrées (nom du skill, pattern, stack ciblée) et sorties (arborescence, `SKILL.md` en 10 rubriques, `resources/`, `docs/`).
   - Définir les critères de validation automatisée (0 erreur au script).
2. **Consolider la version finale du skill :**
   - S'assurer que `.agent/skills/skill-creator/SKILL.md` est parfaitement synchronisé.
   - Vérifier la documentation `docs/guide-10-rubriques-anthropic.md`.
3. **Tester la validation :**
   ```powershell
   node .agent/skills/skill-creator/scripts/validate-skills.cjs
   ```

