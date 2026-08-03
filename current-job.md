# Higgsfield job board

**Read the CURRENT JOB section and do exactly what it says.** Everything above it is
standing context that does not change. When told to "refresh", re-fetch this page —
the CURRENT JOB section will have been replaced.

Last updated: 2026-08-03 — **Lizzie is DONE**, character and all 30 b-roll clips.
**Rodrigo is CURRENT and it is time-critical** — see the deadline note below.

---

## Standing rules

You are working in the Higgsfield web app at higgsfield.ai, signed in as
tmmeskhi@gmail.com (Pro plan, workspace "Private").

**Billing.** This account holds **Unlimited passes that expire 2026-08-04**, applying
**only inside the web app** — never via API or CLI. If anything shows a credit cost
instead of "Unlimited", **stop and say so before proceeding**. Character/Soul *training*
may cost credits even when generation is unlimited — **report the number and wait for the
owner's go-ahead before starting a training run.**

**You cannot reach the local filesystem.** Steps needing a file are marked **[YOU]** —
click Upload to open the native dialog and let the human pick the file.

**Image model — house default.** Use **Nano Banana 2 at 2K** for everything, and use one
model per character set. Nano Banana Pro is too slow for batches of this size, and mixing
models across a set averages several faces together, which is the exact drift we fight on
characters with no source photo.

**Attaching a character.** In the web app you attach a reference by typing **`@Name`** in
the prompt box. The `<<<uuid>>>` form is API syntax and does nothing in the browser. The
name must match the Element name **exactly**.

**Reporting.** Be blunt and critical. We would rather hear that something looks wrong than
be told it is fine. Never call an image spec-compliant if it isn't.

### Already built — do NOT rebuild any of these

| Character | Soul (stills only) | Element for video — use this exact @name |
|---|---|---|
| **Terry Sterling** | `b45b1df9-ca52-4580-89c3-caa756cfe7a7` | **`@Terry Sterling`** |
| **Maya Miller** | `f2f47ddc-7308-4470-8e76-6e8c2b2fd6cd` | **`@Maya-Miller-v2`** |
| **Tim Tanner** | `ab2e0383-bad0-418f-9a85-a1c0a0998c9a` | **`@Tim Tanner-1`** |
| **Lizzie Larsen** | `1e1883a5-56b6-4bfe-8219-8675d3944703` | **`@Lizzie Larsen-1`** |

Also live: **`@Shoe-Dog-Cover`** — a prop Element of the Shoe Dog book cover.

Soul never works with video. Seedance 2.0 and Kling 3.0 take the Element.

**Duplicate Elements exist and the CLEAN NAME IS OFTEN THE WRONG ONE.** The account holds
older `Maya Miller`, `Maya-Miller-—-element`, `Terry-Sterling-—-element`, `Tim Tanner` and
`Lizzie Larsen` Elements. Twice now the correct Element has been the suffixed one —
`Tim Tanner-1`, and `Lizzie Larsen-1`, whose unsuffixed twin is a likeness **rejected on
IP grounds**. **Use only the four @names in the table above, exactly as written**, and do
not create any more Elements for these four characters.

---

# CURRENT JOB

## Build Rodrigo Maxwell — and start today

**His brief:** https://raw.githubusercontent.com/tengmesk/cowork-jobs/main/job-rodrigo-maxwell.md

> ### Why this jumped the queue
>
> **The Unlimited passes expire 2026-08-04 — tomorrow.** Rodrigo's build is 21 coverage
> shots at 3–4 variants each, so **63–84 image generations**. That is the only outstanding
> job big enough for the free window to matter. The Vox style sheet is three images and
> costs almost nothing whenever it runs, so it has moved behind him.
>
> If the passes lapse before the batch is finished, **stop and report** rather than
> spending credits.

### Same route as Lizzie, which just worked

He is fully synthetic — no source photo — so the identity string in his brief is the only
source of his face.

1. **Generate the 21 coverage shots cold, no Element attached.**
2. **3–4 variants per shot.** Cold generation drifts; that is the whole risk.
3. **Curate 22–26 keepers** on one question: *is every one of these the same man?*
4. **Report the Soul training cost and wait for the owner's go-ahead** before training.
5. **Build the Element from the keepers** afterwards.

### The naming trap — this has now bitten twice

Higgsfield appends a numeric suffix when an Element name collides with an existing one.
Both `Tim Tanner-1` and `Lizzie Larsen-1` ended up as the real asset while the clean name
pointed at something superseded.

**Name his Element `Rodrigo Maxwell`, then report back the exact name it actually got.**
Do not assume it saved unsuffixed. His 40-clip b-roll job attaches the Element by exact
name and will silently produce the wrong man if the name is off.

### Watch for, specific to him

- **The silver hoop is in his LEFT ear.** It is one of his few hard identity anchors and
  it swaps ears or vanishes when the model drifts. Reject those frames.
- **Training images stay clean, evenly lit and neutral** even though his content will be
  phone-style. Phone realism is applied later, at generation time.
- **Reject poreless skin**, however flattering.

### Report when done

1. The **Soul ID**, the **Element ID**, and **the exact Element name**
2. How many shots generated, how many kept, what you rejected them for
3. Whether the kept set is unmistakably **one consistent man** — be blunt
4. Whether the hoop stayed in his left ear across the set
5. Anything that showed a credit cost rather than Unlimited

Then stop and wait.

---

## QUEUED — not now

1. **Rodrigo's b-roll — 40 clips** — https://raw.githubusercontent.com/tengmesk/cowork-jobs/main/job-rodrigo-broll.md
   **Blocked until his Element exists.** 10 desk/analytics, 10 coworking, 10 city, 10
   off-duty. Four pilot clips first, then a stop for review.
   **Note:** Lizzie's set was run image-first — a start frame per clip, then animated —
   and that worked better than prompt-only. Plan his the same way.
2. **Vox collage style sheet** — https://raw.githubusercontent.com/tengmesk/cowork-jobs/main/job-vox-style-sheet.md
   **One image, not a video.** Three variants of a reusable style anchor. Only three
   generations, so it is cheap with or without the passes — which is why it now sits
   behind Rodrigo.
3. **Terry: three daylight start frames**, regenerated with hardened skin and background
   wording.

### Coming after the style sheet is approved — do not start it yet

**The AI-productivity explainer** — 11 beats, 48s, **9:16 vertical**, **Google Omni Flash**
(unlimited, 10s max per clip; it also does 16:9 if a YouTube recut is wanted later). Nine beats generate on Omni; two are built outside Higgsfield because
they carry real statistics, which Omni renders convincingly wrong.

It is blocked on two things that are not yours to do:

- the **research gate** — every figure in the script is still a placeholder and must be
  replaced with a sourced number
- the **voiceover**, which sets the exact beat timings

Do not begin it until a job page appears for it here.

---

## DONE — do not re-run

- **Terry Sterling**, **Maya Miller**, **Tim Tanner** — Souls and Elements built.
- **Lizzie Larsen** — Soul `1e1883a5-…`, Element **`@Lizzie Larsen-1`**, ~87 coverage
  images. [Job page](https://raw.githubusercontent.com/tengmesk/cowork-jobs/main/job-lizzie-larsen.md)
- **Lizzie's 30 b-roll clips** — all completed 2026-08-03 on **Kling 3.0 at 10s**, image-first
  (start frame per clip, then animated), 9:16, silent. Ran differently from the written
  spec, which said Seedance 2.0 at 14s; the differences are recorded on the
  [job page](https://raw.githubusercontent.com/tengmesk/cowork-jobs/main/job-lizzie-broll.md).
