# Photo Comparator

A single-page app to compare two photos using instant flip, fade blending, a draggable divider reveal, and a stereoscopic pair view.

## Features
- Instant flip between two photos (button or click on the image)
- Fade slider to blend between images
- Divider reveal with drag-to-move and slider control
- Stereoscopic left/right view with a toggle for parallel vs cross-eye viewing
- Local file uploads, no server required

## Comparison modes
- Instant Flip: tap the button or image to alternate between A and B.
- Fade Slider: drag the slider or drag across the image to blend between photos.
- Divider Reveal: drag the vertical divider or use the slider to set the reveal edge.
- Stereoscopic Pair: view a left/right pair and toggle between parallel vs cross-eye ordering.

## Usage
Open `index.html` in your browser and upload two images (sample images are shown by default).

Optional: run a tiny local server if your browser blocks local file access:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Files
- `index.html` - the complete app (HTML/CSS/JS)
- `LICENSE` - MIT license
