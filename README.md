# EgoMatrix project homepage

Final static project page. Open `index.html` in a browser or serve this directory
with a static web server. No build step or runtime dependencies are required.

Project page: https://egomatrix2027.github.io/

Anonymous source code: https://github.com/EgoMatrix2027/EgoMatrix

## Contents

- 16 human / simulation / synthesized-observation demonstration triplets.
- 10 hand-side reconstruction entries with original-camera, object-centered
  and contact-refinement views.
- A 5×5 background-transfer matrix and a target-workstation / real-replay comparison.
- Six hardware task videos, the teaser and the method overview.

## Files

- `index.html`: the only page entry point.
- `style.css`, `app.js`, `task-carousel.js`: layout and interaction.
- `demo-catalog.js`, `reconstruction-catalog.js`: active media catalogs.
- `reconstruction-viewer.js`, `reconstruction-viewer.css`: integrated reconstruction viewer.
- `assets/`: only the images, posters and videos referenced by the final page.
- `.nojekyll`: static GitHub Pages configuration.

Task arrows stop at each end and remember the selected task within a browser
session where storage is available. Reconstruction supports two comparison layouts,
frame stepping, playback speed and contact-pair markers.

The paper's quantitative results are unchanged by qualitative media updates.
Human / robot excerpts are tail-aligned for presentation, not claimed to be
framewise motion matches. The workstation synthesis and hardware replay retain
their independent timing.

Test pages, unused media, historical backups and development records have been
archived outside this repository. The Git history is preserved.
GitHub Pages serves the repository root on `main`.
