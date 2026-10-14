# Where the content comes from

This is a single-page site: `src/content/bhajans.ts` is a hand-written
TypeScript file holding all bhajans (no build-time content-generation
script, unlike the sibling Bhagwad Gita / Ashtavakra Gita sites), following
the same single-page pattern as the sibling Aarti Sangrah site.

Verse text only — no meaning/translation, matching the rest of this family
of sites. All compositions are traditionally attributed to Meera Bai
(c. 1498–1547), a 16th-century Rajasthani poet-saint and Krishna devotee —
public domain devotional poetry, author deceased roughly 500 years ago.
Presented as the commonly-sung core verses/refrain of each bhajan (not a
full critical-edition padavali — oral-tradition songs like these also carry
genuine regional variation in wording across sources).

## Adding a new bhajan

1. Add a new entry to the `bhajans` array in `src/content/bhajans.ts`
   (`slug`, `title`, `subtitle`, `verses`).
2. The home page (`src/app/page.tsx`) renders every entry in that array
   automatically — no other file needs to change.

## Audio

Not included, matching the rest of this family of sites.
