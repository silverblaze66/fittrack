FITTRACK PRO — FREE PWA

CONTENTS
- index.html: full app (HTML/CSS/JavaScript)
- manifest.json: PWA settings
- service-worker.js: offline caching
- icon.svg, icon-192.png, icon-512.png: app icons

ANDROID-ONLY SETUP (FREE)
1. Download and extract this ZIP on your Android phone.
2. Open https://github.com in Chrome and create/sign into a free account.
3. Create a PUBLIC repository named fittrack.
4. In the repository choose Add file > Upload files.
5. Upload the six files from this folder into the repository root (not the ZIP).
6. Commit changes.
7. Open repository Settings > Pages.
8. Under Build and deployment choose Deploy from a branch; select main and /(root); Save.
9. Wait for GitHub Pages to publish. The address is normally https://YOUR-USERNAME.github.io/fittrack/
10. Open that HTTPS address in Chrome. Three-dot menu > Install app / Add to Home screen.

WEB + ANDROID
The same GitHub Pages URL works as a website on desktop/mobile and can be installed as a PWA on Android.

FEATURES
- Calories, protein, carbs and fat tracking
- Indian food starter database and custom food entries
- Meal diary and meal planner
- Weight log and 7-day calorie chart
- Barcode scanning when browser supports BarcodeDetector and camera permissions; manual barcode entry fallback
- Open Food Facts product lookup requires internet
- Photo meal log: photo preview plus manual nutrition estimate; it is NOT automatic AI recognition
- Offline app shell and local data storage
- JSON export/import backup

IMPORTANT LIMITATIONS
- AI image recognition is not included. Real automatic recognition needs a vision model or API; free availability and offline operation cannot be guaranteed.
- Barcode product data is community-contributed and may be missing or inaccurate. Check packaging.
- Food values are estimates. Recipes, cooking oil, brands and portion sizes change nutrition.
- All user data stays in this browser/device. No account, cloud sync or cross-device sync.
- Keep regular JSON backups. Clearing browser site data may erase records.
