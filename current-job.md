# Higgsfield job board

**Read the CURRENT JOB section and do exactly what it says.** Everything above it is
standing context that does not change. When told to "refresh", re-fetch this page —
the CURRENT JOB section will have been replaced.

Last updated: 2026-07-29 16:20 — **Maya is done. Tim, Lizzie and Rodrigo are queued.**

---

## Standing rules

You are working in the Higgsfield web app at higgsfield.ai, signed in as
tmmeskhi@gmail.com (Pro plan, workspace "Private").

**Billing.** This account holds **Unlimited passes that expire 2026-08-04**, applying
**only inside the web app** — never via API or CLI. If anything shows a credit cost
instead of "Unlimited", **stop and say so before proceeding**. Character/Soul *training*
may cost credits even when generation is unlimited — that is expected, but report the
number before you start it.

**You cannot reach the local filesystem.** Steps needing a file are marked **[YOU]** —
click Upload to open the native dialog and let the human pick the file.

**Attaching a character.** In the web app you attach a reference by typing **`@Name`**
in the prompt box. The `<<<uuid>>>` form is API syntax and does nothing in the browser.

**Element naming matters.** Name each Element exactly as the persona is named —
`Tim Tanner`, not `Tim Tanner — element`. The Element name and the `@` reference have to
match, and a suffix breaks the mention.

**Reporting.** Be blunt and critical. We would rather hear that something looks wrong
than be told it is fine. Never call an image spec-compliant if it isn't.

### Characters already built — do not rebuild

| Character | Asset | ID |
|---|---|---|
| Terry Sterling | Soul (stills only) | `b45b1df9-ca52-4580-89c3-caa756cfe7a7` |
| Terry Sterling | Element (video) | `883ccefd-6b8e-4edf-a048-9d24fa2f1067` |
| Maya Miller | Soul + Element | done 2026-07-29 |

Soul never works with video. Seedance 2.0 and Kling 3.0 take the Element.

---

# CURRENT JOB

## Build the three remaining characters — Tim, Lizzie, Rodrigo

Maya is finished. These three are next. **Do them one at a time, in this order**, and
report after each before starting the next.

Each has its own full brief on a separate page — identity string, all 21 shot lines,
curation criteria, Soul training and Element build. Fetch the page, do what it says,
report back, then return here and start the next.

| Order | Character | Brief |
|---|---|---|
| 1 | **Tim Tanner** | https://raw.githubusercontent.com/tengmesk/cowork-jobs/main/job-tim-tanner.md |
| 2 | **Lizzie Larsen** | https://raw.githubusercontent.com/tengmesk/cowork-jobs/main/job-lizzie-larsen.md |
| 3 | **Rodrigo Maxwell** | https://raw.githubusercontent.com/tengmesk/cowork-jobs/main/job-rodrigo-maxwell.md |

### What is different about these three, versus Maya

**All three are fully synthetic. There is no source photo for any of them.** Maya had a
headshot, so her Element came first and seeded her training batch. These have nothing to
seed from — the written identity string *is* the source.

That changes the procedure in three ways, and each brief repeats them:

1. **Generate the 21 coverage shots cold, with no Element attached.** There is nothing
   to attach yet; this batch is what creates the character.
2. **Budget 3–4 variants per shot, not 2–3.** With nothing anchoring the face, drift
   across the batch is the main failure mode — expect to discard more.
3. **Curate hard for internal consistency.** The question is not "is this like the
   source photo" — there is no source photo. It is **"is every one of these the same
   person?"** Reject anything that has drifted in age, weight or bone structure.

Then train the Soul on 22–26 face-dominant keepers, and build the Element from the
keepers afterwards.

### Two character-specific traps, easy to miss

**Tim Tanner — the pipe, and his weight.** A pipe is his signature prop but it covers
his mouth, and a Soul trained on an obscured mouth renders mouths badly ever after. **No
pipe anywhere in his training set** — it appears in content only. Separately, the model
tends to slim heavy-set body types between shots: **reject any frame where he has lost
weight.** And his defining trait is a warm, open smile — if the set comes back stern,
the character has failed even if the bone structure is right.

**Lizzie Larsen — clean training images, even though her content is scrappy.** Her whole
premise is unpolished, which makes it tempting to train her on gritty phone-style images.
Do not. Training stays clean, evenly lit and neutral; phone realism is applied later at
generation time. Inverting this bakes the grain into her identity permanently. Also her
**grown-out roots are deliberate** — they are what stops her reading as a polished brand
asset. Do not let a prompt tidy them away.

### Report after each character

1. The **Soul ID** and the **Element ID**
2. How many shots you generated, how many you kept, what you rejected them for
3. Whether the kept set genuinely looks like **one consistent person** — be blunt
4. Whether the skin came out unretouched or still smoothed
5. Anything that showed a credit cost rather than Unlimited

Then stop and wait before starting the next character.

---

## QUEUED — not now

**Terry: three daylight start frames**, regenerated with hardened skin and background
wording. Will be restored to CURRENT JOB once these three characters exist.
