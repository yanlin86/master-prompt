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
| `natural-elegance` | 🌸 Natural Elegance | elegant-women |
| `myanmar-royal-elegance` | 👑 Myanmar Royal Elegance | elegant-women |
| `modern-chic-elegance` | ✨ Modern Chic Elegance | elegant-women |
| `golden-hour-elegance` | 🌅 Golden Hour Elegance | elegant-women |
| `studio-glamour-elegance` | 💎 Studio Glamour Elegance | elegant-women |
| `thanaka-elegance` | 🌼 Thanaka Elegance | elegant-women |
| `evening-gown-elegance` | 🌙 Evening Gown Elegance | elegant-women |
| `floral-garden-elegance` | 🌷 Floral Garden Elegance | elegant-women |
| `minimal-beauty-elegance` | 🤍 Minimal Beauty Elegance | elegant-women |
| `cinematic-elegance` | 🎬 Cinematic Elegance | elegant-women |
| `watercolor-elegance` | 🎨 Watercolor Elegance | elegant-women |
| `vintage-glam-elegance` | 📷 Vintage Glam Elegance | elegant-women |
| `street-style-elegance` | 👜 Street Style Elegance | elegant-women |
| `bridal-myanmar-elegance` | 💒 Bridal Myanmar Elegance | elegant-women |
| `professional-elegance` | 💼 Professional Elegance | elegant-women |
| `festival-lights-elegance` | 🏮 Festival Lights Elegance | elegant-women |
| `monsoon-romance-elegance` | 🌧️ Monsoon Romance Elegance | elegant-women |
| `pagoda-serene-elegance` | 🛕 Pagoda Serene Elegance | elegant-women |
| `silk-and-gold-elegance` | 🧵 Silk and Gold Elegance | elegant-women |
| `morning-calm-elegance` | 🌄 Morning Calm Elegance | elegant-women |
| `kpop-idol-girl` | 💄 K-pop Idol Girl | youth |
| `douyin-beauty` | 📱 Douyin Beauty | youth |
| `anime-girl` | 🌸 Anime Girl | youth |
| `soft-girl` | 🎀 Soft Girl | youth |
| `y2k-girl` | ✨ Y2K Girl | youth |
| `coquette-girl` | 🧸 Coquette Girl | youth |
| `streetwear-girl` | 🛹 Streetwear Girl | youth |
| `fairy-core` | 🧚 Fairy Core | youth |
| `princess-glam` | 👑 Princess Glam | youth |
| `ulzzang-student` | 🎓 Ulzzang Student | youth |
| `kpop-idol-boy` | 🎤 K-pop Idol Boy | youth |
| `anime-boy` | ⚔️ Anime Boy | youth |
| `streetwear-boy` | 🏀 Streetwear Boy | youth |
| `esports-gamer` | 🎮 Esports Gamer | youth |
| `footballer` | ⚽ Footballer | youth |
| `biker-boy` | 🏍️ Biker Boy | youth |
| `retro-cool` | 📼 Retro Cool | youth |
| `rockstar` | 🎸 Rockstar | youth |
| `thai-drama-star` | 🎭 Thai Drama Star | youth |
| `dark-street` | 🖤 Dark Street | youth |
| `gta-loading` | 🎮 GTA Loading Screen | trending |
| `pixar-3d` | 🧸 Pixar 3D | trending |
| `lego-figure` | 🟨 Lego Figure | trending |
| `simpsons-style` | 📺 Simpsons Style | trending |
| `clay-3d` | 🏺 Clay 3D | trending |
| `wes-anderson` | 🎞️ Wes Anderson | trending |
| `album-cover` | 💿 Album Cover | trending |
| `barbiecore` | 💖 Barbiecore | trending |
| `clean-girl` | 🧼 Clean Girl | trending |
| `frutiger-aero` | 🫧 Frutiger Aero | trending |
| `phone-mockup-studio` | 📱 Phone Mockup Studio | mockup |
| `phone-in-hand` | 🤳 Phone In Hand | mockup |
| `phone-flatlay` | ☕ Phone Flatlay | mockup |
| `phone-night-glow` | 🌃 Phone Night Glow | mockup |
| `phone-3d-float` | 📐 Phone 3D Float | mockup |
| `phone-3d-dark` | 🌑 Phone 3D Dark | mockup |
| `phone-front-view` | 📲 Phone Front View | mockup |
