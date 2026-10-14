# KSH Prompt Studio — Styles

Style library for **KSH Prompt Studio**. The app fetches `styles.json` from this
repo at launch, so styles can be added/edited here without rebuilding the APK.

## Format

```json
{
  "styles": [
    {
      "id": "unique-slug",
      "name": "Display Name",
      "emoji": "🔥",
      "category": "trending",
      "modifier": "english prompt fragment appended to the master prompt"
    }
  ]
}
```

Built-in categories: `trending, cinematic, anime, vintage, fantasy,
professional, artistic, myanmar`. A new `category` value also works — the app
picks it up automatically and shows a new tab.

## Notes
- Keep `id` unique.
- `modifier` is English; it is appended to the master-prompt system instruction.
- Do not rename `styles.json` or move it out of the repo root.
