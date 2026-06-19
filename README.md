# Manos de Confianza

Renovation and maintenance for property owners in Spain. Part of the Key4Spain network.

Single-page site (`index.html`). No build step. Plain HTML, CSS and JavaScript, with a Three.js background loaded from CDN.

## Deploy on Hostinger via Git
1. Push this repository to GitHub.
2. In Hostinger hPanel open Advanced, then GIT.
3. Create a new repository: paste the GitHub repository URL, set branch `main`, install path `public_html`.
4. Deploy. For updates, push to GitHub and click Deploy (or set up the auto-deploy webhook).

The domain `manosdeconfianza.es` should point to this hosting.

## Note on images
The before and after photos currently load from a content delivery network. For full control they can later be saved into an `assets/` folder and referenced locally.
