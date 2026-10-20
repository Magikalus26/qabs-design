# Qabs Design (web)

Éditeur vectoriel léger (« Illustrator light ») pensé pour iPhone, en un seul fichier HTML.

**Ouvrir :** https://magikalus26.github.io/qabs-design/ — sur iPhone, Safari → Partager → « Sur l'écran d'accueil » pour l'installer (fonctionne hors ligne).

- `index.html` : l'application complète (HTML/CSS/JS en ligne, sans dépendance)
- `sw.js` : cache hors ligne (réseau d'abord pour la page) — incrémenter `VERSION` à chaque publication
- `manifest.webmanifest`, `icons/` : PWA

Formats : dessins enregistrés en `.qabs` (JSON compatible QabsCore), export SVG / PNG.
