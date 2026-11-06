# Todo List : Lab Skill Creator (Outillage & Validation des Skills IA)

## Phase 1 : Cadrage du Besoin & Veille (Assisté par lab-dev)
- [x] **Règles Transversales :** Configurer `.agent/rules/` (`persona.md`, `lab-rules.md`, `stack-principles.md`).
- [x] **Besoin :** Cadrer `1.besoin/contexte-et-besoin.md` (pourquoi un générateur et validateur de skills déterministe pour AgentDev).
- [x] **Veille :** Explorer les générateurs de skills (`plugin-dev`, `skills.sh`, linters d'agents) dans `2.veille/veille-technologique.md`.
- [x] **Consignes 3 & 4 :** Initialiser les README de travail dans `3.skill-technique/` et `4.realisation/`.

## Phase 2 : Réalisation & Tests Déterministes (À Réaliser dans `4.realisation/`)
- [ ] **Script de validation :** Tester `validate-skills.cjs` sur des cas valides et des cas invalides (omission de rubrique, YAML invalide, nom avec préfixe `lab-`).
- [ ] **Tests de génération :** Générer un skill exemple (ex: `alpine-components`) avec `skill-creator` et vérifier son score de conformité.
- [ ] **Documentation :** Valider le guide `docs/guide-10-rubriques-anthropic.md` comme référence pédagogique.

## Phase 3 : Résultat Final du Lab (À Réaliser dans `3.skill-technique/`)
- [ ] **Spécification :** Rédiger `spec-skill.md` détaillant les contrats d'interface et le comportement de `skill-creator`.
- [ ] **Validation finale du skill :** Exécuter le validateur déterministe avec 0 erreur :
  ```powershell
  node .agent/skills/skill-creator/scripts/validate-skills.cjs
  ```

## Phase 4 : Soutenance Sprint Formateur (À Compléter dans `5.rapport-et-presentation/`)
- [ ] **Rapport :** Compléter les zones de résultats dans `Lab-Skill-Creator.md`.
- [ ] **Présentation :** Compléter les diapositives et les 3 phrases orateur A1 par slide dans `Presentation-Skill-Creator.md`.
- [ ] **Live Coding sans IA :** Réaliser le sprint et réussir le mini-défi sans IA devant le formateur.

