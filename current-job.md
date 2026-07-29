# Higgsfield job board

**Read the CURRENT JOB section and do exactly what it says.** Everything above it is
standing context that does not change. When told to "refresh", re-fetch this page —
the CURRENT JOB section will have been replaced.

Last updated: 2026-07-29 04:2x — CURRENT JOB is now **Maya Miller**.

---

## Standing rules

You are working in the Higgsfield web app at higgsfield.ai, signed in as
tmmeskhi@gmail.com (Pro plan, workspace "Private").

**Billing.** This account holds **Unlimited passes that expire 2026-08-04**, applying
**only inside the web app** — never via API or CLI. Covered: Higgsfield Soul 2.0,
Nano Banana 2 (2K), Nano Banana Pro (2K), GPT Image 2 (2K), Seedream 5.0 Pro (2K),
**Seedance 2.0 Standard (720p)**, Kling v3.0. If anything shows a credit cost instead
of "Unlimited", **stop and say so before proceeding**. Character/Soul *training* may
cost credits even when generation is unlimited — that is expected, but report the
number before you start it.

**You cannot reach the local filesystem.** Steps needing a file are marked **[YOU]** —
click Upload to open the native dialog and let the human pick the file. Everything
before and after that is yours.

**Existing character — Terry Sterling** (do not retrain, already built):

| | |
|---|---|
| Soul (stills only) | `b45b1df9-ca52-4580-89c3-caa756cfe7a7` |
| Reference Element (video only) | `883ccefd-6b8e-4edf-a048-9d24fa2f1067` |

Soul never works with video. Seedance 2.0 and Kling 3.0 take the Element, embedded in
the prompt as `<<<element-id>>>`.

**Reporting.** Be blunt and critical. We would rather hear something looks wrong than
be told it's fine. Never call an image spec-compliant if it isn't.

---

# CURRENT JOB

## Build the Maya Miller character — Element, then Soul

Maya is a 36-year-old woman who fronts legal-tech content for AgentX Labs, aimed at
owners of retail law firms. We have **one usable photo** of her, so the Soul cannot be
trained directly. The order is: Element from the photo → 21 portraits generated with
that Element → curate → train the Soul on the keepers.

This is the reverse of Terry, who already had 28 training portraits.

### Step 1 — Reference Element **[YOU]**

Click Upload. The human will select:

`assets/personas/maya-miller/media/headshot-red-backdrop.png`

(Crimson seamless backdrop, black blazer over ivory silk V-neck, silver studs, long
dark wavy hair, warm closed-mouth smile. There is a second file `headshot-office.png` —
**do not use it**, its office background would bleed into her identity.)

Create a **Reference Element** from it. Name it `Maya Miller — element`.

**Note for later:** this first Element is bootstrapped from the one source photo, which
is all we have right now. After Step 3, rebuild the Element from the curated keepers —
Higgsfield accepts multiple images per Element, so give it a front-on chest-up with
hands visible, a three-quarter, and a full-length. The Element is what video uses, so
it needs her proportions and not just her face. Report both Element IDs.

**Report the Element ID.** Everything downstream depends on it.

Keep this Element permanently even after the Soul exists — Elements are what Seedance
2.0 and Kling 3.0 accept for video. Soul does not do video.

### Step 2 — Generate 21 bootstrap portraits

Model: **Nano Banana Pro (2K)** or **Nano Banana 2 (2K)**, with the Maya Element
attached to every generation. Vertical or square, 2K.

Generate **2–3 variants of each** of the 21 shot lines below, then keep the single
best of each. Target **22–26 keepers** overall — the uploader accepts 80, but that
ceiling is not a goal.

**These are TRAINING images. Do not add any iPhone, handheld, grain, HDR or
phone-camera language.** Training images must be clean, evenly lit and neutral so the
model learns her *face* and not the noise. Phone realism is applied later, at content
generation time. Getting this backwards bakes the grain into her identity permanently
and cannot be undone.

Every prompt is exactly three parts in this order, pasted verbatim:

```
[IDENTITY STRING] + [shot line] + [TAIL]
```

**IDENTITY STRING — byte-identical every single time. Never paraphrase or shorten it.**

> A 36-year-old woman with warm Mediterranean/Levantine features. Olive-warm skin. Oval face, softly defined cheekbones, straight nose with a slightly rounded tip, full lips with a clear cupid's bow, warm dark-brown almond eyes, thick dark eyebrows with a soft natural arch. Long dark brown-black hair, loose natural waves, off-centre part, falling over both shoulders. Small silver stud earrings.

**TAIL — also verbatim every time:**

> Clean neutral studio lighting, plain mid-grey seamless background, sharp focus on the face. Unretouched skin shown at its real age: visible pores across the cheeks, nose and forehead, natural skin texture and slight unevenness in tone, fine lines at the outer eyes and mouth left completely intact, a natural shine on the forehead, nose and cheekbones. The face is NOT smoothed, NOT evened out and NOT flattered. No skin smoothing, no beauty filter, no digital retouching, no airbrushing. No text, no logos, no watermark.

*(That skin wording is deliberately blunt. On the Terry build, the softer phrasing
"realistic skin texture — visible pores" was too weak and the model beautified anyway,
twice. Do not soften it back.)*

**NEGATIVE PROMPT**, if a negative field exists:

> smooth skin, airbrushed, retouched, beauty filter, poreless, flawless complexion, glamour lighting, heavy makeup

**Shot lines 1–12 — face coverage:**

1. Head-and-shoulders headshot, facing the camera straight on, neutral expression, mouth closed, eyes to lens.
2. Head-and-shoulders headshot, facing the camera straight on, warm composed closed-mouth smile with a faint crinkle at the outer eyes, eyes to lens.
3. Head-and-shoulders headshot, facing the camera straight on, open genuine laugh with teeth showing and eyes crinkled.
4. Head-and-shoulders headshot, head and body turned three-quarters to her left, neutral expression, eyes back to lens.
5. Head-and-shoulders headshot, head and body turned three-quarters to her right, slight closed-mouth smile, eyes back to lens.
6. Head-and-shoulders headshot in full left profile, ninety degrees to camera, neutral expression, looking off-frame.
7. Head-and-shoulders headshot, chin slightly lowered, eyes raised to the lens, faint knowing half-smile.
8. Head-and-shoulders headshot, chin slightly raised, confident and composed, mouth closed, eyes to lens.
9. Head-and-shoulders headshot, facing the camera straight on, neutral expression, hair pulled back into a low ponytail so the hairline and both ears are fully visible and the jawline and neck are clear. **For this one only**, replace "Long dark brown-black hair, loose natural waves, off-centre part, falling over both shoulders" in the identity string with "Dark brown-black hair pulled back into a low ponytail".
10. Waist-up shot, standing, facing the camera straight on, arms relaxed at her sides, neutral expression, wearing a black tailored blazer over an ivory silk shell.
11. Head-and-shoulders headshot, facing the camera straight on, neutral expression, with hard directional light from camera-left casting a defined shadow across the right side of her face. **For this one only**, replace "Clean neutral studio lighting" in the tail with "Hard directional light from camera-left".
12. Head-and-shoulders headshot, facing the camera straight on, neutral expression, completely flat soft frontal lighting with no visible shadow anywhere on the face.

Shots **9 and 10** matter more than they look — the ponytail gives the model her
jawline and hairline, the waist-up gives it her proportions. Shots **11 and 12** teach
her face under opposite lighting so she survives varied scenes later.

**Then these nine more.** Shots 1–12 are face coverage, which trains a Soul that makes
good stills but weak *video*. Video goes wider than chest-up constantly, rotates the
head, and animates gestures from the hands — none of which the first twelve teach.

13. Head-and-shoulders headshot, straight on, neutral, hair tucked behind one ear so one ear is visible and the other is covered by falling waves.
14. Head-and-shoulders headshot, straight on, neutral, lit from behind by a bright window so the face is in soft even shadow and the background blows out.
15. Full-length shot, standing, facing the camera straight on, feet visible, arms relaxed at her sides, neutral expression. Black tailored blazer over an ivory silk shell, dark tailored trousers, plain court shoes.
16. Full-length shot, standing, turned three-quarters to her left, weight on one hip, one hand at her side and one holding a closed laptop against her body.
17. Seated on a plain stool, facing the camera, forearms resting on her thighs, hands loosely clasped and clearly visible, leaning very slightly forward.
18. Waist-up, straight on, both hands raised to chest height mid-gesture as if explaining something, fingers relaxed and separated, palms angled inward.
19. Waist-up, straight on, holding a plain white coffee cup in both hands at chest height, hands and fingers clearly visible.
20. Head-and-shoulders headshot, straight on, neutral, wearing a camel fine-knit crew-neck instead of the blazer.
21. Waist-up, straight on, neutral, wearing a plain white t-shirt under an open black blazer.

**Shots 15–19 exist for video specifically.** 15 and 16 give the model her build,
height and shoulder width so wide frames stop drifting. 17–19 put hands in the training
set — Seedance animates gestures from the start frame, and hands it has never seen
render as mush. 20 and 21 prove the face survives a wardrobe change.

**Do not simply generate more to be safe.** A Soul trained on too much variety averages
toward a generic face, and full-length shots carry far less facial information per image
than a headshot. Keep the final set **face-dominant — roughly two thirds head-and-
shoulders** — and vary angle and lighting while holding her identity and core wardrobe
constant.

### Step 3 — Curate

Keep **22–26**, judged on one question only: *is this unmistakably the same woman as
the source photo?* Keep the balance face-dominant — about two thirds head-and-shoulders,
the rest body and hands.

Reject anything where the face has drifted younger, thinner, more generic, more
European, or noticeably more symmetrical than the source. **Prefer variety of angle and
lighting over prettiness.** A slightly awkward but accurate image is worth more than a
flattering but wrong one — the Soul learns whatever you feed it.

Tell the human which ones you kept so they can be saved locally.

### Step 4 — Train the Soul

- Name: `Maya Miller`
- Model: **Soul 2.0** (not Soul Cinematic)
- Upload the curated keepers **[YOU]** — native file dialog again
- The uploader accepts up to 80 images
- Report the training cost before starting, then start and wait

**Report the Soul ID** — the UUID, exactly.

### Step 5 — Report

1. The **Element ID**
2. The **Soul ID**
3. How many portraits you generated, how many you kept, and what you rejected them for
4. Whether the kept set genuinely looks like one consistent woman — be blunt about drift
5. Whether the skin came out unretouched or still smoothed. On the Terry build this
   was the persistent failure; say plainly if it happened again.
6. Anything that showed a credit cost rather than Unlimited

Then **stop**. Do not generate content images or video for Maya yet.

---

## QUEUED — not now

**Terry: three daylight start frames, regenerated with hardened skin/background
wording.** Was the previous CURRENT JOB. Superseded by Maya; will be restored to
CURRENT JOB when Maya's character exists.
