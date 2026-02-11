the-blue-alliance-logo
======================

The logo files for The Blue Alliance.

You are free to modify and use these logos when referring to or linking to The Blue Alliance. Unacceptable modifications include tilting, rotating, stretching, cropping, styling with any 3D effect, displaying at partial opacity, and changing the logo's color.

Please do not make derivatives of these logos or use them to brand unofficial The Blue Alliance products so we can maintain our visual identity.

Thanks!

Brand Colors
============

These are the official TBA brand colors, matching the web server's CSS variables in `tba_variables.less`:

| Name           | Hex       |
|----------------|-----------|
| TBA Blue       | `#3F51B5` |
| TBA Blue Dark  | `#303F9F` |
| TBA Red        | `#770000` |
| TBA Red Dark   | `#440000` |

Source Assets
=============

- `tba_lamp.svg` — the TBA lamp logo (white strokes + filled top on transparent background)
- `tba_lamp.ai`, `ic_tba_lamp.ai` — Illustrator source files
- `tba_lamp_text.ai`, `tba_lamp_text_3line.ai` — lamp with text variants

Android Icons
=============

**Adaptive icon (API 26+):** The launcher icon uses Android's [adaptive icon](https://developer.android.com/develop/ui/views/launch/icon_design_adaptive) system. The foreground is a white TBA lamp vector (`ic_launcher_foreground.xml`) on a solid color background — TBA Blue for release, TBA Red for debug builds. Source files are in `android/adaptive-icon/`.

**Notification icons:** Density-specific PNGs in `android/drawable-*/ic_notification.png`, generated from SVG using [Android Asset Studio](https://romannurik.github.io/AndroidAssetStudio/icons-notification.html). These are still raster PNGs because Android notifications require density-specific white silhouette icons on all API levels.

**Legacy raster launcher icons:** The old `ic_launcher_blue.png` and `ic_launcher_red.png` files (and their Illustrator source files) have been moved to `legacy/`. These were generated from Illustrator using `scripts/export_assets_to_android_ios.jsx`.
