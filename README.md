# Sofra, site de présentation

Vite + React + TypeScript + Tailwind CSS v4.

## Lancer en local

```bash
npm install
npm run dev
```

## Ajouter les images

- Splash screen : `public/images/splash.png`, puis `splashImage` dans `src/data/content.ts`
- Captures du carrousel : `public/images/screens/`, puis `image` sur chaque écran dans `src/data/content.ts`

## Déployer sur Vercel

1. Pousser le dépôt sur GitHub
2. Sur vercel.com : Add New > Project > importer le dépôt
3. Vercel détecte Vite : build `npm run build`, dossier `dist`
# Sofra-site
