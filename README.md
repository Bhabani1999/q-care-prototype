# Q Care Prototype

An interactive product-design prototype exploring a caregiver's journey from a family member's report to a doctor's overview.

## Open

The entry point is `index.html`. It is self-contained: app code, fonts, photography, masks and backgrounds are embedded. No install, server or API key is required.

- Guided is the default presentation mode.
- Free Explore removes the external cues. Use `?mode=free` for a direct free-explore link.
- Back restores the previous interaction state, including answers and selections.
- Reset starts a fresh family-selection journey.
- Desktop centres and scales the phone to fit the viewport. Small screens show only the app.

## Main Journey

Choose Mum, open Ask Q, attach the demonstration report, answer the context questions, open the report review, explore the focus areas, arrange next steps and bring a doctor into the conversation.

All AI messages, doctor responses, appointments and service availability are scripted demonstrations. Nothing is submitted to a healthcare service. The health score is illustrative. This is not medical advice.

`sample-report.html` contains demonstration readings already shown in the prototype. The original medical PDF, private working notes and unrelated project files are deliberately excluded.

## Hosting

Serve the repository root with GitHub Pages or any static host. No build step is required. Keep `sample-report.html` beside `index.html`.

## Assets

See `ASSET_CREDITS.md`, `FAMILY_PHOTO_CREDITS.md` and the included font-license notices. Stock portraits illustrate fictional profiles and do not imply endorsement.
