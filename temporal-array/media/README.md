# Landing page media

Videos and posters go here and are referenced as `media/<file>` — for example
`{{< video src="media/overview.mp4" poster="media/overview.jpg" >}}`.

Images may instead be placed in `site/assets/media/`, where the `image`
shortcode picks up their real dimensions (no layout shift).

The main page uses `demo_mastered_02-91.mp4` with `demo-poster.jpg`. Other
potential video additions are listed below:

| Slot | File | Content |
| --- | --- | --- |
| Polyrhythm video | `polyrhythm.mp4` | "3 against 4", then "15 steps / 16 steps"; Euclidean pulse and rotation in Circle view. |
| MIDI video (optional) | `midi.mp4` | Named controller toggling steps and changing fill density. |

Videos stay click-to-play with sound and controls: never add `autoplay` or
`muted`. Supply a poster frame so the slot has a readable still.
