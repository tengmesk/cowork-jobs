# Job — build the Tim Tanner character

---
name: Tim Tanner — Higgsfield Prompt Pack
description: Character-creation job (paste-ready, no file access needed) + 40 b-roll prompts for the trained Soul/Element
type: project
status: not started — Soul not yet trained
---

# Tim Tanner — Higgsfield Prompt Pack

Two parts. **Part 1** builds Tim from nothing — no source photo exists, so there is no
Element to seed the batch, and everything is inlined so it can be pasted straight into
Higgsfield by an operator with no access to this repo. **Part 2** is the 40 b-roll
prompts for once the Soul and Element exist — Element-driven, so his face is never
re-described.

---

# PART 1 — Character creation job

**Paste this whole section into the operator's brief. Nothing here refers back to a
file — treat every block below as complete and final.**

## What Tim is

A 61-year-old, heavy-set, white-and-grey bearded man — warm, gregarious, an
analyst-storyteller on business and private equity. He should read as old-school
operator, not financier; that mismatch is the point. **He is fully synthetic: there is
no source photo of him anywhere, and no Element exists yet.** Two reference photos exist
in the persona folder but they are look-and-feel only (a jolly bearded man at a beer
festival) and cannot seed a batch — wrong angle, mouth blocked by a pipe, terrible
resolution. Ignore them entirely for generation. Tim is built cold from the identity
string below.

## Identity string — paste byte-identical into every one of the 21 prompts

> A 61-year-old white man, heavy-set and broad through the chest and shoulders, with a substantial belly, thick forearms and big hands. A full, round face with heavy cheeks and a ruddy weathered complexion showing sun damage and broken capillaries across the cheeks and nose. Pale grey-blue eyes set wide apart beneath heavy light brows, deeply creased with laugh lines at the outer corners. A full white & grey beard and moustache, grown out and rounded, covering the jaw completely. Short, thinning fair-grey hair, receding at the temples. A naturally warm, good-humoured face that settles into an open smile at rest — physically imposing and entirely unthreatening.

Do not paraphrase, trim, or reorder this. Every drift problem below traces back to this
string not staying identical across the batch.

## Three rules that override everything else in this job

1. **No pipe, anywhere in these 21 prompts.** It is Tim's signature prop, but it occludes
   the mouth, and a Soul trained on an obscured mouth renders mouths badly across every
   future generation. The pipe is added at content time only, never during training. If
   any generated frame shows him with a pipe, reject it — do not curate it in even if the
   face looks good.
2. **His build drifts. Reject any frame where he has lost weight.** Heavy-set body types
   get slimmed by the model between shots more than any other build — this is the single
   biggest failure mode for this batch. Judge every keeper against the identity string's
   "heavy-set... substantial belly... thick forearms and big hands," not against which
   frame looks most flattering. A trimmer, more conventionally handsome Tim is a failed
   frame, full stop.
3. **The warm smile is the defining trait.** Even the shots below marked "neutral" should
   still carry the identity string's baseline — "a naturally warm, good-humoured face
   that settles into an open smile at rest." If the finished set reads as stern or
   closed-off, the character has failed even where the geometry is otherwise correct.
   When curating, actively reject technically-consistent frames that came out cold.

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

**Tim-specific:** a heavy-set build drifting thinner is the failure to watch on every
single variant. And no pipe anywhere in this batch.


## The 21 coverage shots — each one paste-ready as written

Each block below is already the complete prompt: identity string + shot instruction +
tail. Paste each one exactly as it appears, one at a time.

```
A 61-year-old white man, heavy-set and broad through the chest and shoulders, with a substantial belly, thick forearms and big hands. A full, round face with heavy cheeks and a ruddy weathered complexion showing sun damage and broken capillaries across the cheeks and nose. Pale grey-blue eyes set wide apart beneath heavy light brows, deeply creased with laugh lines at the outer corners. A full white & grey beard and moustache, grown out and rounded, covering the jaw completely. Short, thinning fair-grey hair, receding at the temples. A naturally warm, good-humoured face that settles into an open smile at rest — physically imposing and entirely unthreatening. Straight-on headshot, neutral expression, mouth closed, eyes to lens. Clean neutral studio lighting, plain mid-grey seamless background, sharp focus on the face, realistic skin texture with visible pores and natural shine, no retouching, no beauty filter. No text, no logos, no watermark.
```
**1.** Straight-on, neutral, mouth closed.

```
A 61-year-old white man, heavy-set and broad through the chest and shoulders, with a substantial belly, thick forearms and big hands. A full, round face with heavy cheeks and a ruddy weathered complexion showing sun damage and broken capillaries across the cheeks and nose. Pale grey-blue eyes set wide apart beneath heavy light brows, deeply creased with laugh lines at the outer corners. A full white & grey beard and moustache, grown out and rounded, covering the jaw completely. Short, thinning fair-grey hair, receding at the temples. A naturally warm, good-humoured face that settles into an open smile at rest — physically imposing and entirely unthreatening. Straight-on headshot, warm closed-mouth smile, eyes to lens. Clean neutral studio lighting, plain mid-grey seamless background, sharp focus on the face, realistic skin texture with visible pores and natural shine, no retouching, no beauty filter. No text, no logos, no watermark.
```
**2.** Straight-on, warm closed-mouth smile.

```
A 61-year-old white man, heavy-set and broad through the chest and shoulders, with a substantial belly, thick forearms and big hands. A full, round face with heavy cheeks and a ruddy weathered complexion showing sun damage and broken capillaries across the cheeks and nose. Pale grey-blue eyes set wide apart beneath heavy light brows, deeply creased with laugh lines at the outer corners. A full white & grey beard and moustache, grown out and rounded, covering the jaw completely. Short, thinning fair-grey hair, receding at the temples. A naturally warm, good-humoured face that settles into an open smile at rest — physically imposing and entirely unthreatening. Straight-on headshot, open genuine laugh, teeth showing, eyes crinkled. Clean neutral studio lighting, plain mid-grey seamless background, sharp focus on the face, realistic skin texture with visible pores and natural shine, no retouching, no beauty filter. No text, no logos, no watermark.
```
**3.** Straight-on, open genuine laugh.

```
A 61-year-old white man, heavy-set and broad through the chest and shoulders, with a substantial belly, thick forearms and big hands. A full, round face with heavy cheeks and a ruddy weathered complexion showing sun damage and broken capillaries across the cheeks and nose. Pale grey-blue eyes set wide apart beneath heavy light brows, deeply creased with laugh lines at the outer corners. A full white & grey beard and moustache, grown out and rounded, covering the jaw completely. Short, thinning fair-grey hair, receding at the temples. A naturally warm, good-humoured face that settles into an open smile at rest — physically imposing and entirely unthreatening. Three-quarter turn to his left, neutral, eyes back to lens. Clean neutral studio lighting, plain mid-grey seamless background, sharp focus on the face, realistic skin texture with visible pores and natural shine, no retouching, no beauty filter. No text, no logos, no watermark.
```
**4.** Three-quarter turn, left.

```
A 61-year-old white man, heavy-set and broad through the chest and shoulders, with a substantial belly, thick forearms and big hands. A full, round face with heavy cheeks and a ruddy weathered complexion showing sun damage and broken capillaries across the cheeks and nose. Pale grey-blue eyes set wide apart beneath heavy light brows, deeply creased with laugh lines at the outer corners. A full white & grey beard and moustache, grown out and rounded, covering the jaw completely. Short, thinning fair-grey hair, receding at the temples. A naturally warm, good-humoured face that settles into an open smile at rest — physically imposing and entirely unthreatening. Three-quarter turn to his right, slight smile, eyes back to lens. Clean neutral studio lighting, plain mid-grey seamless background, sharp focus on the face, realistic skin texture with visible pores and natural shine, no retouching, no beauty filter. No text, no logos, no watermark.
```
**5.** Three-quarter turn, right.

```
A 61-year-old white man, heavy-set and broad through the chest and shoulders, with a substantial belly, thick forearms and big hands. A full, round face with heavy cheeks and a ruddy weathered complexion showing sun damage and broken capillaries across the cheeks and nose. Pale grey-blue eyes set wide apart beneath heavy light brows, deeply creased with laugh lines at the outer corners. A full white & grey beard and moustache, grown out and rounded, covering the jaw completely. Short, thinning fair-grey hair, receding at the temples. A naturally warm, good-humoured face that settles into an open smile at rest — physically imposing and entirely unthreatening. Full profile, left side, neutral, looking off-frame. Clean neutral studio lighting, plain mid-grey seamless background, sharp focus on the face, realistic skin texture with visible pores and natural shine, no retouching, no beauty filter. No text, no logos, no watermark.
```
**6.** Full profile, left.

```
A 61-year-old white man, heavy-set and broad through the chest and shoulders, with a substantial belly, thick forearms and big hands. A full, round face with heavy cheeks and a ruddy weathered complexion showing sun damage and broken capillaries across the cheeks and nose. Pale grey-blue eyes set wide apart beneath heavy light brows, deeply creased with laugh lines at the outer corners. A full white & grey beard and moustache, grown out and rounded, covering the jaw completely. Short, thinning fair-grey hair, receding at the temples. A naturally warm, good-humoured face that settles into an open smile at rest — physically imposing and entirely unthreatening. Chin slightly lowered, eyes up to lens, faint knowing half-smile. Clean neutral studio lighting, plain mid-grey seamless background, sharp focus on the face, realistic skin texture with visible pores and natural shine, no retouching, no beauty filter. No text, no logos, no watermark.
```
**7.** Chin lowered, knowing half-smile.

```
A 61-year-old white man, heavy-set and broad through the chest and shoulders, with a substantial belly, thick forearms and big hands. A full, round face with heavy cheeks and a ruddy weathered complexion showing sun damage and broken capillaries across the cheeks and nose. Pale grey-blue eyes set wide apart beneath heavy light brows, deeply creased with laugh lines at the outer corners. A full white & grey beard and moustache, grown out and rounded, covering the jaw completely. Short, thinning fair-grey hair, receding at the temples. A naturally warm, good-humoured face that settles into an open smile at rest — physically imposing and entirely unthreatening. Chin slightly raised, confident and composed, mouth closed, eyes to lens. Clean neutral studio lighting, plain mid-grey seamless background, sharp focus on the face, realistic skin texture with visible pores and natural shine, no retouching, no beauty filter. No text, no logos, no watermark.
```
**8.** Chin raised, composed.

```
A 61-year-old white man, heavy-set and broad through the chest and shoulders, with a substantial belly, thick forearms and big hands. A full, round face with heavy cheeks and a ruddy weathered complexion showing sun damage and broken capillaries across the cheeks and nose. Pale grey-blue eyes set wide apart beneath heavy light brows, deeply creased with laugh lines at the outer corners. A full white & grey beard and moustache, grown out and rounded, covering the jaw completely. Short, thinning fair-grey hair, receding at the temples. A naturally warm, good-humoured face that settles into an open smile at rest — physically imposing and entirely unthreatening. Hair fully back or off the face, hairline and both ears visible, jaw and neck clear, neutral, straight-on. Clean neutral studio lighting, plain mid-grey seamless background, sharp focus on the face, realistic skin texture with visible pores and natural shine, no retouching, no beauty filter. No text, no logos, no watermark.
```
**9.** Hair back, hairline and ears visible.

```
A 61-year-old white man, heavy-set and broad through the chest and shoulders, with a substantial belly, thick forearms and big hands. A full, round face with heavy cheeks and a ruddy weathered complexion showing sun damage and broken capillaries across the cheeks and nose. Pale grey-blue eyes set wide apart beneath heavy light brows, deeply creased with laugh lines at the outer corners. A full white & grey beard and moustache, grown out and rounded, covering the jaw completely. Short, thinning fair-grey hair, receding at the temples. A naturally warm, good-humoured face that settles into an open smile at rest — physically imposing and entirely unthreatening. Waist-up, standing, arms relaxed at his sides, straight-on, neutral. Clean neutral studio lighting, plain mid-grey seamless background, sharp focus on the face, realistic skin texture with visible pores and natural shine, no retouching, no beauty filter. No text, no logos, no watermark.
```
**10.** Waist-up, standing, arms relaxed. *(Proportion shot — watch this one hardest for slimming.)*

```
A 61-year-old white man, heavy-set and broad through the chest and shoulders, with a substantial belly, thick forearms and big hands. A full, round face with heavy cheeks and a ruddy weathered complexion showing sun damage and broken capillaries across the cheeks and nose. Pale grey-blue eyes set wide apart beneath heavy light brows, deeply creased with laugh lines at the outer corners. A full white & grey beard and moustache, grown out and rounded, covering the jaw completely. Short, thinning fair-grey hair, receding at the temples. A naturally warm, good-humoured face that settles into an open smile at rest — physically imposing and entirely unthreatening. Straight-on, hard directional light from camera-left casting a defined shadow across the other side of the face. Hard directional light from camera-left, plain mid-grey seamless background, sharp focus on the face, realistic skin texture with visible pores and natural shine, no retouching, no beauty filter. No text, no logos, no watermark.
```
**11.** Hard directional side light.

```
A 61-year-old white man, heavy-set and broad through the chest and shoulders, with a substantial belly, thick forearms and big hands. A full, round face with heavy cheeks and a ruddy weathered complexion showing sun damage and broken capillaries across the cheeks and nose. Pale grey-blue eyes set wide apart beneath heavy light brows, deeply creased with laugh lines at the outer corners. A full white & grey beard and moustache, grown out and rounded, covering the jaw completely. Short, thinning fair-grey hair, receding at the temples. A naturally warm, good-humoured face that settles into an open smile at rest — physically imposing and entirely unthreatening. Straight-on, completely flat soft frontal light, no visible shadow anywhere. Clean neutral studio lighting, plain mid-grey seamless background, sharp focus on the face, realistic skin texture with visible pores and natural shine, no retouching, no beauty filter. No text, no logos, no watermark.
```
**12.** Flat frontal light, no shadow.

```
A 61-year-old white man, heavy-set and broad through the chest and shoulders, with a substantial belly, thick forearms and big hands. A full, round face with heavy cheeks and a ruddy weathered complexion showing sun damage and broken capillaries across the cheeks and nose. Pale grey-blue eyes set wide apart beneath heavy light brows, deeply creased with laugh lines at the outer corners. A full white & grey beard and moustache, grown out and rounded, covering the jaw completely. Short, thinning fair-grey hair, receding at the temples. A naturally warm, good-humoured face that settles into an open smile at rest — physically imposing and entirely unthreatening. Head-and-shoulders headshot, straight-on, warm closed-mouth smile, close enough to show the full texture and coverage of the white-and-grey beard across the jaw, mouth fully visible and unobstructed — no pipe, no hand near the mouth, nothing covering the lips. Clean neutral studio lighting, plain mid-grey seamless background, sharp focus on the face, realistic skin texture with visible pores and natural shine, no retouching, no beauty filter. No text, no logos, no watermark.
```
**13.** Beard detail, mouth unobstructed. *(This is the shot that most needs the pipe rule enforced — nothing near the mouth.)*

```
A 61-year-old white man, heavy-set and broad through the chest and shoulders, with a substantial belly, thick forearms and big hands. A full, round face with heavy cheeks and a ruddy weathered complexion showing sun damage and broken capillaries across the cheeks and nose. Pale grey-blue eyes set wide apart beneath heavy light brows, deeply creased with laugh lines at the outer corners. A full white & grey beard and moustache, grown out and rounded, covering the jaw completely. Short, thinning fair-grey hair, receding at the temples. A naturally warm, good-humoured face that settles into an open smile at rest — physically imposing and entirely unthreatening. Head-and-shoulders headshot, straight-on, neutral, lit from behind by a bright window so the face sits in soft even shadow and the background blows out. Clean neutral studio lighting, plain mid-grey seamless background, sharp focus on the face, realistic skin texture with visible pores and natural shine, no retouching, no beauty filter. No text, no logos, no watermark.
```
**14.** Backlit, soft shadow.

```
A 61-year-old white man, heavy-set and broad through the chest and shoulders, with a substantial belly, thick forearms and big hands. A full, round face with heavy cheeks and a ruddy weathered complexion showing sun damage and broken capillaries across the cheeks and nose. Pale grey-blue eyes set wide apart beneath heavy light brows, deeply creased with laugh lines at the outer corners. A full white & grey beard and moustache, grown out and rounded, covering the jaw completely. Short, thinning fair-grey hair, receding at the temples. A naturally warm, good-humoured face that settles into an open smile at rest — physically imposing and entirely unthreatening. Full-length shot, standing, facing the camera straight-on, feet visible, arms relaxed at his sides, neutral expression. Open-collar check shirt with sleeves rolled, a quilted moss-green gilet over the top, moleskin trousers. Clean neutral studio lighting, plain mid-grey seamless background, sharp focus on the face, realistic skin texture with visible pores and natural shine, no retouching, no beauty filter. No text, no logos, no watermark.
```
**15.** Full-length, standing straight-on. *(His build is a large part of his identity — this and #16 matter more for him than for the others.)*

```
A 61-year-old white man, heavy-set and broad through the chest and shoulders, with a substantial belly, thick forearms and big hands. A full, round face with heavy cheeks and a ruddy weathered complexion showing sun damage and broken capillaries across the cheeks and nose. Pale grey-blue eyes set wide apart beneath heavy light brows, deeply creased with laugh lines at the outer corners. A full white & grey beard and moustache, grown out and rounded, covering the jaw completely. Short, thinning fair-grey hair, receding at the temples. A naturally warm, good-humoured face that settles into an open smile at rest — physically imposing and entirely unthreatening. Full-length shot, standing, turned three-quarters to his left, weight settled on one hip, one hand resting on the back of a wooden chair, the other loose at his side, warm expression. Clean neutral studio lighting, plain mid-grey seamless background, sharp focus on the face, realistic skin texture with visible pores and natural shine, no retouching, no beauty filter. No text, no logos, no watermark.
```
**16.** Full-length, three-quarter turn.

```
A 61-year-old white man, heavy-set and broad through the chest and shoulders, with a substantial belly, thick forearms and big hands. A full, round face with heavy cheeks and a ruddy weathered complexion showing sun damage and broken capillaries across the cheeks and nose. Pale grey-blue eyes set wide apart beneath heavy light brows, deeply creased with laugh lines at the outer corners. A full white & grey beard and moustache, grown out and rounded, covering the jaw completely. Short, thinning fair-grey hair, receding at the temples. A naturally warm, good-humoured face that settles into an open smile at rest — physically imposing and entirely unthreatening. Seated on a plain stool, facing the camera, forearms resting on his thighs, hands loosely clasped and clearly visible, leaning slightly forward, warm half-smile. Clean neutral studio lighting, plain mid-grey seamless background, sharp focus on the face, realistic skin texture with visible pores and natural shine, no retouching, no beauty filter. No text, no logos, no watermark.
```
**17.** Seated, forearms on thighs, hands visible.

```
A 61-year-old white man, heavy-set and broad through the chest and shoulders, with a substantial belly, thick forearms and big hands. A full, round face with heavy cheeks and a ruddy weathered complexion showing sun damage and broken capillaries across the cheeks and nose. Pale grey-blue eyes set wide apart beneath heavy light brows, deeply creased with laugh lines at the outer corners. A full white & grey beard and moustache, grown out and rounded, covering the jaw completely. Short, thinning fair-grey hair, receding at the temples. A naturally warm, good-humoured face that settles into an open smile at rest — physically imposing and entirely unthreatening. Waist-up, straight-on, both hands raised to chest height mid-gesture as if explaining something, fingers relaxed and separated, palms angled inward, hands large and clearly visible. Clean neutral studio lighting, plain mid-grey seamless background, sharp focus on the face, realistic skin texture with visible pores and natural shine, no retouching, no beauty filter. No text, no logos, no watermark.
```
**18.** Hands mid-gesture, explaining.

```
A 61-year-old white man, heavy-set and broad through the chest and shoulders, with a substantial belly, thick forearms and big hands. A full, round face with heavy cheeks and a ruddy weathered complexion showing sun damage and broken capillaries across the cheeks and nose. Pale grey-blue eyes set wide apart beneath heavy light brows, deeply creased with laugh lines at the outer corners. A full white & grey beard and moustache, grown out and rounded, covering the jaw completely. Short, thinning fair-grey hair, receding at the temples. A naturally warm, good-humoured face that settles into an open smile at rest — physically imposing and entirely unthreatening. Waist-up, straight-on, holding a plain white ceramic mug in both hands at chest height, hands and fingers clearly visible, warm expression. Clean neutral studio lighting, plain mid-grey seamless background, sharp focus on the face, realistic skin texture with visible pores and natural shine, no retouching, no beauty filter. No text, no logos, no watermark.
```
**19.** Hands around a mug. *(Deliberately a mug, not a pipe — the hand-to-face prop the training set is allowed to have.)*

```
A 61-year-old white man, heavy-set and broad through the chest and shoulders, with a substantial belly, thick forearms and big hands. A full, round face with heavy cheeks and a ruddy weathered complexion showing sun damage and broken capillaries across the cheeks and nose. Pale grey-blue eyes set wide apart beneath heavy light brows, deeply creased with laugh lines at the outer corners. A full white & grey beard and moustache, grown out and rounded, covering the jaw completely. Short, thinning fair-grey hair, receding at the temples. A naturally warm, good-humoured face that settles into an open smile at rest — physically imposing and entirely unthreatening. Head-and-shoulders headshot, straight-on, warm smile, wearing an unstructured chestnut tweed sport coat over a fine-knit crew-neck instead of the check shirt. Clean neutral studio lighting, plain mid-grey seamless background, sharp focus on the face, realistic skin texture with visible pores and natural shine, no retouching, no beauty filter. No text, no logos, no watermark.
```
**20.** Wardrobe alternate — tweed sport coat.

```
A 61-year-old white man, heavy-set and broad through the chest and shoulders, with a substantial belly, thick forearms and big hands. A full, round face with heavy cheeks and a ruddy weathered complexion showing sun damage and broken capillaries across the cheeks and nose. Pale grey-blue eyes set wide apart beneath heavy light brows, deeply creased with laugh lines at the outer corners. A full white & grey beard and moustache, grown out and rounded, covering the jaw completely. Short, thinning fair-grey hair, receding at the temples. A naturally warm, good-humoured face that settles into an open smile at rest — physically imposing and entirely unthreatening. Waist-up, straight-on, neutral to soft smile, wearing a short-sleeve oatmeal linen shirt open at the collar instead of the gilet. Clean neutral studio lighting, plain mid-grey seamless background, sharp focus on the face, realistic skin texture with visible pores and natural shine, no retouching, no beauty filter. No text, no logos, no watermark.
```
**21.** Wardrobe alternate — warm-weather linen.

## After generation: curate, train, build the Element

1. **Curate to 22–26 keepers**, roughly two-thirds head-and-shoulders. For every frame,
   ask two questions in this order: *is this the same man, at the same weight?* then
   *does this look like him, not a stern stranger wearing his face?* Fail either test and
   the frame is out, regardless of how clean the image is.
2. **No pipe in any keeper.** If one slipped through, discard it — do not crop it out and
   keep the rest of the frame; regenerate that slot instead.
3. **Train the Soul** on the keepers. **Soul 2.0, not Soul Cinematic.** Images only —
   Soul does not take video.
4. **Build the Element** from the keepers, and give it more full-length coverage than the
   other personas' Elements got: the front-on chest-up keeper (#10 or #15), plus a
   three-quarter (#16), plus the standing full-length (#15) explicitly. His build carries
   as much of his identity as his face does, and Seedance/Kling need that proportion
   information to keep him heavy-set through motion, not just through a still.

---

#
