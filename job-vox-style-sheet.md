# Job — generate the Vox collage style sheet

**This is one image, not a video.** It is the reusable style anchor that every future clip
in this style attaches to. Generate it once and it lasts forever.

Do this job **before** any of the video beats. Nothing else in the Vox pipeline can start
until this exists and has been approved.

## Settings

| Control | Set to |
|---|---|
| Model | **Nano Banana Pro (2K)** — or GPT Image 2 (2K) if Nano Banana Pro is unavailable |
| Aspect | **9:16 vertical** |
| Unlimited mode | **On** |

Confirm it reads "Unlimited" before generating. If it shows a credit cost, stop and say so.

## Generate 3 variants of this prompt

Paste verbatim. Generate three, then report all three back — the owner picks one.

```
A single flat reference board for an editorial collage motion-graphics system, photographed straight-on in flat even light, laid out on aged newsprint, vertical 9:16 composition.

The board contains, overlapping and slightly askew: two black-and-white archive photographs of 1970s office workers, scissor-cut with visible paper edges and soft drop shadows; a solid black rectangular censor bar laid across the eyes of one of them; a strip of heavy condensed all-caps display lettering in deep charcoal, cropped by the edge of the board, letters illegible; a hand-drawn red circle and a red arrow, drawn slightly unevenly as if with a marker; an enlarged halftone dot pattern in one corner; three small tan paper label strips; a solid black redaction block over a line of text; a piece of masking tape holding one photograph down; a swatch of dusty blue-grey paper and a swatch of aged tan paper.

Newsprint texture throughout with a visible dot screen, torn fibrous edges on every paper element, scanned-paper grain across the whole image. Muted palette of cream, deep charcoal, one signal red accent, dusty blue-grey and aged tan. Nothing digital-looking, nothing glossy. No legible text anywhere in the image.
```

## Why the text is deliberately illegible

Image models garble type. A style anchor does not need readable words — it needs the
**palette, texture and material language** locked. Real typography gets set later, inside
the clip prompts or in post. If a variant comes back with crisp legible words, that is
luck, not a requirement.

## What to judge

1. **Palette** — is it genuinely cream / charcoal / one red / blue-grey / tan? Reject
   anything that has drifted warm-orange or introduced extra colours.
2. **Texture** — visible newsprint dot screen and torn paper fibres, or is it flat and
   digital?
3. **Material honesty** — does it look like physical paper photographed, or like a
   digital illustration of paper? The former is right.
4. **The censor bar** — present and solid black over the eyes?
5. Anything that showed a credit cost rather than Unlimited.

## Report back

The three image URLs, your read on each against the five points above, and which you would
pick. **Then stop.** Do not start generating video beats — the owner approves the style
sheet first, and every clip in this style will inherit whichever one is chosen.
