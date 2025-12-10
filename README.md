## Intellectual Property Notice

All HTML, CSS, and JavaScript code in this repository is licensed under the MIT License.

However:
- All audio files (MP3, WAV, stems),
- All lyric text,
- All images, artwork, and backgrounds,
- All song metadata (ISRC, credits, publishing info),
- All branding and marks associated with 24-7 Entertainment Studios, Mint Condition, and related entities

are the exclusive intellectual property of Joel Peter Bales (aka Jingle Bales) and 24-7 Entertainment Studios.

They are NOT licensed for reuse, redistribution, modification, sale, or incorporation into derivative works without explicit written permission.
# 247 Lyric Jukebox
**An interactive, browser-based lyric-video player system for 24-7 Entertainment Studios / Mint Condition.**

This project contains:
- A **jukebox-style index.html** that rotates standalone “lyric bots”
- Individual **self-contained lyric player HTML files** under `/songs/`
- A `/manifest/tracks.json` file for future data-driven expansion
- A Netlify-ready static site structure
- MIT-licensed *code*, with proprietary rights retained for audio, lyrics, artwork, and metadata.

---

## 🚀 Features (MVP)

- Cross-browser lyric player (Chrome, Edge, Firefox, Comet)
- Embedded audio player  
- Visualizer canvas  
- Volume + Seek controls  
- Pitch slider (via playbackRate)  
- Background art layer  
- Simple lyric rendering (non-timed for now)  
- Jukebox “Next / Prev / Choose Song” interface  
- Optional ID3 metadata reader for MP3 files  
- Expandable architecture for LRC (timed lyrics), theme modes, token-gating, NFT integration, and streaming logic.

---

## 📁 Project Structure
247-lyric-jukebox/
├─ index.html # Jukebox wrapper (iframe playlist)
├─ songs/
│ ├─ rise-above.html # Single-song lyric player
│ └─ shattered-illusions.html # Another playable track
├─ assets/
│ ├─ audio/ # Your MP3s/WAVs (NOT MIT licensed)
│ │ └─ .gitkeep
│ └─ img/ # Background images (NOT MIT licensed)
│ └─ .gitkeep
├─ manifest/
│ └─ tracks.json # Future master-player manifest (optional)
├─ netlify.toml # Netlify deploy config
├─ LICENSE # MIT license (code only)
├─ README.md # This file
└─ .gitignore # Ignore caches, OS junk, etc.
