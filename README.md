# Joelea’s Birthday Garden — Special Static Edition

A refreshed purple-gradient birthday website for Joelea, a beloved daughter of God. It opens with a welcome screen illustrated with tulips and lilies, keeps the previous birthday letter, and includes both requested Bible verses.

## Features
- Stronger lavender-purple gradient background and animated purple welcome intro with tulips and lilies
- Birthday greeting and original birthday letter card
- Psalm 139:14 and Psalm 20:4 verse carousel
- Flower cards with hidden wishes, including a tulip and lily
- Tiny plantable garden and falling-petal surprise
- Responsive layout for desktop and Android/mobile browsers

## Publish on Render as a free Static Site
1. Extract this ZIP file.
2. Upload the contents of this folder to the main level of your GitHub repository, keeping `css/`, `js/`, and `music/` folders intact.
3. In Render, choose **New + → Static Site** and connect the GitHub repository.
4. Use these settings: Branch `main`; Root Directory blank; Build Command `echo "No build needed"`; Publish Directory `.`.
5. Click **Create Static Site** and open the Render URL when the status says **Live**.

Important: `index.html` must be at the repository top level. Do not upload only the ZIP and do not nest all files inside an extra folder within the repository.

The birthday letter remains the same as the previous static site. Edit its text in `index.html` if you want to personalize it further. Styles are in `css/style.css`; interactions are in `js/main.js`.

This static project does not need Flask, `requirements.txt`, or a `Procfile` on Render. Optional music can be added later, but only use a song you own or have permission to use.
