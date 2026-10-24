7-FIGURES PRINTERS WEBSITE: GITHUB + VERCEL (LIGHT VERSION)
=============================================================

21 FILES, about 12 MB in total. The biggest single file is 3.2 MB.
ALL of them go in the SAME place: the top level of your GitHub repo (no folder).

  index.html  config.js  README.txt  logo.svg  ai-head.png  ai-head-glow.png
  hero.jpg  chart-wall.jpg  floor.jpg
  model-1.jpg  model-2.jpg  model-3.jpg
  poster-1.jpg  poster-2.jpg  poster-3.jpg
  testimony-1.mp4  testimony-2.mp4  testimony-3.mp4
  life-1.mp4  life-2.mp4  life-3.mp4

1) GITHUB
   a. Open your repo > "Add file" > "Upload files".
   b. Drag in ALL 21 files at once (the files, not a folder).
   c. Click "Commit changes".
   d. Optional cleanup: old files no longer used (car-left.jpg, car-right.jpg,
      coins.jpg, ai-head-logo.svg) can be deleted. Leaving them does no harm.

2) VERCEL
   It redeploys by itself after the commit (about 1 minute).
   vercel.com > your project > Deployments: newest one says "Ready".
   Then hard refresh: Ctrl + Shift + R (Mac: Cmd + Shift + R).
   On a phone, close the tab and open the site again.

3) CHECK
   Open https://YOUR-SITE.vercel.app/testimony-1.mp4 and /hero.jpg.
   "404: NOT_FOUND" means that file is missing in GitHub or its name differs.
   Names must match exactly, in small letters.

WHERE TO CHANGE THINGS
   Prices ......... index.html, search for class="price"
   Buy buttons .... config.js, "links" (paste Stripe / Whop / Gumroad links)
   Discord link ... index.html, search for discord.gg
   Videos/pictures  replace the file with a new one using the SAME name
