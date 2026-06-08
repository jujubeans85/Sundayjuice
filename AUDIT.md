# SUNDAYJUICE Usability Audit

Scope: optimisation and usability only.

No enhancements. No redesign. No HARDWAREJUICE bleed.

## ROCK SOLID

- Single-file app shape is simple and iPad-friendly.
- Main flow is clear: paste URLs, choose format, generate command/wrapper, copy to A-Shell.
- Warm visual identity supports creative use.
- CSV import and URL cleaning are useful for crate workflows.
- Generated output stays copy-paste friendly.
- Current code keeps everything in one place, which is acceptable for this creative utility phase.

## SPLIT-BRAIN CLOWN GARBAGE

- Repo previously had no README boundary, so SUNDAYJUICE could be confused with HARDWAREJUICE.
- Main entry file is `Index.html` with a capital `I`; many static hosts expect lowercase `index.html`. Do not rename blindly, but this is a usability risk.
- Current app includes iPad workflow advice, crate grabbing, AI post-processing prompt faders, OCR placeholder behaviour, and download wrapper generation in one surface. Useful, but purpose can blur fast.
- Some labels say polished/AI/max-quality things that may make the tool feel bigger than its actual job.

## DRUNK OCTOPUS ROOTING A FILING CABINET

- The 15 prompt/fader controls are understandable but crowded. They may be useful, but they are too much for low-energy use unless kept clearly secondary.
- OCR is more of a manual helper than real OCR. That is fine if labelled honestly.
- The background/image styling is vibe-positive but should not become the main job.
- The app has grown through version bumps in `Index.html`; keep history, but do not keep stacking features into the same surface forever.

## Safest cleanup plan

1. Keep `Index.html` untouched for now.
2. Add README boundary. Done.
3. Keep this audit file as the review gate before any cleanup.
4. Next safe patch: verify whether the live host needs lowercase `index.html`.
5. After that, only fix broken paths, dead labels, or confusing buttons.

## Leave alone

- `Index.html` until the live path is checked.
- `crate-grabber-bg.jpg` and any background image history.
- Existing command generation flow.
- Existing copy-paste wrapper output.

## Rename or park later

Only after checking live hosting:

- Consider duplicating or renaming `Index.html` to `index.html` if the live host needs lowercase.
- Consider moving older notes/screenshots/assets into a parked folder only if they are visible in the root and causing confusion.

## Missing notes fixed

- README added to define repo purpose and HARDWAREJUICE boundary.

## Usability-only next checks

- Does the app load at the expected public URL?
- Does the background image load?
- Does Upload Image/OCR show a usable panel?
- Does CSV import actually append only URLs?
- Does generated shell command work in A-Shell?
- Does playlist toggle behave as expected?

## Not now

- No new features.
- No monetisation.
- No hardware controls.
- No Max/OSC/AI-engine work.
- No redesign.
