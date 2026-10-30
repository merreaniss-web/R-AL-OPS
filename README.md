# REAL OPS V0.3

Prototype web autonome d'environnement d'opérations aériennes pour le projet REAL OPS.

## Nouveautés V0.3
- Trois identités vocales indépendantes : commandant, copilote et personnel cabine.
- Sélection de voix installées sur l'appareil, débit et hauteur par rôle.
- Profil vocal ATC séparé et style radio ralenti.
- Échanges cockpit alternant commandant et copilote.
- Dialogues bilingues français / anglais.
- Scénarios et événements contextuels : turbulences, météo dégradée, retard, changement de piste, passager malade, anomalie technique.
- Briefing équipage, briefing cabine et débriefing.
- Journal horodaté exportable en fichier texte.
- Interface responsive mobile / ordinateur.

## Mise à jour du dépôt GitHub
1. Ouvrir https://github.com/merreaniss-web/R-AL-OPS
2. Ouvrir `index.html`, puis **Edit this file**.
3. Remplacer intégralement le contenu par le fichier `index.html` de cette livraison.
4. Cliquer sur **Commit changes** sur la branche `main`.
5. Mettre également à jour `README.md`.

L'archive ne pousse pas automatiquement les modifications sur GitHub.

## Audio : limite connue
Les profils utilisent `SpeechSynthesis` et les voix présentes sur le terminal. Le choix, la disponibilité, le rendu et le comportement dépendent du navigateur et du système. Il ne s'agit pas de voix IA distantes ni d'enregistrements professionnels. Pour un rendu réellement naturel, il faudra intégrer un moteur vocal dédié ou des voix enregistrées, avec les contraintes réseau, licences, latence et distribution correspondantes.

## Compatibilité simulateur : limite connue
Cette version est un prototype web autonome. Elle ne lit pas les variables de simulation MSFS 2024, ne se connecte pas à SimConnect, ne contrôle pas l'ATC natif et ne transmet pas de communications radio. Les phases sont sélectionnées dans l'interface. Les données, clairances, fréquences et procédures sont fictives : ne pas utiliser en vol réel.

La cible finale MSFS 2024 sur Xbox nécessite une architecture d'intégration et une voie de distribution autorisées et compatibles avec les contraintes Xbox / Marketplace. Une page HTML autonome ne peut pas, à elle seule, remplacer l'ATC intégré au simulateur.
