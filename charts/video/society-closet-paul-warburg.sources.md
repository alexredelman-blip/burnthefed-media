# SOCIETY'S CLOSET — Paul Warburg (silent)

## Photo (real, public domain)
- Paul Warburg, c. 1909–1920, unattributed. Library of Congress Prints & Photographs, digital ID npcc.20142 (National Photo Company). Public domain.
- Commons: https://commons.wikimedia.org/wiki/File:Paul_Warburg_01.jpg (3611×5090)
- Prep: 16:9 head-and-shoulders crop, levels + mild unsharp, radial vignette to near-black. No face redraw.

## Captions → source (Wikipedia "Paul Warburg", https://en.wikipedia.org/wiki/Paul_Warburg, fetched 2026-11-02)
1. PAUL WARBURG / 1868–1932 · THE BANKER WHO DESIGNED THE FED — "August 10, 1868 – January 24, 1932"; "Many of his contemporaries regarded him as the chief driving force behind the establishment of America's central bank."
2. 1902: A HAMBURG BANKING HEIR MOVES TO WALL ST. / PARTNER AT KUHN, LOEB & CO. — family firm M. M. Warburg & Co. (Hamburg, founded 1798 by his great-grandfather); "settled there [New York] in 1902 as a partner in Kuhn, Loeb & Co."
3. HIS PLAN: A CENTRAL BANK FOR AMERICA / MODELED ON GERMANY'S REICHSBANK — "A central bank constructed along the lines of the Reichsbank could fulfill this role, according to Warburg."
4. 1910: A SECRET BANKERS' MEETING ON JEKYLL ISLAND / WHERE THE CENTRAL BANK BILL WAS DRAFTED — "In 1910, Aldrich invited Warburg to attend a secret meeting with other influential bankers on Jekyll Island in Georgia, where the draft of a bill to establish a central bank was worked out."
5. 1914: HE JOINED THE FIRST FEDERAL RESERVE BOARD / THE BANKER WHO DESIGNED IT HELPED RUN IT — "one of the original members of the Federal Reserve Board, taking office in 1914"; vice chairman 1916–1918.

## Build (all Society's Closet, Nov 2 2026)
- SILENT (owner Nov 2: VO dropped). 32.0s, 1920x1080, 24fps, H.264 yuv420p faststart, CRF 20. Caption holds 5.7–6.3s each (>= 5s).
- Motion: Grok Imagine image-to-video, 8s 1080p, locked-off camera, "preserve exact likeness / eyes steady" prompt; ping-ponged 2x so the clip ENDS on the original photo frame. 9% push-in, brand duotone (#111 → #f2efe6) and captions added after generation in Pillow/ffmpeg (generator never zooms the face).
- Brand (templates/README canonical): bg #111, bone #f2efe6 type, one red #d7261e (SOCIETY'S CLOSET kicker + final punch line); Oswald headline, Inter sub-line, DejaVu Mono photo/source line; @BurnTheFed bone ~55% opacity top-right.
- AI disclosure: the motion (blinks/breathing) is AI-generated from a real photo. Post with X's "Made with AI"/synthetic label if available; never present as original footage.
- Renderer: /workspace/closet/render.py + /workspace/closet/<name>.json; source prep /workspace/closet/prep.py.
- Buffer thumbnailOffset suggestion: 31000 ms (final punch card, original photo frame).
