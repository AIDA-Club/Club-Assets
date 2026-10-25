# AIDA × Hope — individual transparent assets

Each PNG in `assets/` contains one reusable graphic. Larger illustrations have
been separated into independently positionable pieces. Three new mascot portraits, two new ribbons, the neural network illustration and
new icons are included. The repeated Ask AIDA page uses the same assets from batch 2.

Open `preview.html` in a browser to browse every asset over a transparency grid.
`manifest.json` records source references, dimensions, content bounds, and descriptions.

## Fidelity

These are AI-assisted cutouts and reconstructions from flattened screenshot
references, not original editable design layers or exact pixel extractions.
Covered edges were reconstructed; tiny shapes, typography, materials and proportions
can differ. Transparent pixels outside each asset have been checked.

## Website implementation

Use PNGs for the mascot, ribbons and decorative artwork. Render ordinary interface
text, navigation, buttons, cards, input fields, progress dots and toggles as live HTML/CSS.
The provided raster icons can serve as references for matching SVG icons.
The transparent wordmark is a screenshot-derived version; prefer the original club
logo if that is the intended final brand.

The scan, heatmap and microscope sample have not been recreated or included.
Live charts, legend dots, sliders, numbered badges, and layout backgrounds should
be rendered in HTML/CSS or SVG from the actual application values. Actual ultrasound images,
heatmaps, model outputs and scientific data must come from the original application.
Do not use reconstructed artwork as clinical evidence or model input.

Mascots are upper-body portraits: retain the bottom crop when placing them in headers.
