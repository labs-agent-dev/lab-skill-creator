# Contexte et Besoin : Outillage Déterministe & Création Automatisée des Skills

## 1. Contexte : Projet Fil Rouge vs Projet Technique
- **Projet Fil Rouge (100 % IA) :** Développé intégralement par l'agent **`AgentDev`**. Pour que cet agent écrive un code de qualité industrielle, il a besoin de compétences modulaires fiables, structurées et sans hallucination.
- **Projet Technique (Prototype en Live Coding) :** L'apprenant doit comprendre la mécanique interne d'un skill (YAML, 10 rubriques, validation statique) et être capable d'expliquer ou débugger un skill devant le formateur **sans IA et sans prompt**.

## 2. Problématique
La rédaction manuelle de fichiers `SKILL.md` présente des risques majeurs :
1. **Omissions de rubriques clés :** oubli des limites de déclenchement ou de la checklist binaire.
2. **Violations de nommage :** utilisation erronée de préfixes `lab-*` sur des skills techniques.
3. **Erreurs de syntaxe YAML :** blocs `inspiration` incomplets ou descriptions subjectives à la 1ère personne.
4. **Perte de temps :** réinvention permanente de la structure au détriment de l'expertise métier.

## 3. Besoin Concret du Lab
1. **Développer le skill technique `skill-creator` :** Un générateur assisté capable d'échafauder un `SKILL.md` rigoureusement conforme en quelques secondes.
2. **Fournir un outillage de contrôle déterministe (`validate-skills.cjs`) :** Un script Node.js qui vérifie statiquement la conformité (YAML, présence des 10 rubriques exactes, nommage).
3. **Formaliser la documentation de référence :** Rédiger `guide-10-rubriques-anthropic.md` pour expliquer le rôle exact de chaque rubrique aux apprenants et formateurs.

