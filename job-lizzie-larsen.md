# Job — build the Lizzie Larsen character

---
name: Lizzie Larsen — Higgsfield Prompt Pack
description: Character-creation job (cold synthetic build, no source photo) + 40 ambient b-roll prompts
type: project
status: not started
---

# Lizzie Larsen — Higgsfield Prompt Pack

Two parts. **Part 1** builds the character from nothing — she's fully synthetic, no
source photo, so there is no Element to seed the batch. **Part 2** is 40 b-roll prompts
for once the Soul and Element exist, following the house rules in
`../../docs/research/broll-prompting-best-practice.md`.

---

# PART 1 — Character creation job

Paste everything in this section into a browser agent working in the Higgsfield web app.
It cannot read files, so nothing below refers out to one — the identity string, the
tail, and all 21 shot prompts are inlined in full.

## Read before running anything

Lizzie has **no source photo**. The identity string below *is* the source. That means:

- There is **no Element to attach** to the 21 coverage shots. Generate them cold.
- Cold generation drifts. Budget **3–4 variants per slot**, not 1–2 — with nothing
  anchoring the face, drift across the batch is the main risk, not a side risk.
- Curate hard down to **22–26 keepers**, judged only on *is this the same woman as the
  rest of the set?* — not on which frame is prettiest.
- **Only after the Soul is trained** do you build the Element, from the keepers.

### The trap this brief exists to prevent

Lizzie's entire on-screen premise is "unpolished, real, slightly scrappy." It is
extremely tempting to bake that into the *training* images — add a bit of handheld
grain, an off-centre frame, a phone-camera look, because "that's her vibe." **Do not.**
Training images are always clean, evenly lit, neutral, and studio-flat, regardless of
whose face they're teaching. Phone realism, mess, bad lighting — all of that is applied
at *generation* time, on real content, once the Soul already exists. Train on scrappy
images and the model learns the grain instead of the face, permanently. This is the
single most expensive mistake available on this persona specifically, because the
scrappy premise makes it feel correct to do the wrong thing.

Second trap: her **grown-out roots are load-bearing**. They are the one visual detail
that stops her reading as a polished brand asset instead of a real small creator. The
identity string mentions them in every single prompt for exactly this reason — do not
let a lighting note, a hair-back shot, or a "clean up her hair" instinct tidy them away.
If a generated image looks polished enough that the roots have vanished or blended in,
reject it, even if the face is otherwise good.

## The identity string — byte-identical in every prompt below

```
A 29-year-old white woman with a heart-shaped face and a light warm complexion, with faint freckles scattered across the nose and upper cheeks. Wide-set green-hazel eyes, light brown eyebrows with a soft natural arch, a small slightly upturned nose, and a wide mouth with a thin upper lip. Shoulder-length dark-blonde hair with a natural wave and visibly grown-out roots, usually pushed back behind one ear. A small plain stud in each earlobe.
```

Never paraphrase it. It only changes in shots 9 and 13 below, where the *hair clause
specifically* is swapped for a variant that still names the grown-out roots — everything
else in the string stays identical.

## The tail — shared, verbatim

```
Clean neutral studio lighting, plain mid-grey seamless background, sharp focus on the face, realistic skin texture with visible pores and natural shine, no retouching, no beauty filter. No text, no logos, no watermark.
```

For shots 11 and 14 (the two lighting-variant shots), the tail's first clause changes —
noted inline.

## Procedure

1. **Model:** assigned per shot group — see **Generation settings** below. No Element attached to any of the
   21 — check your plan covers these models before starting a batch this size.
2. **Generate 21 coverage shots, 3–4 variants each** (below). Cold — no reference image,
   no Element.
3. **Curate to 22–26 keepers.** Face-dominant — roughly two-thirds should be
   head-and-shoulders, the rest for proportion and hands. Reject anything that has
   drifted younger, thinner, more generic, or more symmetrical than the rest of the
   set, and reject anything where the roots have been smoothed away. See
   `../maya-miller/character-sheet.md` → **Coverage** section for the full reasoning on
   why 21 shots (not the smaller 12) and why face-only coverage under-serves video —
   proportions, hands, head turns, hair in motion, and wardrobe-as-identity all need
   their own shots or video drifts constantly.
4. **Train the Soul** — name it `Lizzie Larsen`, model **Soul 2.0** (not Soul Cinematic),
   upload the 22–26 keepers. Report the Soul ID (UUID).
5. **Build the Element from the keepers** — not from a single new render. Use the best
   front-on chest-up keeper, plus a three-quarter, plus a full-length, so the Element
   carries proportions as well as face. Report the Element ID.
6. **Validate with 2–3 test generations** using the trained Soul, 9:16, 2K. This is
   where phone realism is *finally* allowed — apply it now, not before. A quick sanity
   prompt: waist-up, Lizzie at a cluttered desk on a laptop, shot on an iPhone with
   handheld shake, natural window light, hair pushed back with the roots visible. Check
   the roots survived and the wardrobe reads as unstyled, not aspirational.
7. **Report back:** Soul ID, Element ID, how many keepers and where they're stored,
   whether the roots are visibly intact across the set, and anything that showed a
   credit cost you weren't expecting.

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

## The 21 coverage shots

Each one below is the complete prompt — identity string (or its shots 9/13 variant) +
shot line + tail (or its shots 11/14 variant) — ready to paste as-is.

**A · Face geometry (1–8)**

```
1 — Straight-on, neutral
A 29-year-old white woman with a heart-shaped face and a light warm complexion, with faint freckles scattered across the nose and upper cheeks. Wide-set green-hazel eyes, light brown eyebrows with a soft natural arch, a small slightly upturned nose, and a wide mouth with a thin upper lip. Shoulder-length dark-blonde hair with a natural wave and visibly grown-out roots, usually pushed back behind one ear. A small plain stud in each earlobe. Head-and-shoulders headshot, facing the camera straight on, neutral expression, mouth closed, eyes to lens. Clean neutral studio lighting, plain mid-grey seamless background, sharp focus on the face, realistic skin texture with visible pores and natural shine, no retouching, no beauty filter. No text, no logos, no watermark.
```

```
2 — Straight-on, warm smile
A 29-year-old white woman with a heart-shaped face and a light warm complexion, with faint freckles scattered across the nose and upper cheeks. Wide-set green-hazel eyes, light brown eyebrows with a soft natural arch, a small slightly upturned nose, and a wide mouth with a thin upper lip. Shoulder-length dark-blonde hair with a natural wave and visibly grown-out roots, usually pushed back behind one ear. A small plain stud in each earlobe. Head-and-shoulders headshot, facing the camera straight on, warm closed-mouth smile, eyes to lens. Clean neutral studio lighting, plain mid-grey seamless background, sharp focus on the face, realistic skin texture with visible pores and natural shine, no retouching, no beauty filter. No text, no logos, no watermark.
```

```
3 — Straight-on, open laugh
A 29-year-old white woman with a heart-shaped face and a light warm complexion, with faint freckles scattered across the nose and upper cheeks. Wide-set green-hazel eyes, light brown eyebrows with a soft natural arch, a small slightly upturned nose, and a wide mouth with a thin upper lip. Shoulder-length dark-blonde hair with a natural wave and visibly grown-out roots, usually pushed back behind one ear. A small plain stud in each earlobe. Head-and-shoulders headshot, facing the camera straight on, open genuine laugh, teeth showing, eyes crinkled. Clean neutral studio lighting, plain mid-grey seamless background, sharp focus on the face, realistic skin texture with visible pores and natural shine, no retouching, no beauty filter. No text, no logos, no watermark.
```

```
4 — Three-quarter left, neutral
A 29-year-old white woman with a heart-shaped face and a light warm complexion, with faint freckles scattered across the nose and upper cheeks. Wide-set green-hazel eyes, light brown eyebrows with a soft natural arch, a small slightly upturned nose, and a wide mouth with a thin upper lip. Shoulder-length dark-blonde hair with a natural wave and visibly grown-out roots, usually pushed back behind one ear. A small plain stud in each earlobe. Head-and-shoulders headshot, head and body turned three-quarters to her left, neutral expression, eyes back to lens. Clean neutral studio lighting, plain mid-grey seamless background, sharp focus on the face, realistic skin texture with visible pores and natural shine, no retouching, no beauty filter. No text, no logos, no watermark.
```

```
5 — Three-quarter right, slight smile
A 29-year-old white woman with a heart-shaped face and a light warm complexion, with faint freckles scattered across the nose and upper cheeks. Wide-set green-hazel eyes, light brown eyebrows with a soft natural arch, a small slightly upturned nose, and a wide mouth with a thin upper lip. Shoulder-length dark-blonde hair with a natural wave and visibly grown-out roots, usually pushed back behind one ear. A small plain stud in each earlobe. Head-and-shoulders headshot, head and body turned three-quarters to her right, slight smile, eyes back to lens. Clean neutral studio lighting, plain mid-grey seamless background, sharp focus on the face, realistic skin texture with visible pores and natural shine, no retouching, no beauty filter. No text, no logos, no watermark.
```

```
6 — Full profile
A 29-year-old white woman with a heart-shaped face and a light warm complexion, with faint freckles scattered across the nose and upper cheeks. Wide-set green-hazel eyes, light brown eyebrows with a soft natural arch, a small slightly upturned nose, and a wide mouth with a thin upper lip. Shoulder-length dark-blonde hair with a natural wave and visibly grown-out roots, usually pushed back behind one ear. A small plain stud in each earlobe. Head-and-shoulders headshot in full left profile, ninety degrees to camera, neutral expression, looking off-frame. Clean neutral studio lighting, plain mid-grey seamless background, sharp focus on the face, realistic skin texture with visible pores and natural shine, no retouching, no beauty filter. No text, no logos, no watermark.
```

```
7 — Chin down, eyes up
A 29-year-old white woman with a heart-shaped face and a light warm complexion, with faint freckles scattered across the nose and upper cheeks. Wide-set green-hazel eyes, light brown eyebrows with a soft natural arch, a small slightly upturned nose, and a wide mouth with a thin upper lip. Shoulder-length dark-blonde hair with a natural wave and visibly grown-out roots, usually pushed back behind one ear. A small plain stud in each earlobe. Head-and-shoulders headshot, chin slightly lowered, eyes up to lens, faint knowing half-smile. Clean neutral studio lighting, plain mid-grey seamless background, sharp focus on the face, realistic skin texture with visible pores and natural shine, no retouching, no beauty filter. No text, no logos, no watermark.
```

```
8 — Chin up, confident
A 29-year-old white woman with a heart-shaped face and a light warm complexion, with faint freckles scattered across the nose and upper cheeks. Wide-set green-hazel eyes, light brown eyebrows with a soft natural arch, a small slightly upturned nose, and a wide mouth with a thin upper lip. Shoulder-length dark-blonde hair with a natural wave and visibly grown-out roots, usually pushed back behind one ear. A small plain stud in each earlobe. Head-and-shoulders headshot, chin slightly raised, confident and composed, mouth closed, eyes to lens. Clean neutral studio lighting, plain mid-grey seamless background, sharp focus on the face, realistic skin texture with visible pores and natural shine, no retouching, no beauty filter. No text, no logos, no watermark.
```

**C · Hair states (9, 13)** — note the identity string's hair clause changes here, and
still names the roots.

```
9 — Hair back (jawline + hairline)
A 29-year-old white woman with a heart-shaped face and a light warm complexion, with faint freckles scattered across the nose and upper cheeks. Wide-set green-hazel eyes, light brown eyebrows with a soft natural arch, a small slightly upturned nose, and a wide mouth with a thin upper lip. Dark-blonde hair pulled back off the face into a low ponytail, visibly grown-out roots clearly visible along the parting and at the crown. A small plain stud in each earlobe. Head-and-shoulders headshot, facing the camera straight on, neutral expression, hairline and both ears fully visible, jawline and neck clear. Clean neutral studio lighting, plain mid-grey seamless background, sharp focus on the face, realistic skin texture with visible pores and natural shine, no retouching, no beauty filter. No text, no logos, no watermark.
```

```
13 — Hair tucked one side, one ear visible
A 29-year-old white woman with a heart-shaped face and a light warm complexion, with faint freckles scattered across the nose and upper cheeks. Wide-set green-hazel eyes, light brown eyebrows with a soft natural arch, a small slightly upturned nose, and a wide mouth with a thin upper lip. Shoulder-length dark-blonde hair with a natural wave, tucked behind one ear so that ear is visible while the other side falls loose across the cheek, visibly grown-out roots clearly visible at the parting. A small plain stud in each earlobe. Head-and-shoulders headshot, facing the camera straight on, neutral expression, eyes to lens. Clean neutral studio lighting, plain mid-grey seamless background, sharp focus on the face, realistic skin texture with visible pores and natural shine, no retouching, no beauty filter. No text, no logos, no watermark.
```

**D · Lighting (11, 12, 14)**

```
11 — Hard side light
A 29-year-old white woman with a heart-shaped face and a light warm complexion, with faint freckles scattered across the nose and upper cheeks. Wide-set green-hazel eyes, light brown eyebrows with a soft natural arch, a small slightly upturned nose, and a wide mouth with a thin upper lip. Shoulder-length dark-blonde hair with a natural wave and visibly grown-out roots, usually pushed back behind one ear. A small plain stud in each earlobe. Head-and-shoulders headshot, facing the camera straight on, neutral expression. Hard directional light from camera-left casting a defined shadow across the other side of the face, plain mid-grey seamless background, sharp focus on the face, realistic skin texture with visible pores and natural shine, no retouching, no beauty filter. No text, no logos, no watermark.
```

```
12 — Flat frontal light
A 29-year-old white woman with a heart-shaped face and a light warm complexion, with faint freckles scattered across the nose and upper cheeks. Wide-set green-hazel eyes, light brown eyebrows with a soft natural arch, a small slightly upturned nose, and a wide mouth with a thin upper lip. Shoulder-length dark-blonde hair with a natural wave and visibly grown-out roots, usually pushed back behind one ear. A small plain stud in each earlobe. Head-and-shoulders headshot, facing the camera straight on, neutral expression. Completely flat soft frontal light, no visible shadow anywhere, plain mid-grey seamless background, sharp focus on the face, realistic skin texture with visible pores and natural shine, no retouching, no beauty filter. No text, no logos, no watermark.
```

```
14 — Backlit by a window
A 29-year-old white woman with a heart-shaped face and a light warm complexion, with faint freckles scattered across the nose and upper cheeks. Wide-set green-hazel eyes, light brown eyebrows with a soft natural arch, a small slightly upturned nose, and a wide mouth with a thin upper lip. Shoulder-length dark-blonde hair with a natural wave and visibly grown-out roots, usually pushed back behind one ear. A small plain stud in each earlobe. Head-and-shoulders headshot, facing the camera straight on, neutral expression, lit from behind by a bright window so the face sits in soft even shadow and the background blows out slightly. Plain mid-grey seamless background, sharp focus on the face, realistic skin texture with visible pores and natural shine, no retouching, no beauty filter. No text, no logos, no watermark.
```

**E · Body & proportion (10, 15, 16, 17)** — wardrobe pulled from her palette: oat,
washed denim, sage, warm grey. Never black, never anything styled.

```
10 — Waist-up
A 29-year-old white woman with a heart-shaped face and a light warm complexion, with faint freckles scattered across the nose and upper cheeks. Wide-set green-hazel eyes, light brown eyebrows with a soft natural arch, a small slightly upturned nose, and a wide mouth with a thin upper lip. Shoulder-length dark-blonde hair with a natural wave and visibly grown-out roots, usually pushed back behind one ear. A small plain stud in each earlobe. Waist-up, standing, arms relaxed at her sides, straight-on, neutral expression, wearing a plain oat-coloured t-shirt. Clean neutral studio lighting, plain mid-grey seamless background, sharp focus, realistic skin and fabric texture, no retouching, no beauty filter. No text, no logos, no watermark.
```

```
15 — Full-length, front-on
A 29-year-old white woman with a heart-shaped face and a light warm complexion, with faint freckles scattered across the nose and upper cheeks. Wide-set green-hazel eyes, light brown eyebrows with a soft natural arch, a small slightly upturned nose, and a wide mouth with a thin upper lip. Shoulder-length dark-blonde hair with a natural wave and visibly grown-out roots, usually pushed back behind one ear. A small plain stud in each earlobe. Full-length shot, standing, facing the camera straight on, feet visible, arms relaxed at her sides, neutral expression, wearing a plain oat t-shirt and washed straight-leg denim jeans, a hair tie visible on one wrist. Clean neutral studio lighting, plain mid-grey seamless background, sharp focus, realistic skin and fabric texture, no retouching, no beauty filter. No text, no logos, no watermark.
```

```
16 — Full-length, three-quarter, holding phone
A 29-year-old white woman with a heart-shaped face and a light warm complexion, with faint freckles scattered across the nose and upper cheeks. Wide-set green-hazel eyes, light brown eyebrows with a soft natural arch, a small slightly upturned nose, and a wide mouth with a thin upper lip. Shoulder-length dark-blonde hair with a natural wave and visibly grown-out roots, usually pushed back behind one ear. A small plain stud in each earlobe. Full-length shot, standing, turned three-quarters to her left, weight on one hip, one hand at her side and one holding a phone loosely down by her side, wearing a sage-green zip-up over a plain tee and leggings. Clean neutral studio lighting, plain mid-grey seamless background, sharp focus, realistic skin and fabric texture, no retouching, no beauty filter. No text, no logos, no watermark.
```

```
17 — Seated, hands clasped
A 29-year-old white woman with a heart-shaped face and a light warm complexion, with faint freckles scattered across the nose and upper cheeks. Wide-set green-hazel eyes, light brown eyebrows with a soft natural arch, a small slightly upturned nose, and a wide mouth with a thin upper lip. Shoulder-length dark-blonde hair with a natural wave and visibly grown-out roots, usually pushed back behind one ear. A small plain stud in each earlobe. Seated on a plain stool, facing the camera, forearms resting on her thighs, hands loosely clasped and clearly visible, leaning very slightly forward, wearing an oversized warm-grey knit with the sleeves pushed up. Clean neutral studio lighting, plain mid-grey seamless background, sharp focus, realistic skin and fabric texture, no retouching, no beauty filter. No text, no logos, no watermark.
```

**F · Hands (18, 19)**

```
18 — Mid-gesture
A 29-year-old white woman with a heart-shaped face and a light warm complexion, with faint freckles scattered across the nose and upper cheeks. Wide-set green-hazel eyes, light brown eyebrows with a soft natural arch, a small slightly upturned nose, and a wide mouth with a thin upper lip. Shoulder-length dark-blonde hair with a natural wave and visibly grown-out roots, usually pushed back behind one ear. A small plain stud in each earlobe. Waist-up, straight on, both hands raised to chest height mid-gesture as if explaining something, fingers relaxed and separated, palms angled inward. Clean neutral studio lighting, plain mid-grey seamless background, sharp focus, realistic skin texture with visible pores and natural shine, no retouching, no beauty filter. No text, no logos, no watermark.
```

```
19 — Holding a mug
A 29-year-old white woman with a heart-shaped face and a light warm complexion, with faint freckles scattered across the nose and upper cheeks. Wide-set green-hazel eyes, light brown eyebrows with a soft natural arch, a small slightly upturned nose, and a wide mouth with a thin upper lip. Shoulder-length dark-blonde hair with a natural wave and visibly grown-out roots, usually pushed back behind one ear. A small plain stud in each earlobe. Waist-up, straight on, holding a plain white mug in both hands at chest height, hands and fingers clearly visible. Clean neutral studio lighting, plain mid-grey seamless background, sharp focus, realistic skin texture with visible pores and natural shine, no retouching, no beauty filter. No text, no logos, no watermark.
```

**G · Wardrobe alternate (20, 21)** — proves the face survives an outfit change.

```
20 — Open flannel over tee
A 29-year-old white woman with a heart-shaped face and a light warm complexion, with faint freckles scattered across the nose and upper cheeks. Wide-set green-hazel eyes, light brown eyebrows with a soft natural arch, a small slightly upturned nose, and a wide mouth with a thin upper lip. Shoulder-length dark-blonde hair with a natural wave and visibly grown-out roots, usually pushed back behind one ear. A small plain stud in each earlobe. Head-and-shoulders headshot, straight on, neutral expression, wearing an open flannel shirt over a plain t-shirt, sleeves shoved up. Clean neutral studio lighting, plain mid-grey seamless background, sharp focus on the face, realistic skin texture with visible pores and natural shine, no retouching, no beauty filter. No text, no logos, no watermark.
```

```
21 — Sage zip-up, waist-up
A 29-year-old white woman with a heart-shaped face and a light warm complexion, with faint freckles scattered across the nose and upper cheeks. Wide-set green-hazel eyes, light brown eyebrows with a soft natural arch, a small slightly upturned nose, and a wide mouth with a thin upper lip. Shoulder-length dark-blonde hair with a natural wave and visibly grown-out roots, usually pushed back behind one ear. A small plain stud in each earlobe. Waist-up, straight on, neutral expression, wearing a sage-green zip-up over a plain tee. Clean neutral studio lighting, plain mid-grey seamless background, sharp focus, realistic skin and fabric texture, no retouching, no beauty filter. No text, no logos, no watermark.
```

---

#
