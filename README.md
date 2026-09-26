# Coding dojo yeeso

Slides des coding dojos de l'association **yeeso**, construites avec [Slidev](https://sli.dev) et le thème [`slidev-theme-yeeso`](https://github.com/Yeeso-fr/slidev-theme-yeeso).

L'atelier reprend le format « Redécouvrir la coopération : atelier de mob programming » : un kata de code, choisi ensemble en début de séance.

## Utilisation

Node.js ≥ 22.12 requis.

```bash
npm install
npm run dev     # présentation sur http://localhost:3030
npm run build   # version web dans dist/
npm run export  # export PDF
```

Le déploiement sur GitHub Pages se fait à chaque push sur `main` (`.github/workflows/deploy.yml`).
