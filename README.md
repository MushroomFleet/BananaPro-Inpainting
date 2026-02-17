# BananaPro Inpainting

A desktop application for AI-powered image inpainting. Paint a mask over any part of an image, optionally describe what you want, and let Google's Gemini API intelligently remove or replace the masked region.

Built with React, TypeScript, and [Tauri](https://tauri.app/) for a lightweight native desktop experience.

## Features

- **Mask Painting** - Brush-based mask editor with adjustable size (2-120px), hardness, and opacity. Supports paint, erase, clear, and invert operations.
- **Object Removal** - Mask an object and remove it seamlessly. The AI fills the area naturally based on surrounding context.
- **Selective Editing** - Provide a text prompt to modify the masked area (e.g. "replace with a red door", "add flowers here").
- **Gallery** - All results are saved locally using IndexedDB. Browse, preview in a lightbox, select for bulk download or deletion, and re-edit any saved image directly from the gallery.
- **Touch Support** - Works on touch-enabled devices.

## Installation

Download the latest MSI installer from the [Releases](https://github.com/MushroomFleet/BananaPro-Inpainting/releases) page and run it to install BananaPro Inpainting on Windows.

## Setup

BananaPro Inpainting requires a Google AI API key to access the Gemini image generation model.

1. Obtain an API key from [Google AI Studio](https://aistudio.google.com/apikey).
2. Launch the application and click the **Settings** button.
3. Enter your API key and save.

## How to Use

### Inpainting an Image

1. Click **Load Image** or drag and drop an image onto the editor.
2. Use the toolbar to adjust your brush size, hardness, and opacity.
3. Paint a mask over the area you want to change (shown as a red overlay).
4. Optionally type a prompt describing the desired result. Leave it blank to remove the masked object.
5. Click **Inpaint** and wait for processing.
6. The result appears in the right panel. Click **Download** to save it, or it will be stored automatically in your gallery.

### Gallery

Switch to the **Gallery** tab to view all previously inpainted images. From here you can:

- Double-click an image to open a full-screen lightbox preview.
- Select images and download or delete them in bulk.
- Click **Inpaint** on any gallery card to re-edit that image with a new mask.



## License

See [LICENSE](LICENSE) for details.


## 📚 Citation

### Academic Citation

If you use this codebase in your research or project, please cite:

```bibtex
@software{bananapro_inpainting,
  title = {NamBananaPro Inpainting: Nano Banana Pro Frontend which allows for Inpainting with brushed masks},
  author = {[Drift Johnson]},
  year = {2026},
  url = {https://github.com/MushroomFleet/BananaPro-Inpainting},
  version = {1.0.0}
}
```

### Donate:


[![Ko-Fi](https://cdn.ko-fi.com/cdn/kofi3.png?v=3)](https://ko-fi.com/driftjohnson)
