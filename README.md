# MathsMaster

A static, installable maths practice app for GitHub Pages. No server or build process is required.

## Publish with GitHub Pages

1. Create a new GitHub repository, for example `mathsmaster`.
2. Upload all files and folders from this project to the repository root.
3. Open **Settings > Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`, then save.
6. After deployment, open the GitHub Pages address shown in Settings.

## Install on a phone

### iPhone or iPad

Open the site in Safari, tap Share, then tap **Add to Home Screen**.

### Android

Open the site in Chrome, open the browser menu, then choose **Install app** or **Add to Home screen**.

## Structure

- `index.html`: page structure
- `css/styles.css`: all styling
- `js/app.js`: app, curriculum, quizzes, parent settings and Snake game
- `manifest.json`: installable app metadata
- `sw.js`: offline cache
- `assets/`: phone and browser icons

## Updating offline files

After changing the app, update `CACHE_NAME` in `sw.js`, for example from `mathsmaster-v1` to `mathsmaster-v2`. This ensures installed devices receive the updated files.
