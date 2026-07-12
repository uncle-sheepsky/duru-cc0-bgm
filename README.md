# DURU — CC0 BGM

Background music from the **DURU** YouTube channel (<https://www.youtube.com/@Duru0503>),
released into the public domain under **CC0 1.0** — free for anything (videos, games,
streams, commercial projects), **no attribution required** (attribution welcome, never obligatory).

Every track is **composed and produced by DURU in code** (Python + NumPy / SciPy).
Tracks fall into two groups, marked in the table below:

- **[pure]** — 100% synthesized in code, **zero external audio samples**, no VST instruments.
- **[+sfx]** — original DURU music that also layers in **third-party sound effects that are
  themselves CC0** (see "Third-party CC0 audio" below). The whole mix is CC0; these are **not**
  claimed to be sample-free.

## Tracks

| file | used in | length | melody | build |
|---|---|---|---|---|
| `duru-rondo` | *Duru — Channel surfing (MV)* (ep13) · *Duru — CHANNEL SURF* (ep29) | 1:04 | original | **[pure]** |
| `duru-roomscene-lofi` | *라디오 잼 — 두루와 아늑한 방* / lo-fi radio room (ep11) | 1:44 | original | **[pure]** |
| `duru-arcade-vibe` | *Arcade — vibe (MV)* chiptune (ep14) | 1:02 | original | **[pure]** |
| `mountainking-arcade-loop` | *DURU 2048* (4-seed race) | 0:40 (loop) | Grieg, *In the Hall of the Mountain King* (public domain) | **[pure]** |
| `korobeiniki-boombap-loop` | *DURU BLOCK FEVER* (Tetris tribute) | 0:48 (loop) | *Korobeiniki* (public domain) | **[pure]** |
| `korobeiniki-arcade-fullver` | *뱅크와 스키마로* making-of explainer | 2:40 | *Korobeiniki* (public domain) | **[+sfx]** |
| `duru-rhythm-fever` | *Duru — RHYTHM FEVER (Full Stage)* (ep19) | 1:28 | original | **[+sfx]** |
| `duru-denparcade` | *🕹️DENPARCADE / DURU* (ep16) | 1:25 | original | **[+sfx]** + Faust DSP lead |
| `duru-winter-arcade` | *[Duru] Arcade — vibe (MV)* / winter arcade (ep14) | 1:02 | original | **[+sfx]** |

Each ships as **FLAC** (lossless, `flac/`) and **MP3 320 kbps** (`mp3/`).

## License — please read

- **All nine tracks are released under CC0 1.0** (public-domain dedication). Use them for
  anything — no attribution required. See [LICENSE](LICENSE).
- **Melody**: tracks marked *original* are DURU's own composition. `korobeiniki-*` arrange
  *Korobeiniki* (Коробейники) and `mountainking-*` arranges Grieg's *In the Hall of the
  Mountain King* — both **19th-century, public-domain** melodies anyone may freely use. The
  DURU arrangements & recordings are dedicated to the public domain under CC0.
- **[pure] tracks** are 100% synthesized in code (Python + NumPy / SciPy): no external audio
  samples, no sample libraries, no VST instruments.
- **[+sfx] tracks** are DURU's own music with third-party **CC0** sound effects layered in
  (see below). Because every added component is itself CC0, the finished track is CC0 too —
  but these are, honestly, not sample-free.

### Third-party CC0 audio used in the [+sfx] tracks

All of it is public-domain / CC0 and free to redistribute:

- **Sheep "baa" vocalizations** — BigSoundBank (CC0, free commercial use, no attribution).
- **Retro coin / gem one-shots** — *80 CC0 RPG SFX* pack (CC0).
- **Arcade / interface one-shots** (blip, sparkle, coin, boss, laser, etc.) — Kenney
  *Interface Sounds* & *Sci-Fi Sounds* (CC0; bundled `License.txt` = CC0 1.0).
- **Vocal-chop hit** — Freesound (cat-fox_alex, CC0).
- **Glockenspiel / marimba** (ep19 only) — VSCO 2 Community Edition (CC0) sampled instruments.
- **Faust DSP lead** (ep16 `duru-denparcade`) — a synth instrument *defined in code*
  (Faust via DawDreamer). Not a copyrighted VST; the output is original DURU synthesis.

## Not affiliated with Tetris

*Korobeiniki* is a public-domain folk melody widely recognized from the game *Tetris*.
These releases are independent arrangements of that public-domain melody and are **not
affiliated with, sponsored by, or endorsed by Tetris Holding, LLC**. "Tetris" is a
trademark of its respective owner.

## Integrity

See [MANIFEST.txt](MANIFEST.txt) for SHA-256 checksums and exact durations.
