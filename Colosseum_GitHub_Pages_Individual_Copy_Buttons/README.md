# Minecraft Colosseum, GitHub Pages website

This is your original 56-layer Colosseum block viewer, upgraded with **one-click Copy buttons for each individual `/fill` command**. Each non-air segment in the selected row and column now has its own command and Copy button. Clicking the original "Copy all /fill commands" buttons also creates a list of individually copyable commands under the command output.

## Update your live website

1. Open your GitHub repository (for example, `minecraft-colosseum`).
2. Open `index.html` in the root of your repo.
3. Use the GitHub edit pencil and replace its contents with the downloaded `index.html`, or upload the new `index.html` to the repository root, replacing the old file.
4. Commit the change to the branch that GitHub Pages publishes (usually `main`).
5. Reload your GitHub Pages website. Use Ctrl+Shift+R on Windows if you still see the cached old version.

## Using the new Copy buttons

Select a layer and block. Under **Selected Z row** and **Selected X column**, you will see one complete Minecraft `/fill` command alongside a Copy button for each non-air segment. Click Copy, then paste into Minecraft. Repeat for the next command.

The existing **Copy /setblock** and **Copy all /fill commands** features still work. Clicking Copy all also displays a separate list of individually copyable command lines.

Website has no external dependencies. Blueprint data, world coordinates, materials, and layer counts are unchanged.
