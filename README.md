# Qabs Design (web)

Éditeur vectoriel léger (« Illustrator light ») pensé pour iPhone, en un seul fichier HTML.

**Ouvrir :** https://magikalus26.github.io/qabs-design/ — sur iPhone, Safari → Partager → « Sur l'écran d'accueil » pour l'installer (fonctionne hors ligne).

- `index.html` : l'application complète (HTML/CSS/JS en ligne, sans dépendance)
- `sw.js` : cache hors ligne (réseau d'abord pour la page) — incrémenter `VERSION` à chaque publication
- `manifest.webmanifest`, `icons/` : PWA

Formats : dessins enregistrés en `.qabs` (JSON, format 2 ; les fichiers format 1 de QabsCore sont migrés à l'ouverture), export SVG / PNG (fond transparent possible).

**v2** : édition de points (ajout, suppression, angle ⇄ lisse, reprise d'un tracé ouvert), redimensionnement des objets tournés, rotation / rayon / tirets / limite d'angle dans l'inspecteur, outil Texte, dégradés linéaires et radiaux, opérations booléennes (union, soustraction, intersection, exclusion).

**v3** : crayon à main levée (lissage + ajustement de courbes de Bézier), outils Ligne / Polygone / Étoile (paramètres modifiables), aligner et répartir, magnétisme intelligent avec repères, nuancier du document et pipette, poignées de dégradé sur le canevas, booléens reconstruits en courbes. Barre d'outils groupée (appui long ou second toucher). Format `.qabs` v3 (migration automatique des v1/v2).
