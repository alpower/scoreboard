# OBS scoreboard instructions
This is a scoreboard written in HTML, CSS, JS and localstorage for use in OBS as an interactive browser source via a local single HTML file.

1. Download the zip file locally.
2. load as a browser source in OBS and choose 'local file'.
3. Position it so that the controls are offscreen.
4. Click 'Interact' with browser source to open an OBS panel to adjust controls

## Versions

Two versions of scoreboard are available one for futsal and one for Football (/soccer with built in clock timing for  11-a-side 45 minutes per half matches).

In the **futsal** version the clock *counts down* from 20 minutes to 0 and stops when it hits zero (which will also cause the clock to turn red).

In the **football** version the clock *counts up* from 0 minutes. The clock will turn red after 45 minutes if the period is set as *1st Half* and 90 minutes if the period is set as *2nd Half*.

## Logos

Logos were the only thing that was tricky to work around with local storage, so we opted for local filesystem access and filenames.

You'll have to drop your desired logos in to the `logos` subfolder next to this file (ideally as PNGs for OBS - SVG doesn't work well apparently), then add the file name of each team's logo into the controls, and they will show up in the overlay.

Square and Portrait work better than Landscape orientation.
