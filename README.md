# Miniapp Image Tool

A tiny, local-only HTML tool for resizing and cropping images before uploading them to mini program admin panels.

## Features

- Runs fully in the browser, with no server and no image upload.
- Batch import by selecting or dragging images.
- Default daily preset: WEBP 92%, max width 600 px, long vertical images cropped automatically.
- Extra presets for higher quality, JPG compatibility, and text screenshots.
- Preview, download, download all, and remove individual processed images.
- Remembers your saved settings in the browser.

## Usage

Open `index.html` in a browser, drop images into the upload area, then download the processed files.

The default rule is:

- Width is capped at `600 px`.
- Height is capped at `2 x width`.
- Normal photos are resized proportionally.
- Very tall images are cropped first, then resized.

## Recommended Settings

- Daily admin upload: `WEBP`, quality `92%`.
- Maximum quality: `WEBP`, quality `96%`.
- Compatibility: `JPG`, quality `92%`.
- Text-heavy screenshots: `PNG`.

## Privacy

All processing happens locally in your browser. The tool does not send images anywhere.

## License

MIT
