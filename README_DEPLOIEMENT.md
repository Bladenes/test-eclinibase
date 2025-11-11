
# Déploiement — ECLINIBASE Copilote (Site 2 niveaux)

Ce dossier contient un site statique à **2 niveaux maximum** pour ingestion par **Copilot Agent 365**.

## Structure
- `index.html` (Niveau 1)
- `contexte-eclinibase.html` (Niveau 2 — votre contenu Markdown converti)
- `robots.txt` (ouvert à l’indexation)
- `sitemap.xml` (remplacez `BASE_URL` par l’URL finale)
  
## Publication (GitHub Pages)
1. Créez un dépôt GitHub (public).
2. Glissez ces fichiers à la racine.
3. `Settings` → `Pages` → `Branch: main` (`/root`), **Save**.
4. Remplacez `BASE_URL` dans `sitemap.xml` par l’URL GitHub Pages (ex. `https://<user>.github.io/<repo>`).

## Publication (Netlify/Vercel/Cloudflare Pages)
- Déployez ce dossier tel quel. L’URL sera du type `https://…/`.
- Mettez à jour `sitemap.xml` avec l’URL fournie.

## Conseils Copilot Agent 365
- Donnez comme point d’entrée `index.html` **ou** `contexte-eclinibase.html`.
- Évitez d’ajouter d’autres sous-pages pour garder une profondeur ≤ 2.
- Pas d’authentification, pas d’assets bloquants (JS obligatoire), pas de redirections.

