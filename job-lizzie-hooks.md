# Job — Lizzie Larsen: 50 reaction hooks

50 short selfie reaction clips. Each is the **opening 2–3 seconds** of a video whose
remainder is a real product demo. The synthetic face carries only the hook, then the edit
cuts to real screen capture — that is why these are short and silent.

> ### Two things that decide whether these work
>
> **Generate every prompt exactly as written. Do not simplify the expression.** Each one
> names an expression *and then describes its physical form* — "shocked, hand to the mouth
> — her free hand comes up and presses flat over her mouth, fingers together, eyes wide
> above it". Both halves matter. The label on its own lets the model fall back on a
> rubbery, over-acted stock face; the physical description is what steers it.
>
> **No speech, in any of them.** Lip-sync is the biggest AI tell there is. If a clip comes
> back with the mouth forming words, reject it. The message goes on as a text overlay later.
> **Her Element is `Lizzie Larsen-1`, NOT `Lizzie Larsen`.** The unsuffixed one is a
> superseded likeness rejected on IP grounds. Always type `@Lizzie Larsen-1`.


## Settings

| Control | Set to |
|---|---|
| Model | **Seedance 2.0** |
| Duration | **4s** — the model minimum |
| Aspect | **9:16** |
| Resolution | **1080p** |
| Sound | **Off** |

**4s even though the hook is 2–3s.** 4s is Seedance's floor, and the spare second gives the
editor a choice of where the reaction peaks. Trimming happens later, not here.

## How to run each one

1. Type **`@Lizzie Larsen-1`** and pick the Element from the dropdown.
2. Paste the block whole. Camera, skin and silence paragraphs are already attached.
   **Do not re-describe her face** — the Element carries it and competing description
   causes drift.
3. Same negative prompt for all 50, below.

## Do these five first, then stop

**L01, L04, L05, L10, L24** — deliberately spread across five different expressions and across daylight,
screen-lit dark and hands-to-face. They will show fastest whether the expression
descriptions are landing. Report back before running the other 45.

## Reject on sight

| | Why |
|---|---|
| Mouth forming words | These are silent. |
| A rubbery, over-acted expression | Means the physical description was ignored in favour of a stock face. Retake. |
| Hands warping | Watch the hand-to-mouth and peeping-through-fingers clips especially. Selfie distance should prevent it. |
| Another person's face | Background faces render melted. None of these have company. |
| Waxy, poreless skin | The skin paragraph exists to stop this. |
| A second action after the held pose | These are 4s: one interruption, one expression, one held position. |

## Report back

1. Clip URLs in order with the code
2. Any clip where the face drifted from the Element — be blunt
3. Any clip where the mouth tried to speak
4. **Which expressions rendered well and which did not** — this set exists to find that out
5. Whether the screen-lit night ones held the phone-footage look or went cinematic
6. Anything that showed a credit cost

---

## Eleven expressions, spread across the 50

Reaction hooks die of sameness — fifty identical wide-eyed faces is one asset used fifty
times, not fifty assets. Pick by expression as well as by setting.

| Expression | Count | Clips |
|---|---|---|
| **Eyes wide** | 7 | L01, L09, L16, L23, L33, L42, L49 |
| **Both brows raised** | 6 | L06, L11, L19, L26, L32, L39 |
| **Jaw slack** | 5 | L02, L12, L22, L25, L37 |
| **Hand over the mouth** | 5 | L04, L17, L24, L31, L47 |
| **Squint and lean in** | 5 | L08, L14, L28, L35, L40 |
| **One brow up — sceptical** | 5 | L10, L15, L21, L30, L41 |
| **Double-take** | 4 | L03, L18, L29, L43 |
| **Peeping through fingers** | 4 | L05, L36, L44, L48 |
| **Recoil** | 4 | L07, L13, L27, L46 |
| **Delighted disbelief** | 3 | L34, L38, L50 |
| **Hands to the head** | 2 | L20, L45 |

## How each prompt is built

Three parts, in this order:

1. **The interruption** — an action that stops. A mug that never reaches the mouth, a
   brush that stops mid-stroke, a pour that halts. This is what actually sells surprise;
   real reaction footage is mostly interrupted motion.
2. **The expression, named and then described physically** — e.g. *"shocked, hand to the
   mouth — his free hand comes up and presses flat over his mouth, fingers together, eyes
   wide above it."* The label alone would let the model pick its own stock version, which
   is where the rubbery over-acted look comes from. The label plus the physical form
   steers it.
3. **A held final position.** Without a defined end state the last frames drift back to an
   earlier pose.

**No speech, in any of them.** Lip-sync is the biggest AI tell there is, and these have no
reason to talk — the message goes on as a text overlay in post.

**Arm's length, never closer.** Selfie distance keeps the face at medium close-up where
detail holds, and keeps hands out of the extreme close-up range where they warp. That
matters most on the hand-to-mouth and peeping-through-fingers clips.

## The low-light ones

**L02, L05, L24** are lit only by the phone screen; **L47** by a laptop screen; **L21** by an open fridge.

A dark scene normally overrides the phone-camera wording and renders like graded cinema.
These get around it by making **the screen itself the light source** — which is how someone
actually films in bed at night, and is a hard, unflattering key that holds the phone-footage
read. Do not add lamps or fill light.

---

**Negative prompt field, same for all 50:**

```
No music, no voiceover, no dialogue, no speaking, no lip movement forming words, no on-screen text, no captions, no logo, no watermark. No dolly, no crane, no orbit, no push-in, no gimbal smoothing, no stabilisation. No other people in frame.
```

---

### L01 — Sitting up in bed, morning · Eyes wide

```
@Lizzie Larsen-1 sits up in bed in soft early daylight through sheer curtains, white linen around her, hair loose and slightly slept-on. Anchors: sleek shoulder-length bright Scandi-blonde hair, dark taupe-brown brows, a white strappy tank top. She is mid-scroll when her thumb stops on the screen; eyes wide with shock — her eyes go wide, whites showing above the iris, brows driving up and the forehead creasing; she holds the phone where it is, unmoving.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### L02 — Lying back, phone-lit at night · Jaw slack

```
@Lizzie Larsen-1 lies back against the pillow in a dark bedroom, her face lit only by the cold glow of her own phone. Anchors: dark taupe-brown brows, sleek bright Scandi-blonde hair, bare shoulders. Her thumb stops moving on the screen; shocked, jaw slack — her jaw drops loose and her lips part, chin lowering, eyes fixed; she stays flat on the pillow, the screen light unchanged on her face.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### L03 — Reaching for the phone, dawn · Double-take

```
@Lizzie Larsen-1 props herself on one elbow in bed at first light, phone just lifted off the nightstand. Anchors: sleek shoulder-length bright Scandi-blonde hair, dark taupe-brown brows, a white strappy tank top. She has just lifted the phone off the nightstand and gone to squint at it; double-take — she looks away, then her head snaps back to the phone, brows up; she pushes herself upright and stays there.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### L04 — Edge of the bed · Hand over the mouth

```
@Lizzie Larsen-1 sits on the edge of an unmade bed in flat morning light, feet on the floor. Anchors: sleek bright Scandi-blonde hair, dark taupe-brown brows, an oat waffle robe. She stops scrolling mid-swipe; shocked, hand to the mouth — her free hand comes up and presses flat over her mouth, fingers together, eyes wide above it; she holds, feet still on the floor.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### L05 — Under the duvet · Peeping through fingers

```
@Lizzie Larsen-1 lies under a white duvet pulled to her chin in a dim room, face lit from below by the phone. Anchors: dark taupe-brown brows, sleek bright Scandi-blonde hair, white bedding. The phone light stops moving under the duvet; shocked, peeping through the fingers — she claps a hand over her eyes, then spreads two fingers and looks through the gap; the duvet drops off her shoulder and she stays sitting up.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### L06 — At the vanity · Both brows raised

```
@Lizzie Larsen-1 sits at a small vanity table by a bright window, makeup dish in front of her, no mirror in frame. Anchors: sleek shoulder-length bright Scandi-blonde hair, dark taupe-brown brows, a white strappy tank top. She stops mid-reach for the makeup dish; surprised, brows raised — both eyebrows shoot up and stay up, forehead creasing, eyes normal width; she holds, hand still out over the vanity.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### L07 — Gloss halfway to her lips · Recoil

```
@Lizzie Larsen-1 sits by a bright window with a lip gloss wand halfway to her mouth. Anchors: dark taupe-brown brows, glossy warm terracotta-rose lips, a white strappy tank top. The gloss wand stops halfway to her mouth; startled, recoiling — her chin tucks in and her whole head draws back away from the phone; she lowers it without using it and holds it.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### L08 — Mid-brush, hair · Squint and lean in

```
@Lizzie Larsen-1 stands near a window working a round brush through her hair in bright daylight. Anchors: sleek bright Scandi-blonde hair, dark taupe-brown brows, a white strappy tank top. The brush stops mid-stroke in her hair; disbelieving, leaning in — her eyes narrow to a squint and she brings her face closer to the screen to check; she lets the brush hang there and holds.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### L09 — Hair tie in her teeth · Eyes wide

```
@Lizzie Larsen-1 stands in flat bright light with her hair half-gathered and a hair tie held in her teeth. Anchors: sleek bright Scandi-blonde hair, dark taupe-brown brows, a white strappy tank top. She takes the hair tie out of her teeth; eyes wide with shock — her eyes go wide, whites showing above the iris, brows driving up and the forehead creasing; her hair drops loose and she holds still.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### L10 — Skincare, hands up · One brow up — sceptical

```
@Lizzie Larsen-1 stands in a bright bathroom with cream on her fingertips, mid-routine, no mirror in frame. Anchors: dark taupe-brown brows, dewy bare skin, bare shoulders. Her cream-covered hands stop short of her face; sceptical, one brow raised — one eyebrow lifts on its own, the other stays down, her mouth pulling slightly to one side and her head tilting a few degrees; she holds both hands up, unmoving.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### L11 — Towel on her head · Both brows raised

```
@Lizzie Larsen-1 stands in bright daylight with a towel wrapped turban-style on her head, fresh from a shower. Anchors: dark taupe-brown brows, an oat waffle robe. Her hand stops on the towel wrapped round her head; surprised, brows raised — both eyebrows shoot up and stay up, forehead creasing, eyes normal width; she holds it there, not unwrapping it.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### L12 — Choosing between two tops · Jaw slack

```
@Lizzie Larsen-1 stands holding a hanger in each hand in a bright bedroom. Anchors: sleek bright Scandi-blonde hair, dark taupe-brown brows, a white strappy tank top. Both hangers lower at once; shocked, jaw slack — her jaw drops loose and her lips part, chin lowering, eyes fixed; she holds them at her sides.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### L13 — Sofa, legs tucked · Recoil

```
@Lizzie Larsen-1 sits on a pale sofa with her legs tucked under her, bright living-room daylight. Anchors: sleek shoulder-length bright Scandi-blonde hair, dark taupe-brown brows, a white strappy tank top. She unfolds one leg from under her; startled, recoiling — her chin tucks in and her whole head draws back away from the phone; she stops mid-lean and holds.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### L14 — Sofa, evening lamp · Squint and lean in

```
@Lizzie Larsen-1 sits on a sofa in the evening lit by one warm lamp beside her. Anchors: dark taupe-brown brows, sleek bright Scandi-blonde hair, an oat waffle robe. She stops scrolling under the lamp; disbelieving, leaning in — her eyes narrow to a squint and she brings her face closer to the screen to check; she settles back against the cushion and holds.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### L15 — Slouched, sitting up · One brow up — sceptical

```
@Lizzie Larsen-1 is slouched low into the sofa cushions in flat afternoon light. Anchors: sleek bright Scandi-blonde hair, dark taupe-brown brows, a warm-grey knit. She comes up out of the slouch; sceptical, one brow raised — one eyebrow lifts on its own, the other stays down, her mouth pulling slightly to one side and her head tilting a few degrees; she stops upright and breathes out once.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### L16 — Blanket over her legs · Eyes wide

```
@Lizzie Larsen-1 sits on a sofa with a throw over her legs, grey-bright light from a window opposite. Anchors: dark taupe-brown brows, sleek bright Scandi-blonde hair, a white strappy tank top. She stops mid-scroll under the throw; eyes wide with shock — her eyes go wide, whites showing above the iris, brows driving up and the forehead creasing; she holds the position, blanket still over her legs.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### L17 — Floor by the coffee table · Hand over the mouth

```
@Lizzie Larsen-1 sits on the floor with her back against a sofa, laptop beside her, warm side light. Anchors: sleek shoulder-length bright Scandi-blonde hair, dark taupe-brown brows, a white strappy tank top. Her head comes off the sofa cushion behind her; shocked, hand to the mouth — her free hand comes up and presses flat over her mouth, fingers together, eyes wide above it; she stays forward, laptop untouched beside her.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### L18 — Kitchen island, standing · Double-take

```
@Lizzie Larsen-1 stands at a marble kitchen island in bright morning light, one hand flat on the stone. Anchors: sleek bright Scandi-blonde hair, dark taupe-brown brows, a white strappy tank top. She straightens up off the marble; double-take — she looks away, then her head snaps back to the phone, brows up; she holds them there, elbows out.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### L19 — Blender mid-pour · Both brows raised

```
@Lizzie Larsen-1 stands at a kitchen island tipping a blender jug toward a glass, bright daylight. Anchors: dark taupe-brown brows, sleek bright Scandi-blonde hair, a white strappy tank top. The pour stops halfway to the glass; surprised, brows raised — both eyebrows shoot up and stay up, forehead creasing, eyes normal width; she rights the jug without finishing and holds it.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### L20 — Straw at her lips · Hands to the head

```
@Lizzie Larsen-1 stands in a bright kitchen with a glass straw almost at her mouth. Anchors: glossy warm terracotta-rose lips, dark taupe-brown brows, a white strappy tank top. The glass straw stops at her lips; stunned, hands to the head — both hands come up to the sides of her head and stay there; she sets it down without drinking and holds still.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### L21 — Fridge open behind her · One brow up — sceptical

```
@Lizzie Larsen-1 stands in front of an open fridge, its light on one side of her face, the kitchen dim otherwise. Anchors: dark taupe-brown brows, sleek bright Scandi-blonde hair, an oat waffle robe. She stops reaching into the fridge; sceptical, one brow raised — one eyebrow lifts on its own, the other stays down, her mouth pulling slightly to one side and her head tilting a few degrees; she lets the door rest against her shoulder and stays there.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### L22 — Kettle steaming behind her · Jaw slack

```
@Lizzie Larsen-1 stands in a kitchen with a kettle steaming behind her, flat daylight. Anchors: sleek bright Scandi-blonde hair, dark taupe-brown brows, a white strappy tank top. She stops mid-turn toward the kettle; shocked, jaw slack — her jaw drops loose and her lips part, chin lowering, eyes fixed; she stays turned the wrong way, ignoring the steam.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### L23 — Driver's seat, parked, day · Eyes wide

```
@Lizzie Larsen-1 sits in the driver's seat of a parked car in bright daylight, one hand on the wheel. Anchors: sleek shoulder-length bright Scandi-blonde hair, dark taupe-brown brows, a white strappy tank top. Her hand comes off the steering wheel; eyes wide with shock — her eyes go wide, whites showing above the iris, brows driving up and the forehead creasing; she holds, back against the seat.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### L24 — Car at night, screen-lit · Hand over the mouth

```
@Lizzie Larsen-1 sits in a parked car at night, face lit only by the phone, dark windows behind her. Anchors: dark taupe-brown brows, sleek bright Scandi-blonde hair, a warm-grey knit. Her thumb stops on the screen in the dark car; shocked, hand to the mouth — her free hand comes up and presses flat over her mouth, fingers together, eyes wide above it; she stays still, the cold light unchanged on her face.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### L25 — Passenger seat, sunglasses up · Jaw slack

```
@Lizzie Larsen-1 sits in a passenger seat in bright sun, sunglasses pushed up into her hair. Anchors: sleek bright Scandi-blonde hair, dark taupe-brown brows, a white strappy tank top. She pulls the sunglasses out of her hair; shocked, jaw slack — her jaw drops loose and her lips part, chin lowering, eyes fixed; she holds them in one hand and stays put.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### L26 — Just parked, keys in hand · Both brows raised

```
@Lizzie Larsen-1 sits in a car that has just stopped, keys in her hand, low golden light through the windscreen. Anchors: sleek bright Scandi-blonde hair, dark taupe-brown brows, a sage linen shirt. The keys drop from her hand into her lap; surprised, brows raised — both eyebrows shoot up and stay up, forehead creasing, eyes normal width; she stops, not getting out.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### L27 — Back of a car · Recoil

```
@Lizzie Larsen-1 sits in the back of a car with bright city daylight moving past the window behind her. Anchors: dark taupe-brown brows, sleek bright Scandi-blonde hair, a white strappy tank top. Her head lifts off the seat back; startled, recoiling — her chin tucks in and her whole head draws back away from the phone; she holds, city light moving past behind her.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### L28 — Poolside lounger · Squint and lean in

```
@Lizzie Larsen-1 sits up on a cream poolside lounger in bright sun, skyline soft behind her. Anchors: sleek bright Scandi-blonde hair, dark taupe-brown brows, a fitted oat swimsuit. She comes up off her elbows on the lounger; disbelieving, leaning in — her eyes narrow to a squint and she brings her face closer to the screen to check; she stops fully upright and holds, phone out.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### L29 — Legs in the pool · Double-take

```
@Lizzie Larsen-1 sits on the pale stone edge of a pool with her legs in the water, bright sun. Anchors: dark taupe-brown brows, sleek bright Scandi-blonde hair, a fitted sage swimsuit. Her feet stop moving in the water; double-take — she looks away, then her head snaps back to the phone, brows up; she holds completely still, water settling round her ankles.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### L30 — Cabana daybed · One brow up — sceptical

```
@Lizzie Larsen-1 reclines on a shaded cabana daybed in bright daylight, one knee up. Anchors: sleek bright Scandi-blonde hair, dark taupe-brown brows, a fitted white two-piece and open sage cover-up. She pushes up onto one elbow on the daybed; sceptical, one brow raised — one eyebrow lifts on its own, the other stays down, her mouth pulling slightly to one side and her head tilting a few degrees; she holds the position.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### L31 — Wrapped in a towel · Hand over the mouth

```
@Lizzie Larsen-1 stands at a poolside wrapped in a white towel, bright sun, water still on her shoulders. Anchors: dark taupe-brown brows, sleek wet-darkened blonde hair, a white towel. Her hand stops at the towel knot; shocked, hand to the mouth — her free hand comes up and presses flat over her mouth, fingers together, eyes wide above it; she holds, water still running off her shoulders.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### L32 — Balcony, morning · Both brows raised

```
@Lizzie Larsen-1 stands at a high balcony rail in bright clear morning light, city soft behind her. Anchors: sleek bright Scandi-blonde hair, dark taupe-brown brows, an oat waffle robe. Her forearms come off the balcony rail; surprised, brows raised — both eyebrows shoot up and stay up, forehead creasing, eyes normal width; she steps back from it and holds.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### L33 — Café table, brunch · Eyes wide

```
@Lizzie Larsen-1 sits at an outdoor café table in bright sun, açaí bowl in front of her. Anchors: sleek shoulder-length bright Scandi-blonde hair, dark taupe-brown brows, a white strappy tank top. The spoon stops before her mouth; eyes wide with shock — her eyes go wide, whites showing above the iris, brows driving up and the forehead creasing; she lowers it into the bowl and holds it there.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### L34 — Iced coffee halfway · Delighted disbelief

```
@Lizzie Larsen-1 sits at a bright café table with an iced coffee halfway to her mouth. Anchors: glossy warm terracotta-rose lips, dark taupe-brown brows, a sage linen shirt. The iced coffee stops halfway to her mouth; delighted disbelief — her brows go up and a disbelieving half-smile breaks across her face as she shakes her head slowly; she sets it down and holds still, condensation on her fingers.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### L35 — Sunglasses lifted · Squint and lean in

```
@Lizzie Larsen-1 sits at a sunlit café table lifting her sunglasses off her face to see the phone better. Anchors: sleek bright Scandi-blonde hair, dark taupe-brown brows, a white strappy tank top. She lifts the sunglasses off her face to see the screen; disbelieving, leaning in — her eyes narrow to a squint and she brings her face closer to the screen to check; she holds them at her hairline.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### L36 — Rooftop bar, late afternoon · Peeping through fingers

```
@Lizzie Larsen-1 stands at a rooftop bar rail in warm low afternoon sun, skyline behind her. Anchors: sleek bright Scandi-blonde hair, dark taupe-brown brows, a warm-grey bodycon midi dress. The glass lowers to the rooftop rail; shocked, peeping through the fingers — she claps a hand over her eyes, then spreads two fingers and looks through the gap; she holds, skyline behind her.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### L37 — Stopped on the pavement · Jaw slack

```
@Lizzie Larsen-1 stands stopped mid-stride on a sunlit pavement, no other people in frame. Anchors: sleek bright Scandi-blonde hair, dark taupe-brown brows, a white strappy tank top. Her walk stops dead on the pavement; shocked, jaw slack — her jaw drops loose and her lips part, chin lowering, eyes fixed; she stays stopped, weight on one hip.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### L38 — Against a pastel wall · Delighted disbelief

```
@Lizzie Larsen-1 leans against a plain pastel exterior wall in bright sun, tote on one shoulder. Anchors: sleek bright Scandi-blonde hair, dark taupe-brown brows, a sage linen skirt and white strappy tank top. She pushes off the wall with her shoulders; delighted disbelief — her brows go up and a disbelieving half-smile breaks across her face as she shakes her head slowly; she stands free of the wall and holds.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### L39 — Shop doorway · Both brows raised

```
@Lizzie Larsen-1 stands just inside a bright shop doorway, daylight behind her, bag in one hand. Anchors: dark taupe-brown brows, sleek bright Scandi-blonde hair, a warm-grey bodycon midi dress. The bag lowers to her side in the doorway; surprised, brows raised — both eyebrows shoot up and stay up, forehead creasing, eyes normal width; she stops there, not moving on.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### L40 — Park bench · Squint and lean in

```
@Lizzie Larsen-1 sits on a park bench in clear morning light, elbows on her knees. Anchors: sleek shoulder-length bright Scandi-blonde hair, dark taupe-brown brows, a white strappy tank top. She sits up off her elbows on the bench; disbelieving, leaning in — her eyes narrow to a squint and she brings her face closer to the screen to check; she holds upright, phone low in both hands.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### L41 — Market stall · One brow up — sceptical

```
@Lizzie Larsen-1 stands at a bright farmers-market stall with a mango in one hand, no other shoppers in frame. Anchors: sleek bright Scandi-blonde hair, dark taupe-brown brows, a white strappy tank top. The mango stops turning in her fingers; sceptical, one brow raised — one eyebrow lifts on its own, the other stays down, her mouth pulling slightly to one side and her head tilting a few degrees; she holds it and stays put.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### L42 — Hotel bed, suitcase open · Eyes wide

```
@Lizzie Larsen-1 sits on a hotel bed with an open suitcase beside her, bright window light. Anchors: sleek bright Scandi-blonde hair, dark taupe-brown brows, a white strappy tank top. She stops folding and the top drops onto the case; eyes wide with shock — her eyes go wide, whites showing above the iris, brows driving up and the forehead creasing; she holds, hands empty over the suitcase.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### L43 — Hotel room, curtains just opened · Double-take

```
@Lizzie Larsen-1 stands beside just-opened curtains with strong daylight flooding in. Anchors: sleek bright Scandi-blonde hair, dark taupe-brown brows, an oat waffle robe. Her hand stops on the curtain she has just opened; double-take — she looks away, then her head snaps back to the phone, brows up; she holds the fabric and stays there.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### L44 — Airport seat · Peeping through fingers

```
@Lizzie Larsen-1 sits in an airport waiting seat in bright terminal light, tote between her feet. Anchors: sleek bright Scandi-blonde hair, dark taupe-brown brows, a warm-grey knit. Her head comes up sharply in the terminal seat; shocked, peeping through the fingers — she claps a hand over her eyes, then spreads two fingers and looks through the gap; she stays put, tote still between her feet.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### L45 — Train seat by the window · Hands to the head

```
@Lizzie Larsen-1 sits in a train seat with bright daylight through the window beside her. Anchors: sleek shoulder-length bright Scandi-blonde hair, dark taupe-brown brows, a white strappy tank top. She stops looking out of the train window; stunned, hands to the head — both hands come up to the sides of her head and stay there; she holds, shoulder against the window frame.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### L46 — At the desk, working · Recoil

```
@Lizzie Larsen-1 sits at a pale oak desk by a tall window in bright daylight, laptop open. Anchors: sleek bright Scandi-blonde hair, dark taupe-brown brows, a white strappy tank top. Her hands lift off the keyboard; startled, recoiling — her chin tucks in and her whole head draws back away from the phone; she sits back and stops, hands in her lap.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### L47 — Desk at night, screen-lit · Hand over the mouth

```
@Lizzie Larsen-1 sits at a pale desk in a dark room lit almost entirely by the laptop screen in front of her. Anchors: dark taupe-brown brows, sleek bright Scandi-blonde hair, an oat waffle robe. She stops scrolling in the dark room; shocked, hand to the mouth — her free hand comes up and presses flat over her mouth, fingers together, eyes wide above it; she holds at that distance, the laptop light hard on one side of her face.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### L48 — Phone on a tripod · Peeping through fingers

```
@Lizzie Larsen-1 stands squared up in front of a phone on a small tripod in a bright room, about to film. Anchors: sleek bright Scandi-blonde hair, dark taupe-brown brows, a white strappy tank top. She stops before starting to film; shocked, peeping through the fingers — she claps a hand over her eyes, then spreads two fingers and looks through the gap; she stays on her mark, not performing.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### L49 — Unboxing on the sofa · Eyes wide

```
@Lizzie Larsen-1 sits cross-legged on a pale sofa with an open delivery box and tissue paper, bright daylight. Anchors: sleek bright Scandi-blonde hair, dark taupe-brown brows, a white strappy tank top. Her hands stop in the tissue paper; eyes wide with shock — her eyes go wide, whites showing above the iris, brows driving up and the forehead creasing; she leaves them there and holds.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### L50 — Watering the plants · Delighted disbelief

```
@Lizzie Larsen-1 stands beside a large monstera with a watering can tipped toward the pot, bright window light. Anchors: sleek bright Scandi-blonde hair, dark taupe-brown brows, an oat waffle robe. The pour stops into the pot; delighted disbelief — her brows go up and a disbelieving half-smile breaks across her face as she shakes her head slowly; she rights the can without finishing and holds it.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

