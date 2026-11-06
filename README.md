# Lab Skill Creator : Outillage Déterministe & Création Automatisée des Skills IA

## 1. Contexte & Règle Cardinale
- **Agent Final (`AgentDev`) :** L'agent unique chargé de développer 100 % du code du Projet Fil Rouge selon notre architecture logicielle et nos skills dédiés.
- **Projet Technique (Live Coding sans IA) :** Compris et maîtrisé par l'apprenant, évalué en direct devant le formateur sans IA ni prompt.
- **Objectif du Lab :** Concevoir, implémenter et valider le méta-skill technique **`skill-creator`**, outillé d'un script de validation déterministe (`validate-skills.cjs`) et du guide des 10 rubriques d'Anthropic, pour générer automatiquement des compétences fiables et conformes pour `AgentDev`.

## 2. Architecture des Compétences de ce Lab
| Skill | Type | Déclencheur | Rôle |
| :--- | :--- | :--- | :--- |
| **`lab-dev`** | Méta-Méthodologie | `/lab-dev` | Chef d'orchestre : structure les 5 sous-dossiers, valide le workflow et audite la soutenance. |
| **`skill-creator`** | Technique (Résultat Final) | `/skill-creator` | Conçoit, génère selon les 10 rubriques et valide de façon déterministe tout skill IA. |

## 3. Validation Rapide des Compétences
```powershell
node .agent/skills/skill-creator/scripts/validate-skills.cjs
```

## 4. Références Clés
- Guide interne des 10 rubriques : `.agent/skills/skill-creator/docs/guide-10-rubriques-anthropic.md`
- Dépôt officiel Anthropic : https://github.com/anthropics/claude-plugins-official
- Catalogue Agent Skills : https://www.skills.sh/

