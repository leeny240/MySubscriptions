# SubNote — Add Subscription prototype

Interactive prototype of SubNote's **Add Subscription · First Decision** flow, built from the Figma design system (variables, text styles and components).

**Live preview:** https://leeny240.github.io/MySubscriptions/

## What you can try
- Opens directly on the review step with 3 sample screenshots (YouTube Premium, Notion, Google Gemini).
- Edit amount (live KRW conversion), billing cycle, next payment date, payment method.
- Set usage and the pre-payment alert (D-7 / D-3 / D-1, channels).
- Save & next / Skip, finish → Home with Undo.
- Scenario toggles in the yellow prototype bar: blurry screenshot, duplicate, push permission off, offline.
- Light / dark theme, hover motion on the invite banner.

## Notes
- Single static file (`index.html`), no build step.
- Designed for desktop 1600–1920px; below 1600px the layout scales proportionally.
- OCR, notifications and saving are simulated — nothing is sent or stored.
