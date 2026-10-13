# Budget CH

Application PWA de budget personnel en français, en CHF, sans compte ni serveur. Les données sont conservées dans le stockage local du navigateur sur chaque appareil.

## Installation gratuite

1. Créer un dépôt GitHub public (ne pas y déposer de données financières ou de sauvegardes JSON).
2. Mettre les fichiers `index.html`, `app.js`, `sw.js`, `manifest.webmanifest` et `icon.svg` à la racine du dépôt.
3. Dans GitHub : Settings > Pages > Build and deployment > Deploy from a branch > `main` / `(root)` > Save.
4. Ouvrir l'URL HTTPS publiée sur iPhone avec Safari, puis Partager > Sur l'écran d'accueil > Ajouter. Sur Android, ouvrir avec Chrome et choisir Installer / Ajouter à l'écran d'accueil.
5. Tester les ajouts et l'export JSON. Exporter régulièrement une sauvegarde et la garder en lieu sûr.

Aucun compte bancaire n'est connecté. Les données ne se synchronisent pas entre appareils. Effacer les données du navigateur ou désinstaller l'application peut supprimer les données locales. L'application fonctionne hors ligne après un premier chargement réussi sur HTTPS. GitHub Pages exige un dépôt public sur le plan gratuit pour ce cas d'usage ; seul le code est public, pas les données enregistrées localement.


Mise à jour : catégories Impôts, 3e pilier, Restaurant, Voyage. Conserver la clé de stockage budget-ch-data-v1 pour préserver les données.
