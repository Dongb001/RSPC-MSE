# Reference-Free Singing Pitch Correction

Static GitHub Pages demo for **Reference-Free Singing Pitch Correction via Music-Constrained Sequence Editing**.

Open `index.html` directly, or serve this directory locally:

```bash
python -m http.server 8002
```

Then visit <http://localhost:8002>. The page is dependency-free and uses relative paths, so it can be published from the repository root with GitHub Pages.

## Contents

- Five curated comparison groups (samples 2070, 2030, 2022, 2073, and 2068). Each group contains an 8-second input clip and three aligned reconstruction clips cropped from the plotted intervals.
- Each group includes its discrete MIDI-pitch and continuous mapped-F0 comparison plots under `figures/`.
- The accompanying `Template.pdf` and its local model overview illustration.
- Audio clips begin loading as soon as the sample cards are rendered, so playback is ready without an initial click-to-load delay. The `audio_clip/` excerpts are small, aligned listening previews; check repository, bandwidth, and storage limits before publishing.

The source reconstruction directory is not required at runtime and was not modified while preparing this demo. The current assets do not include a confirmed reference-original WAV, so the page does not invent a reference player.

## Citation

```text
Reference-Free Singing Pitch Correction via Music-Constrained Sequence Editing
Author(s) Name(s), Author Affiliation(s), ICASSP (manuscript).
```
