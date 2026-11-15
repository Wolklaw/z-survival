# Audio credits

All audio below is CC0 (public domain); credit is optional but given here.

| Used for | Source | Author |
|---|---|---|
| Music, day/night (`Resources/Music/day.ogg`, `night.ogg`) | [Post-Apocalyptic Morning, Afternoon and Night](https://opengameart.org/node/178490) (afternoon + night tracks) | see page |
| Click, Sting, Deny | [Kenney Interface Sounds](https://opengameart.org/content/interface-sounds) | Kenney |
| Smash, Build | [Kenney Sci-Fi Sounds](https://opengameart.org/content/sci-fi-sounds) | Kenney |
| Hit, Coin, Build (latch) | [Kenney 50 RPG sound effects](https://opengameart.org/content/50-rpg-sound-effects) | Kenney |
| Groan | [Zombies Sound Pack](https://opengameart.org/content/zombies-sound-pack) | artisticdude |
| Shot, Turret | [Gunshots](https://opengameart.org/content/gunshots) ("22 Pistol", cut into single shots) | see page |
| Alarm, night drone | [30 CC0 SFX loops](https://opengameart.org/content/30-cc0-sfx-loops) (`alarm_01/02`, `ambient_01`) | see page |
| Wind | [wind whoosh loop](https://opengameart.org/content/wind-whoosh-loop) | see page |

Every sound is now real audio; the synth in `AudioManager.cs` / `MusicSynth.cs` is only a fallback if a file is missing.
Each `Sfx` slot loads every clip in `Resources/Sfx/<SfxName>/`; ambience loads from `Resources/Ambience/` (`wind`, `drone`).
