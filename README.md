# Subtle Gradient Bug in Tailwind CSS

This repository demonstrates a subtle bug that can occur when using Tailwind CSS's gradient functionality.  If the `from` and `to` colors in a linear gradient are too similar, the resulting gradient may not be visible or might appear as a solid color, making it difficult to detect.

## Bug Description

The bug manifests when a linear gradient is applied using Tailwind CSS classes, and the starting and ending colors are very close in hue, saturation, and lightness.  The gradient effect becomes almost imperceptible, resulting in what appears to be a solid-colored background.

## Reproduction

1. Clone this repository.
2. Open `bug.html` in your browser.
3. Observe the subtly incorrect gradient.

## Solution

The solution involves either using colors that are sufficiently different or explicitly setting a more pronounced gradient using different color stops.  The corrected code is provided in `bugSolution.html`.

## Contributing

Feel free to contribute to this repository by reporting similar issues or providing alternative solutions.