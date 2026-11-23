THIRTY PLANTS 3.31.1: putting it on your Android phone

The app has to be opened from a web address (not as a file) for Chrome to install it.
Free route with GitHub Pages:

1. Create a new public repository on github.com, e.g. "thirty-plants".
2. Upload every file in this folder (index.html, manifest.webmanifest, sw.js and the three icons) to the repository root.
3. Settings > Pages > Source: "Deploy from a branch", branch "main", folder "/ (root)". Save.
4. After a minute the site is live at https://YOUR-USERNAME.github.io/thirty-plants/
5. Open that address in Chrome on your phone, tap the three-dot menu, then "Add to Home screen" (or "Install app").

It then opens full screen with its own icon and works offline. Plans are stored on the phone itself.
Use Settings > Backup > Export now and then.

On a laptop you can also just double-click index.html to use it in a browser (no install, no offline cache).

Weather (3.27): when the app is online it fetches hourly weather, air pollution and pollen for New Cross
from Open-Meteo (free, no account), about three months back the first time and then a day or two at a time.
It's kept on the phone under its own key, separately from your plans, so it isn't part of the backup file.

Points and levels (3.28): the game counts from the Monday of the week you install this version. Its points,
badges, level and colour choices are part of your plans, so they're in the backup file too.

Dumbbells and bodyweight (3.29): the Train tab has a kit picker for each week (Vitruvian, Dumbbells or
Bodyweight), and each session can have its own. The sets for every muscle stay the same; only the exercises
change. Dumbbells are logged per dumbbell and go up in 2 kg steps to 24 kg, after which the reps get harder
instead (slower lowering, a pause, 1½ reps, then a harder exercise). Bodyweight uses the pull-up bar and benches.

Fit my day, shop-bought and multi-pot (3.30): Today has a Fit my day button for the meals still to come. Shop-bought
lunches and dinners (Sainsbury's, Waitrose, M&S, Caffè Nero, Pret, plus meal deals) and 20 multi-pot dinners are in
the meal picker under their own buttons. They're only ever swapped in by you; the planner never picks them. Shop figures
are from each shop's product page in November 2026, so check the pack if a recipe has changed.

Drinks in the wrap-up (3.30.1): the Meals step shows a night's drink calories next to what was drunk, and units
entered in the Alcohol step now count as calories the same way the morning check-in's units do.

Red meat fix (3.30.2): the Sainsbury's Chicken & Bacon sandwich now counts as a red meat meal.

Shop items from Claude's codes (3.31.0): when a code from Claude carries a shop-bought product that passes the bar
(meals: sat fat 5g or less, salt 1.5g or less, added sugar 5g or less, per pack, with no protein floor since 3.31.1; snacks: sat fat
3g, salt 0.5g, added sugar 5g at most), the paste box offers to save it, ticked. Saved items show under Shop-bought in
the meal picker (with Tesco and Co-op chips once there's one from them) and in Fit my day, and are never planned on
their own. Settings > Your shop items lists them, with Remove. The same product with new figures replaces the old one;
days that already had the old one keep it.
