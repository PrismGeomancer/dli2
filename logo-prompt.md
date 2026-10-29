# DALI logo: image-generation prompt

Paste this into your image generator, then send me the PNG. I will cut out the background (flood/silhouette mask, anti-aliased edges), embed it as a base64 data URI and use it in the header and favicon.

**Prompt**

> A polished app-icon style logo mark, centred, on a flat solid pure-white background (no shadow on the background, no gradient background, nothing else in the frame). A minimal, original octopus whose round head is a clock face that is softly melting: the lower edge of the head sags into one single smooth drip. The clock face has twelve small tick marks and two hands (one white, one warm amber #ffb829) showing roughly ten past ten. Eight slim, flowing arms hang below the head. Only two arms are awake and glowing: one electric violet (#8052ff) and one warm amber (#ffb829). The other six arms are thin, quiet grey outlines, so the mark shows "some arms awake, some asleep". Glossy translucent glass-like finish on the head and the two lit arms, with a soft inner glow and a single crisp highlight. Clean vector-like edges, generous padding around the shape, symmetrical composition, designed to stay readable at 32 px. Colour palette: pure white or near-black linework on the head, violet #8052ff, amber #ffb829, mid grey #6a6a6a. Style: modern, minimal, surreal, calm. No text, no letters, no background scenery, no bubbles, no stars.
>
> Do not copy any real brand, mascot, character, logo or existing artwork. Do not reference any painting. The melting clock is a generic idea: draw an original one.

**Negative prompt (if supported):** text, watermark, photo background, gradient background, drop shadow on background, extra limbs beyond eight arms, cartoon face, eyes, hands, human, brand logos, painting reproduction.

**Notes for generation**
- Ask for a square canvas, 1024 x 1024 or larger.
- A pure white background makes the cut-out cleaner. If the model adds a shadow or vignette, regenerate.
- If the white of the clock face touches the background white, ask for a thin dark outline around the whole silhouette.
