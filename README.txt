TOPL WATER TRACKER – NFC SETUP

WHAT IT DOES
- Each visit to https://YOUR-USERNAME.github.io/topl-water-tracker/?add=1 logs 475 mL.
- The main page (without ?add=1) displays totals without adding water.
- Keeps timestamps, daily progress, undo, CSV export, and adjustable goal.
- All records stay in the browser's local storage on your Android phone.

FREE HOSTING WITH GITHUB PAGES
1. Create a public GitHub repository called topl-water-tracker.
2. Upload index.html to the root of the repository.
3. Repository Settings > Pages > Build and deployment: Deploy from a branch; main, /(root), Save.
4. After deployment, open https://YOUR-USERNAME.github.io/topl-water-tracker/ on your Android phone to see the tracker.
5. Use NFC Tools > Write > Add a record > URL/URI and set it to:
   https://YOUR-USERNAME.github.io/topl-water-tracker/?add=1
6. Write it to your TOPL mug's NFC tag. This replaces the existing contact data unless you carefully preserve other records.
7. To test, scan the mug with your unlocked Android phone and open the offered link. One load = +475 mL.

IMPORTANT LIMITATIONS
- The NFC tag cannot tell whether the mug was emptied; each scan logs a completed cup.
- Refreshing the ?add=1 page can add another cup. Use 'Undo last' if this happens.
- Android may require a tap to open the link; this is operating-system behavior.
- Browser data is local, so use the same browser and don't clear site data.
- Opening the link on another phone/browser has a separate history.
- On Android 17+, scanning an NFC URL may show a notification you must tap.
