# Job — Rodrigo Maxwell: 50 reaction hooks

50 short selfie reaction clips. Each is the **opening 2–3 seconds** of a video whose
remainder is a real product demo. The synthetic face carries only the hook, then the edit
cuts to real screen capture — that is why these are short and silent.

> ### Two things that decide whether these work
>
> **Generate every prompt exactly as written. Do not simplify the expression.** Each one
> names an expression *and then describes its physical form* — "shocked, hand to the mouth
> — his free hand comes up and presses flat over his mouth, fingers together, eyes wide
> above it". Both halves matter. The label on its own lets the model fall back on a
> rubbery, over-acted stock face; the physical description is what steers it.
>
> **No speech, in any of them.** Lip-sync is the biggest AI tell there is. If a clip comes
> back with the mouth forming words, reject it. The message goes on as a text overlay later.

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

1. Type **`@Rodrigo Maxwell`** and pick the Element from the dropdown.
2. Paste the block whole. Camera, skin and silence paragraphs are already attached.
   **Do not re-describe his face** — the Element carries it and competing description
   causes drift.
3. Same negative prompt for all 50, below.

## Do these five first, then stop

**R01, R04, R05, R10, R25** — deliberately spread across five different expressions and across daylight,
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
| **Eyes wide** | 7 | R01, R09, R16, R23, R33, R42, R49 |
| **Both brows raised** | 6 | R06, R11, R19, R26, R32, R39 |
| **Jaw slack** | 5 | R02, R12, R22, R25, R37 |
| **Hand over the mouth** | 5 | R04, R17, R24, R31, R47 |
| **Squint and lean in** | 5 | R08, R14, R28, R35, R40 |
| **One brow up — sceptical** | 5 | R10, R15, R21, R30, R41 |
| **Double-take** | 4 | R03, R18, R29, R43 |
| **Peeping through fingers** | 4 | R05, R36, R44, R48 |
| **Recoil** | 4 | R07, R13, R27, R46 |
| **Delighted disbelief** | 3 | R34, R38, R50 |
| **Hands to the head** | 2 | R20, R45 |

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

**R02, R05, R25** are lit only by the phone screen; **R08** by a monitor; **R23** by an open fridge.

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

### R01 — Sitting up in bed, morning · Eyes wide

```
@Rodrigo Maxwell sits up in bed in soft early daylight through half-open blinds, duvet across his lap, hair slightly flattened on one side. Anchors: neatly tapered dark hair, precisely edged dark stubble, a plain white tee. He is mid-scroll when his thumb stops on the screen; eyes wide with shock — his eyes go wide, whites showing above the iris, brows driving up and the forehead creasing; he holds the phone where it is, unmoving.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### R02 — Lying back, phone-lit at night · Jaw slack

```
@Rodrigo Maxwell lies back against the pillow in a dark bedroom, the only light the cold glow of his own phone screen on his face. Anchors: precisely edged dark stubble, the silver hoop, bare shoulders. His thumb stops moving on the screen; shocked, jaw slack — his jaw drops loose and his lips part, chin lowering, eyes fixed; he stays flat on the pillow, the screen light unchanged on his face.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### R03 — Reaching for the phone, dawn · Double-take

```
@Rodrigo Maxwell half-props himself on one elbow in bed at first light, having just picked the phone off the nightstand. Anchors: neatly tapered dark hair, precisely edged dark stubble, a plain white tee. He has just picked the phone up and gone to squint at it; double-take — he looks away, then his head snaps back to the phone, brows up; he pushes himself upright and stays there.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### R04 — Edge of the bed · Hand over the mouth

```
@Rodrigo Maxwell sits on the edge of an unmade bed in flat morning light, feet on the floor, elbows on knees. Anchors: neatly tapered dark hair combed back, the silver hoop, a crisp grey tee. He stops scrolling mid-swipe; shocked, hand to the mouth — his free hand comes up and presses flat over his mouth, fingers together, eyes wide above it; he holds, elbows still on his knees.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### R05 — Under the duvet · Peeping through fingers

```
@Rodrigo Maxwell lies under a duvet pulled to his chin in a dim room, face lit from below by the phone. Anchors: precisely edged dark stubble, the silver hoop, dark bedding. The phone light stops moving under the duvet; shocked, peeping through the fingers — he claps a hand over his eyes, then spreads two fingers and looks through the gap; the duvet drops off his shoulder and he stays sitting up.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### R06 — Desk, two monitors · Both brows raised

```
@Rodrigo Maxwell sits at a home desk with two monitors glowing behind him, bright morning light from a window to his right. Anchors: neatly tapered dark hair combed back, the silver hoop, a crisp black heavyweight t-shirt. His hand comes off the mouse; surprised, brows raised — both eyebrows shoot up and stay up, forehead creasing, eyes normal width; he holds, monitors still glowing behind him.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### R07 — Leaning back in the chair · Recoil

```
@Rodrigo Maxwell leans back in a desk chair with one arm behind his head, bright office daylight. Anchors: neatly tapered dark hair, precisely edged dark stubble, a crisp bone-coloured heavyweight t-shirt. His arm comes down from behind his head; startled, recoiling — his chin tucks in and his whole head draws back away from the phone; he stops leaning forward and stays there, hand on the armrest.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### R08 — Desk at night, screen-lit · Squint and lean in

```
@Rodrigo Maxwell sits at a desk in a dark room lit almost entirely by the monitor in front of him, cool light across one side of his face. Anchors: precisely edged dark stubble, the silver hoop, a crisp black heavyweight t-shirt. He stops scrolling; disbelieving, leaning in — his eyes narrow to a squint and he brings his face closer to the screen to check; he holds at that distance, the monitor light hard on one side of his face.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### R09 — Standing at the desk · Eyes wide

```
@Rodrigo Maxwell stands at a standing desk mid-afternoon, laptop open in front of him, flat daylight. Anchors: neatly tapered dark hair combed back, the silver hoop, a crisp plain grey t-shirt. His hands lift off the keyboard; eyes wide with shock — his eyes go wide, whites showing above the iris, brows driving up and the forehead creasing; he steps back half a pace and stops.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### R10 — Headphones round the neck · One brow up — sceptical

```
@Rodrigo Maxwell sits at a desk with over-ear headphones pushed down around his neck, warm late-afternoon light. Anchors: neatly tapered dark hair, the silver hoop, a crisp black heavyweight t-shirt. He pulls the headphones further off his neck; sceptical, one brow raised — one eyebrow lifts on its own, the other stays down, his mouth pulling slightly to one side and his head tilting a few degrees; he holds them there, not putting them back.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### R11 — Mid-sip at the desk · Both brows raised

```
@Rodrigo Maxwell sits at a desk raising a coffee mug toward his mouth, morning window light. Anchors: neatly tapered dark hair combed back, precisely edged dark stubble, a crisp bone-coloured heavyweight t-shirt. The mug stops before it reaches his lips; surprised, brows raised — both eyebrows shoot up and stay up, forehead creasing, eyes normal width; he lowers the mug to the desk without drinking and holds it there.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### R12 — Frozen mid-type · Jaw slack

```
@Rodrigo Maxwell sits close to the laptop mid-typing, bright flat daylight from the side. Anchors: neatly tapered dark hair, the silver hoop, a crisp plain grey t-shirt. His hands stop dead over the keys; shocked, jaw slack — his jaw drops loose and his lips part, chin lowering, eyes fixed; he keeps his hands hovering, not typing.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### R13 — Pushing back from the desk · Recoil

```
@Rodrigo Maxwell sits at a cluttered desk, afternoon sun coming in low behind him. Anchors: neatly tapered dark hair combed back, the silver hoop, a crisp black heavyweight t-shirt. He shoves the chair back a few inches with his heels; startled, recoiling — his chin tucks in and his whole head draws back away from the phone; he stops with both hands flat on the desk edge.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### R14 — Sofa, feet up · Squint and lean in

```
@Rodrigo Maxwell sits back on a pale sofa with his feet on the coffee table, bright living-room daylight. Anchors: neatly tapered dark hair, precisely edged dark stubble, a crisp plain grey t-shirt. His feet come off the coffee table; disbelieving, leaning in — his eyes narrow to a squint and he brings his face closer to the screen to check; he stays leaning forward, one hand on his knee.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### R15 — Sofa, evening lamp · One brow up — sceptical

```
@Rodrigo Maxwell sits on a sofa in the evening lit by a single warm lamp beside him. Anchors: precisely edged dark stubble, the silver hoop, a clean slate-grey plain hoodie. He stops scrolling under the lamp; sceptical, one brow raised — one eyebrow lifts on its own, the other stays down, his mouth pulling slightly to one side and his head tilting a few degrees; he settles back against the cushion and holds.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### R16 — Slouched, sitting up · Eyes wide

```
@Rodrigo Maxwell is slouched low into the sofa cushions in flat afternoon light. Anchors: neatly tapered dark hair combed back, the silver hoop, a crisp black heavyweight t-shirt. He comes up out of the slouch; eyes wide with shock — his eyes go wide, whites showing above the iris, brows driving up and the forehead creasing; he stops upright and breathes out once.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### R17 — Sofa, blanket · Hand over the mouth

```
@Rodrigo Maxwell sits on a sofa with a throw blanket over his legs, grey-bright daylight from a window opposite. Anchors: precisely edged dark stubble, the silver hoop, a clean slate-grey plain hoodie. He stops mid-scroll under the blanket; shocked, hand to the mouth — his free hand comes up and presses flat over his mouth, fingers together, eyes wide above it; he holds the position, blanket still over his legs.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### R18 — Sofa arm, half-turned · Double-take

```
@Rodrigo Maxwell sits sideways on the arm of a sofa, half-turned to the phone, bright afternoon light. Anchors: neatly tapered dark hair, the silver hoop, a crisp bone-coloured heavyweight t-shirt. He turns from the room to the phone; double-take — he looks away, then his head snaps back to the phone, brows up; he holds the turn, one foot on the floor.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### R19 — Floor, back to the sofa · Both brows raised

```
@Rodrigo Maxwell sits on the floor with his back against a sofa, laptop beside him, warm side light. Anchors: neatly tapered dark hair combed back, precisely edged dark stubble, a crisp plain grey t-shirt. His head comes off the sofa cushion behind him; surprised, brows raised — both eyebrows shoot up and stay up, forehead creasing, eyes normal width; he stays forward, laptop untouched beside him.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### R20 — Kitchen island, standing · Hands to the head

```
@Rodrigo Maxwell stands at a kitchen island in bright morning light, one hand flat on the counter. Anchors: neatly tapered dark hair combed back, the silver hoop, a crisp black heavyweight t-shirt. He straightens up off the counter; stunned, hands to the head — both hands come up to the sides of his head and stay there; he holds them there, elbows out.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### R21 — Kettle boiling behind him · One brow up — sceptical

```
@Rodrigo Maxwell stands in a kitchen with a kettle steaming behind him, flat daylight. Anchors: neatly tapered dark hair, precisely edged dark stubble, a crisp bone-coloured heavyweight t-shirt. He stops mid-turn toward the kettle; sceptical, one brow raised — one eyebrow lifts on its own, the other stays down, his mouth pulling slightly to one side and his head tilting a few degrees; he stays turned the wrong way, ignoring the steam.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### R22 — Mid-bite at the counter · Jaw slack

```
@Rodrigo Maxwell stands at a kitchen counter about to bite a piece of toast, bright morning light. Anchors: neatly tapered dark hair combed back, the silver hoop, a crisp plain grey t-shirt. The toast stops at his mouth; shocked, jaw slack — his jaw drops loose and his lips part, chin lowering, eyes fixed; he lowers it without biting and holds it.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### R23 — Fridge open behind him · Eyes wide

```
@Rodrigo Maxwell stands in front of an open fridge, its light on one side of his face, dim kitchen otherwise. Anchors: precisely edged dark stubble, the silver hoop, a plain white tee. He stops reaching into the fridge; eyes wide with shock — his eyes go wide, whites showing above the iris, brows driving up and the forehead creasing; he lets the door rest against his shoulder and stays there.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### R24 — Driver's seat, parked, day · Hand over the mouth

```
@Rodrigo Maxwell sits in the driver's seat of a parked car in bright daylight, seatbelt off, one hand on the wheel. Anchors: neatly tapered dark hair combed back, the silver hoop, a crisp black heavyweight t-shirt. His hand comes off the steering wheel; shocked, hand to the mouth — his free hand comes up and presses flat over his mouth, fingers together, eyes wide above it; he holds, back against the seat.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### R25 — Car at night, screen-lit · Jaw slack

```
@Rodrigo Maxwell sits in a parked car at night, face lit only by the phone in his hand, dark windows behind. Anchors: precisely edged dark stubble, the silver hoop, a crisp black heavyweight t-shirt. His thumb stops on the screen in the dark car; shocked, jaw slack — his jaw drops loose and his lips part, chin lowering, eyes fixed; he stays still, the cold light unchanged on his face.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### R26 — Passenger seat, sunglasses up · Both brows raised

```
@Rodrigo Maxwell sits in a passenger seat in bright sun, sunglasses pushed up onto his head. Anchors: neatly tapered dark hair, the silver hoop, a crisp bone-coloured heavyweight t-shirt. He pulls the sunglasses off his head; surprised, brows raised — both eyebrows shoot up and stay up, forehead creasing, eyes normal width; he holds them in one hand and stays put.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### R27 — Just parked, engine off · Recoil

```
@Rodrigo Maxwell sits in a car that has just stopped, keys still in his hand, low golden light through the windscreen. Anchors: neatly tapered dark hair combed back, precisely edged dark stubble, a crisply pressed slate-grey unstructured overshirt. The keys drop from his hand into his lap; startled, recoiling — his chin tucks in and his whole head draws back away from the phone; he stops, not getting out.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### R28 — Back seat of a cab · Squint and lean in

```
@Rodrigo Maxwell sits in the back of a car with city daylight moving past the window behind him. Anchors: neatly tapered dark hair, the silver hoop, a crisp black heavyweight t-shirt. His head lifts off the seat back; disbelieving, leaning in — his eyes narrow to a squint and he brings his face closer to the screen to check; he holds, city light moving past behind him.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### R29 — Stopped on the pavement · Double-take

```
@Rodrigo Maxwell stands stopped in the middle of a sunlit pavement, people-free, mid-walk. Anchors: neatly tapered dark hair combed back, the silver hoop, a crisply pressed slate-grey unstructured overshirt. His walk stops dead on the pavement; double-take — he looks away, then his head snaps back to the phone, brows up; he stays stopped, weight on one foot.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### R30 — Against a wall outside · One brow up — sceptical

```
@Rodrigo Maxwell leans against a plain sunlit exterior wall, one foot back against it. Anchors: neatly tapered dark hair, precisely edged dark stubble, a crisp black heavyweight t-shirt. He pushes off the wall with his shoulders; sceptical, one brow raised — one eyebrow lifts on its own, the other stays down, his mouth pulling slightly to one side and his head tilting a few degrees; he stands free of the wall and holds.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### R31 — Café table outside · Hand over the mouth

```
@Rodrigo Maxwell sits at an outdoor café table in bright sun, coffee in front of him. Anchors: neatly tapered dark hair combed back, the silver hoop, a crisp bone-coloured heavyweight t-shirt. He sets the coffee down harder than intended; shocked, hand to the mouth — his free hand comes up and presses flat over his mouth, fingers together, eyes wide above it; he leaves his hand on the cup and holds.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### R32 — Park bench · Both brows raised

```
@Rodrigo Maxwell sits on a park bench in clear morning light, elbows on knees. Anchors: neatly tapered dark hair, the silver hoop, a crisp plain grey t-shirt. He sits up off his elbows on the bench; surprised, brows raised — both eyebrows shoot up and stay up, forehead creasing, eyes normal width; he holds upright, phone low in both hands.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### R33 — Waiting at a crossing · Eyes wide

```
@Rodrigo Maxwell stands at a pedestrian crossing in bright midday light. Anchors: neatly tapered dark hair combed back, the silver hoop, a crisply pressed slate-grey unstructured overshirt. He stops watching the road and looks down at the phone; eyes wide with shock — his eyes go wide, whites showing above the iris, brows driving up and the forehead creasing; he stands still as the light changes, not moving.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### R34 — Balcony, morning · Delighted disbelief

```
@Rodrigo Maxwell stands on a small balcony in bright clear morning light, rooftops behind him. Anchors: neatly tapered dark hair, precisely edged dark stubble, a crisp plain grey t-shirt. His forearms come off the balcony railing; delighted disbelief — his brows go up and a disbelieving half-smile breaks across his face as he shakes his head slowly; he steps back from the rail and holds.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### R35 — Steps outside a building · Squint and lean in

```
@Rodrigo Maxwell sits on wide stone steps outside a building in strong midday sun, bag beside him. Anchors: neatly tapered dark hair combed back, the silver hoop, a crisp black heavyweight t-shirt. He stops halfway to picking up his bag; disbelieving, leaning in — his eyes narrow to a squint and he brings his face closer to the screen to check; his hand stays out, unmoving.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### R36 — Gym, between sets · Peeping through fingers

```
@Rodrigo Maxwell sits on a gym bench between sets under bright even overhead light, towel round his neck. Anchors: precisely edged dark stubble, the silver hoop, a plain grey gym tee. He stops wiping his face with the towel; shocked, peeping through the fingers — he claps a hand over his eyes, then spreads two fingers and looks through the gap; he holds there, chest still moving from the set.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### R37 — Gym mirror-free corner · Jaw slack

```
@Rodrigo Maxwell stands in a plain gym corner with a water bottle halfway to his mouth, bright flat light. Anchors: precisely edged dark stubble, the silver hoop, a plain grey gym tee. The water bottle stops halfway to his mouth; shocked, jaw slack — his jaw drops loose and his lips part, chin lowering, eyes fixed; he lowers it without drinking and holds it.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### R38 — After a run · Delighted disbelief

```
@Rodrigo Maxwell stands outdoors after a run in bright clear light, breathing steadily, hands on hips. Anchors: precisely edged dark stubble, the silver hoop, a plain dark running t-shirt. One hand comes off his hip; delighted disbelief — his brows go up and a disbelieving half-smile breaks across his face as he shakes his head slowly; he holds, still breathing hard from the run.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### R39 — Coworking long table · Both brows raised

```
@Rodrigo Maxwell sits at a long shared coworking table in bright daylight, laptop open. Anchors: neatly tapered dark hair combed back, the silver hoop, a crisp black heavyweight t-shirt. He leans back off the laptop; surprised, brows raised — both eyebrows shoot up and stay up, forehead creasing, eyes normal width; he stops leaning and holds, hands off the keys.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### R40 — Coworking lounge chair · Squint and lean in

```
@Rodrigo Maxwell sits low in a lounge chair in a coworking space, laptop on his knees, soft daylight. Anchors: neatly tapered dark hair, precisely edged dark stubble, a crisp bone-coloured heavyweight t-shirt. He pushes the laptop back on his knees; disbelieving, leaning in — his eyes narrow to a squint and he brings his face closer to the screen to check; he holds, staring past it.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### R41 — Meeting room alone · One brow up — sceptical

```
@Rodrigo Maxwell sits alone in an empty glass-walled meeting room, bright flat daylight. Anchors: neatly tapered dark hair combed back, the silver hoop, a crisply pressed slate-grey unstructured overshirt. His head comes up from the phone; sceptical, one brow raised — one eyebrow lifts on its own, the other stays down, his mouth pulling slightly to one side and his head tilting a few degrees; he settles, elbows on the meeting-room table.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### R42 — Studio, ring light off · Eyes wide

```
@Rodrigo Maxwell stands in a small studio corner with an unlit ring light beside him, plain daylight. Anchors: neatly tapered dark hair, the silver hoop, a crisp black heavyweight t-shirt. He stops adjusting the light stand; eyes wide with shock — his eyes go wide, whites showing above the iris, brows driving up and the forehead creasing; his hand drops and he holds.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### R43 — Kitchenette at work · Double-take

```
@Rodrigo Maxwell stands at an office kitchenette with a mug in one hand, bright even light. Anchors: neatly tapered dark hair combed back, precisely edged dark stubble, a crisp plain grey t-shirt. The mug tips slightly as his attention leaves it; double-take — he looks away, then his head snaps back to the phone, brows up; he rights it without looking and holds it level.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### R44 — Bathroom, getting ready · Peeping through fingers

```
@Rodrigo Maxwell stands in a bright bathroom having just finished at the sink, no mirror in frame, daylight from a window. Anchors: precisely edged dark stubble, the silver hoop, bare shoulders. He stops with the towel half-raised to his face; shocked, peeping through the fingers — he claps a hand over his eyes, then spreads two fingers and looks through the gap; he lowers the towel and holds it at his chest.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### R45 — Collar half-done · Hands to the head

```
@Rodrigo Maxwell stands in flat bright light adjusting his shirt collar, no mirror in frame. Anchors: neatly tapered dark hair combed back, the silver hoop, a crisp white shirt collar open. His hands drop from his collar; stunned, hands to the head — both hands come up to the sides of his head and stay there; he holds them there, collar still undone.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### R46 — Putting on a jacket · Recoil

```
@Rodrigo Maxwell stands mid-way into pulling a jacket onto one shoulder, bright hallway light. Anchors: neatly tapered dark hair, the silver hoop, a crisply pressed slate-grey unstructured overshirt. He stops with the jacket half onto one shoulder; startled, recoiling — his chin tucks in and his whole head draws back away from the phone; he holds the position, one arm still out of the sleeve.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### R47 — Hotel room, suitcase open · Hand over the mouth

```
@Rodrigo Maxwell sits on a hotel bed with an open suitcase beside him, bright window light. Anchors: neatly tapered dark hair combed back, precisely edged dark stubble, a crisp plain grey t-shirt. He stops folding and the shirt drops onto the case; shocked, hand to the mouth — his free hand comes up and presses flat over his mouth, fingers together, eyes wide above it; he holds, hands empty over the suitcase.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### R48 — Airport seat · Peeping through fingers

```
@Rodrigo Maxwell sits in an airport waiting seat in bright terminal light, bag between his feet. Anchors: neatly tapered dark hair, the silver hoop, a crisp black heavyweight t-shirt. His head comes up sharply in the terminal seat; shocked, peeping through the fingers — he claps a hand over his eyes, then spreads two fingers and looks through the gap; he stays put, bag still between his feet.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### R49 — Train seat by the window · Eyes wide

```
@Rodrigo Maxwell sits in a train seat with bright daylight through the window beside him. Anchors: neatly tapered dark hair combed back, the silver hoop, a crisp bone-coloured heavyweight t-shirt. He stops looking out of the train window; eyes wide with shock — his eyes go wide, whites showing above the iris, brows driving up and the forehead creasing; he holds, shoulder against the window frame.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

### R50 — Hotel corridor, walking · Delighted disbelief

```
@Rodrigo Maxwell stops walking in a brightly lit hotel corridor, key card still in one hand. Anchors: neatly tapered dark hair combed back, precisely edged dark stubble, a crisply pressed slate-grey unstructured overshirt. His walk halts in the corridor; delighted disbelief — his brows go up and a disbelieving half-smile breaks across his face as he shakes his head slowly; the key card lowers and he holds.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. The reaction is carried entirely by the face, the hands and the posture.
```

