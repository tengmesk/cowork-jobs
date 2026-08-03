# Job — Lizzie Larsen lifestyle b-roll, 30 clips

> ## ✅ DONE — 2026-08-03. Do not re-run.
>
> All 30 clips generated and completed. Verified against Higgsfield history.
>
> **How they were actually made**, which differs from the spec below — recorded so the
> next persona is planned around what really happened, not what was written:
>
> | | Spec said | Actually run |
> |---|---|---|
> | Model | Seedance 2.0 | **Kling 3.0** |
> | Duration | 14s | **10s** |
> | Route | prompt-only | **image-first** — 30 start frames on Nano Banana, then animated |
> | Prompt | full block + 4 shared paragraphs | condensed to one paragraph + a one-line camera/skin tail |
>
> Aspect (9:16) and silence were as specified, and all 30 completed with no failures.
>
> **The image-first route is the finding worth keeping.** Generating a start frame and
> animating it is more controllable than prompt-only and it is how the next b-roll set
> should be planned. The beats still say "by ten seconds… in the final beats" while the
> clips are 10s long, so the last beat had no room — shorten the beat ladder to ~3s/~6s/end
> for 10s clips.
>
> **Element used: `Lizzie Larsen-1`** — see the warning below.

30 silent b-roll clips of Lizzie living her life: 7 poolside, 13 in her apartment,
10 around Miami. No dialogue, no on-screen text — text is added in post, which is why
each prompt reserves a specific third of the frame.

## Settings — these are UI controls, not prompt text

| Control | Set to |
|---|---|
| Model | **Seedance 2.0** |
| Duration | **14s** — the house maximum. 15s fails noticeably more often. Do not use it. |
| Aspect | **9:16 vertical** |
| Resolution | **1080p** |
| Sound | **Off** |
| Unlimited mode | **On** |

Confirm it reads "Unlimited" before generating. If any clip shows a credit cost, stop and
say so.

## How to run each clip

1. Type **`@Lizzie Larsen-1`** in the prompt box and pick the Element from the dropdown. Check the name has the `-1`.
2. Paste the block for that clip. Every block is complete and paste-ready — do not add
   anything, do not shorten it, do not re-describe her face. **The Element carries the
   face. Describing it again fights the Element and causes the drift you are trying to
   avoid.**
3. Put this in the **negative prompt** field, the same for all 30:

```
No music, no voiceover, no on-screen text, no captions, no logo, no watermark, no lower-third graphic. No dolly, no crane, no orbit, no rack focus, no push-in, no gimbal smoothing, no stabilisation.
```

## Do these three first, then stop

Generate **P01, A01 and M04** and report back before running the other 27. Those three
cover the three locations and will show immediately whether the Element holds up in
motion. One bad setting caught after three clips is cheap; caught after thirty is not.

## Two things that must stay consistent across the set

**The apartment is one place.** All 13 A-clips describe the same flat — pale wood floors,
white walls, tall windows with palm fronds outside, a marble kitchen island, a pale oak
desk, a large monstera. The wording repeats on purpose. If a clip comes back with a
different-looking flat, flag it; that is what makes her space recognisable across a feed.

**The pool is one place.** All 7 P-clips are the same rooftop pool — pale stone edge,
cream loungers, a city skyline beyond.

## Known failure modes — reject on sight

| What to look for | Why |
|---|---|
| Any other person's face appearing | Seedance renders background crowds as melted faces. Several clips imply company; none should show it. |
| Hands warping | Only an issue in extreme close-up; every prompt keeps hands at medium distance. If one drifts in, reject. |
| A mirror or a reflection of her | Reflections break. No prompt asks for one. |
| Any text, sign or logo rendering legibly | Always garbled. Text goes on in post. |
| Waxy, poreless skin | The skin line in every prompt exists to prevent this. |
| The clip freezing or looping after ~3s | Means the beats were dropped. Regenerate with the full block. |

## Report back

1. Which clips you generated and their URLs, grouped P / A / M
2. Any clip where the face drifted from the Element — be blunt, we would rather retake
3. Whether the apartment stayed the same apartment across the 13 A-clips
4. Any clip that froze, warped, or rendered another person's face
5. Anything that showed a credit cost rather than Unlimited

---

## Group P — Poolside (7)

### P01 — Pool edge, legs in the water

```
@Lizzie Larsen-1 A woman with sleek shoulder-length bright Scandi-blonde hair and dark taupe-brown brows, with an accentuated hourglass figure, a narrow waist and curved wide hips, wearing a fitted oat one-piece swimsuit, sits on the pale stone edge of a rooftop pool with her legs in the water, a city skyline hazy beyond the far edge. At the start she leans back on her hands, face tilted slightly to the sun; by around five seconds she stirs the water slowly with one foot, ripples spreading; by ten seconds she lifts her wet foot and watches the water run off it; in the final beats she settles back on her hands and goes still, breathing gently. The sky and skyline above her stay clear and simple, reserved in the top third of the frame for a text overlay.

Ultra-realistic vertical 9:16 video that looks like it was filmed by a real person on their phone, not a studio production. Heavy handheld shake softened to a gentle sway, imperfect framing, frequent autofocus hunting, exposure pumping slightly, occasional motion blur, subtle rolling shutter, mild digital compression artifacts. Deep focus, background clearly readable, no creamy bokeh. Neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, dewy and luminous, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

Subject fully absorbed in what she is doing and never turns toward or acknowledges the camera. Subtle natural breathing, occasional small head movement, natural blinking, slight weight shifts, realistic idle posture.
```

### P02 — Floating on her back

```
@Lizzie Larsen-1 A woman with sleek shoulder-length bright Scandi-blonde hair and dark taupe-brown brows, with an accentuated hourglass figure, a narrow waist and curved wide hips, wearing a fitted sage one-piece swimsuit, floats on her back in a rooftop pool, arms out to her sides, hair fanned in the water. At the start she drifts slowly with her eyes closed; by around five seconds her fingertips sweep small circles at the surface; by ten seconds she tips her chin back further and exhales, drifting a little; in the final beats she goes still, only the water moving her. The open water below her body stays clear, reserved in the bottom third of the frame for a text overlay.

Ultra-realistic vertical 9:16 video that looks like it was filmed by a real person on their phone, not a studio production. Heavy handheld shake softened to a gentle sway, imperfect framing, frequent autofocus hunting, exposure pumping slightly, occasional motion blur, subtle rolling shutter, mild digital compression artifacts. Deep focus, background clearly readable, no creamy bokeh. Neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, dewy and luminous, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

Subject fully absorbed in what she is doing and never turns toward or acknowledges the camera. Subtle natural breathing, occasional small head movement, natural blinking, slight weight shifts, realistic idle posture.
```

### P03 — Sunscreen on the lounger

```
@Lizzie Larsen-1 A woman with sleek shoulder-length bright Scandi-blonde hair and dark taupe-brown brows, with an accentuated hourglass figure, a narrow waist and curved wide hips, wearing a fitted white two-piece swimsuit, sits on a cream lounger applying sunscreen to her shoulder, an iced drink with a straw on the low table beside her. At the start she smooths the cream along her shoulder; by around five seconds she works it down her arm in unhurried strokes; by ten seconds she caps the bottle and reaches for the drink; in the final beats she takes a slow sip through the straw, looking out over the pool. The pale decking to her left stays uncluttered, reserved in the left third of the frame for a text overlay.

Ultra-realistic vertical 9:16 video that looks like it was filmed by a real person on their phone, not a studio production. Heavy handheld shake softened to a gentle sway, imperfect framing, frequent autofocus hunting, exposure pumping slightly, occasional motion blur, subtle rolling shutter, mild digital compression artifacts. Deep focus, background clearly readable, no creamy bokeh. Neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, dewy and luminous, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

Subject fully absorbed in what she is doing and never turns toward or acknowledges the camera. Subtle natural breathing, occasional small head movement, natural blinking, slight weight shifts, realistic idle posture.
```

### P04 — Walking the pool edge in a sarong

```
@Lizzie Larsen-1 A woman with sleek shoulder-length bright Scandi-blonde hair and dark taupe-brown brows, with an accentuated hourglass figure, a narrow waist and curved wide hips, wearing a fitted oat swimsuit with a warm-grey sarong tied low on her hips, walks unhurried along the pale stone edge of a rooftop pool trailing a towel from one hand. At the start she walks toward a cream lounger, sarong moving with each step; by around five seconds she pauses to look out at the skyline; by ten seconds she continues, dropping the towel onto the lounger as she passes; in the final beats she sits down on the lounger's edge and settles. The still water to her right stays clear, reserved in the right third of the frame for a text overlay.

Ultra-realistic vertical 9:16 video that looks like it was filmed by a real person on their phone, not a studio production. Heavy handheld shake softened to a gentle sway, imperfect framing, frequent autofocus hunting, exposure pumping slightly, occasional motion blur, subtle rolling shutter, mild digital compression artifacts. Deep focus, background clearly readable, no creamy bokeh. Neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, dewy and luminous, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

Subject fully absorbed in what she is doing and never turns toward or acknowledges the camera. Subtle natural breathing, occasional small head movement, natural blinking, slight weight shifts, realistic idle posture.
```

### P05 — Coconut on the cabana daybed

```
@Lizzie Larsen-1 A woman with sleek shoulder-length bright Scandi-blonde hair and dark taupe-brown brows, with an accentuated hourglass figure, a narrow waist and curved wide hips, wearing a fitted white two-piece swimsuit with an open sage cover-up, reclines on a cabana daybed with one knee up, a whole coconut with a straw resting on her stomach, phone in her other hand. At the start she scrolls slowly with her thumb; by around five seconds she takes a long sip from the coconut without looking away from the phone; by ten seconds something makes her smile faintly; in the final beats she sets the phone face-down beside her and rests her head back. The cabana canopy and sky above stay simple, reserved in the top third of the frame for a text overlay.

Ultra-realistic vertical 9:16 video that looks like it was filmed by a real person on their phone, not a studio production. Heavy handheld shake softened to a gentle sway, imperfect framing, frequent autofocus hunting, exposure pumping slightly, occasional motion blur, subtle rolling shutter, mild digital compression artifacts. Deep focus, background clearly readable, no creamy bokeh. Neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, dewy and luminous, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

Subject fully absorbed in what she is doing and never turns toward or acknowledges the camera. Subtle natural breathing, occasional small head movement, natural blinking, slight weight shifts, realistic idle posture.
```

### P06 — Towelling off, stepping into slides

```
@Lizzie Larsen-1 A woman with sleek shoulder-length bright Scandi-blonde hair and dark taupe-brown brows, with an accentuated hourglass figure, a narrow waist and curved wide hips, wearing a fitted sage one-piece swimsuit, stands dripping at the pool edge wrapping a white towel around herself. At the start she wraps the towel and tucks it at her chest; by around five seconds she gathers her wet hair and wrings it gently to one side, water darkening the stone; by ten seconds she steps one foot then the other into pale slides; in the final beats she picks up her phone from a lounger and walks out of frame. The row of cream loungers to her left stays quiet, reserved in the left third of the frame for a text overlay.

Ultra-realistic vertical 9:16 video that looks like it was filmed by a real person on their phone, not a studio production. Heavy handheld shake softened to a gentle sway, imperfect framing, frequent autofocus hunting, exposure pumping slightly, occasional motion blur, subtle rolling shutter, mild digital compression artifacts. Deep focus, background clearly readable, no creamy bokeh. Neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, dewy and luminous, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

Subject fully absorbed in what she is doing and never turns toward or acknowledges the camera. Subtle natural breathing, occasional small head movement, natural blinking, slight weight shifts, realistic idle posture.
```

### P07 — Golden hour on the pool step (POLISHED)

```
@Lizzie Larsen-1 A woman with sleek shoulder-length bright Scandi-blonde hair and dark taupe-brown brows, with an accentuated hourglass figure, a narrow waist and curved wide hips, wearing a fitted oat one-piece swimsuit, sits on the submerged top step of a rooftop pool at golden hour, water at her waist, low sun catching the surface. At the start she rests her arms on her knees watching the light move on the water; by around five seconds she draws one hand slowly across the surface, breaking the reflections; by ten seconds she tips her head back briefly into the last warmth; in the final beats she goes still, the water settling around her. The glowing water in front of her stays clear, reserved in the bottom third of the frame for a text overlay.

Ultra-realistic vertical 9:16 video that looks like it was filmed by a real person on their phone, not a studio production. Heavy handheld shake softened to a gentle sway, imperfect framing, frequent autofocus hunting, exposure pumping slightly, occasional motion blur, subtle rolling shutter, mild digital compression artifacts. Deep focus, background clearly readable, no creamy bokeh. Neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, dewy and luminous, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

Subject fully absorbed in what she is doing and never turns toward or acknowledges the camera. Subtle natural breathing, occasional small head movement, natural blinking, slight weight shifts, realistic idle posture.
```

## Group A — the apartment (13)

### A01 — Smoothie: blending

```
@Lizzie Larsen-1 A woman with sleek shoulder-length bright Scandi-blonde hair and dark taupe-brown brows, with an accentuated hourglass figure, a narrow waist and curved wide hips, wearing a fitted white strappy tank top and fitted high-waisted washed denim, stands at a marble kitchen island in a bright apartment with pale wood floors and tall windows, palm fronds visible outside, dropping fruit into a blender. At the start she drops in strawberries and a handful of spinach; by around five seconds she pours in oat milk, presses the lid on and starts the blender, holding the lid with one hand; by ten seconds she stops it and lifts the lid to check; in the final beats she gives the jug a small satisfied shake. The white wall and window above the island stay clear, reserved in the top third of the frame for a text overlay.

Ultra-realistic vertical 9:16 video that looks like it was filmed by a real person on their phone, not a studio production. Heavy handheld shake softened to a gentle sway, imperfect framing, frequent autofocus hunting, exposure pumping slightly, occasional motion blur, subtle rolling shutter, mild digital compression artifacts. Deep focus, background clearly readable, no creamy bokeh. Neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, dewy and luminous, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

Subject fully absorbed in what she is doing and never turns toward or acknowledges the camera. Subtle natural breathing, occasional small head movement, natural blinking, slight weight shifts, realistic idle posture.
```

### A02 — Smoothie: pouring and tasting

```
@Lizzie Larsen-1 A woman with sleek shoulder-length bright Scandi-blonde hair and dark taupe-brown brows, with an accentuated hourglass figure, a narrow waist and curved wide hips, wearing a fitted white strappy tank top and fitted high-waisted washed denim, pours a pink smoothie from a blender jug into a tall glass at a marble island, morning light across the counter. At the start she pours slowly, tilting the glass; by around five seconds she sets the jug down and slides the glass toward herself; by ten seconds she takes a first taste through a glass straw and considers it; in the final beats she nods slightly to herself and takes a longer sip, leaning a hip against the island. The tall bright window to her right stays simple, reserved in the right third of the frame for a text overlay.

Ultra-realistic vertical 9:16 video that looks like it was filmed by a real person on their phone, not a studio production. Heavy handheld shake softened to a gentle sway, imperfect framing, frequent autofocus hunting, exposure pumping slightly, occasional motion blur, subtle rolling shutter, mild digital compression artifacts. Deep focus, background clearly readable, no creamy bokeh. Neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, dewy and luminous, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

Subject fully absorbed in what she is doing and never turns toward or acknowledges the camera. Subtle natural breathing, occasional small head movement, natural blinking, slight weight shifts, realistic idle posture.
```

### A03 — "Working" at the desk

```
@Lizzie Larsen-1 A woman with sleek shoulder-length bright Scandi-blonde hair and dark taupe-brown brows, with an accentuated hourglass figure, a narrow waist and curved wide hips, wearing a fitted white strappy tank top and fitted high-waisted washed denim, sits at a pale oak desk by a tall window, laptop open, an iced coffee sweating beside it, palm fronds moving gently outside. At the start she types in a short unhurried burst; by around five seconds she pauses, takes a sip of the iced coffee and looks out of the window; by ten seconds she returns to the laptop and scrolls with one finger; in the final beats she sits back in the chair and stretches her arms overhead. The plain white wall to her left stays clear, reserved in the left third of the frame for a text overlay.

Ultra-realistic vertical 9:16 video that looks like it was filmed by a real person on their phone, not a studio production. Heavy handheld shake softened to a gentle sway, imperfect framing, frequent autofocus hunting, exposure pumping slightly, occasional motion blur, subtle rolling shutter, mild digital compression artifacts. Deep focus, background clearly readable, no creamy bokeh. Neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, dewy and luminous, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

Subject fully absorbed in what she is doing and never turns toward or acknowledges the camera. Subtle natural breathing, occasional small head movement, natural blinking, slight weight shifts, realistic idle posture.
```

### A04 — Filming herself

```
@Lizzie Larsen-1 A woman with sleek shoulder-length bright Scandi-blonde hair and dark taupe-brown brows, with an accentuated hourglass figure, a narrow waist and curved wide hips, wearing a fitted white strappy tank top and fitted high-waisted washed denim, sets her phone into a small tripod on the marble island and steps back to check the framing. At the start she seats the phone in the tripod and angles it down slightly; by around five seconds she steps back behind the island and squares her shoulders as if about to film; by ten seconds she steps forward again to nudge the tripod a centimetre; in the final beats she returns to her mark and settles, hands resting on the counter. The white wall above the island stays clear, reserved in the top third of the frame for a text overlay.

Ultra-realistic vertical 9:16 video that looks like it was filmed by a real person on their phone, not a studio production. Heavy handheld shake softened to a gentle sway, imperfect framing, frequent autofocus hunting, exposure pumping slightly, occasional motion blur, subtle rolling shutter, mild digital compression artifacts. Deep focus, background clearly readable, no creamy bokeh. Neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, dewy and luminous, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

Subject fully absorbed in what she is doing and never turns toward or acknowledges the camera. Subtle natural breathing, occasional small head movement, natural blinking, slight weight shifts, realistic idle posture.
```

### A05 — Getting ready: lip gloss at the window

```
@Lizzie Larsen-1 A woman with sleek shoulder-length bright Scandi-blonde hair and dark taupe-brown brows, with an accentuated hourglass figure, a narrow waist and curved wide hips, wearing a fitted white strappy tank top, sits at a small vanity table beside a tall bright window applying gloss to her lips, no mirror in frame, working by feel with her chin tilted up. At the start she sweeps the gloss across her lower lip; by around five seconds she presses her lips together and tilts her head; by ten seconds she recaps the gloss and drops it into a small dish of makeup; in the final beats she runs a hand through her hair and settles it behind one ear. The bright window to her right stays clear, reserved in the right third of the frame for a text overlay.

Ultra-realistic vertical 9:16 video that looks like it was filmed by a real person on their phone, not a studio production. Heavy handheld shake softened to a gentle sway, imperfect framing, frequent autofocus hunting, exposure pumping slightly, occasional motion blur, subtle rolling shutter, mild digital compression artifacts. Deep focus, background clearly readable, no creamy bokeh. Neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, dewy and luminous, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

Subject fully absorbed in what she is doing and never turns toward or acknowledges the camera. Subtle natural breathing, occasional small head movement, natural blinking, slight weight shifts, realistic idle posture.
```

### A06 — Hair with the round brush

```
@Lizzie Larsen-1 A woman with sleek shoulder-length bright Scandi-blonde hair and dark taupe-brown brows, with an accentuated hourglass figure, a narrow waist and curved wide hips, wearing a fitted white strappy tank top, stands near the tall window working a round brush through her hair, head tipped to one side. At the start she draws the brush slowly through one section; by around five seconds she tips her head the other way and starts the other side; by ten seconds she smooths the finished side down with her palm; in the final beats she shakes her hair out gently and it settles at her shoulders. The plain wall to her left stays clear, reserved in the left third of the frame for a text overlay.

Ultra-realistic vertical 9:16 video that looks like it was filmed by a real person on their phone, not a studio production. Heavy handheld shake softened to a gentle sway, imperfect framing, frequent autofocus hunting, exposure pumping slightly, occasional motion blur, subtle rolling shutter, mild digital compression artifacts. Deep focus, background clearly readable, no creamy bokeh. Neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, dewy and luminous, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

Subject fully absorbed in what she is doing and never turns toward or acknowledges the camera. Subtle natural breathing, occasional small head movement, natural blinking, slight weight shifts, realistic idle posture.
```

### A07 — Choosing between two outfits

```
@Lizzie Larsen-1 A woman with sleek shoulder-length bright Scandi-blonde hair and dark taupe-brown brows, with an accentuated hourglass figure, a narrow waist and curved wide hips, wearing a fitted white strappy tank top and fitted high-waisted washed denim, stands at the foot of a white-linen bed holding up two dresses on hangers, one sage and one oat, looking between them. At the start she holds the sage one against herself; by around five seconds she swaps and holds the oat one up, tilting her head; by ten seconds she decides, tossing the sage dress onto the bed; in the final beats she holds the chosen one at arm's length with a small satisfied nod. The plain wall above the bed stays clear, reserved in the top third of the frame for a text overlay.

Ultra-realistic vertical 9:16 video that looks like it was filmed by a real person on their phone, not a studio production. Heavy handheld shake softened to a gentle sway, imperfect framing, frequent autofocus hunting, exposure pumping slightly, occasional motion blur, subtle rolling shutter, mild digital compression artifacts. Deep focus, background clearly readable, no creamy bokeh. Neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, dewy and luminous, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

Subject fully absorbed in what she is doing and never turns toward or acknowledges the camera. Subtle natural breathing, occasional small head movement, natural blinking, slight weight shifts, realistic idle posture.
```

### A08 — Unboxing on the sofa

```
@Lizzie Larsen-1 A woman with sleek shoulder-length bright Scandi-blonde hair and dark taupe-brown brows, with an accentuated hourglass figure, a narrow waist and curved wide hips, wearing a fitted white strappy tank top and fitted high-waisted washed denim, sits cross-legged on a pale sofa opening a delivery box, tissue paper folded over the contents. At the start she lifts the lid and sets it aside; by around five seconds she parts the tissue paper carefully; by ten seconds she lifts out a folded warm-grey knit and holds it up to look at it; in the final beats she presses it briefly against herself, pleased. The pale rug and floor below the sofa stay clear, reserved in the bottom third of the frame for a text overlay.

Ultra-realistic vertical 9:16 video that looks like it was filmed by a real person on their phone, not a studio production. Heavy handheld shake softened to a gentle sway, imperfect framing, frequent autofocus hunting, exposure pumping slightly, occasional motion blur, subtle rolling shutter, mild digital compression artifacts. Deep focus, background clearly readable, no creamy bokeh. Neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, dewy and luminous, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

Subject fully absorbed in what she is doing and never turns toward or acknowledges the camera. Subtle natural breathing, occasional small head movement, natural blinking, slight weight shifts, realistic idle posture.
```

### A09 — Watering the monstera in a robe

```
@Lizzie Larsen-1 A woman with sleek shoulder-length bright Scandi-blonde hair and dark taupe-brown brows, with an accentuated hourglass figure, a narrow waist and curved wide hips, wearing an oat waffle robe loosely tied at her narrow waist, waters a large monstera by the tall window with a slim brass watering can, a coffee cup in the other hand. At the start she tips the can into the pot; by around five seconds she pauses to touch one broad leaf, turning it toward the light; by ten seconds she takes a sip of coffee while the can rests against her hip; in the final beats she gives the pot a final short pour and steps back to look at the plant. The bright window to her right stays clear, reserved in the right third of the frame for a text overlay.

Ultra-realistic vertical 9:16 video that looks like it was filmed by a real person on their phone, not a studio production. Heavy handheld shake softened to a gentle sway, imperfect framing, frequent autofocus hunting, exposure pumping slightly, occasional motion blur, subtle rolling shutter, mild digital compression artifacts. Deep focus, background clearly readable, no creamy bokeh. Neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, dewy and luminous, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

Subject fully absorbed in what she is doing and never turns toward or acknowledges the camera. Subtle natural breathing, occasional small head movement, natural blinking, slight weight shifts, realistic idle posture.
```

### A10 — Journaling on the sofa

```
@Lizzie Larsen-1 A woman with sleek shoulder-length bright Scandi-blonde hair and dark taupe-brown brows, with an accentuated hourglass figure, a narrow waist and curved wide hips, wearing a fitted white strappy tank top and soft warm-grey high-waisted lounge trousers, sits on the pale sofa with her legs tucked under her, writing in a linen-covered journal in golden late light. At the start she writes steadily; by around five seconds she pauses, pen resting at her lip, thinking; by ten seconds she writes again, shorter; in the final beats she closes the journal over the pen and rests her head back against the cushion. The plain wall to her left stays clear, reserved in the left third of the frame for a text overlay.

Ultra-realistic vertical 9:16 video that looks like it was filmed by a real person on their phone, not a studio production. Heavy handheld shake softened to a gentle sway, imperfect framing, frequent autofocus hunting, exposure pumping slightly, occasional motion blur, subtle rolling shutter, mild digital compression artifacts. Deep focus, background clearly readable, no creamy bokeh. Neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, dewy and luminous, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

Subject fully absorbed in what she is doing and never turns toward or acknowledges the camera. Subtle natural breathing, occasional small head movement, natural blinking, slight weight shifts, realistic idle posture.
```

### A11 — Making the bed

```
@Lizzie Larsen-1 A woman with sleek shoulder-length bright Scandi-blonde hair and dark taupe-brown brows, with an accentuated hourglass figure, a narrow waist and curved wide hips, wearing a fitted white strappy tank top and fitted high-waisted washed denim, makes a bed with white linen in low morning sun, dust drifting in the light. At the start she throws the duvet high and lets it billow and settle; by around five seconds she smooths it flat with both hands in long strokes; by ten seconds she plumps one pillow and sets it against the headboard; in the final beats she places the second pillow and pats it once. The wall above the bed stays clear, reserved in the top third of the frame for a text overlay.

Ultra-realistic vertical 9:16 video that looks like it was filmed by a real person on their phone, not a studio production. Heavy handheld shake softened to a gentle sway, imperfect framing, frequent autofocus hunting, exposure pumping slightly, occasional motion blur, subtle rolling shutter, mild digital compression artifacts. Deep focus, background clearly readable, no creamy bokeh. Neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, dewy and luminous, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

Subject fully absorbed in what she is doing and never turns toward or acknowledges the camera. Subtle natural breathing, occasional small head movement, natural blinking, slight weight shifts, realistic idle posture.
```

### A12 — Flowers at the island

```
@Lizzie Larsen-1 A woman with sleek shoulder-length bright Scandi-blonde hair and dark taupe-brown brows, with an accentuated hourglass figure, a narrow waist and curved wide hips, wearing a fitted white strappy tank top and fitted high-waisted washed denim, trims the stems of white and green flowers at the marble island and arranges them into a clear vase. At the start she snips a stem at an angle and drops the cutting aside; by around five seconds she places two stems into the vase and adjusts them; by ten seconds she turns the vase slowly to check it from another side; in the final beats she tucks one last stem in and steps back half a pace to look. The tall window to her right stays clear, reserved in the right third of the frame for a text overlay.

Ultra-realistic vertical 9:16 video that looks like it was filmed by a real person on their phone, not a studio production. Heavy handheld shake softened to a gentle sway, imperfect framing, frequent autofocus hunting, exposure pumping slightly, occasional motion blur, subtle rolling shutter, mild digital compression artifacts. Deep focus, background clearly readable, no creamy bokeh. Neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, dewy and luminous, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

Subject fully absorbed in what she is doing and never turns toward or acknowledges the camera. Subtle natural breathing, occasional small head movement, natural blinking, slight weight shifts, realistic idle posture.
```

### A13 — Evening wind-down (POLISHED)

```
@Lizzie Larsen-1 A woman with sleek shoulder-length bright Scandi-blonde hair and dark taupe-brown brows, with an accentuated hourglass figure, a narrow waist and curved wide hips, wearing an oat waffle robe over a fitted white strappy tank top, lights a candle on a low coffee table in the last blue-gold light of the evening, a glass of white wine beside it. At the start she strikes a match and touches it to the wick; by around five seconds she shakes the match out and sets it in a small dish; by ten seconds she picks up the wine and settles back into the sofa, legs curling under her; in the final beats she watches the flame steady, glass resting against her knee. The low table surface in the bottom third of frame stays simple, reserved for a text overlay.

Ultra-realistic vertical 9:16 video that looks like it was filmed by a real person on their phone, not a studio production. Heavy handheld shake softened to a gentle sway, imperfect framing, frequent autofocus hunting, exposure pumping slightly, occasional motion blur, subtle rolling shutter, mild digital compression artifacts. Deep focus, background clearly readable, no creamy bokeh. Neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, dewy and luminous, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

Subject fully absorbed in what she is doing and never turns toward or acknowledges the camera. Subtle natural breathing, occasional small head movement, natural blinking, slight weight shifts, realistic idle posture.
```

## Group M — Miami (10)

### M01 — Brunch arriving

```
@Lizzie Larsen-1 A woman with sleek shoulder-length bright Scandi-blonde hair and dark taupe-brown brows, with an accentuated hourglass figure, a narrow waist and curved wide hips, wearing a fitted white strappy tank top and a sage linen skirt, sits at an outdoor café table as an açai bowl and an iced matcha are set down in front of her, sunglasses pushed up in her hair. At the start she lifts her sunglasses off and sets them on the table to look at the food; by around five seconds she turns the bowl slowly by its rim, admiring it; by ten seconds she picks up the spoon and takes a first small taste; in the final beats she reaches for the matcha and takes a sip through the straw. The café awning and bright sky above stay simple, reserved in the top third of the frame for a text overlay.

Ultra-realistic vertical 9:16 video that looks like it was filmed by a real person on their phone, not a studio production. Heavy handheld shake softened to a gentle sway, imperfect framing, frequent autofocus hunting, exposure pumping slightly, occasional motion blur, subtle rolling shutter, mild digital compression artifacts. Deep focus, background clearly readable, no creamy bokeh. Neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, dewy and luminous, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

Subject fully absorbed in what she is doing and never turns toward or acknowledges the camera. Subtle natural breathing, occasional small head movement, natural blinking, slight weight shifts, realistic idle posture.
```

### M02 — Photographing brunch

```
@Lizzie Larsen-1 A woman with sleek shoulder-length bright Scandi-blonde hair and dark taupe-brown brows, with an accentuated hourglass figure, a narrow waist and curved wide hips, wearing a fitted white strappy tank top and a sage linen skirt, stands slightly over an outdoor café table photographing an açai bowl from above with her phone, held at medium distance. At the start she frames the shot, elbows steady; by around five seconds she moves the matcha glass an inch into frame and reshoots; by ten seconds she checks the photo, thumb flicking between two takes; in the final beats she puts the phone face-down on the table, sits, and picks up her spoon. The table edge and floor in the bottom third of frame stay simple, reserved for a text overlay.

Ultra-realistic vertical 9:16 video that looks like it was filmed by a real person on their phone, not a studio production. Heavy handheld shake softened to a gentle sway, imperfect framing, frequent autofocus hunting, exposure pumping slightly, occasional motion blur, subtle rolling shutter, mild digital compression artifacts. Deep focus, background clearly readable, no creamy bokeh. Neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, dewy and luminous, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

Subject fully absorbed in what she is doing and never turns toward or acknowledges the camera. Subtle natural breathing, occasional small head movement, natural blinking, slight weight shifts, realistic idle posture.
```

### M03 — Rooftop bar at dusk (POLISHED)

```
@Lizzie Larsen-1 A woman with sleek shoulder-length bright Scandi-blonde hair and dark taupe-brown brows, with an accentuated hourglass figure, a narrow waist and curved wide hips, wearing a fitted warm-grey bodycon midi dress, leans on the railing of a rooftop bar at dusk, a spritz in one hand, a lit city skyline behind her. At the start she looks out over the skyline, glass resting on the rail; by around five seconds she turns the glass slowly by its stem, ice shifting; by ten seconds she takes an unhurried sip, hair moving slightly in the rooftop breeze; in the final beats she sets the glass back on the rail and leans onto her forearms. The open sky to her left stays clear, reserved in the left third of the frame for a text overlay.

Ultra-realistic vertical 9:16 video that looks like it was filmed by a real person on their phone, not a studio production. Heavy handheld shake softened to a gentle sway, imperfect framing, frequent autofocus hunting, exposure pumping slightly, occasional motion blur, subtle rolling shutter, mild digital compression artifacts. Deep focus, background clearly readable, no creamy bokeh. Neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, dewy and luminous, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

Subject fully absorbed in what she is doing and never turns toward or acknowledges the camera. Subtle natural breathing, occasional small head movement, natural blinking, slight weight shifts, realistic idle posture.
```

### M04 — Palm-lined avenue mid-stride

```
@Lizzie Larsen-1 A woman with sleek shoulder-length bright Scandi-blonde hair and dark taupe-brown brows, with an accentuated hourglass figure, a narrow waist and curved wide hips, wearing a fitted white strappy tank top and fitted high-waisted washed denim with a straw tote on one shoulder and sunglasses on, walks along a wide palm-lined avenue in bright sun, each step landing heel-first and rolling forward. At the start she walks at an easy pace, tote swinging slightly; by around five seconds she glances into a shopfront without stopping; by ten seconds she moves the tote higher onto her shoulder; in the final beats she keeps walking, unhurried, past a bank of planted palms. The palm crowns and bright sky above stay simple, reserved in the top third of the frame for a text overlay.

Ultra-realistic vertical 9:16 video that looks like it was filmed by a real person on their phone, not a studio production. Heavy handheld shake softened to a gentle sway, imperfect framing, frequent autofocus hunting, exposure pumping slightly, occasional motion blur, subtle rolling shutter, mild digital compression artifacts. Deep focus, background clearly readable, no creamy bokeh. Neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, dewy and luminous, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

Subject fully absorbed in what she is doing and never turns toward or acknowledges the camera. Subtle natural breathing, occasional small head movement, natural blinking, slight weight shifts, realistic idle posture.
```

### M05 — Pastel buildings, iced coffee

```
@Lizzie Larsen-1 A woman with sleek shoulder-length bright Scandi-blonde hair and dark taupe-brown brows, with an accentuated hourglass figure, a narrow waist and curved wide hips, wearing a fitted sage ribbed bodycon midi dress and white trainers, walks past a row of pastel art-deco buildings with an iced coffee in hand, morning light flat and bright. At the start she walks past a pale pink façade, cup in hand; by around five seconds she takes a sip through the straw without breaking stride; by ten seconds she slows to look up at a curved balcony; in the final beats she carries on walking, swinging the cup gently at her side. The flat pastel wall to her right stays uncluttered, reserved in the right third of the frame for a text overlay.

Ultra-realistic vertical 9:16 video that looks like it was filmed by a real person on their phone, not a studio production. Heavy handheld shake softened to a gentle sway, imperfect framing, frequent autofocus hunting, exposure pumping slightly, occasional motion blur, subtle rolling shutter, mild digital compression artifacts. Deep focus, background clearly readable, no creamy bokeh. Neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, dewy and luminous, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

Subject fully absorbed in what she is doing and never turns toward or acknowledges the camera. Subtle natural breathing, occasional small head movement, natural blinking, slight weight shifts, realistic idle posture.
```

### M06 — Hotel lobby exit

```
@Lizzie Larsen-1 A woman with sleek shoulder-length bright Scandi-blonde hair and dark taupe-brown brows, with an accentuated hourglass figure, a narrow waist and curved wide hips, wearing a fitted oat bodycon midi dress and sunglasses, steps out of a hotel lobby into bright sun as a doorman in a light uniform holds the door from behind her, only his arm and shoulder in frame. At the start she steps through the held door onto the pavement; by around five seconds she pauses at the kerb and settles her sunglasses; by ten seconds she checks her phone briefly and puts it away in a small bag; in the final beats she turns and walks along the front of the building. The pale stone façade to her left stays simple, reserved in the left third of the frame for a text overlay.

Ultra-realistic vertical 9:16 video that looks like it was filmed by a real person on their phone, not a studio production. Heavy handheld shake softened to a gentle sway, imperfect framing, frequent autofocus hunting, exposure pumping slightly, occasional motion blur, subtle rolling shutter, mild digital compression artifacts. Deep focus, background clearly readable, no creamy bokeh. Neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, dewy and luminous, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

Subject fully absorbed in what she is doing and never turns toward or acknowledges the camera. Subtle natural breathing, occasional small head movement, natural blinking, slight weight shifts, realistic idle posture.
```

### M07 — Open-top car at the light (POLISHED)

```
@Lizzie Larsen-1 A woman with sleek shoulder-length bright Scandi-blonde hair and dark taupe-brown brows, with an accentuated hourglass figure, a narrow waist and curved wide hips, wearing a fitted white strappy tank top and sage linen trousers with sunglasses on, sits in the back seat of a stationary open-top car at a red light, one arm resting along the door, palms overhead against the sky. At the start she rests her head back against the seat, face to the sun; by around five seconds she drums her fingers once slowly on the door; by ten seconds she turns to watch something pass on the pavement; in the final beats she settles back again, hair lifting slightly in the breeze. The palms and sky overhead stay simple, reserved in the top third of the frame for a text overlay.

Ultra-realistic vertical 9:16 video that looks like it was filmed by a real person on their phone, not a studio production. Heavy handheld shake softened to a gentle sway, imperfect framing, frequent autofocus hunting, exposure pumping slightly, occasional motion blur, subtle rolling shutter, mild digital compression artifacts. Deep focus, background clearly readable, no creamy bokeh. Neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, dewy and luminous, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

Subject fully absorbed in what she is doing and never turns toward or acknowledges the camera. Subtle natural breathing, occasional small head movement, natural blinking, slight weight shifts, realistic idle posture.
```

### M08 — Designer storefront

```
@Lizzie Larsen-1 A woman with sleek shoulder-length bright Scandi-blonde hair and dark taupe-brown brows, with an accentuated hourglass figure, a narrow waist and curved wide hips, wearing a fitted warm-grey bodycon midi dress, pauses at an angle before a designer storefront window, the display of bags lit inside, her body angled so the glass shows the display and not her reflection. At the start she slows and stops, weight settling onto one hip; by around five seconds she lifts her sunglasses onto her hair to look properly; by ten seconds she leans in slightly toward one bag on its plinth; in the final beats she straightens, drops the sunglasses back down, and moves on. The clean pavement in the bottom third of frame stays clear, reserved for a text overlay.

Ultra-realistic vertical 9:16 video that looks like it was filmed by a real person on their phone, not a studio production. Heavy handheld shake softened to a gentle sway, imperfect framing, frequent autofocus hunting, exposure pumping slightly, occasional motion blur, subtle rolling shutter, mild digital compression artifacts. Deep focus, background clearly readable, no creamy bokeh. Neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, dewy and luminous, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

Subject fully absorbed in what she is doing and never turns toward or acknowledges the camera. Subtle natural breathing, occasional small head movement, natural blinking, slight weight shifts, realistic idle posture.
```

### M09 — Balcony sunrise in a robe (POLISHED)

```
@Lizzie Larsen-1 A woman with sleek shoulder-length bright Scandi-blonde hair and dark taupe-brown brows, with an accentuated hourglass figure, a narrow waist and curved wide hips, wearing an oat waffle robe tied at her narrow waist, stands at a high hotel balcony rail at sunrise holding a coffee cup in both hands, the city skyline below washed in first light. At the start she blows gently across the coffee; by around five seconds she takes a careful first sip; by ten seconds she rests the cup on the rail, hands wrapped around it, watching the light move across the buildings; in the final beats she closes her eyes briefly into the warmth and opens them again. The skyline below the rail stays soft and simple, reserved in the bottom third of the frame for a text overlay.

Ultra-realistic vertical 9:16 video that looks like it was filmed by a real person on their phone, not a studio production. Heavy handheld shake softened to a gentle sway, imperfect framing, frequent autofocus hunting, exposure pumping slightly, occasional motion blur, subtle rolling shutter, mild digital compression artifacts. Deep focus, background clearly readable, no creamy bokeh. Neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, dewy and luminous, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

Subject fully absorbed in what she is doing and never turns toward or acknowledges the camera. Subtle natural breathing, occasional small head movement, natural blinking, slight weight shifts, realistic idle posture.
```

### M10 — Market mangoes

```
@Lizzie Larsen-1 A woman with sleek shoulder-length bright Scandi-blonde hair and dark taupe-brown brows, with an accentuated hourglass figure, a narrow waist and curved wide hips, wearing a fitted white strappy tank top and a sage linen skirt with a straw tote over one shoulder, chooses mangoes at a farmers-market stall stacked with fruit, no other shoppers in frame. At the start she picks up a mango and presses it gently with her thumb; by around five seconds she lifts it briefly to smell it; by ten seconds she drops it into her straw tote and picks up a second; in the final beats she adds the second one and steadies the tote against her hip. The stall canopy edge and bright sky to her right stay simple, reserved in the right third of the frame for a text overlay.

Ultra-realistic vertical 9:16 video that looks like it was filmed by a real person on their phone, not a studio production. Heavy handheld shake softened to a gentle sway, imperfect framing, frequent autofocus hunting, exposure pumping slightly, occasional motion blur, subtle rolling shutter, mild digital compression artifacts. Deep focus, background clearly readable, no creamy bokeh. Neutral auto white balance, no colour grade, no cinematic camera moves, no stabilisation, no 3D, no cartoon, no VFX.

Natural skin texture with visible pores and natural tone variation, dewy and luminous, no studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

Subject fully absorbed in what she is doing and never turns toward or acknowledges the camera. Subtle natural breathing, occasional small head movement, natural blinking, slight weight shifts, realistic idle posture.
```
