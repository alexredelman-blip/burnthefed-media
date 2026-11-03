# SOCIETY'S CLOSET — John D. Rockefeller (silent)

## Photo (real, public domain)
- "Portrait of J. D. Rockefeller", 1895 (published by Scientific American Compiling Dep't, 1907). Public domain. Credit: Rockefeller Archive Center.
- Commons: https://commons.wikimedia.org/wiki/File:Portrait_of_J._D._Rockefeller.jpg
- Prep: 16:9 head-and-shoulders crop; light studio background removed to #111 with a segmentation mask (rembg u2net_human_seg, background pixels only — no face redraw); levels + mild unsharp; vignette.

## Captions → source (Wikipedia "John D. Rockefeller", https://en.wikipedia.org/wiki/John_D._Rockefeller, fetched 2026-11-02)
1. JOHN D. ROCKEFELLER / 1839–1937 · AMERICA'S FIRST BILLIONAIRE — "July 8, 1839 – May 23, 1937"; "became the country's first billionaire on 28 September 1916."
2. 1870s: RAILROADS GAVE HIM SECRET REBATES / UP TO 50% OFF, PLUS A CUT OF HIS RIVALS' SHIPMENTS — South Improvement Company cartel: "rebates of up to 50% for their product but rebates for the shipment of competing products"; "secret transportation rebates" among Standard's "most potent weapons".
3. REFUSE TO SELL? HE'D BANKRUPT YOU / THEN BUY YOUR ASSETS CHEAP AT AUCTION — "If they refused his offer, he told them he would run them into bankruptcy and then cheaply buy up their assets at auction."
4. 1900: STANDARD OIL HELD ~90% OF U.S. OIL / HIS REPUTED MOTTO: "COMPETITION IS A SIN." — "By 1900, Standard Oil controlled about 90% of the nation's oil production"; "Rockefeller's reputed remark, 'Competition is a sin.'" (reputed — caption says so).
5. 1911: THE SUPREME COURT BROKE IT INTO 34 PIECES / HIS FORTUNE THEN JUMPED TO $900 MILLION — "broken up into 34 separate entities"; "over the next 10 years the breakup proved immensely profitable for him... Rockefeller's personal wealth jumped to $900 million." (Also "personal wealth in 1913 was estimated at $900 million".)

## Build (all Society's Closet, Nov 2 2026)
- SILENT (owner Nov 2: VO dropped). 32.0s, 1920x1080, 24fps, H.264 yuv420p faststart, CRF 20. Caption holds 5.7–6.3s each (>= 5s).
- Motion: Grok Imagine image-to-video, 8s 1080p, locked-off camera, "preserve exact likeness / eyes steady" prompt; ping-ponged 2x so the clip ENDS on the original photo frame. 9% push-in, brand duotone (#111 → #f2efe6) and captions added after generation in Pillow/ffmpeg (generator never zooms the face).
- Brand (templates/README canonical): bg #111, bone #f2efe6 type, one red #d7261e (SOCIETY'S CLOSET kicker + final punch line); Oswald headline, Inter sub-line, DejaVu Mono photo/source line; @BurnTheFed bone ~55% opacity top-right.
- AI disclosure: the motion (blinks/breathing) is AI-generated from a real photo. Post with X's "Made with AI"/synthetic label if available; never present as original footage.
- Renderer: /workspace/closet/render.py + /workspace/closet/<name>.json; source prep /workspace/closet/prep.py.
- Buffer thumbnailOffset suggestion: 31000 ms (final punch card, original photo frame).
