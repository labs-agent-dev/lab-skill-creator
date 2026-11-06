# Rapport de Lab : Outillage Déterministe & Création Automatisée des Skills

> **Consigne à l'Apprenant :** Ce document est le rapport officiel de votre lab. Complétez les sections annotées `[À compléter]` à partir de vos expérimentations réelles dans `4.realisation/` et du skill finalisé dans `3.skill-technique/`.

---

## 1. Contexte & Règle Cardinale (Cadré)
- **Agent Final (`AgentDev`) :** L'agent unique chargé de développer 100 % du code du Projet Fil Rouge selon notre architecture logicielle et nos skills dédiés.
- **Projet Technique (Prototype en Live Coding) :** Compris par l'apprenant, évalué lors du sprint en direct devant le formateur **sans IA et sans prompt**.
- **Objectif du Lab :** Concevoir le méta-skill technique `skill-creator` et outiller notre chaîne de fabrication avec le validateur déterministe `validate-skills.cjs`.

## 2. Architecture & Normalisation
- **Standard Retenu :** Format Anthropic en 10 rubriques normées.
- **Règles Inviolables Actées :**
  - Pas de préfixe `lab-*` pour les compétences techniques (réservé aux dossiers de labs).
  - Bloc YAML `inspiration` obligatoire pour la traçabilité.
  - Colocalisation d'un guide pédagogique `docs/guide-10-rubriques-anthropic.md`.

## 3. Réalisation Pratique (Résultats des Tests)
- **Test de Validation Déterministe :**
  - *Cas d'erreur testés :* [À compléter : Décrire les erreurs volontairement injectées et détectées par validate-skills.cjs]
  - *Résultat obtenu :* [À compléter : Confirmer la détection des non-conformités]
- **Génération Automatisée :**
  - *Skill testé :* [À compléter : Nom du skill généré pour tester l'outil, ex: alpine-components]
  - *Conformité :* [À compléter : Résultat du script validate-skills.cjs sur le skill généré]

## 4. Préparation de la Démonstration en Sprint (5 min sans IA)
1. Présentation de l'arborescence des compétences sous `.agent/skills/`.
2. Démonstration de l'exécution du validateur `validate-skills.cjs` en direct dans le terminal.
3. [À compléter : Anticiper le mini-défi de code du formateur à réaliser en live coding direct sans IA ni prompt].

