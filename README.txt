DAILY EXPENSE TRACKER — PUBLIC WEB APP PACKAGE

WHAT IS INCLUDED
- index.html: complete responsive expense tracker
- manifest.json + sw.js + icons/: installable/offline app support on compatible browsers

FEATURES
- Large total spent this month and spent today cards
- Add, edit, search, filter, and delete expenses
- Custom expense categories (add, rename, remove unused categories)
- Attach bill/receipt photos (images are resized before saving)
- Monthly bar graph, scatter graph, pie chart, and category breakdown
- CSV export, JSON backup/restore, currency label preferences
- Mobile-friendly layout and PWA installation support when hosted over HTTPS

HOW TO PUBLISH IT FOR EVERYONE (FREE STATIC HOSTING)
The app needs to be uploaded to a static HTTPS hosting service to get a public URL. This package does not itself create a live public URL.

OPTION A — GitHub Pages
1. Sign in or create an account at https://github.com/
2. Create a new repository (for example: daily-expense-tracker).
3. Upload the contents of this folder into the repository root: index.html, manifest.json, sw.js, and the icons folder. Do not upload only the ZIP file.
4. Open the repository Settings → Pages.
5. Under Build and deployment, choose Deploy from a branch. Choose the main branch and /(root), then Save.
6. Wait for the deployment to finish. GitHub will show the public HTTPS site address in Settings → Pages. Open it to use the tracker.
7. On Android, open that address in Chrome → ⋮ → Install app or Add to Home screen.

OPTION B — Cloudflare Pages
1. Open https://pages.cloudflare.com/ and sign in.
2. Create a Pages project and upload/connect the folder's files using the current dashboard flow.
3. Deploy the static files and open the generated HTTPS address.
4. On Android Chrome, use ⋮ → Install app or Add to Home screen.

IMPORTANT DATA / PRIVACY LIMITATION
This is a client-side personal expense tracker. Each person’s records are stored in that person’s browser/device using localStorage. The site does not send records to a shared database, and people do not see one another’s expenses. Data does not automatically sync across devices or browsers. For transfer, use JSON backup/restore. Clearing browser/site data can delete records. Bill photos are included in backups, so keep backups private.

If you need login accounts, cloud synchronisation across devices, shared records, or an administrator dashboard, a backend/database and user authentication must be added; this static package does not provide those features.
