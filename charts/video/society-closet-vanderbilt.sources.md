# SOCIETY'S CLOSET — Cornelius Vanderbilt (silent)

## Photo (real, public domain)
- "Cornelius Vanderbilt, head-and-shoulders portrait", half-plate daguerreotype, Mathew Brady's studio, c. 1844–1860 (restoration by Michel Vuijlsteke). Library of Congress cph.3a11569. Public domain.
- Commons: https://commons.wikimedia.org/wiki/File:Cornelius_Vanderbilt_Daguerrotype2_(cropped)(b).jpg
- Prep: 16:9 head-and-shoulders crop, levels + mild unsharp, radial vignette. No face redraw. (Generation attempt 3 used; attempts 1–2 drifted / held eyes closed too long — rejected.)

## Captions → source (Wikipedia "Cornelius Vanderbilt", https://en.wikipedia.org/wiki/Cornelius_Vanderbilt, fetched 2026-11-02)
1. CORNELIUS "COMMODORE" VANDERBILT / 1794–1877 · THE ORIGINAL ROBBER BARON — "May 27, 1794 – January 4, 1877", nicknamed "the Commodore"; "For his monopoly on shipping and the railroads, facilitated in part by political manipulation, Vanderbilt is often described as either a 'captain of industry' or a 'robber baron'." ("original" = editorial framing.)
2. 1834: HE UNDERCUT A HUDSON RIVER MONOPOLY / THE MONOPOLY PAID HIM TO STOP COMPETING — "In 1834, Vanderbilt competed on the Hudson River against the Hudson River Steamboat Association, a steamboat monopoly... At the end of the year, the monopoly paid him a large amount to stop competing."
3. 1863: HE CORNERED HARLEM RAILROAD STOCK / AND SEIZED CONTROL OF THE LINE — "In 1863, Vanderbilt took control of the Harlem in a famous stockmarket corner, and was elected its president."
4. 1868: THE ERIE WAR / RIVALS PRINTED NEW STOCK, THEN BRIBED LAWMAKERS TO LEGALIZE IT — Vanderbilt tried to corner Erie stock; Gould and Fisk "defeated the corner by issuing 'watered stock' in defiance of state law... But Gould bribed the legislature to legalize the new stock."
5. 1877: HE DIED WORTH $105 MILLION / 95% OF IT LEFT TO ONE SON AND HIS BOYS — "estimated worth of $105 million"; "he left 95% of his $105 million estate to his son William (Billy) and four grandsons through him."

## Build (all Society's Closet, Nov 2 2026)
- SILENT (owner Nov 2: VO dropped). 32.0s, 1920x1080, 24fps, H.264 yuv420p faststart, CRF 20. Caption holds 5.7–6.3s each (>= 5s).
- Motion: Grok Imagine image-to-video, 8s 1080p, locked-off camera, "preserve exact likeness / eyes steady" prompt; ping-ponged 2x so the clip ENDS on the original photo frame. 9% push-in, brand duotone (#111 → #f2efe6) and captions added after generation in Pillow/ffmpeg (generator never zooms the face).
- Brand (templates/README canonical): bg #111, bone #f2efe6 type, one red #d7261e (SOCIETY'S CLOSET kicker + final punch line); Oswald headline, Inter sub-line, DejaVu Mono photo/source line; @BurnTheFed bone ~55% opacity top-right.
- AI disclosure: the motion (blinks/breathing) is AI-generated from a real photo. Post with X's "Made with AI"/synthetic label if available; never present as original footage.
- Renderer: /workspace/closet/render.py + /workspace/closet/<name>.json; source prep /workspace/closet/prep.py.
- Buffer thumbnailOffset suggestion: 31000 ms (final punch card, original photo frame).
