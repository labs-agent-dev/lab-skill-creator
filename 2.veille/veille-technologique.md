# Veille Technologique : Outillage de Création et de Validation des Skills IA

## 1. État de l'Art des Outils d'Ingénierie de Compétences
| Référence | Type | Apport Principal | Limite pour notre Stack |
| :--- | :--- | :--- | :--- |
| **`plugin-dev`** *(Anthropic Official)* | Méta-Plugin de scaffolding | Modèles officiels de plugins et skills pour Claude Code. | Conçu pour l'écosystème Node/CLI natif de Claude, pas orienté Laravel/Alpine. |
| **`skills.sh CLI`** *(Vercel Labs)* | Gestionnaire de paquets (`npx skills`) | Découverte, installation et mise à jour de skills. | Se limite au téléchargement sans contrôle strict des 10 rubriques normées. |
| **Linters Markdown & Schémas JSON** | Outils de validation statique | Contrôle déterministe syntaxique rapide. | Nécessitent une adaptation sur mesure pour les titres de rubriques spécifiques. |

## 2. Analyse Critique du Motif `plugin-dev` d'Anthropic
Le plugin officiel `plugin-dev` montre que la création de compétences IA ne doit pas être laissée au hasard :
- L'utilisation de **gabarits paramétrables** évite l'oubli des contraintes de sécurité et des checklists.
- L'enrichissement avec un **bloc inspiration** garantit la traçabilité des patterns adoptés.
- La validation automatisée en pré-commit ou par script Node.js assure que 100% des skills déployés dans l'agent sont exécutables sans crash.

## 3. Choix Technique pour notre Lab
Pour équiper `AgentDev` de manière robuste :
1. **Un skill outillé dédié :** `skill-creator`, activable à la demande via `/skill-creator`.
2. **Un script de validation déterministe léger :** `validate-skills.cjs` en JavaScript vanilla exécutable sans dépendance npm lourde.
3. **Une documentation colocalisée :** `docs/guide-10-rubriques-anthropic.md` intégrée directement au skill.

