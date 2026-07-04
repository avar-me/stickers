# Стикер 23 — "Гьаб щи хӏарп?"
_(Это что за буква?)_

## Готовый промпт (base + специфика) — просто скопируй целиком

```
A cute mascot character: a large open book that is alive, standing upright like a small
biped creature. The book's left page shows the bold letters "АВ" and the right page shows
the bold letters "РУ", printed in a rounded bold sans-serif font. The book cover is bright
deep blue (#295BA7) with soft glossy highlights, the pages are warm cream/beige, and all
outlines are dark navy blue with a thick white sticker border around the whole character.
The character has big expressive dark blue round eyes with a small white highlight dot,
placed on the pages, with very emotive thick eyebrows that carry most of the emotion, and
soft pink blush circles on the pages/cheeks. The mouth is minimal and simple. It has two
white cartoon-glove hands on short flexible arms, blue cartoon sneakers with laces as feet,
and a small red bookmark ribbon sticking out of the book.

FIXED STYLE (approved reference: ../png/final/01_barkala.png — match it exactly):
- Semi-3D glossy sticker illustration style: soft highlights on the cover/pages, gentle
  shading, a soft drop shadow under the character. NOT flat, but also NOT fully realistic.
- Bold uniform dark-navy outlines, thick white sticker die-cut border around the silhouette.
- Pink blush circles on the pages, red bookmark ribbon, blue sneakers with laces, white
  gloves — these small details must appear consistently on every sticker.
- No fine texture/noise, no extra background elements, no additional characters.
- Very readable as a tiny 100px Telegram sticker/icon.

BACKGROUND — CRITICAL, DO NOT IGNORE:
- The background MUST be fully transparent: a real PNG alpha channel, with zero opaque
  pixels outside the character's silhouette and its white sticker border.
- Do NOT render a checkerboard/grid pattern as actual pixels. Do NOT render a white,
  grey, or any solid-color background. "Transparent" means see-through alpha, not an
  image of a transparent-looking pattern.
- When exporting/downloading the result, export or download the actual PNG file with
  its alpha channel intact — do not save a flattened screenshot of an on-screen preview,
  since preview UIs often draw a grey/checker pattern as a stand-in for transparency and
  that pattern must never end up baked into the final pixels.

CAPTION TEXT — CRITICAL, DO NOT IGNORE:
- Reproduce the caption text EXACTLY character-for-character as given below, including
  every diacritic and special Avar letter (е.g. Ӏ/ӏ "palochka", ь, ъ). Do not "correct",
  simplify, transliterate, or substitute any letter. Copy the exact Cyrillic string given,
  letter by letter, as if copy-pasting it.
- Caption text is dark navy, bold, rounded font, rendered directly on the sticker below
  the character, matching the look of the reference sticker.

Consistent proportions with the character sheet (see ../concepts/character.md).
Color palette limited to 6 core colors.

Curious puzzled expression, eyebrows raised in surprise, one gloved hand pointing at a giant standalone letter "Ӏ" (palochka) floating next to the character, exclamation and question marks above the head, the other hand open in a questioning shrug gesture.
Caption text rendered on the sticker (dark navy, bold, rounded font, below the character): "Гьаб щи хӏарп?"
```

**Caption overlay (текст на стикере):** "Гьаб щи хӏарп?"

**Известная особенность:** большая буква-загадка на картинке получилась похожей на
"Лі", а не на чистую палочку "Ӏ" — принято как декоративный элемент, не критично.
