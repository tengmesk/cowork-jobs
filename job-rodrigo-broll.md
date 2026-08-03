# Job — Rodrigo Maxwell b-roll, 40 clips

> ## BLOCKED — do not start this yet
>
> This job needs an Element named exactly **`Rodrigo Maxwell`**, which does not exist until
> his character job is finished and the owner has approved the keepers. If typing
> `@Rodrigo Maxwell` in the prompt box does not offer a matching Element, **stop and say
> so**. Do not substitute a Soul — Soul is stills only and does nothing for video.
>
> His character job is here and comes first:
> https://raw.githubusercontent.com/tengmesk/cowork-jobs/main/job-rodrigo-maxwell.md

40 silent b-roll clips of Rodrigo working: 10 at the desk with analytics open, 10 in a
coworking space or studio, 10 in the city or in transit, 10 off-duty. No dialogue, no
on-screen text — text is added in post, which is why each prompt reserves a specific third
of the frame.

**What these are for.** He is the *operator* — the one who ran other people's funnels and
saw the same leak forty times. The b-roll has to look like someone who actually does the
work, not someone performing being busy. That is why the analytics group is the largest
single reason this set exists, and why nothing here shows him presenting to camera.

## Settings — these are UI controls, not prompt text

| Control | Set to |
|---|---|
| Model | **Seedance 2.0** |
| Duration | **14s** — the house maximum. 15s fails noticeably more often. Do not use it. |
| Aspect | **9:16 vertical** — not "Auto" |
| Resolution | **1080p** |
| Sound | **Off** |
| Unlimited mode | **On** |

Confirm it reads "Unlimited" before generating. If any clip shows a credit cost, stop and
say so.

## How to run each clip

1. Type **`@Rodrigo Maxwell`** in the prompt box and pick the Element from the dropdown.
2. Paste the block for that clip. Every block below is complete and paste-ready — the
   realism, camera, skin and ambient paragraphs are already appended. Do not add anything,
   do not shorten it, and **do not re-describe his face**. Each prompt deliberately carries
   only three to five anchors — the hair, the silver hoop, one garment. The Element carries
   the face; describing it again fights the Element and causes the drift you are trying to
   avoid.
3. Put this in the **negative prompt** field, the same for all 40:

```
No music, no voiceover, no on-screen text, no captions, no logo, no watermark, no lower-third graphic. No dolly, no crane, no orbit, no rack focus, no push-in, no gimbal smoothing, no stabilisation.
```

## Do these four first, then stop

Generate **W01, S01, C01 and O01** and report back before running the other 36. Those four
cover the four environments and will show immediately whether the Element holds in motion.
One bad setting caught after four clips is cheap; caught after forty it is not.

## Known failure modes — reject on sight

| What to look for | Why |
|---|---|
| Any other person's face rendering | Seedance renders background crowds as melted faces. The coworking and city groups imply other people; none should show a readable face. |
| Screen content rendering as legible text | Always garbled. Dashboards should read as shapes and graphs, never words. Any real number goes on in post. |
| Hands warping | Only an issue in extreme close-up; every prompt keeps hands at medium distance and anchored to an object. If one drifts in, reject. |
| A mirror or a reflection of him | Reflections break. No prompt asks for one. |
| Waxy, poreless skin | The skin paragraph in every block exists to prevent this. |
| The clip freezing or looping after ~3s | Means the beats were dropped. Regenerate with the full block. |
| The silver hoop moving ears or vanishing | It is in his left ear. It is one of the few identity anchors these prompts carry. |

**Every scene in this set is daylight or bright indoor light, deliberately.** A low-key
scene overrides the phone-camera wording and renders closer to graded cinema than to a
phone snapshot, which is the opposite of what these are for. If a clip comes back looking
dim, moody or colour-graded, that is a fault — flag it and retake.

## Report back

1. Which clips you generated and their URLs, grouped W / S / C / O
2. Any clip where the face drifted from the Element — be blunt, we would rather retake
3. Any clip that froze, warped, or rendered another person's face
4. Whether screen content stayed illegible rather than resolving into fake words
5. Anything that showed a credit cost rather than Unlimited

---

## Group W — Working / analytics (10)

### W01 — Two monitors, morning scroll
*Hook: "the leak was in the data the whole time" / attribution-gap opener.*

```
@Rodrigo Maxwell He sits at a home desk in front of two monitors, one showing a dense analytics dashboard with graphs and click-through tables, right hand resting on a mouse. Anchors: neatly tapered dark hair combed back, the silver hoop, a crisp heavyweight black plain t-shirt. Small apartment home office, morning light coming in low through a window on his right, a plain pale wall filling the left third of frame reserved for text. Camera appears to be propped on a stack of books at desk height, static frame with a tiny natural handheld sway. Beats: ~0s he's mid-scroll through the dashboard, cursor moving; ~5s he pauses on one row, leans in slightly, brow tightening; ~10s he reaches for a coffee cup beside the keyboard without looking away from the screen; ~13s he sets the cup down and resumes scrolling, unresolved, still absorbed.

Ultra-realistic vertical 9:16 video that looks like it was filmed by a real person on their phone, not a studio production. No 3D, no cartoon, no VFX, no modern colour grading, no cinematic camera moves, no stabilisation.

Heavy handheld shake, imperfect framing, frequent autofocus hunting, lens breathing, exposure pumping slightly, occasional motion blur, subtle rolling shutter, mild digital compression artifacts. Camera catches the moment a beat late, framing slightly off-centre.

Natural skin texture with visible pores and natural tone variation. No studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

Subject fully absorbed in what he is doing and never turns toward or acknowledges the camera. Subtle natural breathing, occasional small head movement, natural blinking, slight weight shifts, realistic idle posture.
```

### W02 — Kitchen table, early laptop
*Hook: "before the office opens, the numbers don't wait" / grind-adjacent b-roll.*

```
@Rodrigo Maxwell He sits at a kitchen table working on a laptop, a bowl with a spoon in it pushed to one side, phone face-down beside the keyboard. Anchors: the silver hoop, precisely edged dark stubble, a crisp bone-coloured heavyweight t-shirt. Small kitchen, early morning light through a window behind him, a plain cabinet door filling the top third of frame reserved for text. Camera held low on the table itself, resting, very slight handheld drift. Beats: ~0s he's typing, unhurried; ~5s he flips the phone over, glances at it, sets it back down face-up; ~10s he picks up the spoon and eats a bite without looking away from the laptop; ~14s he returns both hands to the keyboard, still reading.

Ultra-realistic vertical 9:16 video that looks like it was filmed by a real person on their phone, not a studio production. No 3D, no cartoon, no VFX, no modern colour grading, no cinematic camera moves, no stabilisation.

Heavy handheld shake, imperfect framing, frequent autofocus hunting, lens breathing, exposure pumping slightly, occasional motion blur, subtle rolling shutter, mild digital compression artifacts. Camera catches the moment a beat late, framing slightly off-centre.

Natural skin texture with visible pores and natural tone variation. No studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

Subject fully absorbed in what he is doing and never turns toward or acknowledges the camera. Subtle natural breathing, occasional small head movement, natural blinking, slight weight shifts, realistic idle posture.
```

### W03 — Whiteboard, funnel sketch
*Hook: "this is where the tap-through dies" / explainer-adjacent cutaway.*

```
@Rodrigo Maxwell He stands at a whiteboard with a funnel diagram already partly sketched — boxes and arrows — marker in his right hand, adding a new box. Anchors: neatly tapered dark hair, the silver hoop, a crisply pressed slate-grey unstructured overshirt open over a black tee. Small office nook, midday light, a plain section of whiteboard filling the right third of frame kept clear for text. Camera held at chest height a few steps back, small natural handheld sway, no repositioning. Beats: ~0s he finishes an arrow between two boxes; ~5s he steps back, capping the marker, studying the diagram; ~10s he uncaps it again and circles one box firmly; ~13s he taps the circled box twice with the marker tip, still looking at the board.

Ultra-realistic vertical 9:16 video that looks like it was filmed by a real person on their phone, not a studio production. No 3D, no cartoon, no VFX, no modern colour grading, no cinematic camera moves, no stabilisation.

Heavy handheld shake, imperfect framing, frequent autofocus hunting, lens breathing, exposure pumping slightly, occasional motion blur, subtle rolling shutter, mild digital compression artifacts. Camera catches the moment a beat late, framing slightly off-centre.

Natural skin texture with visible pores and natural tone variation. No studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

Subject fully absorbed in what he is doing and never turns toward or acknowledges the camera. Subtle natural breathing, occasional small head movement, natural blinking, slight weight shifts, realistic idle posture.
```

### W04 — Headphones, muted call
*Hook: "listening to a client explain the thing you already fixed" / relatable-operator beat.*

```
@Rodrigo Maxwell He sits at his desk wearing over-ear headphones, laptop open showing a video call window, leaning back slightly in his chair. Anchors: the silver hoop, precisely edged dark stubble, a crisp black heavyweight plain t-shirt. Home office, early evening, warm lamp light from one side, a plain wall filling the bottom third of frame behind the desk edge reserved for text. Camera propped on a shelf slightly above eye level, static with faint natural drift. Beats: ~0s he's nodding slowly, listening; ~5s he leans forward and types a short note on a pad beside the keyboard; ~10s he leans back again, rubbing his jaw once; ~14s he reaches for the mouse and clicks something on screen, still listening.

Ultra-realistic vertical 9:16 video that looks like it was filmed by a real person on their phone, not a studio production. No 3D, no cartoon, no VFX, no modern colour grading, no cinematic camera moves, no stabilisation.

Heavy handheld shake, imperfect framing, frequent autofocus hunting, lens breathing, exposure pumping slightly, occasional motion blur, subtle rolling shutter, mild digital compression artifacts. Camera catches the moment a beat late, framing slightly off-centre.

Natural skin texture with visible pores and natural tone variation. No studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

Subject fully absorbed in what he is doing and never turns toward or acknowledges the camera. Subtle natural breathing, occasional small head movement, natural blinking, slight weight shifts, realistic idle posture.
```

### W05 — Co-working desk, printed spreadsheet
*Hook: "printed it out because the pattern only shows up on paper" / old-school-operator beat.*

```
@Rodrigo Maxwell He sits at a shared desk with a printed spreadsheet in front of him next to an open laptop, pen in hand, tracing down a column of numbers. Anchors: neatly tapered dark hair, the silver hoop, a crisp bone-coloured heavyweight t-shirt. Co-working space, bright afternoon sunlight through a large window behind him, the window filling the left third of frame reserved for text. Camera held roughly at chest height across the table, small natural sway, no movement. Beats: ~0s his pen traces down the printed column; ~5s he stops, circles one number, glances between paper and laptop screen; ~10s he types something into the laptop with one hand while the pen stays on the paper; ~13s he sits back, tapping the pen twice against the desk.

Ultra-realistic vertical 9:16 video that looks like it was filmed by a real person on their phone, not a studio production. No 3D, no cartoon, no VFX, no modern colour grading, no cinematic camera moves, no stabilisation.

Heavy handheld shake, imperfect framing, frequent autofocus hunting, lens breathing, exposure pumping slightly, occasional motion blur, subtle rolling shutter, mild digital compression artifacts. Camera catches the moment a beat late, framing slightly off-centre.

Natural skin texture with visible pores and natural tone variation. No studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

Subject fully absorbed in what he is doing and never turns toward or acknowledges the camera. Subtle natural breathing, occasional small head movement, natural blinking, slight weight shifts, realistic idle posture.
```

### W06 — Standing desk, late afternoon
*Hook: "standing up doesn't fix a broken funnel but it helps you think" / working-late texture.*

```
@Rodrigo Maxwell He works at a raised standing desk, laptop showing an analytics dashboard, one hand on the trackpad. Anchors: precisely edged dark stubble, the silver hoop, a crisp black heavyweight t-shirt under an open slate-grey overshirt. Home office, warm late-afternoon light low through a window, a plain stretch of wall filling the top third of frame reserved for text. Camera set on a shelf across the room at desk height, static with a faint handheld tremor. Beats: ~0s he scrolls the dashboard, weight on one foot; ~5s he shifts his weight to the other foot, rolling one shoulder; ~10s he leans both hands on the desk edge, studying the screen closely; ~14s he straightens up and resumes scrolling, unresolved.

Ultra-realistic vertical 9:16 video that looks like it was filmed by a real person on their phone, not a studio production. No 3D, no cartoon, no VFX, no modern colour grading, no cinematic camera moves, no stabilisation.

Heavy handheld shake, imperfect framing, frequent autofocus hunting, lens breathing, exposure pumping slightly, occasional motion blur, subtle rolling shutter, mild digital compression artifacts. Camera catches the moment a beat late, framing slightly off-centre.

Natural skin texture with visible pores and natural tone variation. No studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

Subject fully absorbed in what he is doing and never turns toward or acknowledges the camera. Subtle natural breathing, occasional small head movement, natural blinking, slight weight shifts, realistic idle posture.
```

### W07 — Floor and coffee table, sunny afternoon
*Hook: "Sunday afternoon, still checking the numbers" / off-hours-working beat.*

```
@Rodrigo Maxwell He sits on the floor with his back against a couch, laptop open on a low coffee table in front of him, typing steadily. Anchors: neatly tapered dark hair combed back, the silver hoop, a clean slate-grey plain hoodie sleeves pushed up. Living room, bright afternoon sunlight through a window falling in a hard rectangle across the floor beside him, the window filling the right third of frame reserved for text. Camera held low at coffee-table height, resting, slight natural sway. Beats: ~0s steady typing; ~5s he shifts slightly to get the sun off the laptop screen, then keeps typing; ~10s he stretches one arm overhead briefly, then returns his hand to the keyboard; ~13s he resumes typing, absorbed.

Ultra-realistic vertical 9:16 video that looks like it was filmed by a real person on their phone, not a studio production. No 3D, no cartoon, no VFX, no modern colour grading, no cinematic camera moves, no stabilisation.

Heavy handheld shake, imperfect framing, frequent autofocus hunting, lens breathing, exposure pumping slightly, occasional motion blur, subtle rolling shutter, mild digital compression artifacts. Camera catches the moment a beat late, framing slightly off-centre.

Natural skin texture with visible pores and natural tone variation. No studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

Subject fully absorbed in what he is doing and never turns toward or acknowledges the camera. Subtle natural breathing, occasional small head movement, natural blinking, slight weight shifts, realistic idle posture.
```

### W08 — Dual monitor, phone lights up
*Hook: "the notification that means someone's dashboard just broke" / mild-tension beat.*

```
@Rodrigo Maxwell He sits at a desk in front of dual monitors showing dashboards, phone lying screen-up beside the keyboard. Anchors: the silver hoop, precisely edged dark stubble, a crisp black heavyweight t-shirt. Home office, mid-morning daylight, a bookshelf softened by distance filling the bottom third of frame reserved for text. Camera propped at desk level to one side, static with faint natural sway. Beats: ~0s he's reading the left monitor; ~5s the phone screen lights up beside him, he glances down at it; ~10s he picks it up, reads briefly, sets it back down without unlocking it further; ~14s he returns both hands to the keyboard, back to the monitor.

Ultra-realistic vertical 9:16 video that looks like it was filmed by a real person on their phone, not a studio production. No 3D, no cartoon, no VFX, no modern colour grading, no cinematic camera moves, no stabilisation.

Heavy handheld shake, imperfect framing, frequent autofocus hunting, lens breathing, exposure pumping slightly, occasional motion blur, subtle rolling shutter, mild digital compression artifacts. Camera catches the moment a beat late, framing slightly off-centre.

Natural skin texture with visible pores and natural tone variation. No studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

Subject fully absorbed in what he is doing and never turns toward or acknowledges the camera. Subtle natural breathing, occasional small head movement, natural blinking, slight weight shifts, realistic idle posture.
```

### W09 — Kitchen counter, standing laptop
*Hook: "no desk, still working the numbers" / makeshift-office beat.*

```
@Rodrigo Maxwell He stands at a kitchen counter, laptop propped on a closed cookbook, stirring a mug of coffee slowly with the other hand while reading the screen. Anchors: neatly tapered dark hair, the silver hoop, a crisp bone-coloured heavyweight t-shirt. Kitchen, soft morning light, a plain cabinet filling the left third of frame reserved for text. Camera held at counter height across from him, small natural sway. Beats: ~0s he stirs and reads; ~5s he sets the spoon down on a saucer and lifts the mug to drink; ~10s he sets the mug down and scrolls the laptop trackpad with two fingers; ~13s he leans in slightly closer to the screen, still reading.

Ultra-realistic vertical 9:16 video that looks like it was filmed by a real person on their phone, not a studio production. No 3D, no cartoon, no VFX, no modern colour grading, no cinematic camera moves, no stabilisation.

Heavy handheld shake, imperfect framing, frequent autofocus hunting, lens breathing, exposure pumping slightly, occasional motion blur, subtle rolling shutter, mild digital compression artifacts. Camera catches the moment a beat late, framing slightly off-centre.

Natural skin texture with visible pores and natural tone variation. No studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

Subject fully absorbed in what he is doing and never turns toward or acknowledges the camera. Subtle natural breathing, occasional small head movement, natural blinking, slight weight shifts, realistic idle posture.
```

### W10 — Late-night desk lamp
*Hook: "the numbers don't clock off at six" / late-night-operator beat.*

```
@Rodrigo Maxwell He sits at a desk lit mainly by a single lamp, one monitor glowing in front of him, city lights visible faintly through half-open blinds behind. Anchors: precisely edged dark stubble, the silver hoop, a crisp black heavyweight plain t-shirt. Home office at night, warm lamp light against cool window light behind, the blinds and window filling the top third of frame reserved for text. Camera set on the desk itself at a low angle, static with faint natural tremor. Beats: ~0s he types, focused; ~5s he stops, leans back in the chair, rubbing the back of his neck; ~10s he leans forward again, scrolling slowly with the mouse; ~14s he pauses on something, chin resting briefly on one hand.

Ultra-realistic vertical 9:16 video that looks like it was filmed by a real person on their phone, not a studio production. No 3D, no cartoon, no VFX, no modern colour grading, no cinematic camera moves, no stabilisation.

Heavy handheld shake, imperfect framing, frequent autofocus hunting, lens breathing, exposure pumping slightly, occasional motion blur, subtle rolling shutter, mild digital compression artifacts. Camera catches the moment a beat late, framing slightly off-centre.

Natural skin texture with visible pores and natural tone variation. No studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

Subject fully absorbed in what he is doing and never turns toward or acknowledges the camera. Subtle natural breathing, occasional small head movement, natural blinking, slight weight shifts, realistic idle posture.
```

## Group S — Coworking / studio (10)

### S01 — Shared long table, morning
*Hook: "everyone at this table is building something" / coworking-texture beat.*

```
@Rodrigo Maxwell He sits at a long shared coworking table, laptop open, typing, with two other people working quietly further down the table, out of focus. Anchors: neatly tapered dark hair combed back, the silver hoop, a crisp black heavyweight t-shirt. Bright coworking space, big windows behind, morning light, a section of plain wall to one side filling the right third of frame reserved for text. Camera held at chest height across the table, small natural sway. Beats: ~0s steady typing; ~5s he glances briefly at a notification on his phone screen beside the keyboard then back to the laptop; ~10s he shifts in his seat, one hand now resting on the table; ~13s he resumes typing, absorbed.

Ultra-realistic vertical 9:16 video that looks like it was filmed by a real person on their phone, not a studio production. No 3D, no cartoon, no VFX, no modern colour grading, no cinematic camera moves, no stabilisation.

Heavy handheld shake, imperfect framing, frequent autofocus hunting, lens breathing, exposure pumping slightly, occasional motion blur, subtle rolling shutter, mild digital compression artifacts. Camera catches the moment a beat late, framing slightly off-centre.

Natural skin texture with visible pores and natural tone variation. No studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

Subject fully absorbed in what he is doing and never turns toward or acknowledges the camera. Subtle natural breathing, occasional small head movement, natural blinking, slight weight shifts, realistic idle posture.
```

### S02 — Meeting-room corner, someone else's rig
*Hook: "borrowed a corner of someone else's studio" / creator-adjacent proximity beat.*

```
@Rodrigo Maxwell He sits at a small table in the corner of a glass-walled meeting room, laptop open, reviewing something on screen; behind him, out of focus, a ring light and a phone rig on a tripod belong to someone else and stand unattended. Anchors: precisely edged dark stubble, the silver hoop, a crisply pressed slate-grey unstructured overshirt over a black tee. Coworking space, soft daylight through the glass wall, the glass wall filling the left third of frame reserved for text. Camera held roughly at eye height a few feet back, static with slight natural sway. Beats: ~0s he reads the screen, still; ~5s he taps a key and leans in slightly; ~10s he glances briefly toward the ring light behind him, unbothered, then back to his screen; ~14s he continues typing.

Ultra-realistic vertical 9:16 video that looks like it was filmed by a real person on their phone, not a studio production. No 3D, no cartoon, no VFX, no modern colour grading, no cinematic camera moves, no stabilisation.

Heavy handheld shake, imperfect framing, frequent autofocus hunting, lens breathing, exposure pumping slightly, occasional motion blur, subtle rolling shutter, mild digital compression artifacts. Camera catches the moment a beat late, framing slightly off-centre.

Natural skin texture with visible pores and natural tone variation. No studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

Subject fully absorbed in what he is doing and never turns toward or acknowledges the camera. Subtle natural breathing, occasional small head movement, natural blinking, slight weight shifts, realistic idle posture.
```

### S03 — Lounge corner, laptop on knees
*Hook: "no desk required when the numbers are the job" / informal-office beat.*

```
@Rodrigo Maxwell He sits sideways on a low couch in a coworking lounge, laptop balanced on his knees, one arm along the couch back. Anchors: neatly tapered dark hair, the silver hoop, a crisp bone-coloured heavyweight t-shirt. Exposed brick wall behind him, midday light through a skylight, the brick wall filling the top third of frame reserved for text. Camera held at seated eye height, small natural sway. Beats: ~0s he reads the screen, relaxed posture; ~5s he adjusts the laptop slightly on his knees; ~10s he reaches to scroll with one finger, other hand still on the couch back; ~13s he settles back again, still reading.

Ultra-realistic vertical 9:16 video that looks like it was filmed by a real person on their phone, not a studio production. No 3D, no cartoon, no VFX, no modern colour grading, no cinematic camera moves, no stabilisation.

Heavy handheld shake, imperfect framing, frequent autofocus hunting, lens breathing, exposure pumping slightly, occasional motion blur, subtle rolling shutter, mild digital compression artifacts. Camera catches the moment a beat late, framing slightly off-centre.

Natural skin texture with visible pores and natural tone variation. No studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

Subject fully absorbed in what he is doing and never turns toward or acknowledges the camera. Subtle natural breathing, occasional small head movement, natural blinking, slight weight shifts, realistic idle posture.
```

### S04 — Video call, own setup
*Hook: "the call where you tell someone their link is leaking money" / direct-to-camera-adjacent beat (he faces his own screen, not ours).*

```
@Rodrigo Maxwell He sits at a desk with a laptop propped up showing a video call window, looking at his own screen and gesturing with one hand as if mid-explanation. Anchors: precisely edged dark stubble, the silver hoop, a crisp black heavyweight t-shirt. Small private coworking booth, warm even light, a plain acoustic panel wall filling the bottom third of frame reserved for text. Camera set slightly to the side of the laptop at desk height, static with faint natural sway. Beats: ~0s he gestures once with an open hand toward the screen; ~5s he pauses, nodding, listening; ~10s he leans forward and types something quickly with one hand; ~14s he leans back again, still facing the laptop screen.

Ultra-realistic vertical 9:16 video that looks like it was filmed by a real person on their phone, not a studio production. No 3D, no cartoon, no VFX, no modern colour grading, no cinematic camera moves, no stabilisation.

Heavy handheld shake, imperfect framing, frequent autofocus hunting, lens breathing, exposure pumping slightly, occasional motion blur, subtle rolling shutter, mild digital compression artifacts. Camera catches the moment a beat late, framing slightly off-centre.

Natural skin texture with visible pores and natural tone variation. No studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

Subject fully absorbed in what he is doing and never turns toward or acknowledges the camera. Subtle natural breathing, occasional small head movement, natural blinking, slight weight shifts, realistic idle posture.
```

### S05 — Setting up beside someone else's ring light
*Hook: "everyone else here is building a personal brand, he's building the plumbing" / contrast beat.*

```
@Rodrigo Maxwell He crouches beside a desk, plugging a laptop charger into a power strip, a ring light and phone tripod belonging to someone else standing switched-off nearby. Anchors: neatly tapered dark hair combed back, the silver hoop, a clean slate-grey plain hoodie sleeves pushed up. Coworking space, afternoon window light, a plain painted wall filling the left third of frame reserved for text. Camera held at standing eye height a few feet back, small natural sway. Beats: ~0s he finishes plugging in the charger; ~5s he stands, glancing briefly at the ring light beside him, unimpressed but not dismissive; ~10s he sits down at the desk and opens the laptop; ~13s he starts typing, settled in.

Ultra-realistic vertical 9:16 video that looks like it was filmed by a real person on their phone, not a studio production. No 3D, no cartoon, no VFX, no modern colour grading, no cinematic camera moves, no stabilisation.

Heavy handheld shake, imperfect framing, frequent autofocus hunting, lens breathing, exposure pumping slightly, occasional motion blur, subtle rolling shutter, mild digital compression artifacts. Camera catches the moment a beat late, framing slightly off-centre.

Natural skin texture with visible pores and natural tone variation. No studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

Subject fully absorbed in what he is doing and never turns toward or acknowledges the camera. Subtle natural breathing, occasional small head movement, natural blinking, slight weight shifts, realistic idle posture.
```

### S06 — Kitchenette, making coffee
*Hook: "the only break in six hours of dashboards" / small-human-beat.*

```
@Rodrigo Maxwell He stands at a shared coworking kitchenette, pressing a button on a coffee machine, mug already waiting under the spout. Anchors: precisely edged dark stubble, the silver hoop, a crisp black heavyweight t-shirt. Bright shared kitchen area, midday light, a row of plain cabinets filling the top third of frame reserved for text. Camera held at counter height, small natural sway. Beats: ~0s he presses the machine button, coffee starts pouring; ~5s he watches the cup fill, weight shifted onto one hip; ~10s he lifts the full mug and takes a first careful sip; ~13s he turns slightly and starts walking back toward the desks, mug in hand.

Ultra-realistic vertical 9:16 video that looks like it was filmed by a real person on their phone, not a studio production. No 3D, no cartoon, no VFX, no modern colour grading, no cinematic camera moves, no stabilisation.

Heavy handheld shake, imperfect framing, frequent autofocus hunting, lens breathing, exposure pumping slightly, occasional motion blur, subtle rolling shutter, mild digital compression artifacts. Camera catches the moment a beat late, framing slightly off-centre.

Natural skin texture with visible pores and natural tone variation. No studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

Subject fully absorbed in what he is doing and never turns toward or acknowledges the camera. Subtle natural breathing, occasional small head movement, natural blinking, slight weight shifts, realistic idle posture.
```

### S07 — Quiet pod, headphones
*Hook: "the fifteen minutes with no notifications" / focus-block beat.*

```
@Rodrigo Maxwell He sits in a small enclosed coworking phone-booth pod, laptop on his knees, headphones on, eyes on the screen. Anchors: neatly tapered dark hair, the silver hoop, a crisp bone-coloured heavyweight t-shirt. Narrow acoustic pod, warm interior light, a plain acoustic-panel wall filling the right third of frame reserved for text. Camera held at seated eye height, static with faint natural sway. Beats: ~0s he reads, still; ~5s he taps a key, small nod along to something only he can hear; ~10s he adjusts one headphone slightly with a finger; ~14s he resumes reading, absorbed.

Ultra-realistic vertical 9:16 video that looks like it was filmed by a real person on their phone, not a studio production. No 3D, no cartoon, no VFX, no modern colour grading, no cinematic camera moves, no stabilisation.

Heavy handheld shake, imperfect framing, frequent autofocus hunting, lens breathing, exposure pumping slightly, occasional motion blur, subtle rolling shutter, mild digital compression artifacts. Camera catches the moment a beat late, framing slightly off-centre.

Natural skin texture with visible pores and natural tone variation. No studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

Subject fully absorbed in what he is doing and never turns toward or acknowledges the camera. Subtle natural breathing, occasional small head movement, natural blinking, slight weight shifts, realistic idle posture.
```

### S08 — Shared whiteboard wall, sticky notes
*Hook: "someone else's sprint board, his own funnel note stuck in the corner" / borrowed-space beat.*

```
@Rodrigo Maxwell He stands at a shared whiteboard wall covered in other people's sticky notes, adding one of his own in a clear corner, marker in hand. Anchors: precisely edged dark stubble, the silver hoop, a crisply pressed slate-grey unstructured overshirt over a black tee. Coworking common area, bright overhead light, a section of the whiteboard filling the bottom third of frame reserved for text. Camera held at chest height a few steps back, small natural sway. Beats: ~0s he writes on the sticky note; ~5s he presses it onto the board and steps back to look; ~10s he adjusts its position slightly, pressing the corners flat; ~13s he caps the marker and turns slightly, done.

Ultra-realistic vertical 9:16 video that looks like it was filmed by a real person on their phone, not a studio production. No 3D, no cartoon, no VFX, no modern colour grading, no cinematic camera moves, no stabilisation.

Heavy handheld shake, imperfect framing, frequent autofocus hunting, lens breathing, exposure pumping slightly, occasional motion blur, subtle rolling shutter, mild digital compression artifacts. Camera catches the moment a beat late, framing slightly off-centre.

Natural skin texture with visible pores and natural tone variation. No studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

Subject fully absorbed in what he is doing and never turns toward or acknowledges the camera. Subtle natural breathing, occasional small head movement, natural blinking, slight weight shifts, realistic idle posture.
```

### S09 — Window seat, blinds
*Hook: "watching the street, still thinking about the leak" / thinking-beat.*

```
@Rodrigo Maxwell He sits at a small table beside a large window in a coworking space, laptop closed in front of him for a moment, hand reaching to adjust the blinds slightly. Anchors: neatly tapered dark hair combed back, the silver hoop, a crisp black heavyweight t-shirt. Warm afternoon light through the window and blinds, the window filling the top third of frame reserved for text. Camera held at seated eye height, small natural sway. Beats: ~0s he adjusts the blind slat with two fingers; ~5s he opens the laptop again; ~10s he starts typing, glancing once more toward the window; ~13s he settles into steady typing.

Ultra-realistic vertical 9:16 video that looks like it was filmed by a real person on their phone, not a studio production. No 3D, no cartoon, no VFX, no modern colour grading, no cinematic camera moves, no stabilisation.

Heavy handheld shake, imperfect framing, frequent autofocus hunting, lens breathing, exposure pumping slightly, occasional motion blur, subtle rolling shutter, mild digital compression artifacts. Camera catches the moment a beat late, framing slightly off-centre.

Natural skin texture with visible pores and natural tone variation. No studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

Subject fully absorbed in what he is doing and never turns toward or acknowledges the camera. Subtle natural breathing, occasional small head movement, natural blinking, slight weight shifts, realistic idle posture.
```

### S10 — Long table, blurred figures, note pad
*Hook: "wrote the whole funnel fix on a napkin first" / analog-thinking beat.*

```
@Rodrigo Maxwell He sits at a communal coworking table, a note pad and pen in front of him next to a closed laptop, sketching a simple diagram by hand; two other people are visible working far down the table, out of focus. Anchors: precisely edged dark stubble, the silver hoop, a crisp bone-coloured heavyweight t-shirt. Bright morning light through large windows, a section of plain wall filling the left third of frame reserved for text. Camera held at seated eye height across the table, small natural sway. Beats: ~0s he draws a line on the pad; ~5s he adds an arrow and a small box; ~10s he taps the pen against the pad, studying it; ~14s he opens the laptop with his other hand, still looking at the sketch.

Ultra-realistic vertical 9:16 video that looks like it was filmed by a real person on their phone, not a studio production. No 3D, no cartoon, no VFX, no modern colour grading, no cinematic camera moves, no stabilisation.

Heavy handheld shake, imperfect framing, frequent autofocus hunting, lens breathing, exposure pumping slightly, occasional motion blur, subtle rolling shutter, mild digital compression artifacts. Camera catches the moment a beat late, framing slightly off-centre.

Natural skin texture with visible pores and natural tone variation. No studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

Subject fully absorbed in what he is doing and never turns toward or acknowledges the camera. Subtle natural breathing, occasional small head movement, natural blinking, slight weight shifts, realistic idle posture.
```

## Group C — City / in transit (10)

### C01 — Sidewalk, coffee, morning
*Hook: "walking to the one meeting that actually matters this week" / commute-opener.*

```
@Rodrigo Maxwell He walks along a city sidewalk holding a takeaway coffee cup, unhurried pace, other pedestrians sparse and blurred by distance. Anchors: neatly tapered dark hair, the silver hoop, a crisp black heavyweight t-shirt under an open slate-grey overshirt. Dry clear morning, low sun casting long shadows, a stretch of plain building facade filling the right third of frame reserved for text. Camera held at chest height, walking alongside him at a matched, unhurried pace. Beats: ~0s he takes a sip of coffee mid-stride; ~5s he shifts the cup to his other hand and checks his watch briefly; ~10s he glances up the street ahead, still walking; ~13s he continues at the same steady pace, unresolved.

Ultra-realistic vertical 9:16 video that looks like it was filmed by a real person on their phone, not a studio production. No 3D, no cartoon, no VFX, no modern colour grading, no cinematic camera moves, no stabilisation.

Heavy handheld shake, imperfect framing, frequent autofocus hunting, lens breathing, exposure pumping slightly, occasional motion blur, subtle rolling shutter, mild digital compression artifacts. Camera catches the moment a beat late, framing slightly off-centre.

Natural skin texture with visible pores and natural tone variation. No studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

Subject fully absorbed in what he is doing and never turns toward or acknowledges the camera. Subtle natural breathing, occasional small head movement, natural blinking, slight weight shifts, realistic idle posture.
```

### C02 — Train seat, phone
*Hook: "checking the numbers between stops" / in-transit-still-working beat.*

```
@Rodrigo Maxwell He sits in a train seat by the window, tapping on his phone, the city passing outside blurred by motion and distance. Anchors: precisely edged dark stubble, the silver hoop, a crisp bone-coloured heavyweight t-shirt. Bright clear day, sunlight coming through the train window, the window and passing scenery filling the left third of frame reserved for text. Camera held at seated eye height across the aisle, small natural sway matching the train's motion. Beats: ~0s he scrolls the phone with his thumb; ~5s he pauses, reading something more closely; ~10s he glances briefly out the window at the passing city, then back to the phone; ~14s he resumes scrolling, settled.

Ultra-realistic vertical 9:16 video that looks like it was filmed by a real person on their phone, not a studio production. No 3D, no cartoon, no VFX, no modern colour grading, no cinematic camera moves, no stabilisation.

Heavy handheld shake, imperfect framing, frequent autofocus hunting, lens breathing, exposure pumping slightly, occasional motion blur, subtle rolling shutter, mild digital compression artifacts. Camera catches the moment a beat late, framing slightly off-centre.

Natural skin texture with visible pores and natural tone variation. No studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

Subject fully absorbed in what he is doing and never turns toward or acknowledges the camera. Subtle natural breathing, occasional small head movement, natural blinking, slight weight shifts, realistic idle posture.
```

### C03 — Parked car, waiting
*Hook: "five minutes early, catching up on messages" / parked-waiting beat.*

```
@Rodrigo Maxwell He sits in the driver's seat of a parked car, engine off, looking at his phone resting on the steering wheel, occasionally glancing up through the windshield. Anchors: neatly tapered dark hair combed back, the silver hoop, a crisp black heavyweight t-shirt. Bright sunny afternoon, parked on a quiet street, a stretch of plain wall visible through the windshield filling the top third of frame reserved for text. Camera held just outside the driver's window at eye height, static with faint natural sway. Beats: ~0s he reads the phone screen; ~5s he looks up briefly out the windshield at the street; ~10s he sets the phone in the cup holder and rests one hand on the wheel; ~13s he settles back into the seat, waiting.

Ultra-realistic vertical 9:16 video that looks like it was filmed by a real person on their phone, not a studio production. No 3D, no cartoon, no VFX, no modern colour grading, no cinematic camera moves, no stabilisation.

Heavy handheld shake, imperfect framing, frequent autofocus hunting, lens breathing, exposure pumping slightly, occasional motion blur, subtle rolling shutter, mild digital compression artifacts. Camera catches the moment a beat late, framing slightly off-centre.

Natural skin texture with visible pores and natural tone variation. No studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

Subject fully absorbed in what he is doing and never turns toward or acknowledges the camera. Subtle natural breathing, occasional small head movement, natural blinking, slight weight shifts, realistic idle posture.
```

### C04 — Waiting outside a building
*Hook: "waiting for a client who's about to hear the bad news about their links" / tension-lite beat.*

```
@Rodrigo Maxwell He stands just outside the entrance of an office building, hands in his jacket pockets, glancing at his watch, weight shifting slightly from foot to foot. Anchors: precisely edged dark stubble, the silver hoop, a crisply pressed slate-grey unstructured overshirt over a black tee. Bright clear day, a plain section of the building's facade filling the right third of frame reserved for text. Camera held at standing eye height a few feet back, small natural sway. Beats: ~0s he checks his watch; ~5s he looks up the street, then back toward the entrance doors; ~10s he takes one hand out of his pocket to check his phone briefly; ~14s he puts the phone away and settles into stillness, still waiting.

Ultra-realistic vertical 9:16 video that looks like it was filmed by a real person on their phone, not a studio production. No 3D, no cartoon, no VFX, no modern colour grading, no cinematic camera moves, no stabilisation.

Heavy handheld shake, imperfect framing, frequent autofocus hunting, lens breathing, exposure pumping slightly, occasional motion blur, subtle rolling shutter, mild digital compression artifacts. Camera catches the moment a beat late, framing slightly off-centre.

Natural skin texture with visible pores and natural tone variation. No studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

Subject fully absorbed in what he is doing and never turns toward or acknowledges the camera. Subtle natural breathing, occasional small head movement, natural blinking, slight weight shifts, realistic idle posture.
```

### C05 — Cycling in a bike lane
*Hook: "cycling to the pitch he's about to make" / motion-but-not-fast beat.*

```
@Rodrigo Maxwell He rides a plain city bike along a marked bike lane at a steady, unhurried pace, both hands on the handlebars. Anchors: neatly tapered dark hair, the silver hoop, a crisp black heavyweight t-shirt. Bright dry afternoon, a long stretch of plain low wall running alongside the lane filling the bottom third of frame reserved for text. Camera held at handlebar height, moving alongside him at the same steady pace. Beats: ~0s he pedals at a steady, even cadence; ~5s he glances over one shoulder to check for traffic, then back ahead; ~10s he shifts his weight slightly and continues at the same pace; ~13s he approaches a gentle bend in the lane, still riding steadily.

Ultra-realistic vertical 9:16 video that looks like it was filmed by a real person on their phone, not a studio production. No 3D, no cartoon, no VFX, no modern colour grading, no cinematic camera moves, no stabilisation.

Heavy handheld shake, imperfect framing, frequent autofocus hunting, lens breathing, exposure pumping slightly, occasional motion blur, subtle rolling shutter, mild digital compression artifacts. Camera catches the moment a beat late, framing slightly off-centre.

Natural skin texture with visible pores and natural tone variation. No studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

Subject fully absorbed in what he is doing and never turns toward or acknowledges the camera. Subtle natural breathing, occasional small head movement, natural blinking, slight weight shifts, realistic idle posture.
```

### C06 — Sunlit street, jacket over one shoulder
*Hook: "between meetings, on foot" / transition beat.*

```
@Rodrigo Maxwell He walks along a sunlit city street with a jacket slung over one shoulder, one hand in his pocket, hard shadows falling across the pavement ahead of him. Anchors: precisely edged dark stubble, the silver hoop, a crisp black heavyweight t-shirt. Bright clear afternoon, strong side light, a stretch of plain shopfront shutter filling the left third of frame reserved for text. Camera held at chest height, walking alongside him at a matched, unhurried pace. Beats: ~0s he walks steadily through the sun; ~5s he shifts the jacket onto his other shoulder without breaking stride; ~10s he squints slightly and glances up the street ahead; ~14s he continues at the same pace, unresolved.

Ultra-realistic vertical 9:16 video that looks like it was filmed by a real person on their phone, not a studio production. No 3D, no cartoon, no VFX, no modern colour grading, no cinematic camera moves, no stabilisation.

Heavy handheld shake, imperfect framing, frequent autofocus hunting, lens breathing, exposure pumping slightly, occasional motion blur, subtle rolling shutter, mild digital compression artifacts. Camera catches the moment a beat late, framing slightly off-centre.

Natural skin texture with visible pores and natural tone variation. No studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

Subject fully absorbed in what he is doing and never turns toward or acknowledges the camera. Subtle natural breathing, occasional small head movement, natural blinking, slight weight shifts, realistic idle posture.
```

### C07 — Pedestrian crossing, waiting
*Hook: "waiting for the light, still running the numbers in his head" / pause-beat.*

```
@Rodrigo Maxwell He stands at a pedestrian crossing waiting for the signal to change, hands loose at his sides, looking down the street. Anchors: neatly tapered dark hair combed back, the silver hoop, a crisp bone-coloured heavyweight t-shirt. Bright midday light, a plain traffic-control box and stretch of low wall filling the top third of frame reserved for text. Camera held at standing eye height across the crossing, static with faint natural sway. Beats: ~0s he stands still, looking down the street; ~5s he shifts his weight onto one foot; ~10s he glances down briefly at the crossing signal; ~13s the signal changes and he steps forward, beginning to walk.

Ultra-realistic vertical 9:16 video that looks like it was filmed by a real person on their phone, not a studio production. No 3D, no cartoon, no VFX, no modern colour grading, no cinematic camera moves, no stabilisation.

Heavy handheld shake, imperfect framing, frequent autofocus hunting, lens breathing, exposure pumping slightly, occasional motion blur, subtle rolling shutter, mild digital compression artifacts. Camera catches the moment a beat late, framing slightly off-centre.

Natural skin texture with visible pores and natural tone variation. No studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

Subject fully absorbed in what he is doing and never turns toward or acknowledges the camera. Subtle natural breathing, occasional small head movement, natural blinking, slight weight shifts, realistic idle posture.
```

### C08 — Train platform, walking to stairs
*Hook: "off the train, straight into the next thing" / momentum-beat.*

```
@Rodrigo Maxwell He walks along a train platform after stepping off a train, heading toward a staircase, unhurried but purposeful pace. Anchors: precisely edged dark stubble, the silver hoop, a crisp black heavyweight t-shirt under an open slate-grey overshirt. Bright clear day, sunlight falling in bands across the platform between the canopy supports, a stretch of plain platform wall filling the right third of frame reserved for text. Camera held at chest height, walking alongside him at a matched pace. Beats: ~0s he steps off the train onto the platform; ~5s he checks his phone briefly without slowing; ~10s he puts the phone away and starts up the first few stairs; ~14s he continues climbing the staircase steadily.

Ultra-realistic vertical 9:16 video that looks like it was filmed by a real person on their phone, not a studio production. No 3D, no cartoon, no VFX, no modern colour grading, no cinematic camera moves, no stabilisation.

Heavy handheld shake, imperfect framing, frequent autofocus hunting, lens breathing, exposure pumping slightly, occasional motion blur, subtle rolling shutter, mild digital compression artifacts. Camera catches the moment a beat late, framing slightly off-centre.

Natural skin texture with visible pores and natural tone variation. No studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

Subject fully absorbed in what he is doing and never turns toward or acknowledges the camera. Subtle natural breathing, occasional small head movement, natural blinking, slight weight shifts, realistic idle posture.
```

### C09 — Steps outside a building, coffee
*Hook: "ten minutes on the steps before the pitch" / calm-before-beat.*

```
@Rodrigo Maxwell He sits on stone steps outside an office building, a laptop bag beside him, drinking from a takeaway coffee cup, midday sun on his face. Anchors: neatly tapered dark hair, the silver hoop, a crisp black heavyweight t-shirt. Bright midday sun, a plain stretch of building wall filling the left third of frame reserved for text. Camera held at seated eye height a few feet away, small natural sway. Beats: ~0s he takes a sip of coffee; ~5s he sets the cup down beside him and checks his watch; ~10s he picks up the laptop bag and pulls it onto his lap; ~13s he stands up, coffee in one hand, ready to head in.

Ultra-realistic vertical 9:16 video that looks like it was filmed by a real person on their phone, not a studio production. No 3D, no cartoon, no VFX, no modern colour grading, no cinematic camera moves, no stabilisation.

Heavy handheld shake, imperfect framing, frequent autofocus hunting, lens breathing, exposure pumping slightly, occasional motion blur, subtle rolling shutter, mild digital compression artifacts. Camera catches the moment a beat late, framing slightly off-centre.

Natural skin texture with visible pores and natural tone variation. No studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

Subject fully absorbed in what he is doing and never turns toward or acknowledges the camera. Subtle natural breathing, occasional small head movement, natural blinking, slight weight shifts, realistic idle posture.
```

### C10 — Late-afternoon walk home
*Hook: "the walk home after a day of other people's leaks" / wind-down beat.*

```
@Rodrigo Maxwell He walks along a city street in the late afternoon, hands in his jacket pockets, low golden sun coming down the street behind him, brisk but unhurried pace. Anchors: precisely edged dark stubble, the silver hoop, a crisply pressed slate-grey unstructured overshirt over a black tee. Bright clear late afternoon, long shadows stretching across the pavement, a stretch of plain shopfront shutter filling the bottom third of frame reserved for text. Camera held at chest height, walking alongside him at a matched pace. Beats: ~0s he walks steadily, hands in pockets; ~5s he squints briefly into the low sun as he crosses a gap between buildings; ~10s he takes one hand out to check his phone briefly, then puts it away; ~14s he continues walking at the same unhurried pace.

Ultra-realistic vertical 9:16 video that looks like it was filmed by a real person on their phone, not a studio production. No 3D, no cartoon, no VFX, no modern colour grading, no cinematic camera moves, no stabilisation.

Heavy handheld shake, imperfect framing, frequent autofocus hunting, lens breathing, exposure pumping slightly, occasional motion blur, subtle rolling shutter, mild digital compression artifacts. Camera catches the moment a beat late, framing slightly off-centre.

Natural skin texture with visible pores and natural tone variation. No studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

Subject fully absorbed in what he is doing and never turns toward or acknowledges the camera. Subtle natural breathing, occasional small head movement, natural blinking, slight weight shifts, realistic idle posture.
```

## Group O — Off-duty (10)

### O01 — Gym, resting between sets
*Hook: "the only forty minutes a day nobody can reach him" / off-duty-opener.*

```
@Rodrigo Maxwell He sits on a gym bench between sets, a loaded dumbbell resting on the floor beside his feet, wiping his brow with a small towel. Anchors: neatly tapered dark hair, the silver hoop, plain dark gym shorts and a plain grey tee. Gym floor, bright overhead light, a stretch of plain painted wall filling the top third of frame reserved for text. Camera held at seated eye height a few feet back, small natural sway. Beats: ~0s he wipes his brow with the towel; ~5s he sets the towel down and picks up a water bottle; ~10s he drinks, catching his breath; ~13s he sets the bottle down and reaches for the dumbbell again, about to stand.

Ultra-realistic vertical 9:16 video that looks like it was filmed by a real person on their phone, not a studio production. No 3D, no cartoon, no VFX, no modern colour grading, no cinematic camera moves, no stabilisation.

Heavy handheld shake, imperfect framing, frequent autofocus hunting, lens breathing, exposure pumping slightly, occasional motion blur, subtle rolling shutter, mild digital compression artifacts. Camera catches the moment a beat late, framing slightly off-centre.

Natural skin texture with visible pores and natural tone variation. No studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

Subject fully absorbed in what he is doing and never turns toward or acknowledges the camera. Subtle natural breathing, occasional small head movement, natural blinking, slight weight shifts, realistic idle posture.
```

### O02 — Five-a-side, jogging back
*Hook: "still plays like the attribution model owes him a goal" / physical-off-duty beat.*

```
@Rodrigo Maxwell He jogs back into position on a small artificial-turf five-a-side pitch after a play, breathing steadily, glancing across the pitch. Anchors: precisely edged dark stubble, the silver hoop, a plain dark football bib over a grey tee. Bright clear late afternoon, warm low sun across the pitch, a stretch of the pitch's perimeter fencing filling the right third of frame reserved for text. Camera held at chest height near the touchline, small natural sway, no repositioning. Beats: ~0s he jogs at a steady pace back into position; ~5s he slows to a walk, hands on his hips briefly; ~10s he calls out and points across the pitch with one arm, no words audible; ~14s he sets off jogging again as play resumes.

Ultra-realistic vertical 9:16 video that looks like it was filmed by a real person on their phone, not a studio production. No 3D, no cartoon, no VFX, no modern colour grading, no cinematic camera moves, no stabilisation.

Heavy handheld shake, imperfect framing, frequent autofocus hunting, lens breathing, exposure pumping slightly, occasional motion blur, subtle rolling shutter, mild digital compression artifacts. Camera catches the moment a beat late, framing slightly off-centre.

Natural skin texture with visible pores and natural tone variation. No studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

Subject fully absorbed in what he is doing and never turns toward or acknowledges the camera. Subtle natural breathing, occasional small head movement, natural blinking, slight weight shifts, realistic idle posture.
```

### O03 — Bar with friends
*Hook: "off the clock, actually off the clock" / social-off-duty beat.*

```
@Rodrigo Maxwell He sits at a bar table with a drink in front of him, laughing quietly at something, one other person visible across the table out of focus. Anchors: neatly tapered dark hair combed back, the silver hoop, a crisp black heavyweight plain t-shirt. Warm dim bar lighting in the evening, a section of exposed brick wall filling the left third of frame reserved for text. Camera held at seated eye height across the table, small natural sway. Beats: ~0s he laughs, head tilting back slightly; ~5s he picks up his drink and takes a sip; ~10s he sets it down and leans forward, gesturing loosely with one hand mid-conversation; ~13s he leans back again, relaxed.

Ultra-realistic vertical 9:16 video that looks like it was filmed by a real person on their phone, not a studio production. No 3D, no cartoon, no VFX, no modern colour grading, no cinematic camera moves, no stabilisation.

Heavy handheld shake, imperfect framing, frequent autofocus hunting, lens breathing, exposure pumping slightly, occasional motion blur, subtle rolling shutter, mild digital compression artifacts. Camera catches the moment a beat late, framing slightly off-centre.

Natural skin texture with visible pores and natural tone variation. No studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

Subject fully absorbed in what he is doing and never turns toward or acknowledges the camera. Subtle natural breathing, occasional small head movement, natural blinking, slight weight shifts, realistic idle posture.
```

### O04 — Cooking, chopping vegetables
*Hook: "cooks the way he audits a funnel — methodically" / domestic beat.*

```
@Rodrigo Maxwell He stands at a kitchen counter chopping vegetables on a board with a kitchen knife, steady even strokes. Anchors: precisely edged dark stubble, the silver hoop, a crisp plain grey t-shirt, sleeves pushed up. Kitchen, warm evening light from an overhead fixture, a stretch of plain cabinet filling the bottom third of frame reserved for text. Camera held at counter height across from him, small natural sway. Beats: ~0s he chops steadily, knife moving in even strokes; ~5s he sweeps the chopped vegetables into a pan with the flat of the knife; ~10s he turns to stir the pan with a spoon in his other hand; ~14s he goes back to the board and starts on the next vegetable.

Ultra-realistic vertical 9:16 video that looks like it was filmed by a real person on their phone, not a studio production. No 3D, no cartoon, no VFX, no modern colour grading, no cinematic camera moves, no stabilisation.

Heavy handheld shake, imperfect framing, frequent autofocus hunting, lens breathing, exposure pumping slightly, occasional motion blur, subtle rolling shutter, mild digital compression artifacts. Camera catches the moment a beat late, framing slightly off-centre.

Natural skin texture with visible pores and natural tone variation. No studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

Subject fully absorbed in what he is doing and never turns toward or acknowledges the camera. Subtle natural breathing, occasional small head movement, natural blinking, slight weight shifts, realistic idle posture.
```

### O05 — Grocery store, weekend errand
*Hook: "even the operator has to buy groceries" / mundane-relatable beat.*

```
@Rodrigo Maxwell He pushes a shopping cart slowly down a grocery store aisle, scanning the shelves, one item already in the cart. Anchors: neatly tapered dark hair, the silver hoop, a crisp bone-coloured heavyweight t-shirt. Bright even store lighting, a shelf of plain packaged goods filling the top third of frame reserved for text. Camera held at chest height, walking alongside the cart at a matched, unhurried pace. Beats: ~0s he scans the shelf while pushing the cart slowly; ~5s he stops, reaches out and picks up an item; ~10s he checks the item briefly, then places it in the cart; ~13s he pushes the cart forward again, continuing down the aisle.

Ultra-realistic vertical 9:16 video that looks like it was filmed by a real person on their phone, not a studio production. No 3D, no cartoon, no VFX, no modern colour grading, no cinematic camera moves, no stabilisation.

Heavy handheld shake, imperfect framing, frequent autofocus hunting, lens breathing, exposure pumping slightly, occasional motion blur, subtle rolling shutter, mild digital compression artifacts. Camera catches the moment a beat late, framing slightly off-centre.

Natural skin texture with visible pores and natural tone variation. No studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

Subject fully absorbed in what he is doing and never turns toward or acknowledges the camera. Subtle natural breathing, occasional small head movement, natural blinking, slight weight shifts, realistic idle posture.
```

### O06 — Folding laundry
*Hook: "the least glamorous part of running your own thing" / domestic-beat.*

```
@Rodrigo Maxwell He stands at a table folding a t-shirt from a small laundry pile, methodical and unhurried. Anchors: precisely edged dark stubble, the silver hoop, plain grey sweatpants and a fitted white undershirt. Bedroom, soft daylight through a window, a plain section of wall filling the right third of frame reserved for text. Camera held at standing eye height across the table, small natural sway. Beats: ~0s he folds a t-shirt and sets it on a stack; ~5s he picks up another item and folds it; ~10s he glances briefly toward the window; ~14s he continues folding, steady and unhurried.

Ultra-realistic vertical 9:16 video that looks like it was filmed by a real person on their phone, not a studio production. No 3D, no cartoon, no VFX, no modern colour grading, no cinematic camera moves, no stabilisation.

Heavy handheld shake, imperfect framing, frequent autofocus hunting, lens breathing, exposure pumping slightly, occasional motion blur, subtle rolling shutter, mild digital compression artifacts. Camera catches the moment a beat late, framing slightly off-centre.

Natural skin texture with visible pores and natural tone variation. No studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

Subject fully absorbed in what he is doing and never turns toward or acknowledges the camera. Subtle natural breathing, occasional small head movement, natural blinking, slight weight shifts, realistic idle posture.
```

### O07 — Balcony plants, morning
*Hook: "the one thing he waters that isn't a growth metric" / quiet-morning beat.*

```
@Rodrigo Maxwell He stands on a small apartment balcony watering a potted plant with a small watering can, unhurried morning routine. Anchors: neatly tapered dark hair combed back, the silver hoop, a crisp plain grey t-shirt. Bright clear morning, city rooftops visible softened by distance, the sky filling the top third of frame reserved for text. Camera held at standing eye height a few feet away, small natural sway. Beats: ~0s he tips the watering can over one pot; ~5s he moves to a second pot and waters it too; ~10s he sets the can down and touches a leaf between two fingers, checking it; ~13s he leans on the railing briefly, looking out over the rooftops.

Ultra-realistic vertical 9:16 video that looks like it was filmed by a real person on their phone, not a studio production. No 3D, no cartoon, no VFX, no modern colour grading, no cinematic camera moves, no stabilisation.

Heavy handheld shake, imperfect framing, frequent autofocus hunting, lens breathing, exposure pumping slightly, occasional motion blur, subtle rolling shutter, mild digital compression artifacts. Camera catches the moment a beat late, framing slightly off-centre.

Natural skin texture with visible pores and natural tone variation. No studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

Subject fully absorbed in what he is doing and never turns toward or acknowledges the camera. Subtle natural breathing, occasional small head movement, natural blinking, slight weight shifts, realistic idle posture.
```

### O08 — Washing the car, driveway
*Hook: "weekend chore, same attention to detail as the dashboards" / methodical-off-duty beat.*

```
@Rodrigo Maxwell He washes a parked car in a driveway with a sponge and a bucket of soapy water, working in slow even strokes across the hood. Anchors: precisely edged dark stubble, the silver hoop, a crisp plain grey t-shirt, sleeves pushed up. Bright weekend afternoon, a stretch of plain garage door filling the left third of frame reserved for text. Camera held at standing eye height a few feet back, small natural sway. Beats: ~0s he wipes the sponge across the hood in even strokes; ~5s he dips the sponge back in the bucket; ~10s he moves to the side panel and continues washing; ~14s he steps back briefly to check his work, sponge still in hand.

Ultra-realistic vertical 9:16 video that looks like it was filmed by a real person on their phone, not a studio production. No 3D, no cartoon, no VFX, no modern colour grading, no cinematic camera moves, no stabilisation.

Heavy handheld shake, imperfect framing, frequent autofocus hunting, lens breathing, exposure pumping slightly, occasional motion blur, subtle rolling shutter, mild digital compression artifacts. Camera catches the moment a beat late, framing slightly off-centre.

Natural skin texture with visible pores and natural tone variation. No studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

Subject fully absorbed in what he is doing and never turns toward or acknowledges the camera. Subtle natural breathing, occasional small head movement, natural blinking, slight weight shifts, realistic idle posture.
```

### O09 — Stretching before a run, park
*Hook: "stretching before a run, same discipline as the job" / physical-quiet beat.*

```
@Rodrigo Maxwell He stands on a park path stretching one leg against a low bench, unhurried, preparing to run. Anchors: neatly tapered dark hair, the silver hoop, a plain dark running t-shirt and shorts. Bright clear early morning in the park, sunlight coming through the trees, a stretch of open grass filling the bottom third of frame reserved for text. Camera held at standing eye height a few feet away, small natural sway. Beats: ~0s he stretches one leg against the bench; ~5s he switches to stretch the other leg; ~10s he rolls both shoulders and shakes out his arms; ~13s he takes a first few steps into a light jog, moving off down the path.

Ultra-realistic vertical 9:16 video that looks like it was filmed by a real person on their phone, not a studio production. No 3D, no cartoon, no VFX, no modern colour grading, no cinematic camera moves, no stabilisation.

Heavy handheld shake, imperfect framing, frequent autofocus hunting, lens breathing, exposure pumping slightly, occasional motion blur, subtle rolling shutter, mild digital compression artifacts. Camera catches the moment a beat late, framing slightly off-centre.

Natural skin texture with visible pores and natural tone variation. No studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

Subject fully absorbed in what he is doing and never turns toward or acknowledges the camera. Subtle natural breathing, occasional small head movement, natural blinking, slight weight shifts, realistic idle posture.
```

### O10 — Couch, evening, phone
*Hook: "the last scroll of the day, not even work-related" / wind-down closer.*

```
@Rodrigo Maxwell He sits on a couch in the evening, scrolling slowly on his phone, one leg crossed over the other, relaxed posture. Anchors: precisely edged dark stubble, the silver hoop, plain grey sweatpants and a fitted white undershirt. Living room, warm lamp light, a plain section of wall filling the right third of frame reserved for text. Camera held at seated eye height across the room, small natural sway. Beats: ~0s he scrolls slowly with his thumb; ~5s he smiles faintly at something on the screen; ~10s he sets the phone face-down on the couch cushion beside him; ~14s he leans his head back against the couch, eyes still open, unhurried.

Ultra-realistic vertical 9:16 video that looks like it was filmed by a real person on their phone, not a studio production. No 3D, no cartoon, no VFX, no modern colour grading, no cinematic camera moves, no stabilisation.

Heavy handheld shake, imperfect framing, frequent autofocus hunting, lens breathing, exposure pumping slightly, occasional motion blur, subtle rolling shutter, mild digital compression artifacts. Camera catches the moment a beat late, framing slightly off-centre.

Natural skin texture with visible pores and natural tone variation. No studio lighting, no model-perfect retouched skin, no waxy or plastic sheen.

Subject fully absorbed in what he is doing and never turns toward or acknowledges the camera. Subtle natural breathing, occasional small head movement, natural blinking, slight weight shifts, realistic idle posture.
```
