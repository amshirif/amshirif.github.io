# Work Card Image Direction

These are placeholder image directions for the three `Selected Work` cards on the homepage. The current files are intentionally believable editorial-photo stand-ins so they can be swapped later with similar real photos without changing the layout.

## Shared Art Direction

- Muted blue, charcoal, slate, and soft warm-gray palette
- Editorial photography, not illustration or CGI
- No visible logos, readable UI text, or watermarks
- No obvious faces as the subject
- Center-weighted composition so the image still works in a shallow card crop
- Calm, professional, slightly cinematic, not flashy
- Target crop: horizontal `16:9`

## Shared Negative Prompt

`logo, brand mark, watermark, readable text, UI screenshot, meme style, neon cyberpunk, cartoon, illustration, 3d render, futuristic holograms, crowded scene, exaggerated contrast, oversaturated colors, low-resolution blur, distorted hands, distorted faces`

## Image 1

- Card: `Decentralized betting protocol architecture`
- Current file: `images/work-stadium-placeholder.jpg`
- Current source: `https://images.pexels.com/photos/3571569/pexels-photo-3571569.jpeg?cs=srgb&dl=pexels-frederthal-3571569.jpg&fm=jpg`
- Concept: empty sports environment with quiet tension
- Prompt:

```text
Editorial real photo of an empty stadium or arena at dusk, subtle scoreboard glow, cool blue and charcoal tones, quiet high-stakes atmosphere, clean symmetrical composition, no crowd, no visible branding, realistic lighting, slightly cinematic, horizontal 16:9
```

- Search keywords:
  - `empty stadium dusk editorial`
  - `sports arena empty blue tones`
  - `stadium scoreboard moody photo`
- Real-photo replacement target:
  - wide sports venue, no logos, low visual clutter, strong horizon line

## Image 2

- Card: `chatter-blocks`
- Current file: `images/work-desk-placeholder.jpg`
- Current source: `https://images.pexels.com/photos/34804003/pexels-photo-34804003.jpeg?cs=srgb&dl=pexels-dkomov-34804003.jpg&fm=jpg`
- Concept: secure engineering desk / terminal setup
- Prompt:

```text
Editorial real photo of a dark desk with a laptop showing a terminal-style interface, soft blue screen light, notebook and cables nearby, minimal secure engineering atmosphere, realistic photography, no readable text, no visible logos, restrained composition, horizontal 16:9
```

- Search keywords:
  - `developer desk terminal editorial photo`
  - `laptop terminal blue light workspace`
  - `secure engineering desk moody photo`
- Real-photo replacement target:
  - laptop or keyboard scene with subtle tooling/terminal feel, no branded hardware emphasis

## Image 3

- Card: `Wallet and payments integration infrastructure`
- Current file: `images/work-payments-placeholder.jpg`
- Current source: `https://images.pexels.com/photos/11009960/pexels-photo-11009960.jpeg?cs=srgb&dl=pexels-towfiqu-barbhuiya-3440682-11009960.jpg&fm=jpg`
- Concept: modern fintech still life
- Prompt:

```text
Editorial real photo of a smartphone, payment terminal, and bank card on a clean surface, soft natural light, muted blue-gray palette, professional fintech atmosphere, no visible logos, no hands, minimal composition, realistic photography, horizontal 16:9
```

- Search keywords:
  - `payment terminal smartphone editorial photo`
  - `fintech still life card reader muted`
  - `mobile payments clean product photo`
- Real-photo replacement target:
  - payments/device scene with simple geometry and neutral lighting, no loud branding

## Replacement Notes

- Keep all three images in the same tonal family so the section reads as one set.
- Favor compositions that still work when darkened slightly by overlays.
- Replace images by updating the `background-image` URLs in `css/styles.css`.
