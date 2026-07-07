# How to Put the Vatrian Constitution Online for Free

You have two good free options. Use Netlify if you want the fastest drag-and-drop upload. Use GitHub Pages if you want the best long-term setup for future edits.

## Option 1: Fastest Upload with Netlify

1. Go to `https://app.netlify.com/drop`.
2. Sign in or make a free Netlify account.
3. Open this folder on your computer: `outputs/vatria-constitution-upload`.
4. Drag the whole `vatria-constitution-upload` folder onto the Netlify upload page.
5. Wait for Netlify to finish uploading.
6. Netlify will give you a public link ending in `.netlify.app`.
7. Open the link once to make sure it works.
8. Post that link in your Discord server.

To update the site later, edit the files, rebuild the site, then drag the updated folder into the same Netlify site's Deploys page.

## Option 2: Better Long-Term Setup with GitHub Pages

1. Make a free GitHub account at `https://github.com`.
2. Click **New repository**.
3. Name it something like `vatria-constitution`.
4. Make the repository **Public**.
5. Upload these files from `outputs/vatria-constitution-upload`:
   - `index.html`
   - `.nojekyll`
   - `PUBLISHING_GUIDE.md`
   - the `assets` folder
6. Open the repository's **Settings** tab.
7. Click **Pages** in the sidebar.
8. Under **Build and deployment**, choose **Deploy from a branch**.
9. Choose the `main` branch and `/root`, then save.
10. Wait a few minutes.
11. GitHub will show a public link. It usually looks like:

`https://YOUR-GITHUB-NAME.github.io/vatria-constitution/`

12. Open the link once to check it.
13. Post that link in your Discord server.

## What Your Friends Need

Nothing extra. Once the site is public, Discord members just click the link and it opens in their browser.
