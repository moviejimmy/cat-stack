# 🐾 貓貓疊疊樂 · Neko Stack

A layered tile-matching game (羊了個羊 style) starring 8 real cats.
Each level has a boss cat 👑 buried deep in the pile — match three boss
tiles and the boss rescues your tray. Fill the 7-slot tray and the boss
taunts you personally.

**Play:** https://moviejimmy.github.io/cat-stack/

## Features

* 20 levels, 156 → 300 tiles, up to 20 tile types (8 cats + 12 animals)
* Fog of war: buried tiles are face-down; deep-fog levels hide everything below the surface
* 3 blind stacks, buried boss cats with per-cat Cantonese taunt lines
* Random 2-of-3 lifelines each attempt (退回 / 彈出三張 / 洗牌); Level 20: 洗牌 only
* 咪咪 is the final boss. Nobody expected 咪咪.
* Shared leaderboard on Supabase, ranked by highest level then score
* Single HTML file, no build step; progress saves locally

