# Patricia J. Root Designs — GitHub Pages portfolio

A standalone HTML/CSS/JavaScript reconstruction based on the original Squarespace **Webpage, Complete** archive. No Squarespace runtime required.

## Publish to GitHub Pages
1. Extract this ZIP to your computer.
2. Open your `pattyjake99/pjroot-portfolio` GitHub repository and back up its current files if you want to keep them.
3. Upload **`index.html`, `style.css`, `script.js`, and the entire `assets` folder** to the **root** of the repository (not the containing ZIP or folder). Commit the changes.
4. Under **Settings → Pages**, use **Deploy from a branch**, `main`, `/(root)`.
5. Open `https://pattyjake99.github.io/pjroot-portfolio/`.

## Content notes
- Six original TikTok video IDs were recovered and embedded using TikTok's public embed URL; playback requires internet access and TikTok allowing the embeds.
- The historical mashing GIF, site branding, original product photography, design icons, color study, and cinematic character image are bundled locally.
- The original Squarespace capture contains a Kinetic Typography video element but **not the video file** (its `blob:` URL is temporary). This section is included as a labeled text project, not a fake video. Upload an MP4 if you have one.
- Some Squarespace-only effects or other pages were not included in the supplied saved webpage; this is a faithful-content **standalone reconstruction**, not a pixel-perfect export of the proprietary Squarespace theme.
- You may want to add a follower/likes screenshot later. The original saved file does not contain one, so none was fabricated.


## Meet the Artist update
This version adds the olive-green portrait to the About/Meet the Artist section. The file is `assets/meet-the-artist.png`. All previous portfolio sections remain included.


## November refinements
- Added stylized cursive text signature under Meet the Artist (not a scan of a handwritten signature).
- The Color Study image now uses `object-fit: contain` at full 5:4 aspect ratio, so the entire palette remains visible.
- Kinetic Typography currently displays a deliberate branded placeholder because the Squarespace save only contained a temporary `blob:` video address, not an MP4. To restore video playback, put your actual video file at `assets/kinetic-typography.mp4`. The page will detect it on GitHub Pages and show controls.
- Existing Blender feature remains the Juliet cinematic image. Any additional Blender projects will need their original renders or animation files.


## Personal signature and Kinetic Typography
The Meet the Artist section now displays `assets/patricia-signature.png`, the original handwritten image supplied by Patricia.

To enable the Kinetic Typography video, export/download the original as an MP4, name it exactly `kinetic-typography.mp4`, and put it in the `assets` folder (GitHub path `assets/kinetic-typography.mp4`). The player will reveal itself when GitHub Pages serves that file. Use H.264 video + AAC audio for broad browser support. Squarespace's saved-page HTML contains only a temporary player reference, not this actual video. If the MP4 isn't available, the designed placeholder remains visible.


## Kinetic Typography restored — November 23
- Added `assets/kinetic-typography.mp4`, converted from the user-supplied screen recording, trimmed to one approximately 3.33-second repetition at 1280×720 H.264.
- The embedded video now autoplays, loops, plays inline, and is muted to meet browser autoplay restrictions. Viewer can use the controls.
- Upload the entire assets folder alongside the updated HTML/CSS/JS files. This file does not require Squarespace.
