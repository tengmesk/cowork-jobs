# Higgsfield job board

**Read the CURRENT JOB section and do exactly what it says.** Everything above it is
standing context that does not change. When told to "refresh", re-fetch this page —
the CURRENT JOB section will have been replaced.

Last updated: 2026-07-30 — Tim DONE. Lizzie is CURRENT. Both Lizzie's and Rodrigo's b-roll
jobs are now written and queued; each unlocks the moment its own Element exists.

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

Also live: **`@Shoe-Dog-Cover`** — a prop Element of the Shoe Dog book cover.

Soul never works with video. Seedance 2.0 and Kling 3.0 take the Element.

**Duplicate Elements exist and the right one is not obvious** — there are older
`Maya Miller`, `Maya-Miller-—-element`, `Terry-Sterling-—-element` and `Tim Tanner`
Elements on the account. **Use only the three @names in the table above.** Do not create
any more Elements for these three characters.

---

# CURRENT JOB

## Build Lizzie Larsen

**Her brief:** https://raw.githubusercontent.com/tengmesk/cowork-jobs/main/job-lizzie-larsen.md

> ### Her look was respecified on 2026-07-30 — read this first
>
> If you fetched her brief before 2026-07-30, **discard it.** The old spec described
> dark-blonde hair with visibly grown-out roots, faint freckles and deliberately unstyled
> clothes. That is superseded.
>
> She is now **bright Scandi-blonde, sleek shoulder-length, polished and premium-styled** —
> high-end Scandinavian minimalist. Use only the identity string in the brief.

### Before you start generating

**Report the Soul training cost and wait for the owner's confirmation before starting the
training run.** Generating the coverage images is unlimited; training may not be. Do not
start a training run on your own initiative.

### What is different about Lizzie versus Maya and Tim

**She is fully synthetic — there is no source photo.** Maya had a headshot, so her Element
came first and seeded her training batch. Lizzie has nothing to seed from; the written
identity string *is* the source.

1. **Generate the 21 coverage shots cold, with no Element attached.** There is nothing to
   attach yet — this batch is what creates the character.
2. **Budget 3–4 variants per shot, not 2–3.** With nothing anchoring the face, drift across
   the batch is the main failure mode.
3. **Curate for internal consistency.** The question is not "is this like the source photo"
   — there isn't one. It is **"is every one of these the same woman?"**

Then train the Soul on 22–26 face-dominant keepers, and build the Element from the keepers
afterwards. **Name the Element exactly `Lizzie Larsen`** — no suffix, so `@Lizzie Larsen`
works.

### The trap specific to Lizzie

**Her training images stay clean, evenly lit and neutral — even though her content is shot
to look like a phone snapshot.** Her subject is polished and her camera is not, which makes
it tempting to train her on gritty handheld images. Do not. Phone realism is applied later,
at generation time. Inverting this bakes grain into her identity permanently.

**And the brows.** Full taupe-brown, brushed up and out, **noticeably darker than her
hair** — the strongest feature of the reference and the one most likely to drift back
toward pale blonde. **Reject any frame where the brows have gone light.**

**And the skin, which is subtle.** Her look calls for "flawless glowing skin" while the
house rule is unretouched skin with visible pores. These are not opposed:

- **Glowing** is a *lighting* quality — dewy, healthy, light catching the cheekbones.
- **Retouched** is an *absence of texture* — no pores, no fine lines.

Ask for both. **Reject any frame where the skin has gone poreless**, however flattering it
looks — the Soul would learn a plastic face permanently.

### Report when done

1. The **Soul ID** and the **Element ID**
2. How many shots you generated, how many you kept, what you rejected them for
3. Whether the kept set genuinely looks like **one consistent woman** — be blunt
4. Whether the skin came out unretouched or still smoothed
5. Anything that showed a credit cost rather than Unlimited

Then stop and wait.

---

## QUEUED — not now

1. **Lizzie's b-roll — 30 clips** — https://raw.githubusercontent.com/tengmesk/cowork-jobs/main/job-lizzie-broll.md
   Seedance 2.0, **14s each, 9:16, 1080p, silent.** 7 poolside, 13 in her apartment, 10
   around Miami. **Blocked until her Element exists** and the owner has approved her
   keepers — it attaches `@Lizzie Larsen`, so it cannot start a moment earlier. The job
   asks for three pilot clips first, then a stop for review.
2. **Vox collage style sheet** — https://raw.githubusercontent.com/tengmesk/cowork-jobs/main/job-vox-style-sheet.md
   **One image, not a video.** Three variants of a reusable style anchor for the faceless
   explainer channel. Cheap, fast, and it unblocks a whole content format — do this
   straight after Lizzie if the owner says so. Uses **Nano Banana Pro at 9:16**, not Omni.
3. **Rodrigo Maxwell — the character** — https://raw.githubusercontent.com/tengmesk/cowork-jobs/main/job-rodrigo-maxwell.md
   Same synthetic route as Lizzie: 21 shots cold, no Element, 3–4 variants each, curate to
   22–26 keepers, then train. **Name his Element exactly `Rodrigo Maxwell`.** Do not start
   until Lizzie is reported and approved.
4. **Rodrigo's b-roll — 40 clips** — https://raw.githubusercontent.com/tengmesk/cowork-jobs/main/job-rodrigo-broll.md
   Seedance 2.0, **14s each, 9:16, 1080p, silent.** 10 at the desk with analytics, 10
   coworking/studio, 10 city/transit, 10 off-duty. **Blocked until his Element exists.**
   Four pilot clips first, then a stop for review.
4. **Terry: three daylight start frames**, regenerated with hardened skin and background
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
