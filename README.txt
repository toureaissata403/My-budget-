# Mon Budget — version PWA

Cette version peut être installée comme une application sur Android ou iPhone.

## Important
Une PWA doit être servie depuis une adresse HTTPS pour que l'installation et le Service Worker fonctionnent.

## Déploiement gratuit recommandé
1. Crée un dépôt GitHub.
2. Mets les 5 fichiers du dossier dans le dépôt :
   - index.html
   - manifest.json
   - sw.js
   - icon-192.png
   - icon-512.png
3. Active GitHub Pages.
4. Ouvre l'adresse HTTPS fournie sur ton téléphone.
5. Android : menu du navigateur → « Installer l'application » / « Ajouter à l'écran d'accueil ».
6. iPhone : Safari → Partager → « Sur l'écran d'accueil ».

Les données du budget restent stockées localement sur l'appareil via localStorage. Pour les transférer, utilise Exporter JSON.
