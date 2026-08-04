# Job — Rodrigo Maxwell: 50 reaction hooks

50 very short selfie reaction clips. Each one is the **opening 2–3 seconds** of a video
whose remainder is a real product demo. The synthetic face carries only the hook, then the
edit cuts away to real screen capture — that is why these are short and why they are
silent.

> ### Read this before generating anything
>
> **Do not add the word "shock", "shocked" or "surprised" to any prompt.** It is not an
> omission. Asking a model for a shocked face produces a rubbery, over-acted expression
> that reads as AI immediately, and it is the fastest way to ruin these. Every prompt
> instead describes a **physical interruption** — brows lifting, a chin drawing back, a
> mug stopping before it reaches the mouth. Surprise is read from the interrupted action.
>
> **No speech, ever.** Lip-sync is the biggest AI tell there is. If a clip comes back with
> the mouth forming words, reject it. The message goes on as a text overlay later.

## Settings

| Control | Set to |
|---|---|
| Model | **Seedance 2.0** |
| Duration | **4s** — the model minimum |
| Aspect | **9:16** |
| Resolution | **1080p** |
| Sound | **Off** |

**4s is deliberate even though the hook is 2–3s.** 4 seconds is Seedance's floor, and the
extra second gives the editor a choice of where the reaction peaks instead of betting the
whole hook on one generation. Trimming happens later, not here.

## How to run each one

1. Type **`@Rodrigo Maxwell`** and pick the Element from the dropdown.
2. Paste the block. Every block is complete — the camera, skin and silence paragraphs are
   already attached. **Do not re-describe he face**; the Element carries it and competing
   description is what causes drift.
3. Use the same negative prompt for all 50, below.

## Do these five first, then stop

**R01, R08, R24, R25, R36** — they cover
daylight indoor, screen-lit dark, car, and outdoors. Report back before running the other 45.

## Reject on sight

| | Why |
|---|---|
| Mouth forming words | These are silent. Lip-sync is the giveaway. |
| An over-acted, rubbery "shocked" face | The prompts avoid it deliberately; if the model adds it anyway, retake. |
| Hands warping | Selfie distance should prevent it. If a hand drifts into extreme close-up, reject. |
| Another person's face | Background faces render melted. None of these have company. |
| Waxy, poreless skin | The skin paragraph exists to stop this. |
| The clip drifting into a different action | These are 4s. One beat, then a held position. |

## Report back

1. Clip URLs in order, with the code (e.g. R01)
2. Any clip where the face drifted from the Element — be blunt
3. Any clip where the mouth tried to speak
4. Whether the screen-lit night ones held the phone-footage look or went cinematic
5. Anything that showed a credit cost

---

**Negative prompt field, same for all 50:**

```
No music, no voiceover, no dialogue, no speaking, no lip movement forming words, no on-screen text, no captions, no logo, no watermark. No dolly, no crane, no orbit, no push-in, no gimbal smoothing, no stabilisation. No other people in frame.
```

---

### R01 — Sitting up in bed, morning

```
@Rodrigo Maxwell sits up in bed in soft early daylight through half-open blinds, duvet across his lap, hair slightly flattened on one side. Anchors: neatly tapered dark hair, precisely edged dark stubble, a plain white tee. he is mid-scroll when his brows lift and his chin draws back an inch; he goes still, eyes fixed just off-lens; in the last beat he blinks once and holds, lips parted.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. Reaction is carried entirely by the eyes, brows and posture.
```

### R02 — Lying back, phone-lit at night

```
@Rodrigo Maxwell lies back against the pillow in a dark bedroom, the only light the cold glow of his own phone screen on his face. Anchors: precisely edged dark stubble, the silver hoop, bare shoulders. his eyes widen and hold; his head lifts an inch off the pillow; he settles back, staring, mouth slightly open.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. Reaction is carried entirely by the eyes, brows and posture.
```

### R03 — Reaching for the phone, dawn

```
@Rodrigo Maxwell half-props himself on one elbow in bed at first light, having just picked the phone off the nightstand. Anchors: neatly tapered dark hair, precisely edged dark stubble, a plain white tee. he squints, then his eyes open fully and his brows shoot up; he pushes himself upright; he holds there, awake now.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. Reaction is carried entirely by the eyes, brows and posture.
```

### R04 — Edge of the bed

```
@Rodrigo Maxwell sits on the edge of an unmade bed in flat morning light, feet on the floor, elbows on knees. Anchors: neatly tapered dark hair combed back, the silver hoop, a crisp grey tee. his head jerks back a few centimetres and stops; he leans slowly toward the phone instead; he holds, jaw slack.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. Reaction is carried entirely by the eyes, brows and posture.
```

### R05 — Under the duvet

```
@Rodrigo Maxwell lies under a duvet pulled to his chin in a dim room, face lit from below by the phone. Anchors: precisely edged dark stubble, the silver hoop, dark bedding. only his eyes move at first, widening; then the duvet drops as he sits up sharply; he stares, blinking once, and holds there.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. Reaction is carried entirely by the eyes, brows and posture.
```

### R06 — Desk, two monitors

```
@Rodrigo Maxwell sits at a home desk with two monitors glowing behind him, bright morning light from a window to his right. Anchors: neatly tapered dark hair combed back, the silver hoop, a crisp black heavyweight t-shirt. he freezes mid-scroll, brows climbing; he glances off to the monitors and straight back to the lens; he holds, unmoving.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. Reaction is carried entirely by the eyes, brows and posture.
```

### R07 — Leaning back in the chair

```
@Rodrigo Maxwell leans back in a desk chair with one arm behind his head, bright office daylight. Anchors: neatly tapered dark hair, precisely edged dark stubble, a crisp bone-coloured heavyweight t-shirt. his arm comes down; he sits forward hard, eyes locked on the screen; he stops, staring, hand still on the armrest.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. Reaction is carried entirely by the eyes, brows and posture.
```

### R08 — Desk at night, screen-lit

```
@Rodrigo Maxwell sits at a desk in a dark room lit almost entirely by the monitor in front of him, cool light across one side of his face. Anchors: precisely edged dark stubble, the silver hoop, a crisp black heavyweight t-shirt. his eyes widen and his head tilts a few degrees; he leans in until the light brightens on his face; he holds there.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. Reaction is carried entirely by the eyes, brows and posture.
```

### R09 — Standing at the desk

```
@Rodrigo Maxwell stands at a standing desk mid-afternoon, laptop open in front of him, flat daylight. Anchors: neatly tapered dark hair combed back, the silver hoop, a crisp plain grey t-shirt. his hands lift off the keyboard; his brows go up and stay; he steps back half a pace and stops, arms loose.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. Reaction is carried entirely by the eyes, brows and posture.
```

### R10 — Headphones round the neck

```
@Rodrigo Maxwell sits at a desk with over-ear headphones pushed down around his neck, warm late-afternoon light. Anchors: neatly tapered dark hair, the silver hoop, a crisp black heavyweight t-shirt. he pulls the headphones further off; his eyes widen; he goes completely still, one hand still on the band.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. Reaction is carried entirely by the eyes, brows and posture.
```

### R11 — Mid-sip at the desk

```
@Rodrigo Maxwell sits at a desk raising a coffee mug toward his mouth, morning window light. Anchors: neatly tapered dark hair combed back, precisely edged dark stubble, a crisp bone-coloured heavyweight t-shirt. the mug stops before it reaches his lips; his eyebrows lift; he lowers the mug slowly without drinking and holds it there, staring.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. Reaction is carried entirely by the eyes, brows and posture.
```

### R12 — Frozen mid-type

```
@Rodrigo Maxwell sits close to the laptop mid-typing, bright flat daylight from the side. Anchors: neatly tapered dark hair, the silver hoop, a crisp plain grey t-shirt. his hands stop dead over the keys; his chin draws back; he holds the position, eyes moving fractionally.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. Reaction is carried entirely by the eyes, brows and posture.
```

### R13 — Pushing back from the desk

```
@Rodrigo Maxwell sits at a cluttered desk, afternoon sun coming in low behind him. Anchors: neatly tapered dark hair combed back, the silver hoop, a crisp black heavyweight t-shirt. he shoves the chair back a few inches with his heels; his mouth opens slightly; he stops, both hands flat on the desk edge.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. Reaction is carried entirely by the eyes, brows and posture.
```

### R14 — Sofa, feet up

```
@Rodrigo Maxwell sits back on a pale sofa with his feet on the coffee table, bright living-room daylight. Anchors: neatly tapered dark hair, precisely edged dark stubble, a crisp plain grey t-shirt. his feet come off the table; he sits forward; he stops mid-lean, eyes fixed, one hand on his knee.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. Reaction is carried entirely by the eyes, brows and posture.
```

### R15 — Sofa, evening lamp

```
@Rodrigo Maxwell sits on a sofa in the evening lit by a single warm lamp beside him. Anchors: precisely edged dark stubble, the silver hoop, a clean slate-grey plain hoodie. his eyebrows lift; his head turns a few degrees toward the light and back; he settles, staring, very still.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. Reaction is carried entirely by the eyes, brows and posture.
```

### R16 — Slouched, sitting up

```
@Rodrigo Maxwell is slouched low into the sofa cushions in flat afternoon light. Anchors: neatly tapered dark hair combed back, the silver hoop, a crisp black heavyweight t-shirt. he sits bolt upright out of the slouch; his eyes stay on the phone the whole way; he stops upright, breathing once.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. Reaction is carried entirely by the eyes, brows and posture.
```

### R17 — Sofa, blanket

```
@Rodrigo Maxwell sits on a sofa with a throw blanket over his legs, grey-bright daylight from a window opposite. Anchors: precisely edged dark stubble, the silver hoop, a clean slate-grey plain hoodie. his hand comes up and stops halfway to his mouth; his brows are already up; he lowers the hand and keeps staring.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. Reaction is carried entirely by the eyes, brows and posture.
```

### R18 — Sofa arm, half-turned

```
@Rodrigo Maxwell sits sideways on the arm of a sofa, half-turned to the phone, bright afternoon light. Anchors: neatly tapered dark hair, the silver hoop, a crisp bone-coloured heavyweight t-shirt. he turns fully to the lens; his eyes widen; he holds the turn, one foot on the floor.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. Reaction is carried entirely by the eyes, brows and posture.
```

### R19 — Floor, back to the sofa

```
@Rodrigo Maxwell sits on the floor with his back against a sofa, laptop beside him, warm side light. Anchors: neatly tapered dark hair combed back, precisely edged dark stubble, a crisp plain grey t-shirt. his head tips back against the cushion and comes forward again fast; he stares at the phone; he stops, unmoving.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. Reaction is carried entirely by the eyes, brows and posture.
```

### R20 — Kitchen island, standing

```
@Rodrigo Maxwell stands at a kitchen island in bright morning light, one hand flat on the counter. Anchors: neatly tapered dark hair combed back, the silver hoop, a crisp black heavyweight t-shirt. he straightens up off the counter; his brows lift; he plants both hands on the counter and holds, staring down at the phone.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. Reaction is carried entirely by the eyes, brows and posture.
```

### R21 — Kettle boiling behind him

```
@Rodrigo Maxwell stands in a kitchen with a kettle steaming behind him, flat daylight. Anchors: neatly tapered dark hair, precisely edged dark stubble, a crisp bone-coloured heavyweight t-shirt. he stops mid-turn toward the kettle; his eyes come back to the phone and widen; he stays turned the wrong way, ignoring the kettle.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. Reaction is carried entirely by the eyes, brows and posture.
```

### R22 — Mid-bite at the counter

```
@Rodrigo Maxwell stands at a kitchen counter about to bite a piece of toast, bright morning light. Anchors: neatly tapered dark hair combed back, the silver hoop, a crisp plain grey t-shirt. the toast stops at his mouth; his eyebrows go up; he lowers it without biting and keeps reading.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. Reaction is carried entirely by the eyes, brows and posture.
```

### R23 — Fridge open behind him

```
@Rodrigo Maxwell stands in front of an open fridge, its light on one side of his face, dim kitchen otherwise. Anchors: precisely edged dark stubble, the silver hoop, a plain white tee. he lets the fridge door start to swing shut against his shoulder; his eyes stay on the phone, widening; he holds, door resting on him.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. Reaction is carried entirely by the eyes, brows and posture.
```

### R24 — Driver's seat, parked, day

```
@Rodrigo Maxwell sits in the driver's seat of a parked car in bright daylight, seatbelt off, one hand on the wheel. Anchors: neatly tapered dark hair combed back, the silver hoop, a crisp black heavyweight t-shirt. his hand comes off the wheel; his head goes back against the headrest and forward again; he stops, staring at the phone.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. Reaction is carried entirely by the eyes, brows and posture.
```

### R25 — Car at night, screen-lit

```
@Rodrigo Maxwell sits in a parked car at night, face lit only by the phone in his hand, dark windows behind. Anchors: precisely edged dark stubble, the silver hoop, a crisp black heavyweight t-shirt. his eyes widen in the cold light; his mouth opens slightly; he goes still, the light unchanged on his face.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. Reaction is carried entirely by the eyes, brows and posture.
```

### R26 — Passenger seat, sunglasses up

```
@Rodrigo Maxwell sits in a passenger seat in bright sun, sunglasses pushed up onto his head. Anchors: neatly tapered dark hair, the silver hoop, a crisp bone-coloured heavyweight t-shirt. he pulls the sunglasses off his head entirely; his brows are up; he holds them in one hand and stares.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. Reaction is carried entirely by the eyes, brows and posture.
```

### R27 — Just parked, engine off

```
@Rodrigo Maxwell sits in a car that has just stopped, keys still in his hand, low golden light through the windscreen. Anchors: neatly tapered dark hair combed back, precisely edged dark stubble, a crisply pressed slate-grey unstructured overshirt. his hand with the keys drops into his lap; his chin draws back; he stops, not getting out.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. Reaction is carried entirely by the eyes, brows and posture.
```

### R28 — Back seat of a cab

```
@Rodrigo Maxwell sits in the back of a car with city daylight moving past the window behind him. Anchors: neatly tapered dark hair, the silver hoop, a crisp black heavyweight t-shirt. his head lifts off the seat back; his eyes widen; he holds, ignoring the window entirely.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. Reaction is carried entirely by the eyes, brows and posture.
```

### R29 — Stopped on the pavement

```
@Rodrigo Maxwell stands stopped in the middle of a sunlit pavement, people-free, mid-walk. Anchors: neatly tapered dark hair combed back, the silver hoop, a crisply pressed slate-grey unstructured overshirt. his walk stops dead; he turns his shoulders square to the phone; he holds, weight on one foot.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. Reaction is carried entirely by the eyes, brows and posture.
```

### R30 — Against a wall outside

```
@Rodrigo Maxwell leans against a plain sunlit exterior wall, one foot back against it. Anchors: neatly tapered dark hair, precisely edged dark stubble, a crisp black heavyweight t-shirt. he pushes off the wall with his shoulders; his brows climb; he stops standing free, staring down at the phone.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. Reaction is carried entirely by the eyes, brows and posture.
```

### R31 — Café table outside

```
@Rodrigo Maxwell sits at an outdoor café table in bright sun, coffee in front of him. Anchors: neatly tapered dark hair combed back, the silver hoop, a crisp bone-coloured heavyweight t-shirt. he sets the cup down harder than intended; his eyes widen; he leaves his hand on the cup and holds, staring.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. Reaction is carried entirely by the eyes, brows and posture.
```

### R32 — Park bench

```
@Rodrigo Maxwell sits on a park bench in clear morning light, elbows on knees. Anchors: neatly tapered dark hair, the silver hoop, a crisp plain grey t-shirt. he sits up off his elbows; his mouth opens slightly; he holds upright, phone still low in both hands.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. Reaction is carried entirely by the eyes, brows and posture.
```

### R33 — Waiting at a crossing

```
@Rodrigo Maxwell stands at a pedestrian crossing in bright midday light. Anchors: neatly tapered dark hair combed back, the silver hoop, a crisply pressed slate-grey unstructured overshirt. he stops looking at the road entirely; his head snaps down to the phone; he stands still as the light changes, not moving.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. Reaction is carried entirely by the eyes, brows and posture.
```

### R34 — Balcony, morning

```
@Rodrigo Maxwell stands on a small balcony in bright clear morning light, rooftops behind him. Anchors: neatly tapered dark hair, precisely edged dark stubble, a crisp plain grey t-shirt. his forearms come off the railing; his brows lift; he steps back from the rail and holds.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. Reaction is carried entirely by the eyes, brows and posture.
```

### R35 — Steps outside a building

```
@Rodrigo Maxwell sits on wide stone steps outside a building in strong midday sun, bag beside him. Anchors: neatly tapered dark hair combed back, the silver hoop, a crisp black heavyweight t-shirt. he stops mid-reach for the bag; his eyes widen; his hand stays out, unmoving, eyes on the phone.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. Reaction is carried entirely by the eyes, brows and posture.
```

### R36 — Gym, between sets

```
@Rodrigo Maxwell sits on a gym bench between sets under bright even overhead light, towel round his neck. Anchors: precisely edged dark stubble, the silver hoop, a plain grey gym tee. he stops wiping his face; the towel drops from one hand; he stares, chest still moving from the set.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. Reaction is carried entirely by the eyes, brows and posture.
```

### R37 — Gym mirror-free corner

```
@Rodrigo Maxwell stands in a plain gym corner with a water bottle halfway to his mouth, bright flat light. Anchors: precisely edged dark stubble, the silver hoop, a plain grey gym tee. the bottle stops; his eyebrows go up; he lowers it without drinking and holds.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. Reaction is carried entirely by the eyes, brows and posture.
```

### R38 — After a run

```
@Rodrigo Maxwell stands outdoors after a run in bright clear light, breathing steadily, hands on hips. Anchors: precisely edged dark stubble, the silver hoop, a plain dark running t-shirt. one hand comes off his hip to the phone; his eyes widen; he goes still, still breathing hard.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. Reaction is carried entirely by the eyes, brows and posture.
```

### R39 — Coworking long table

```
@Rodrigo Maxwell sits at a long shared coworking table in bright daylight, laptop open. Anchors: neatly tapered dark hair combed back, the silver hoop, a crisp black heavyweight t-shirt. he leans back off the laptop; his brows lift; he stops leaning and holds, hands off the keys.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. Reaction is carried entirely by the eyes, brows and posture.
```

### R40 — Coworking lounge chair

```
@Rodrigo Maxwell sits low in a lounge chair in a coworking space, laptop on his knees, soft daylight. Anchors: neatly tapered dark hair, precisely edged dark stubble, a crisp bone-coloured heavyweight t-shirt. he pushes the laptop back on his knees; his mouth opens slightly; he holds, staring past it at the phone.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. Reaction is carried entirely by the eyes, brows and posture.
```

### R41 — Meeting room alone

```
@Rodrigo Maxwell sits alone in an empty glass-walled meeting room, bright flat daylight. Anchors: neatly tapered dark hair combed back, the silver hoop, a crisply pressed slate-grey unstructured overshirt. his head comes up from the phone and back down fast; his brows stay high; he settles, elbows on the table.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. Reaction is carried entirely by the eyes, brows and posture.
```

### R42 — Studio, ring light off

```
@Rodrigo Maxwell stands in a small studio corner with an unlit ring light beside him, plain daylight. Anchors: neatly tapered dark hair, the silver hoop, a crisp black heavyweight t-shirt. he stops adjusting the light stand; his hand drops; his eyes widen and he holds, staring at the phone instead.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. Reaction is carried entirely by the eyes, brows and posture.
```

### R43 — Kitchenette at work

```
@Rodrigo Maxwell stands at an office kitchenette with a mug in one hand, bright even light. Anchors: neatly tapered dark hair combed back, precisely edged dark stubble, a crisp plain grey t-shirt. the mug tips slightly as his attention leaves it; his brows climb; he rights it without looking and keeps staring.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. Reaction is carried entirely by the eyes, brows and posture.
```

### R44 — Bathroom, getting ready

```
@Rodrigo Maxwell stands in a bright bathroom having just finished at the sink, no mirror in frame, daylight from a window. Anchors: precisely edged dark stubble, the silver hoop, bare shoulders. he stops with a towel half-raised to his face; his eyes widen over the top of it; he lowers the towel and holds.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. Reaction is carried entirely by the eyes, brows and posture.
```

### R45 — Collar half-done

```
@Rodrigo Maxwell stands in flat bright light adjusting his shirt collar, no mirror in frame. Anchors: neatly tapered dark hair combed back, the silver hoop, a crisp white shirt collar open. his hands drop from the collar; his brows lift; he leaves the collar undone and holds, staring.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. Reaction is carried entirely by the eyes, brows and posture.
```

### R46 — Putting on a jacket

```
@Rodrigo Maxwell stands mid-way into pulling a jacket onto one shoulder, bright hallway light. Anchors: neatly tapered dark hair, the silver hoop, a crisply pressed slate-grey unstructured overshirt. he stops with the jacket half on; his mouth opens slightly; he holds the position, one arm still out of the sleeve.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. Reaction is carried entirely by the eyes, brows and posture.
```

### R47 — Hotel room, suitcase open

```
@Rodrigo Maxwell sits on a hotel bed with an open suitcase beside him, bright window light. Anchors: neatly tapered dark hair combed back, precisely edged dark stubble, a crisp plain grey t-shirt. he stops folding; the shirt in his hands drops onto the case; his eyes stay wide on the phone.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. Reaction is carried entirely by the eyes, brows and posture.
```

### R48 — Airport seat

```
@Rodrigo Maxwell sits in an airport waiting seat in bright terminal light, bag between his feet. Anchors: neatly tapered dark hair, the silver hoop, a crisp black heavyweight t-shirt. his head comes up sharply and back down to the phone; his brows stay raised; he goes still, ignoring the gate.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. Reaction is carried entirely by the eyes, brows and posture.
```

### R49 — Train seat by the window

```
@Rodrigo Maxwell sits in a train seat with bright daylight through the window beside him. Anchors: neatly tapered dark hair combed back, the silver hoop, a crisp bone-coloured heavyweight t-shirt. he stops looking out; his eyes come to the phone and widen; he holds, shoulder against the window frame.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. Reaction is carried entirely by the eyes, brows and posture.
```

### R50 — Hotel corridor, walking

```
@Rodrigo Maxwell stops walking in a brightly lit hotel corridor, key card still in one hand. Anchors: neatly tapered dark hair combed back, precisely edged dark stubble, a crisply pressed slate-grey unstructured overshirt. his walk halts; he turns his shoulders to the phone; the key card lowers and he holds, staring.

Vertical 9:16 selfie filmed at arm's length on a phone front camera, face filling the upper half of the frame, mild wide-lens distortion, natural handheld sway, imperfect off-centre framing, deep focus with the background clearly readable, neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

No speech of any kind. The mouth never forms words and never attempts to talk. Reaction is carried entirely by the eyes, brows and posture.
```

