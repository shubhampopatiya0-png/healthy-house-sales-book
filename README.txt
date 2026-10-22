HEALTHY HOUSE SALES BOOK — ANDROID INSTALLABLE PACKAGE

WHAT'S INCLUDED
- index.html: installable sales tracker
- manifest.webmanifest: app name, icon, and standalone display settings
- sw.js: offline caching after the first successful visit
- icons/: updated Healthy House logo and app icons
- healthy_house_sales_tracker.html: recovered original standalone HTML file

IMPORTANT ABOUT YOUR DATA
- Sales, expenses, costs, and stock notes are saved in this browser on this device.
- They do NOT automatically sync to another phone/computer.
- In the tracker, open “Reports & Backup” and tap “Export all data (JSON backup)” regularly.
- Keep the downloaded JSON backup somewhere safe (for example, Google Drive or another folder).
- To restore: open the app, go to “Reports & Backup”, choose the JSON backup file under “Restore a previous JSON backup”, and confirm. Restoring replaces the current data in this browser, so export the current data first if you want to keep it.

ANDROID INSTALL STEPS (FREE HOSTING WITH GITHUB PAGES)
1. On a computer or mobile browser, sign in to GitHub and create a PUBLIC repository, e.g. healthy-house-sales-book.
2. Upload index.html, manifest.webmanifest, sw.js, and the icons folder, keeping the same folder structure. (You do not need to upload the standalone HTML file.)
3. Open repository Settings > Pages.
4. Under Build and deployment, choose “Deploy from a branch”, select branch “main” and folder “/(root)”, then Save.
5. Wait for GitHub Pages to show the website's HTTPS URL.
6. Open that HTTPS URL in Chrome on your Android phone.
7. Tap Chrome's ⋮ menu > “Install app” (or “Add to Home screen”) > Install. The wording can vary by Chrome version.
8. Open the new Healthy House icon from your home screen. Visit once while online so offline caching can be set up.

NOTES
- Do not open index.html directly as a local file if you want installation; the PWA must be served from HTTPS.
- Keep your GitHub repository public if using GitHub Pages on the free plan. Do not upload customer-sensitive information.
- This package does not provide cloud database syncing. JSON export/import is the backup and transfer method.
