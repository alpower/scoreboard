# scoreboard instructions

Hopefully all self-explanatory!

1. load as a browser source in OBS and choose 'local file'.
2. Position it so that the controls are offscreen.
3. Click 'Interact' with browser source

## Logos

Logos were the only thing that was tricky to work around with local storage, so we opted for local filesystem access and filenames.

You'll have to drop your desired logos in to the `logos` subfolder next to this file (ideally as PNGs for OBS - SVG doesn't work well apparently), then add the file name of each team's logo into the controls, and they will show up in the overlay.

Square and Portrait work better than Landscape orientation.
