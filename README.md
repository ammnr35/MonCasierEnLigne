# Études — Mon espace de travail

Web app autonome en HTML, CSS et JavaScript. Aucune dépendance externe ni compilation nécessaire.

## Fonctionnalités
- Agenda mensuel : devoirs, évaluations, événements, dates, heures, notes et types personnalisables.
- Dossiers : création de dossiers et sous-dossiers, import de fichiers, téléchargement, renommage et suppression.
- Révisions : synthèses enregistrées et paquets de flashcards avec mode entraînement.
- Paramètres : couleur d’accent, affichage clair/sombre/automatique, catégories personnalisées, export et import d’une sauvegarde complète.
- Sauvegarde locale : IndexedDB pour les données et les pièces jointes.
- Transfert d’appareil : export d’un fichier JSON qui inclut les pièces jointes, puis import de ce fichier sur l’autre appareil.

## Hébergement avec GitHub Pages
1. Crée un dépôt GitHub, par exemple `mon-espace-etudes`.
2. Ajoute `index.html` à la racine du dépôt (le README est facultatif).
3. Dans **Settings → Pages**, choisis la branche principale et le dossier `/ (root)` puis enregistre.
4. Ouvre l’adresse fournie par GitHub Pages.

Le site doit être servi via HTTPS (GitHub Pages le fait automatiquement), ce qui permet aux navigateurs modernes d’utiliser IndexedDB de façon fiable.

## Sauvegarde et limites
Les données restent dans le stockage du navigateur sur l’appareil actuel. Elles ne sont pas synchronisées automatiquement entre appareils. Pour transférer ton espace, ouvre **Réglages → Exporter toutes mes données**, puis importe le JSON sur l’autre appareil via **Importer une sauvegarde**. Le fichier JSON peut devenir volumineux si tu y ajoutes de gros documents.

Comme pour toute application web locale, garde plusieurs copies de tes sauvegardes. Effacer les données du site ou le stockage du navigateur peut supprimer les données locales.
