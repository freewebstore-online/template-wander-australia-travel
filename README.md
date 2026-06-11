# wander-australia-travel

A FreeWebStore template for **travel.agency** by **@kirantikoo**.

## Vibecoding this template

Open `index.html` in your editor of choice (Claude Code, Cursor, Windsurf,
plain VS Code with an AI sidebar) and iterate. Constraints:

- **HTML + Tailwind utility classes only.** No templating engines, no
  framework, no build step.
- **Slot markers (`data-fws-slot="..."`) mark customization points.**
  See `slots.md` for the conventional set for your category.
- **Single-page output.** FWS produces one HTML file per business. Multi-page
  is a PWS feature, not FWS.

When the design looks good in your browser, capture a 1280×720 PNG hero shot
as `preview.png` (replace the placeholder).

## Publishing

```sh
npx @freewebstore/cli doctor     # local validation
npx @freewebstore/cli login      # one-time GitHub App install
npx @freewebstore/cli publish    # upload + create repo + queue for review
```

## License

MIT (auto-set by `fws init`). FreeWebStore requires MIT for community
templates — see CONTRIBUTING.md in the platform docs for the why.
