# REAL OPS CORE 0.2

## Nouveautés
- Phases de vol sélectionnables.
- Dialogues ATC, cockpit et cabine en français et anglais.
- Lecture vocale via la synthèse vocale du navigateur (`SpeechSynthesis`), si disponible.
- Événements scénarisés : turbulences, météo, retard, changement de piste, passager malade et anomalie technique.
- Interface adaptée au mobile.

## Mise à jour du dépôt GitHub existant
1. Ouvrir https://github.com/merreaniss-web/R-AL-OPS
2. Ouvrir `index.html`, puis le crayon **Edit this file**.
3. Remplacer tout le contenu par le nouveau fichier `index.html` de cette archive.
4. Faire **Commit changes** sur `main`.
5. Refaire la même opération pour `README.md`.

Cette archive ne pousse pas automatiquement les changements vers GitHub.

## Limites
Prototype autonome : aucune connexion à MSFS 2024, SimConnect ou SimVars. Il ne contrôle pas l'ATC natif et ne transmet pas de communications radio. La voix utilise les voix disponibles dans le navigateur et n'est pas un moteur IA vocal dédié. Dialogues, procédures et éléments de trafic sont fictifs et ne doivent pas être utilisés pour la navigation réelle.

L'intégration Xbox nécessitera un environnement Windows avec le SDK MSFS 2024, des tests techniques et une validation de distribution.
