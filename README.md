# Hywall
Hywall is a tool for generating inspiring colour palettes from images in Houdini. 
Generates 5 palette variants: Main, Pastels, Warm Shift, Dark Mode, and Cool Shift.

![HywallScreenShot.png](HywallScreenShot.png)

## Features
- Generate colour palettes from any image
- 5 palette variants: Main, Pastels, Warm Shift, Dark Mode, Cool Shift
- Click a colour swatch to copy hex to the clipboard
- Click a palette row to apply as a colour ramp to a selected node (Node needs to have a ramp)
- Export palettes to CSV, JSON, GPL, CSS
- Colour space selector for exports (sRGB, ACEScg, OKLab, etc.)

## Installation
1. Clone or download this repo
2. Copy `hywall.json` to `~/houdini21.0/packages/` (create the `packages` folder if it doesn't exist)
3. Restart Houdini
4. Open via **Parameter Panel > Hywall**

> If you placed the repo outside your Houdini prefs folder, edit `hywall.json` and replace `$PACKAGE_PATH` with the full path to the repo.

## Requirements
- Houdini 21+ (Pillow and Coloraide are bundled)

## Usage
- Browse or type a path and press Enter to load an image
- Click any colour swatch to copy its hex value
- Select a node with a colour ramp parameter, then click a palette row to apply it
- Choose export format and colour space, then click Export

## License
MIT

## Credits
Developed by [Hakeem Adam](https://hakeemadam.info).
Inspired by [Pywal](https://github.com/dylanaraps/pywal) and [Pastel](https://github.com/sharkdp/pastel). 