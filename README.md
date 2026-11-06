# Veda Bharath · User Management

## Current rice-paddy artwork

The local dashboard now uses `dist/assets/rice-paddy.webp`, generated with the built-in image tool. It depicts branching rice panicles and green paddy leaves. It replaces the previous wheat-like harvest illustration. The small community dial uses a leaf icon instead of the former grain image. Earlier harvest notes below are historical.

Final rice-paddy prompt:

> Use case: photorealistic-natural. Asset type: 1536x1024 landscape photographic background for Veda Bharath rice dashboard. Subject: authentic Indian RICE PADDY, Oryza sativa, near harvest. Close-up gracefully drooping OPEN BRANCHING rice panicles on the right and lower half: thin branching stems bearing many separate small elongated golden-green unhusked rice grains on fine pedicels, with long narrow arching GREEN rice leaves. Recognizably rice, botanically distinct from wheat. Background: lush Indian paddy field in gentle morning sunlight, green and straw-gold, softly blurred. Composition: main rice panicle lower right, foliage and paddy bottom half, bright white/ivory negative space in upper half and upper left for HTML headings. Premium natural editorial photography, soft depth of field, green and warm golden tones matching an agricultural brand. No text, no labels, no logo, no gauges, no borders, no UI. Absolutely NO wheat, NO barley, NO compact cylindrical grain spikes, NO braided wheat ears, NO wheat awns. Rice grows in airy branching loose clusters, never dense symmetrical ears. Make the branching rice panicles and green blades clearly visible.

A separate, buildless dashboard based on the supplied design-system document, logo, screen recording and live Super Admin pages. Uses the original Figtree font and Veda Bharath logo. No dependencies or build step.

Run locally: `python3 -m http.server 4173 --directory dist`.

Includes overview summaries, customer directory, warehouse network, administrator management, search, status/location filters, sorting, pagination, CSV export, detail/edit/create dialogs, activity history and browser-local persistence. Sample records do not update the original Veda Bharath application. Creating an administrator does not send an invitation or provision access.

Local changes use the `veda-people-v1` localStorage key. No real customer information or credentials are embedded. Native dialogs handle modal focus and Escape; layouts support small screens and reduced motion.

## Reference-inspired redesign

The supplied agricultural references informed the asymmetric card grid, prominent harvest photography, floating pill navigation, large metrics, a dark contrast card, restrained chart bars and a soft backdrop. The implementation retains Veda Bharath's logo, Figtree, orange primary actions, green state cues, rounded surfaces, existing data and management workflows. Background colors derive from the design system's green and orange soft surfaces. This revision is hosted locally; it has not replaced the previously published Site.

Hero asset: `dist/assets/harvest-editorial.webp`. Prepared with the built-in image-generation tool from the original application's harvest banner, then encoded as WebP. The original logo is unchanged. `dist/assets/rice-grain.png` is the original application's grain image.

Final image prompt:

> Edit this existing Veda Bharath dashboard harvest banner into a clean photographic background asset for a large dashboard card, landscape 1536x1024. Preserve the recognizable golden grain ear on the right with sunlit golden crops below, amber and warm cream colors, natural materials, premium soft photographic lighting. Remove ALL typography and labels, including the Organic and Healthy pills. Remove the circular white gauge graphic entirely. Fill the top half and upper left with soft pure white / near-white light gradually blending naturally into the golden harvest lower half. Main detailed grain ear on the lower right, plenty of calm bright white negative space upper left for HTML heading. Crop more like a closeup editorial agriculture photograph, no orange flat block, no graphic gauge. Image only: no words, no text, no labels, no logos, no interface elements, no borders, no rounded corners.
