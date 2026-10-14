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

## Preview images (thumbnails)

The style picker shows a preview picture for each style. Put a JPG named after
the style `id` in the [`thumbs/`](thumbs/) folder:

```
thumbs/<style-id>.jpg      e.g. thumbs/thingyan-festival.jpg
```

The app loads them from this repo (square, ~512×512, ≈40–80 KB). Styles with no
image file just show their emoji, so you can add images gradually. See
[`thumbs/README.md`](thumbs/README.md) for the full list of ids.

## Notes
- Keep `id` unique.
- `modifier` is English; it is appended to the master-prompt system instruction.
- Do not rename `styles.json` or move it out of the repo root.
