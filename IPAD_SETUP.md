# COMPASS GitHub Edition — iPad-Only Upload Guide

### Before you begin

You need an iPad, Safari, the Files app, and a GitHub account. You **do not** need Python, Docker, Render, a Mac, a Windows computer, or a terminal.

**Security note:** This publicly hosted edition is only for fictional demonstrations. GitHub Pages cannot provide secure application accounts or a shared personnel database. Do not enter real Soldier data or nonpublic training plans.

### A. Download and extract

1. Download `COMPASS_GitHub_Pages_iPad_Kit.zip` from ChatGPT.
2. Open the **Files** app and locate it in Downloads.
3. Tap the ZIP once to extract a folder named `COMPASS_GitHub_Pages_iPad_Kit`.
4. Open the extracted folder. You should see `index.html`, three PNG icons, `manifest.webmanifest`, `compass-icon.svg`, and instructions.

### B. Create your GitHub repository

1. In Safari, open https://github.com/new and log in.
2. Repository name: `compass-demo` (or choose another name).
3. Visibility: **Public** for GitHub Free GitHub Pages. Everything in this repository and the resulting site should be fictional and safe for public disclosure.
4. Tap **Create repository**. Optionally initialize with a README; you will upload the included README anyway.

### C. Upload the site files

1. From your repository page, tap **Add file → Upload files**.
2. Tap **choose your files**, open **Browse**, and select the files in the extracted folder.
3. **Do not upload the ZIP itself.** GitHub Pages needs an actual `index.html` file at the root of the repository.
4. If iPad Safari only allows one file at a time, start with `index.html`, commit, and repeat for the icon and manifest files. You can upload in batches too.
5. Enter commit message `Add COMPASS fictional demo website` and commit directly to `main`.
6. Return to the repository Code tab: **`index.html` must appear in the top-level file list**, not inside a second folder.

### D. Publish with GitHub Pages

1. Tap **Settings** (if the tab is hidden, find it from the repository menu or request the desktop website).
2. In the left sidebar, find **Pages**.
3. Under **Build and deployment** set **Source** to `Deploy from a branch`.
4. Choose branch **`main`** and folder **`/(root)`**; tap **Save**.
5. Return to **Settings → Pages** after GitHub finishes deploying and open **Visit site**, or use the published URL shown there.
6. Your URL will resemble `https://YOUR-USERNAME.github.io/compass-demo/` (replace both placeholders with your actual account and repository names).

### E. Add it to your iPad Home Screen

1. Visit your *published site* in **Safari**, not the GitHub source file page.
2. Tap **Share** (square with arrow).
3. Choose **Add to Home Screen**; name it `COMPASS`.
4. Tap **Add**. The shortcut opens your hosted demonstration in an app-style window on supported iPadOS versions.

### F. Test the working demonstration

1. Verify the title includes **PUBLIC DEMONSTRATION**.
2. Tap **LRTC** to review fictional events and aggregate Troops-to-Task estimates.
3. Tap **Matrix** to review fictional person-by-person assignments and conflict warnings.
4. Tap **Tasks** to see example suspenses and follow event links.
5. Tap **Docs** to see example administrative writing drafts.
6. Create a clearly fictional test task, refresh Safari, and confirm it still appears **on that same device and browser**.
7. Open **About this demo** to reset the fictional records whenever necessary.

### Troubleshooting

- **404 or README page instead of COMPASS:** `index.html` is not at the root, Pages is not set to `main` + `/(root)`, or publishing is not finished.
- **Blank page:** make sure the `index.html` file uploaded completely, and reload the page. Check that you did not upload just the ZIP.
- **Can't see Settings / Upload:** in Safari use **aA → Request Desktop Website** and rotate your iPad to landscape.
- **Changes missing on another device:** expected. There is no cloud database in GitHub Pages; browser storage is device-specific.
- **Changes disappear after Safari data is cleared:** expected. This is browser-local demonstration storage, not a backup.
- **GitHub repo marked private:** with GitHub Free, Pages publishing requires a public repository. Even with plans supporting private source repositories, published sites may still be publicly accessible.
- **Published website not accessible on a government computer:** ask IT to approve access; do not bypass web filtering or security blocks.
- **You need true multiuser accounts and shared database:** use COMPASS 4.1 with a separately hosted backend and an authorized information environment. GitHub Pages alone cannot do it.

Documentation: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
