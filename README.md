# COMPASS — GitHub Pages Demonstration

**A mobile-friendly, self-contained static website based on the COMPASS 3.2 Stryker Company prototype.** All personnel, training events, locations and tasks are fictional.

## What works

- Company overview and the existing demonstration roster, equipment, training, readiness and MTOE pages.
- Training-event creation, editing and rolling 12-week schedule.
- Long-Range Training Calendar (3/6/9/12-month views) with estimated Troops-to-Task allocations.
- Person-by-person weekly Troops-to-Task matrix with linked tasks/events and scheduling conflict flags.
- Task/suspense creation and updates, linked to training events or documents.
- Administrative document drafts, edit histories and plain-text exports.
- Responsive mobile navigation and optional iPad Home Screen icon.
- **Browser-local demo edits**: fictional changes save to localStorage and survive refreshes on the **same device and browser**. Reset from the "About this demo" panel.

## What does NOT work

- No real account login, password protection, access enforcement, MFA or identity verification. The role selector is a UI preview only.
- No database, server, shared storage, live updates, remote synchronization, notifications or multiuser collaboration.
- Data entered on one iPad does **not** appear on another device. Clearing Safari website data or using private browsing can erase demo edits.
- Not approved for real Army usage. Do not enter real Soldier names, PII, medical details, CUI, classified content, real tasking, operational schedules, or nonpublic locations.

**GitHub Pages sites are publicly reachable.** Even if your repository is private under an eligible plan, treat the site and client-side code as public. Never put passwords, secrets or real records in these files.

## Deploy from an iPad

1. Download `COMPASS_GitHub_Pages_iPad_Kit.zip` and open it in the iPad **Files** app to extract it.
2. In **Safari**, open https://github.com/new and sign in to GitHub. Create a repository, e.g. `compass-demo`, set it **Public** if using GitHub Free, and create it.
3. Inside the new repository, choose **Add file → Upload files** (on narrow iPad view, use **Request Desktop Website** if needed).
4. Upload the **extracted files themselves** — `index.html`, `manifest.webmanifest`, `compass-icon.svg`, `icon-192.png`, `icon-512.png`, `apple-touch-icon.png`, `README.md`, and `IPAD_SETUP.md` — **not the ZIP**. Keep them at the repository root, without an enclosing folder.
5. Commit the upload to your `main` branch.
6. Choose **Settings → Pages → Build and deployment → Deploy from a branch → main → /(root) → Save**.
7. Once GitHub finishes publishing, visit `https://YOUR-USERNAME.github.io/compass-demo/` using Safari. The exact URL appears under your repository's **Settings → Pages**.
8. From Safari choose **Share → Add to Home Screen** to make a COMPASS shortcut on your iPad.

Start with `index.html` alone if selecting many files is difficult; it contains all app logic and styles. The other files add the app icon, home-screen presentation, and instructions.

For illustrated troubleshooting and common mistakes, see `IPAD_SETUP.md`.

## Updates

Edit or replace `index.html` in GitHub and commit to `main`. GitHub Pages republishes from the same branch. **Do not put any real organizational data into GitHub source files.**

## Tech notes

- Static HTML/CSS/JavaScript — no build system or external JS libraries.
- Uses relative paths, which work with GitHub Pages repository subpaths.
- `localStorage` is browser-local convenience only, **not secure storage or a shared database**.
- Training and personnel dates are illustrative and do not represent current readiness.
