# test-apk

Petite application Flutter de test. À chaque dépôt de code sur `main`,
GitHub Actions fabrique automatiquement :

- un **APK Android** (`application-android-apk`) à installer sur un téléphone ;
- une **application Windows** (`application-windows`) contenant le `.exe`.

## Récupérer les fichiers

1. Onglet **Actions** du projet.
2. Ouvrir la dernière exécution « Fabriquer l'APK et le .exe » (coche verte).
3. En bas, section **Artifacts** : télécharger le fichier voulu (il arrive en `.zip`).

L'APK est signé avec une clé de test : il s'installe sur un téléphone
(autoriser les « sources inconnues »), mais il n'est pas prêt pour le Play Store.
