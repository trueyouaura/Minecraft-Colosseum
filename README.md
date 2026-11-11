# Minecraft Colosseum: Blueprint and Progress Tracker

A standalone GitHub Pages site. No build steps, external dependencies, or server required.

## Deploy

1. Upload `index.html` to the **root** of your GitHub repository (not inside another folder).
2. In **Settings → Pages**, publish from `main` / `/(root)`.
3. The public URL is `https://trueyouaura.github.io/minecraft-colosseum/` if your repository is named `minecraft-colosseum`.
4. For local offline use, double-click `index.html` in a browser.

## Resizable row and column command panels

The **Selected Z row** and **Selected X column** command lists, plus the **Rows (Z coordinates)** and **Columns (X coordinates)** progress checklists, can each be made taller or shorter by dragging the **bottom-right corner**. Each keeps its own height while the page remains open. The original manual selection textarea remains resizable too.

## What's new

- **✓ Last copied** stays highlighted beside the most recently copied command and in a status banner.
- **Mark placed / ✓ Placed** buttons for each row/column `/fill` command and each individual command in the copied-command list.
- **Mark block placed** for the currently selected block; use it when building by hand.
- A separate **Progress Checklist** tab with checkboxes for every buildable row and column on the selected layer and an overview of all 56 layers.
- Counts confirmed placed blocks **uniquely** across row/column overlaps, both per-layer and across the whole build.
- **Optional:** automatically mark copied commands as placed, if you're confident you paste each one successfully. Disabled by default.
- Progress saved to your browser; JSON **export/import** buttons make it portable between the local file and the GitHub Pages address. Local progress is *not* synced across devices or browser origins.
- Green dots on the close-up map indicate blocks you marked placed.

### Important

The site cannot read Minecraft or verify that a pasted `/fill` or `/setblock` command ran. A Copy action is not proof of placement. For reliable progress, click **Mark placed** after running the command, or enable optional auto-mark at your own discretion. Only non-air blueprint blocks count toward the total. Undoing an individual row/column undoes its blocks, including any intersections with other completed rows/columns.

All original 56 blueprint layers and original world coordinate alignment are preserved: X 566–753, Z 417–572, Y 120–175 (ground/arena Y 127).
