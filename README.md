# REAL OPS CORE — Prototype V0.1

Prototype web de démonstration pour le projet REAL OPS.

## Fonctionnalités
- Phases de vol simulées : parking, roulage, décollage, croisière, approche, atterrissage/parking.
- Dialogues de démonstration ATC, équipage et personnel cabine.
- Sélection français / anglais.
- Choix du type d'avion et champs indicatif/aéroport.
- Checklist indicative et panneau d'état.

## Limites importantes
Cette version est une maquette autonome. Elle ne se connecte pas à Microsoft Flight Simulator 2024, ne lit aucune donnée SimVars/SimConnect, ne transmet aucune fréquence radio et ne remplace pas l'ATC natif. Les voix naturelles ne sont pas encore intégrées : les dialogues sont affichés en texte.

Les fréquences et autorisations affichées sont fictives et ne doivent jamais être utilisées pour la navigation réelle. Les procédures sont illustratives et ne remplacent pas les checklists approuvées d'un exploitant.

## Tester
Ouvrir `index.html` dans un navigateur moderne.

## Publier avec GitHub Pages depuis un iPhone
1. Créer un dépôt GitHub nommé `real-ops-core`.
2. Ajouter `index.html` et `README.md` à la racine du dépôt.
3. Dans le dépôt, ouvrir **Settings → Pages**.
4. Dans **Build and deployment**, choisir **Deploy from a branch**.
5. Choisir la branche `main` et le dossier `/ (root)`, puis enregistrer.
6. GitHub affichera l'adresse du site après publication.

## Prochaine étape technique
Concevoir un adaptateur de données de vol et vérifier, sur un environnement Windows avec le SDK MSFS 2024, les possibilités réelles d'intégration ATC/audio et les contraintes Marketplace Xbox.
