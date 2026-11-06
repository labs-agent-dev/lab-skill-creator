# Travail à Réaliser : 4. Réalisation & Expérimentation

Ce dossier accueille les tests concrets d'outillage, les bancs d'essai de validation et les expérimentations de génération de skills.

---

## 🎯 Objectif Technique
Valider empiriquement le bon fonctionnement du générateur et du validateur `skill-creator` sur des cas de test typiques.

## 📋 Travail Concret à Réaliser par l'Apprenant
1. **Banc d'Essai de Validation (Test Déterministe) :**
   - Tester le script `validate-skills.cjs` en injectant volontairement des erreurs :
     - Test A : Un skill avec un préfixe interdit `lab-*`.
     - Test B : Un skill avec une rubrique manquante parmi les 10.
     - Test C : Un skill sans bloc `inspiration` dans le YAML.
   - Constater que le validateur détecte et bloque ces anomalies.
2. **Génération Réelle d'un Skill Modèle :**
   - Utiliser `skill-creator` pour générer un skill technique d'exemple (ex: `alpine-components` ou `preline-ui`).
   - Vérifier que le skill généré passe le validateur avec 0 erreur.
3. **Consigner les Résultats :**
   - Consigner les logs d'exécution et les temps de validation dans ce dossier.

