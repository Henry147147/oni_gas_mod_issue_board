# Steam upload kit

Everything needed to fill in the Steam Workshop page for Mixed Atmospheres.
Nothing here has been uploaded to Steam yet.

## What is in this folder

| File | Use it for | Size |
| --- | --- | --- |
| `preview.png` | The square thumbnail shown in Workshop lists | 512×512, under 1 MB |
| `screenshots/00-header.jpg` | First picture in the gallery | 1920×1080 |
| `screenshots/01` to `06` `-captioned.jpg` | Gallery pictures with a one-line explanation on each | 1920×1080 |
| `screenshots/01` to `06` `.jpg` | The same pictures without captions | 1920×1080 |
| `videos/00-trailer.mp4` | The main video (37 seconds, no sound) | 1920×1080 |
| `videos/01-colony-in-motion.mp4` | A colony running (14 seconds) | 1920×1080 |
| `videos/02-overlay-tour.mp4` | The four overlays, labelled (23 seconds) | 1920×1080 |
| `overlay-tour.gif` | Small animation of the overlays | 640×360 |
| `workshop-description.bbcode` | The page text in Steam's format | |
| `STORE_PAGE.md` | The same text, easier to read and review | |

## Upload checklist

1. **Publish the mod** from the game's mod uploader as usual. Use
   `preview.png` as the preview image.
2. **Title:** `Mixed Atmospheres: real gas and liquid mixtures`
3. **Description:** open `workshop-description.bbcode`, copy all of it and
   paste it into the description box. Steam shows the formatting after you
   save.
4. **Pictures:** on the Workshop page choose **Add/edit images & videos** and
   upload, in this order:
   `00-header`, `01-colony-captioned`, `02-gas-composition-captioned`,
   `03-gas-pressure-captioned`, `04-oxygen-margin-captioned`,
   `05-breathability-captioned`, `06-settings-captioned`.
   You can also add `overlay-tour.gif` here.
5. **Video:** the Workshop only accepts YouTube links. Upload
   `videos/00-trailer.mp4` to YouTube, then paste its link in the same
   **Add/edit images & videos** screen.
6. **Tags:** Gameplay, Simulation, and the content it supports (Base Game,
   Spaced Out!).
7. **Visibility:** leave it on Hidden or Friends-only until you have checked
   the page, then switch to Public.

## Before you make it public

- Read the **Speed** paragraph in the description and make sure it still
  matches how the current build runs.
- Check the supported game version and content packs are still right.
- Make sure the issue board link works for someone who is not signed in.

## About the pictures and videos

All of them were captured from the real game running the mod (build
`c9e73d2`, game build 744825) on a 32-duplicant test colony, at 1920×1080.
The captions were added afterwards. The clips have no sound.
