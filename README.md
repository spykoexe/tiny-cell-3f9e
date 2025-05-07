# Kit de Démarrage Astro : Blog

![Aperçu du modèle Astro](https://github.com/withastro/astro/assets/2244813/ff10799f-a816-4703-b967-c78997e8323d)

<!-- dash-content-start -->

Créez un blog avec Astro et déployez-le sur Cloudflare Workers en tant que [site web statique](https://developers.cloudflare.com/workers/static-assets/).

Fonctionnalités :

- ✅ Style minimal (personnalisez-le à votre goût !)
- ✅ Performance 100/100 sur Lighthouse
- ✅ Optimisé pour le SEO avec des URLs canoniques et des données OpenGraph
- ✅ Support du sitemap
- ✅ Support du flux RSS
- ✅ Support du Markdown & MDX

<!-- dash-content-end -->
## Bien démarrer

En dehors de ce dépôt, vous pouvez démarrer un nouveau projet avec ce modèle en utilisant [C3](https://developers.cloudflare.com/pages/get-started/c3/) (le CLI `create-cloudflare`) :

```bash
npm create cloudflare@latest -- --template=cloudflare/templates/tiny-cell-3f9e

---

### 🧩 Bloc 3 – Structure du projet

```markdown
## 🚀 Structure du projet

Astro recherche les fichiers `.astro` ou `.md` dans le répertoire `src/pages/`. Chaque fichier devient une route basée sur son nom.

Il n’y a rien de spécial à propos de `src/components/`, mais c’est l’endroit où nous aimons placer les composants Astro/React/Vue/Svelte/Preact.

Le répertoire `src/content/` contient des "collections" de documents Markdown et MDX associés. Utilisez `getCollection()` pour récupérer les articles de `src/content/blog/`, et vérifiez le typage de vos métadonnées (`frontmatter`) à l’aide d’un schéma optionnel. Voir la documentation des [Collections de contenu d’Astro](https://docs.astro.build/en/guides/content-collections/) pour en savoir plus.

Les fichiers statiques, comme les images, peuvent être placés dans le répertoire `public/`.
## 🧞 Commandes

Toutes les commandes sont à exécuter depuis la racine du projet, dans un terminal :

| Commande                   | Action                                               |
| :------------------------ | :--------------------------------------------------- |
| `npm install`             | Installe les dépendances                            |
| `npm run dev`             | Démarre le serveur de développement à `localhost:4321` |
| `npm run build`           | Génère le site de production dans `./dist/`          |
| `npm run preview`         | Prévisualise la version production localement        |
| `npm run astro ...`       | Lance des commandes CLI comme `astro add`, `astro check` |
| `npm run astro -- --help` | Affiche l’aide de la CLI Astro                      |
| `npm run deploy`          | Déploie le site de production sur Cloudflare         |
## 👀 Envie d’en savoir plus ?

Consultez [notre documentation](https://docs.astro.build) ou rejoignez notre [serveur Discord](https://astro.build/chat).
