# 🥊 Chrono Box

Minuteur de boxe en une seule page (`index.html`, aucune dépendance).

- Durée des rounds, repos entre rounds, nombre de rounds, nombre de cycles, repos entre cycles
- Préparation avant le 1er round, clap d'alerte avant la fin du round
- Réglage à la seconde (saisie directe ou boutons −/+, maintenir pour défiler)
- Cloche, bips de décompte, annonce vocale optionnelle
- Pause, phase précédente/suivante, écran maintenu allumé
- Raccourcis clavier : Espace (pause), ← / → (phase), Échap (arrêt)
- Réglages mémorisés dans le navigateur

## Mise en ligne sur GitHub Pages

1. Créer un dépôt vide sur https://github.com/new (`timer`), sans README.
2. Dans ce dossier :
   ```bash
   git remote add origin https://github.com/kelianboutreux/timer.git
   git push -u origin main
   ```
3. Sur GitHub : **Settings → Pages → Source : Deploy from a branch → `main` / `/ (root)`** → Save.
4. Le site est disponible après ~1 min sur `https://kelianboutreux.github.io/timer/`.
