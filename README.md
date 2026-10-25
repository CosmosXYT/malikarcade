# Face Arcade

A responsive, zero-dependency HTML/CSS/JavaScript arcade with four playable games: Flappy Face, Face Dash, Heart Catcher, and Face Match.

## Deploy on GitHub Pages
1. Upload `index.html`, `style.css`, `app.js`, and the `assets` folder to the root of a GitHub repository.
2. Go to repository **Settings → Pages → Build and deployment**.
3. Select **Deploy from a branch**, branch `main`, folder `/ (root)`, then save.
4. Open the GitHub Pages URL once deployment completes.

GitHub Pages hosts static sites. No Worker, build system, Node.js, or backend is needed. If you meant Cloudflare Workers, you can serve these same static files using Cloudflare's static-assets configuration.

## Replace the face
Replace `assets/face.png` with a transparent PNG of the same name. This is the only required image. The arcade automatically uses it in the logo, hero, and game characters. Keep the image square-ish with transparent padding for the best result.

## Controls
- Flappy Face: tap or press Space to flap.
- Face Dash: drag left/right or use arrow keys to avoid bombs.
- Heart Catcher: drag left/right or use arrow keys; collect hearts and stars, avoid bombs.
- Face Match: tap cards to reveal pairs.
- P pauses arcade canvas games. Sound can be toggled. Best scores save locally on each device via localStorage.

## Notes
Works on mobile Safari and modern desktop browsers, including iPhone 13 and newer. No analytics or external dependencies. GitHub Pages is public by default: only publish the face photo with the subject's permission.
