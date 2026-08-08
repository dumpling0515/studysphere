# Studysphere — Landing Page

A single-file static site (`index.html`) — no build step, no dependencies to install.

## Preview it locally
Just double-click `index.html`, or open it in a browser.

## Put it on GitHub (with free hosting via GitHub Pages)

1. **Create a repo**
   - Go to [github.com/new](https://github.com/new)
   - Name it whatever you like (e.g. `meridian-academy`)
   - Keep it Public if you want free GitHub Pages hosting
   - Click **Create repository**

2. **Upload the file**
   - On your new repo's page, click **"uploading an existing file"**
   - Drag in `index.html` (and this `README.md` if you want)
   - Click **Commit changes**

3. **Turn on GitHub Pages**
   - In your repo, go to **Settings → Pages**
   - Under "Build and deployment" → Source, choose **Deploy from a branch**
   - Branch: `main`, folder: `/ (root)` → **Save**
   - Wait ~1 minute, then your site is live at:
     `https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/`

## Customizing
Everything — copy, colors, curriculum modules, mentor bios — lives directly in `index.html`:
- Colors are CSS variables at the top of the `<style>` block (`--brass`, `--ink-black`, etc.)
- The 6 curriculum modules are in the `.modules` section — copy/paste a `.module` block to add more
- Mentor cards are in the `.mentors` section

No build tools, no npm install — edit the HTML and refresh.
