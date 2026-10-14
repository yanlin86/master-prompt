# Style preview images (thumbnails)

The app shows a preview picture for every style. It looks for the
image here:

```
thumbs/<style-id>.jpg
```

A **JPG named exactly like the style `id`**. That is all — when you
upload the file to this folder the app picks it up on the next launch
(it reads from GitHub). No APK rebuild, no `styles.json` edit.

## Rules

- File name = style id, extension `.jpg` (e.g. `thangyan-festival.jpg` → `thingyan-festival.jpg`).
- Square images look best (~512×512). Other shapes are center-cropped.
- Keep them small (≈40–80 KB) so the app stays fast.
- Styles without an image simply show their emoji — safe to add them gradually.

## Style ids

| id (file name) | Style | Category |
|---|---|---|
| `rain-neon-hero` | 🌧️ Rain Neon Hero | trending |
| `golden-hour-glow` | 🌅 Golden Hour Glow | trending |
| `toy-figure` | 📦 Toy Figure | trending |
| `chibi-avatar` | 🍡 Chibi Avatar | trending |
| `cyberpunk-hacker` | 🌃 Cyberpunk Hacker | trending |
| `royal-portrait` | 👑 Royal Portrait | trending |
| `imperfect-film` | 🎞️ Imperfect Film | trending |
| `half-shadow-drama` | 🎭 Half-Shadow Drama | trending |
| `motion-energy` | 💨 Motion Energy | trending |
| `y2k-camcorder` | 📼 Y2K Camcorder | trending |
| `anamorphic-noir` | 🌌 Anamorphic Noir | cinematic |
| `chiaroscuro-study` | 🕯️ Chiaroscuro Study | cinematic |
| `editorial-flash` | 📸 Editorial Flash | cinematic |
| `foggy-backlight` | 🌫️ Foggy Backlight | cinematic |
| `neon-alley` | 🌆 Neon Alley | cinematic |
| `desert-epic` | 🏜️ Desert Epic | cinematic |
| `window-light-soft` | 🪟 Window Light Soft | cinematic |
| `underwater-dream` | 🌊 Underwater Dream | cinematic |
| `stage-spotlight` | 🎤 Stage Spotlight | cinematic |
| `snow-bokeh` | ❄️ Snow Bokeh | cinematic |
| `ghibli-soft` | 🌿 Ghibli Soft | anime |
| `shinkai-sky` | 🌇 Shinkai Sky | anime |
| `cyber-samurai` | ⚔️ Cyber Samurai | anime |
| `chibi-pop` | 🍬 Chibi Pop | anime |
| `ukiyo-e-wave` | 🌊 Ukiyo-e Wave | anime |
| `dark-gothic` | 🦇 Dark Gothic | anime |
| `mecha-pilot` | 🤖 Mecha Pilot | anime |
| `shojo-sparkle` | ✨ Shojo Sparkle | anime |
| `pixel-sprite` | 👾 Pixel Sprite | anime |
| `ink-manga` | 🖋️ Ink Manga | anime |
| `polaroid-90s` | 📷 Polaroid 90s | vintage |
| `kodachrome-70s` | 🌞 Kodachrome 70s | vintage |
| `tintype-1800s` | 🏛️ Tintype 1800s | vintage |
| `noir-1940s` | 🎬 Noir 1940s | vintage |
| `bollywood-glam` | 💃 Bollywood Glam | vintage |
| `disposable-flash` | 📸 Disposable Flash | vintage |
| `magazine-80s` | 📰 Magazine 80s | vintage |
| `daguerreotype-mirror` | 🪞 Daguerreotype Mirror | vintage |
| `lomography-pop` | 🎡 Lomography Pop | vintage |
| `yearbook-60s` | 🎓 Yearbook 60s | vintage |
| `elven-royal` | 🧝 Elven Royal | fantasy |
| `dark-sorcerer` | 🔮 Dark Sorcerer | fantasy |
| `dragon-knight` | 🐉 Dragon Knight | fantasy |
| `celestial-angel` | 😇 Celestial Angel | fantasy |
| `ice-queen` | ❄️ Ice Queen | fantasy |
| `desert-nomad` | 🏜️ Desert Nomad | fantasy |
| `sea-captain` | 🌊 Sea Captain | fantasy |
| `forest-druid` | 🌲 Forest Druid | fantasy |
| `clockwork-noble` | ⚙️ Clockwork Noble | fantasy |
| `phoenix-reborn` | 🔥 Phoenix Reborn | fantasy |
| `executive-headshot` | 💼 Executive Headshot | professional |
| `studio-minimal` | 🤍 Studio Minimal | professional |
| `founder-story` | 🚀 Founder Story | professional |
| `medical-trust` | 🩺 Medical Trust | professional |
| `creative-director` | 🎨 Creative Director | professional |
| `outdoor-professional` | 🌳 Outdoor Professional | professional |
| `speaker-stage` | 🎙️ Speaker Stage | professional |
| `tech-casual` | 💻 Tech Casual | professional |
| `luxury-brand` | 🥂 Luxury Brand | professional |
| `impasto-oil` | 🎨 Impasto Oil | artistic |
| `rembrandt-glow` | 🕯️ Rembrandt Glow | artistic |
| `watercolor-wash` | 💧 Watercolor Wash | artistic |
| `charcoal-sketch` | ✏️ Charcoal Sketch | artistic |
| `pop-art` | 💥 Pop Art | artistic |
| `baroque-drama` | 👑 Baroque Drama | artistic |
| `impressionist-light` | 🌸 Impressionist Light | artistic |
| `ink-wash-zen` | 🖌️ Ink Wash Zen | artistic |
| `mosaic-gold` | ✨ Mosaic Gold | artistic |
| `myanmar-royal` | 🇲🇲 Myanmar Royal | myanmar |
| `shwedagon-sunset` | 🛕 Shwedagon Sunset | myanmar |
| `thanaka-portrait` | 🌼 Thanaka Portrait | myanmar |
| `bagan-temples` | 🌅 Bagan Temples | myanmar |
| `inle-fisherman` | 🚣 Inle Fisherman | myanmar |
| `myanmar-wedding` | 💒 Myanmar Wedding | myanmar |
| `chinlone-player` | ⚽ Chinlone Player | myanmar |
| `teashop-culture` | 🍵 Teashop Culture | myanmar |
| `thadingyut-lights` | 🌕 Thadingyut Festival of Lights | myanmar |
| `thingyan-festival` | 💦 Thingyan Water Festival | myanmar |
| `nyaung-ye-offering` | 🌳 Nyaung-ye Water Offering | myanmar |
| `tazaungdaing-balloons` | 🎈 Tazaungdaing Balloons | myanmar |
| `shwedagon-night` | ✨ Shwedagon by Night | myanmar |
| `u-bein-bridge-sunset` | 🌉 U Bein Bridge Sunset | myanmar |
| `kyaiktiyo-golden-rock` | ⛰️ Kyaiktiyo Golden Rock | myanmar |
| `mrauk-u-ancient` | 🏯 Mrauk U Ancient Kingdom | myanmar |
| `mandalay-palace` | 🏛️ Mandalay Palace | myanmar |
| `nat-spirit-festival` | 🌀 Nat Spirit Festival | myanmar |
| `burmese-monsoon` | 🌧️ Burmese Monsoon | myanmar |
| `burmese-village-life` | 🛖 Burmese Village Life | myanmar |
