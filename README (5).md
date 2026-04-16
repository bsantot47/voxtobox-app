# VoxToBox PWA

Application mobile VoxToBox — Perceptech

## Déploiement sur GitHub Pages

1. Crée un repo GitHub : `voxtobox-app`
2. Upload tous les fichiers de ce dossier
3. Dans Settings → Pages → Source : `main` branch, `/ (root)`
4. Ton app est disponible sur : `https://[ton-username].github.io/voxtobox-app`

## Installation sur téléphone

### iPhone / iPad
1. Ouvre l'URL dans Safari
2. Appuie sur le bouton Partager ↑
3. "Sur l'écran d'accueil"
4. VoxToBox apparaît comme une app

### Android
1. Ouvre l'URL dans Chrome
2. Menu ⋮ → "Ajouter à l'écran d'accueil"
3. VoxToBox apparaît comme une app

## Fichiers

- `index.html` — Application principale
- `manifest.json` — Métadonnées PWA
- `sw.js` — Service Worker (cache offline)
- `icon.svg` — Icône de l'app

## Note importante

L'app appelle ton Space HuggingFace `bgman47/voxtobox`.
Si l'URL du Space change, modifie `HF_SPACE` dans index.html.
