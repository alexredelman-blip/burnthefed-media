# SOCIETY'S CLOSET — J. Pierpont Morgan (silent, day-1 asset)

## Photo (real, public domain)
- Pach Brothers, portrait of J. P. Morgan, 1902. Public domain.
- Wikimedia Commons: https://commons.wikimedia.org/wiki/File:J._P._Morgan_in_1902.jpg
- Original file (5112×7800): https://upload.wikimedia.org/wikipedia/commons/7/71/J._P._Morgan_in_1902.jpg
- Commons credit line: Google Arts & Culture. (Same Pach Bros 1902 sitting also held by Library of Congress, LCCN 92517707: https://lccn.loc.gov/92517707, and The Henry Ford, obj. 2005.0.32.76.)
- Prep: cropped to 16:9 head-and-shoulders, mat/oval masked to near-black, levels + mild unsharp, radial vignette (Pillow). No face redraw.
- Motion: Grok Imagine image-to-video (8s, 1080p, static camera, "preserve exact likeness" prompt), ping-ponged 2x to 32.0s (ends on the original photo frame); slow 9% push-in, duotone to brand #111/#f2efe6, and captions done in Pillow/ffmpeg after generation (generator never zooms the face).

## Captions (on screen) → source
1. J. PIERPONT MORGAN / 1837–1913 · THE BANKER WHO BAILED OUT AMERICA — Wikipedia "J. P. Morgan": Drexel Morgan "bailed out the U.S. government in 1895"; led rescue in Panic of 1907.
2. 1895: THE U.S. TREASURY RAN LOW ON GOLD / MORGAN'S SYNDICATE SOLD IT 3.5 MILLION OUNCES — Wikipedia "J. P. Morgan": Treasury "nearly depleted its gold reserves"; "Morgan and the Rothschilds [sold] 3.5 million ounces of gold directly to the U.S. Treasury in exchange for a 30-year bond issue." https://en.wikipedia.org/wiki/J._P._Morgan
3. 1907: HE LOCKED ~120 BANKERS IN HIS LIBRARY / UNTIL THEY SIGNED A $25 MILLION BAILOUT — Wikipedia "Panic of 1907" (Drama at the library): ~120 bank and trust officials at 3 a.m.; "Morgan had locked them in the library and pocketed the key"; trust companies to provide a $25 million loan; signed ~4:45 a.m. https://en.wikipedia.org/wiki/Panic_of_1907
4. 1910: HIS PARTNERS HELPED SECRETLY DRAFT / A U.S. CENTRAL BANK ON JEKYLL ISLAND — Wikipedia "Jekyll Island Club": Nov 22, 1910 secret trip incl. Henry P. Davison (senior partner, J. P. Morgan Co.) and Benjamin Strong (representing J. P. Morgan); drafted the Aldrich Plan, ideas later in the Federal Reserve Act. https://en.wikipedia.org/wiki/Jekyll_Island_Club
5. 1913: THE FEDERAL RESERVE WAS BORN / MORGAN'S DEPUTY RAN THE NEW YORK FED — Wikipedia "Panic of 1907": Federal Reserve Act Dec 23, 1913; "Morgan's deputy Benjamin Strong became president of the Federal Reserve Bank of New York." (Morgan died Mar 31, 1913.)

Checked 2026-11-02 against Wikipedia. Britannica spot-check (2026-11-02, https://www.britannica.com/biography/J-P-Morgan) confirms dates, 1890s gold syndicate, 1907 rescue; library lock-in, Jekyll Island partners, Strong at NY Fed are Wikipedia-sourced. "~120" is approximate.

## Build
- Silent (owner Nov 2: VO dropped). 32.0s, 1920x1080, 24fps, H.264 yuv420p faststart, CRF 20.
- Caption holds: 5.7s / 6.1s / 6.3s / 6.2s / 6.2s (all >= 5s).
- Brand (templates/README): bg #111, bone #f2efe6 type, one red #d7261e (SOCIETY'S CLOSET kicker + final punch line); Oswald headline, Inter sub-line, DejaVu Mono photo/source line; @BurnTheFed bone @ ~55% opacity.
- Renderer: /workspace/closet/render.py + /workspace/closet/morgan.json. Last frame = thumbnail (eyes open, final punch card).
- Thumbnail offset suggestion for Buffer: 31000 ms.
