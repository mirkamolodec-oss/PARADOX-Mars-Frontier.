# Third-party components and asset licenses

## Audio

All audio files included in the `audio/` directory were provided by the team as downloads from **Mixkit**. Mixkit audio is distributed under the Mixkit License; consult the current license terms at https://mixkit.co/license/ before redistribution or use outside the permitted scope.

| Local file | Use in game | Source / license record |
|---|---|---|
| `background-1.mp3` | Background ambience track 1 | Mixkit; exact source item URL/title not supplied |
| `background-2.mp3` | Background ambience track 2 | Mixkit; exact source item URL/title not supplied |
| `background-3.wav` | Background ambience track 3 | Mixkit; exact source item URL/title not supplied |
| `dome-enter.wav` | Entering a habitat dome | Mixkit; exact source item URL/title not supplied |
| `metal-mining.wav` | Mining / resource extraction | Mixkit; exact source item URL/title not supplied |
| `scanner.wav` | Scanner activation | Mixkit; exact source item URL/title not supplied |
| `notification.wav` | UI / crafting notification | Mixkit; exact source item URL/title not supplied |
| `construction.wav` | Construction / installation | Mixkit; exact source item URL/title not supplied |

**Important:** the team identified Mixkit as the source for all audio, but did not provide the individual Mixkit item pages, titles, download dates, or license snapshots. Add those exact URLs and retain a copy of the applicable license terms before final submission. Do not claim that the individual sound files have been independently license-audited until this information is recorded.

## Runtime / platform APIs

- HTML5 Canvas — browser platform API; no separate third-party package.
- JavaScript and CSS — native browser technologies.
- `localStorage` — browser platform API used for local saves and audio settings.
- `HTMLAudioElement` — browser platform API used for audio playback.

## Fonts and visual assets

The HTML references system font fallbacks (`Space Grotesk`, `Segoe UI`, `Roboto`, `Arial`, sans-serif). No separate font package is bundled in this delivery. The exact origin and license of all pre-existing visual assets / generated icon URLs should be recorded by the team before submission; their provenance is not established by the supplied project archive alone.

## Game engine / framework

- Custom HTML5 Canvas 2D game code written in JavaScript. No Godot, Unity, or other game-engine runtime is bundled.
