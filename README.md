# Miller Knight Fitness — privacy policy site

The public privacy policy for the Miller Knight Fitness iPhone and Apple Watch app, served by GitHub Pages at
**https://ndm9946.github.io/millerknight-fitness-privacy/** (the URL given to App Store Connect and linked from the app's
Settings › Privacy › How your data is handled).

This repository holds only the policy page — no app code. The app's source lives in a separate private repository; the
files here are copied from its `docs/privacy-site/` folder.

| File | What it is |
|---|---|
| `index.html` | The whole policy: one static, self-contained page. No scripts, fonts, images, trackers or external requests; inline CSS with light and dark appearance; readable on a phone. |
| `.nojekyll` | Tells GitHub Pages to serve the files as they are (no Jekyll build). |
| `README.md` | This file. |

## Publishing
GitHub Pages: Settings › Pages › Source "Deploy from a branch", branch `main`, folder `/ (root)`. A push to `main`
republishes within about 10 minutes. Check it with `curl -sI https://ndm9946.github.io/millerknight-fitness-privacy/`
(expect `HTTP/2 200`).

## Changing the policy
1. Edit `docs/privacy-site/index.html` in the app repository (so the policy and the app change together), then copy it
   here.
2. Update the effective date in both places it appears (the line under the title and the footer).
3. A change to what the app collects or shares also needs the App Store Connect privacy answers reviewed
   (`docs/APP_STORE_CONNECT.md` in the app repository).

Contact: nathaniel9946@yahoo.com
