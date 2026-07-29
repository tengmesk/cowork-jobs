# Job — build the Rodrigo Maxwell character

---
name: Rodrigo Maxwell — Higgsfield Prompt Pack
description: Paste-ready character-creation job (21 cold coverage shots, no Element) plus 40 Element-driven b-roll prompts for Seedance 2.0
type: project
brand: Tapglide
status: not started — fully synthetic, no source photo
---

# Rodrigo Maxwell — Higgsfield Prompt Pack

Two parts. **Part 1** builds the character from nothing — Rodrigo has no source
photo, so there is no Element to seed the batch; the 21 coverage shots are
generated cold and the Element is built *after* the Soul, from the keepers.
**Part 2** is the 40-prompt b-roll library that uses the finished Element.

Full house rules: `../../docs/research/broll-prompting-best-practice.md`.
Coverage reasoning: `../maya-miller/character-sheet.md` (Coverage section).
Bootstrap construction rules: `../_shared/bootstrap-shot-list.md`.

---

## PART 1 — Character creation job

**For a browser agent with no file access.** Every prompt below is fully
self-contained — copy one block, paste it whole into the Higgsfield web app,
generate, move to the next. Nothing here refers back to another file.

### Job parameters

- **Model:** assigned per shot group — see **Generation settings** below. 2K, web app.
- **No Element, no reference image attached to any of these 21.** Rodrigo is
  fully synthetic — the identity string below is the only source of his face.
  Do not attach anything.
- **Variants per prompt: 3–4**, not 2–3. With nothing anchoring the face,
  drift across the batch is the main failure mode, and more variants per slot
  is the only defence.
- **Training images are clean, neutral and evenly lit. No phone-camera
  language, no handheld, no grain, no HDR, no off-centre framing.** Save all
  of that for Part 2. Training on gritty phone-style images teaches the model
  the grain instead of the face, and that is permanent.
- After generating all 21 (63–84 raw images), **curate to 22–26 keepers**,
  face-dominant at roughly two-thirds head-and-shoulders. Judge every keeper
  on one question only: *is this unmistakably the same man?* Reject anything
  that drifted younger, thinner, more generic or more symmetrical than the
  rest of the set.
- **Train the Soul** (Soul 2.0, not Soul Cinematic) on the 22–26 keepers.
- **Then build the Element** from the keepers — feed it the best front-on
  chest-up keeper with hands visible (shot 18 or 19 below), plus the best
  three-quarter (shot 16) and the best full-length (shot 15), so the Element
  carries his proportions as well as his face. The Element is what Part 2 and
  all future video runs on.

## Generation settings

### Which model for which shot — do not scatter them

Three models are used deliberately, assigned **by shot group**, not at random. Each model
renders faces slightly differently, so scattering them across the set would average three
faces together — which is exactly the drift we are trying to avoid on a character with no
source photo.

| Shots | Model | Why |
|---|---|---|
| **1–8, plus 9 and 13** (10 shots) | **Nano Banana Pro, 2K** | The identity core — front, three-quarters, profiles, chin up/down, hair back. These define the face. Best model, one model, no mixing. |
| **11, 12, 14, 20, 21** (5 shots) | **GPT Image 2, 2K** | Lighting variants and the wardrobe alternates. Face is already established by the group above; these test that it survives different light and clothes. |
| **10, 15, 16, 17, 18, 19** (6 shots) | **Nano Banana 2, 2K** | Body, proportion and hands. Framing is wider, so per-image face detail matters least here. |

If any shot from the Nano Banana Pro group comes out inconsistent with the others,
**regenerate it on Nano Banana Pro** — do not substitute a different model to get a
result you like better. The identity group must stay single-model.

### Everything else

- **2K. Web app. No Reference Element attached** — there is nothing to attach yet; this
  batch *creates* the source material the Element will later be built from.
- Generate **3–4 variants of every one of the 21 shots**, not 2–3. With no photo anchoring
  the face, drift across the batch is the main risk.

### Lighting — vary the angle deliberately

Do not let every shot default to the same flat frontal key. Across the set the light
should come from genuinely different directions, because a Soul trained under one lighting
condition renders badly the moment a scene lights the face differently.

Where a shot line already specifies its lighting, use exactly that. Where it does not,
rotate through these so the set covers all of them:

| Angle | How to phrase it |
|---|---|
| Flat frontal | `flat soft frontal lighting, no visible shadow on the face` |
| Side, camera-left | `hard directional light from camera-left, defined shadow down the right side of the face` |
| Side, camera-right | `directional light from camera-right, soft shadow falling across the left of the face` |
| Three-quarter / Rembrandt | `key light high and forty-five degrees to one side, a small triangle of light under the far eye` |
| Backlit | `lit from behind by a bright window, face in soft even shadow, background blown out` |
| Overhead | `light from directly above, shadow pooling slightly under the brows and nose` |

**Lighting only — never change the background, wardrobe or expression to suit it.** One
variable at a time. Changing two at once is where identity drift starts.

### Consistency is the whole job

The set exists to teach a model one face. Judge every single variant against the same
question: **is this unmistakably the same person as the rest of the batch?**

- Compare each new variant against the ones already kept, not against the prompt.
- Reject on **bone structure** first — face width, jaw, brow, eye spacing, nose. Those are
  identity. Hair, expression and lighting are not.
- Reject anything that has drifted **younger, thinner, more symmetrical or more generic**.
  Models pull toward an averaged attractive face; that pull is the enemy here.
- A slightly awkward but accurate frame beats a flattering but drifted one, every time.
- If more than a third of a shot's variants drift, **stop and say so** rather than keeping
  the best of a bad batch. It means the identity string needs strengthening, and it is far
  cheaper to fix that now than after the Soul is trained.


### Identity string — byte-identical in every one of the 21 prompts below

> A 28-year-old Latino man. Warm mid-brown skin with a neutral undertone. Square jaw with a defined chin, straight dark eyebrows set close to deep-set dark brown eyes, a straight nose with a slightly broad base, and full lips. Short black hair, thick and slightly wavy, cropped close at the sides and left longer on top, pushed back off the forehead. Neatly kept dark stubble across the jaw and upper lip. A small silver hoop in his left ear.

Never paraphrase it. It appears verbatim in every prompt below — that is
what makes the batch cohere.

---

### 1 — Straight-on, neutral

```
A 28-year-old Latino man. Warm mid-brown skin with a neutral undertone. Square jaw with a defined chin, straight dark eyebrows set close to deep-set dark brown eyes, a straight nose with a slightly broad base, and full lips. Short black hair, thick and slightly wavy, cropped close at the sides and left longer on top, pushed back off the forehead. Neatly kept dark stubble across the jaw and upper lip. A small silver hoop in his left ear. Head-and-shoulders headshot, facing the camera straight on, neutral expression, mouth closed, eyes to lens. Clean neutral studio lighting, plain mid-grey seamless background, sharp focus on the face, realistic skin texture with visible pores and natural shine, no retouching, no beauty filter. No text, no logos, no watermark.
```

### 2 — Straight-on, warm smile

```
A 28-year-old Latino man. Warm mid-brown skin with a neutral undertone. Square jaw with a defined chin, straight dark eyebrows set close to deep-set dark brown eyes, a straight nose with a slightly broad base, and full lips. Short black hair, thick and slightly wavy, cropped close at the sides and left longer on top, pushed back off the forehead. Neatly kept dark stubble across the jaw and upper lip. A small silver hoop in his left ear. Head-and-shoulders headshot, facing the camera straight on, warm closed-mouth smile, eyes to lens. Clean neutral studio lighting, plain mid-grey seamless background, sharp focus on the face, realistic skin texture with visible pores and natural shine, no retouching, no beauty filter. No text, no logos, no watermark.
```

### 3 — Straight-on, open laugh

```
A 28-year-old Latino man. Warm mid-brown skin with a neutral undertone. Square jaw with a defined chin, straight dark eyebrows set close to deep-set dark brown eyes, a straight nose with a slightly broad base, and full lips. Short black hair, thick and slightly wavy, cropped close at the sides and left longer on top, pushed back off the forehead. Neatly kept dark stubble across the jaw and upper lip. A small silver hoop in his left ear. Head-and-shoulders headshot, facing the camera straight on, open genuine laugh, teeth showing, eyes crinkled. Clean neutral studio lighting, plain mid-grey seamless background, sharp focus on the face, realistic skin texture with visible pores and natural shine, no retouching, no beauty filter. No text, no logos, no watermark.
```

### 4 — Three-quarter left, neutral

```
A 28-year-old Latino man. Warm mid-brown skin with a neutral undertone. Square jaw with a defined chin, straight dark eyebrows set close to deep-set dark brown eyes, a straight nose with a slightly broad base, and full lips. Short black hair, thick and slightly wavy, cropped close at the sides and left longer on top, pushed back off the forehead. Neatly kept dark stubble across the jaw and upper lip. A small silver hoop in his left ear. Head-and-shoulders headshot, head and body turned three-quarters to his left, neutral expression, eyes back to lens. Clean neutral studio lighting, plain mid-grey seamless background, sharp focus on the face, realistic skin texture with visible pores and natural shine, no retouching, no beauty filter. No text, no logos, no watermark.
```

### 5 — Three-quarter right, slight smile

```
A 28-year-old Latino man. Warm mid-brown skin with a neutral undertone. Square jaw with a defined chin, straight dark eyebrows set close to deep-set dark brown eyes, a straight nose with a slightly broad base, and full lips. Short black hair, thick and slightly wavy, cropped close at the sides and left longer on top, pushed back off the forehead. Neatly kept dark stubble across the jaw and upper lip. A small silver hoop in his left ear. Head-and-shoulders headshot, head and body turned three-quarters to his right, slight closed-mouth smile, eyes back to lens. Clean neutral studio lighting, plain mid-grey seamless background, sharp focus on the face, realistic skin texture with visible pores and natural shine, no retouching, no beauty filter. No text, no logos, no watermark.
```

### 6 — Full profile

```
A 28-year-old Latino man. Warm mid-brown skin with a neutral undertone. Square jaw with a defined chin, straight dark eyebrows set close to deep-set dark brown eyes, a straight nose with a slightly broad base, and full lips. Short black hair, thick and slightly wavy, cropped close at the sides and left longer on top, pushed back off the forehead. Neatly kept dark stubble across the jaw and upper lip. A small silver hoop in his left ear. Head-and-shoulders headshot in full left profile, ninety degrees to camera, neutral expression, looking off-frame, the silver hoop clearly visible. Clean neutral studio lighting, plain mid-grey seamless background, sharp focus on the face, realistic skin texture with visible pores and natural shine, no retouching, no beauty filter. No text, no logos, no watermark.
```

### 7 — Chin down, eyes up

```
A 28-year-old Latino man. Warm mid-brown skin with a neutral undertone. Square jaw with a defined chin, straight dark eyebrows set close to deep-set dark brown eyes, a straight nose with a slightly broad base, and full lips. Short black hair, thick and slightly wavy, cropped close at the sides and left longer on top, pushed back off the forehead. Neatly kept dark stubble across the jaw and upper lip. A small silver hoop in his left ear. Head-and-shoulders headshot, chin slightly lowered, eyes raised to the lens, faint knowing half-smile. Clean neutral studio lighting, plain mid-grey seamless background, sharp focus on the face, realistic skin texture with visible pores and natural shine, no retouching, no beauty filter. No text, no logos, no watermark.
```

### 8 — Chin up, confident

```
A 28-year-old Latino man. Warm mid-brown skin with a neutral undertone. Square jaw with a defined chin, straight dark eyebrows set close to deep-set dark brown eyes, a straight nose with a slightly broad base, and full lips. Short black hair, thick and slightly wavy, cropped close at the sides and left longer on top, pushed back off the forehead. Neatly kept dark stubble across the jaw and upper lip. A small silver hoop in his left ear. Head-and-shoulders headshot, chin slightly raised, confident and composed, mouth closed, eyes to lens. Clean neutral studio lighting, plain mid-grey seamless background, sharp focus on the face, realistic skin texture with visible pores and natural shine, no retouching, no beauty filter. No text, no logos, no watermark.
```

### 9 — Hair fully back (jawline + hairline)

```
A 28-year-old Latino man. Warm mid-brown skin with a neutral undertone. Square jaw with a defined chin, straight dark eyebrows set close to deep-set dark brown eyes, a straight nose with a slightly broad base, and full lips. Short black hair, thick and slightly wavy, cropped close at the sides and left longer on top, pushed back off the forehead. Neatly kept dark stubble across the jaw and upper lip. A small silver hoop in his left ear. Head-and-shoulders headshot, facing the camera straight on, hair pushed fully back off the face, hairline and both ears visible, the silver hoop clearly visible, jaw and neck clear, neutral expression. Clean neutral studio lighting, plain mid-grey seamless background, sharp focus on the face, realistic skin texture with visible pores and natural shine, no retouching, no beauty filter. No text, no logos, no watermark.
```

### 10 — Waist-up (proportions)

```
A 28-year-old Latino man. Warm mid-brown skin with a neutral undertone. Square jaw with a defined chin, straight dark eyebrows set close to deep-set dark brown eyes, a straight nose with a slightly broad base, and full lips. Short black hair, thick and slightly wavy, cropped close at the sides and left longer on top, pushed back off the forehead. Neatly kept dark stubble across the jaw and upper lip. A small silver hoop in his left ear. Waist-up shot, standing, facing the camera straight on, arms relaxed at his sides, neutral expression, wearing a heavyweight black plain t-shirt. Clean neutral studio lighting, plain mid-grey seamless background, sharp focus, realistic skin texture and fabric texture, no retouching, no beauty filter. No text, no logos, no watermark.
```

### 11 — Hard side light

```
A 28-year-old Latino man. Warm mid-brown skin with a neutral undertone. Square jaw with a defined chin, straight dark eyebrows set close to deep-set dark brown eyes, a straight nose with a slightly broad base, and full lips. Short black hair, thick and slightly wavy, cropped close at the sides and left longer on top, pushed back off the forehead. Neatly kept dark stubble across the jaw and upper lip. A small silver hoop in his left ear. Head-and-shoulders headshot, facing the camera straight on, neutral expression. Hard directional light from camera-left casting a defined shadow across the right side of his face, plain mid-grey seamless background, sharp focus on the face, realistic skin texture with visible pores and natural shine, no retouching, no beauty filter. No text, no logos, no watermark.
```

### 12 — Flat frontal light

```
A 28-year-old Latino man. Warm mid-brown skin with a neutral undertone. Square jaw with a defined chin, straight dark eyebrows set close to deep-set dark brown eyes, a straight nose with a slightly broad base, and full lips. Short black hair, thick and slightly wavy, cropped close at the sides and left longer on top, pushed back off the forehead. Neatly kept dark stubble across the jaw and upper lip. A small silver hoop in his left ear. Head-and-shoulders headshot, facing the camera straight on, neutral expression. Completely flat soft frontal lighting with no visible shadow anywhere on the face, plain mid-grey seamless background, sharp focus on the face, realistic skin texture with visible pores and natural shine, no retouching, no beauty filter. No text, no logos, no watermark.
```

### 13 — Hair damp and pushed back (alt hair state)

```
A 28-year-old Latino man. Warm mid-brown skin with a neutral undertone. Square jaw with a defined chin, straight dark eyebrows set close to deep-set dark brown eyes, a straight nose with a slightly broad base, and full lips. Short black hair, thick and slightly wavy, cropped close at the sides and left longer on top, pushed back off the forehead. Neatly kept dark stubble across the jaw and upper lip. A small silver hoop in his left ear. Head-and-shoulders headshot, straight on, neutral expression, hair damp and pushed straight back off the forehead with visible comb lines, both ears and the silver hoop visible. Clean neutral studio lighting, plain mid-grey seamless background, sharp focus on the face, realistic skin texture with visible pores and natural shine, no retouching, no beauty filter. No text, no logos, no watermark.
```

### 14 — Backlit by a window

```
A 28-year-old Latino man. Warm mid-brown skin with a neutral undertone. Square jaw with a defined chin, straight dark eyebrows set close to deep-set dark brown eyes, a straight nose with a slightly broad base, and full lips. Short black hair, thick and slightly wavy, cropped close at the sides and left longer on top, pushed back off the forehead. Neatly kept dark stubble across the jaw and upper lip. A small silver hoop in his left ear. Head-and-shoulders headshot, straight on, neutral expression, lit from behind by a bright window so the face is in soft even shadow and the background blows out to white. Sharp focus on the face, realistic skin texture with visible pores and natural shine, no retouching, no beauty filter. No text, no logos, no watermark.
```

### 15 — Full-length, front-on (Element proportion source)

```
A 28-year-old Latino man. Warm mid-brown skin with a neutral undertone. Square jaw with a defined chin, straight dark eyebrows set close to deep-set dark brown eyes, a straight nose with a slightly broad base, and full lips. Short black hair, thick and slightly wavy, cropped close at the sides and left longer on top, pushed back off the forehead. Neatly kept dark stubble across the jaw and upper lip. A small silver hoop in his left ear. Full-length shot, standing, facing the camera straight on, feet visible, arms relaxed at his sides, neutral expression. Wearing a black heavyweight plain t-shirt under an open slate-grey unstructured overshirt, dark jeans, plain dark-strap watch. Clean neutral studio lighting, plain mid-grey seamless background, sharp focus, realistic skin texture and fabric texture, no retouching, no beauty filter. No text, no logos, no watermark.
```

### 16 — Full-length, three-quarter (Element proportion source)

```
A 28-year-old Latino man. Warm mid-brown skin with a neutral undertone. Square jaw with a defined chin, straight dark eyebrows set close to deep-set dark brown eyes, a straight nose with a slightly broad base, and full lips. Short black hair, thick and slightly wavy, cropped close at the sides and left longer on top, pushed back off the forehead. Neatly kept dark stubble across the jaw and upper lip. A small silver hoop in his left ear. Full-length shot, standing, turned three-quarters to his left, weight on one hip, one hand in his pocket and one holding a phone loosely at his side. Wearing a bone-coloured heavyweight plain t-shirt, dark tapered chinos, plain dark-strap watch. Clean neutral studio lighting, plain mid-grey seamless background, sharp focus, realistic skin texture and fabric texture, no retouching, no beauty filter. No text, no logos, no watermark.
```

### 17 — Seated, hands visible

```
A 28-year-old Latino man. Warm mid-brown skin with a neutral undertone. Square jaw with a defined chin, straight dark eyebrows set close to deep-set dark brown eyes, a straight nose with a slightly broad base, and full lips. Short black hair, thick and slightly wavy, cropped close at the sides and left longer on top, pushed back off the forehead. Neatly kept dark stubble across the jaw and upper lip. A small silver hoop in his left ear. Seated on a plain stool, facing the camera, forearms resting on his thighs, hands loosely clasped and clearly visible, leaning very slightly forward. Wearing a plain slate-grey hoodie, sleeves pushed up, over a black collarless tee, dark jeans. Clean neutral studio lighting, plain mid-grey seamless background, sharp focus, realistic skin texture and fabric texture, no retouching, no beauty filter. No text, no logos, no watermark.
```

### 18 — Hands mid-gesture (Element face+hands source)

```
A 28-year-old Latino man. Warm mid-brown skin with a neutral undertone. Square jaw with a defined chin, straight dark eyebrows set close to deep-set dark brown eyes, a straight nose with a slightly broad base, and full lips. Short black hair, thick and slightly wavy, cropped close at the sides and left longer on top, pushed back off the forehead. Neatly kept dark stubble across the jaw and upper lip. A small silver hoop in his left ear. Waist-up, straight on, both hands raised to chest height mid-gesture as if explaining something, fingers relaxed and separated, palms angled inward. Wearing a heavyweight black plain t-shirt. Clean neutral studio lighting, plain mid-grey seamless background, sharp focus, realistic skin texture and fabric texture, no retouching, no beauty filter. No text, no logos, no watermark.
```

### 19 — Hands holding a mug (Element face+hands source)

```
A 28-year-old Latino man. Warm mid-brown skin with a neutral undertone. Square jaw with a defined chin, straight dark eyebrows set close to deep-set dark brown eyes, a straight nose with a slightly broad base, and full lips. Short black hair, thick and slightly wavy, cropped close at the sides and left longer on top, pushed back off the forehead. Neatly kept dark stubble across the jaw and upper lip. A small silver hoop in his left ear. Waist-up, straight on, holding a plain white ceramic mug in both hands at chest height, hands and fingers clearly visible. Wearing a heavyweight slate-grey plain t-shirt. Clean neutral studio lighting, plain mid-grey seamless background, sharp focus, realistic skin texture and fabric texture, no retouching, no beauty filter. No text, no logos, no watermark.
```

### 20 — Wardrobe alternate, headshot

```
A 28-year-old Latino man. Warm mid-brown skin with a neutral undertone. Square jaw with a defined chin, straight dark eyebrows set close to deep-set dark brown eyes, a straight nose with a slightly broad base, and full lips. Short black hair, thick and slightly wavy, cropped close at the sides and left longer on top, pushed back off the forehead. Neatly kept dark stubble across the jaw and upper lip. A small silver hoop in his left ear. Head-and-shoulders headshot, straight on, neutral expression, wearing a plain bone-coloured heavyweight t-shirt. Clean neutral studio lighting, plain mid-grey seamless background, sharp focus on the face, realistic skin texture with visible pores and natural shine, no retouching, no beauty filter. No text, no logos, no watermark.
```

### 21 — Wardrobe alternate, waist-up

```
A 28-year-old Latino man. Warm mid-brown skin with a neutral undertone. Square jaw with a defined chin, straight dark eyebrows set close to deep-set dark brown eyes, a straight nose with a slightly broad base, and full lips. Short black hair, thick and slightly wavy, cropped close at the sides and left longer on top, pushed back off the forehead. Neatly kept dark stubble across the jaw and upper lip. A small silver hoop in his left ear. Waist-up, straight on, neutral expression, wearing a plain hoodie, sleeves pushed up, over a black collarless tee. Clean neutral studio lighting, plain mid-grey seamless background, sharp focus, realistic skin texture and fabric texture, no retouching, no beauty filter. No text, no logos, no watermark.
```

---

##
