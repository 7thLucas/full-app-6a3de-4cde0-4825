# Product Overview

> Product name: **TrueScale** (set as the product title; renameable later).
> Single source of truth for the product. Update when product facts change.

## One-line

A phone-camera AR tool that lets 3D-printing makers preview a model at its **true print
scale** in their real space — before committing filament and machine time — so the
printed result matches expectations the first time.

**Tagline (official):** "See your 3D model at true print scale in your real space,
through your phone camera — before you waste a gram of filament."

**Brand direction:** maker-friendly and precise; teal + indigo palette (logo TBD).

## The user

- **Primary:** Hobbyist / newbie 3D designers who print their own designs frequently
  (desktop FDM and resin makers).
- They model and print often, but as relative newcomers they regularly misjudge how big
  a model will actually be once printed.

## The problem (tangible, consequential)

- The on-screen model and the physical print don't match the maker's size expectations.
- A scale miss isn't free: a failed or wrong-sized print quietly burns **filament,
  hours of machine time, and money**, and the maker only finds out after the print is
  done.
- Newbies hit this more often because they lack the intuition to "see" final scale from
  a screen.

## The solution (focused, credible)

A web app that closes the gap between screen and reality before printing:

1. **Upload a 3D model** (the file the maker is about to print).
2. **Set the real print dimensions** (the size it will actually print at).
3. **Point the phone camera** and see the model placed at **true 1:1 scale** in the
   real environment — desk, shelf, table — using markerless camera AR.
4. **Decide with confidence:** does it fit, does it look right at that size? Adjust the
   scale or commit to printing.

The buildable core is the **true-scale AR preview**, not full holographic
manipulation. It answers the "does it fit / does it look right at real size?" question
pre-print.

## Core workflow → the operation that matters

The domain event the app exists to perform is a **pre-print scale check**: a maker
loads a model, sets its real dimensions, views it at true scale in their space, and
reaches a print/adjust decision. Each completed check is one verified operation.

## Value

- **Avoided failed prints** — each prevented wrong-scale print saves the filament and
  the machine hours that print would have consumed.
- **Confidence before commitment** — replaces guesswork with a real-world look at final
  size.
- **Time and money saved**, which is exactly the outcome the user is after.

## Scope & strategic principles

- Web app, phone-camera based — no special hardware beyond a phone.
- Start with the true-scale AR preview as the spine; richer interaction can come later.
- Keep it approachable for newcomers; the tool should make scale obvious, not technical.

## Open / to confirm

- Final product name and branding.
- Supported model file formats and any size/complexity limits.
- Typical print frequency per maker (used for impact projections — currently an
  assumption).
