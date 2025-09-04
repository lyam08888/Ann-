# Application de Publication d'Offres d'Emploi avec IA

## Fonctionnalités améliorées

### 🚀 Nouvelles fonctionnalités ajoutées :

1. **Intégration API Gemini** 
   - Auto-remplissage intelligent des formulaires
   - Basé sur l'intitulé du poste saisi

2. **Configuration sécurisée**
   - Sauvegarde locale de la clé API Gemini
   - Interface utilisateur intuitive pour la gestion des clés

3. **Champs supplémentaires**
   - Description du poste (auto-remplie par l'IA)
   - Compétences requises (auto-remplies par l'IA)
   - Type de contrat
   - Expérience minimale
   - Fourchette salariale

## 🔧 Comment utiliser l'auto-remplissage IA :

### Étape 1: Configuration de la clé API
1. Allez sur [Google AI Studio](https://aistudio.google.com/app/apikey)
2. Créez une clé API Gemini gratuite
3. Dans l'application, collez votre clé dans le champ "Clé API Gemini"
4. Cliquez sur "Sauvegarder" (la clé sera stockée localement dans votre navigateur)

### Étape 2: Utilisation de l'auto-remplissage
1. Saisissez l'intitulé du poste (ex: "Développeur Full Stack H/F")
2. Cliquez sur le bouton "Auto-remplir avec IA" 🧠
3. L'IA analysera l'intitulé et remplira automatiquement :
   - Le secteur d'activité approprié
   - Le métier correspondant
   - Une description détaillée du poste
   - Les compétences requises
   - Le type de contrat suggéré
   - L'expérience minimale
   - Une fourchette salariale estimée

### Étape 3: Validation et ajustement
- Vérifiez les informations auto-remplies
- Ajustez si nécessaire
- Complétez les autres champs du formulaire
- Soumettez votre offre

## 🛠️ Fonctionnalités techniques :

- **API utilisée** : Google Gemini 1.5 Flash
- **Stockage local** : Les clés API sont sauvegardées dans le localStorage du navigateur
- **Interface responsive** : Compatible avec tous les appareils
- **Gestion d'erreurs** : Messages d'erreur explicites et gestion des cas d'échec
- **Sécurité** : Masquage de la clé API par défaut avec option de visibilité

## 🎯 Avantages :

1. **Gain de temps** : Plus besoin de remplir manuellement tous les champs
2. **Cohérence** : L'IA assure une cohérence entre l'intitulé et les informations
3. **Inspiration** : Obtenez des idées pour la description et les compétences
4. **Précision** : Mapping automatique vers les bonnes catégories du formulaire

## 🔒 Sécurité et Confidentialité :

- La clé API est stockée uniquement dans votre navigateur
- Aucune donnée n'est envoyée vers des serveurs tiers (excepté Google Gemini pour le traitement)
- Vous gardez le contrôle total de vos données

## 📝 Exemples d'intitulés compatibles :

- "Développeur Full Stack H/F"
- "Chef de Projet Marketing Digital H/F"
- "Comptable Senior H/F"
- "Ingénieur DevOps H/F"
- "Responsable Ressources Humaines H/F"
- "Commercial BtoB H/F"

L'IA est capable de traiter une grande variété d'intitulés de postes et de proposer des informations pertinentes pour chacun.
