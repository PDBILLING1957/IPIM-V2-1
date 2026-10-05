IPIM V2.1 — GITHUB PAGES DEPLOYMENT

1. Create/open your GitHub repository for IPIM.
2. Upload these three files to the repository root:
   index.html
   manifest.webmanifest
   sw.js
3. GitHub -> Settings -> Pages -> Deploy from branch -> main -> /(root) -> Save.
4. Wait for GitHub Pages to publish.
5. Open the resulting https://...github.io/... address.
6. On iPhone/iPad use Share -> Add to Home Screen.
7. On Windows/Surface use the browser's Install/Add to app option if offered.

FIRST TEST:
Save sample customer -> CUS-000001.
New customer -> CUS-000002.
Edit first -> ID unchanged.
Close/reopen -> records remain on that device/browser.

IMPORTANT:
This V2.1 foundation uses IndexedDB for local persistence. It is not yet a shared multi-device cloud database. The next production step is to add a real backend/database if the same data must synchronize between Surface, iPhone and iPad.
