# Live ASCII Webcam

🎥 [▶ Try the Live Demo](https://rjtpp.github.io/ascii-cam/)

A self-contained HTML application that captures your webcam, converts each frame into real-time ASCII art (monochrome or color), and displays it in the browser. You can adjust width and contrast, toggle color and invert modes, save snapshots, choose from multiple ASCII character sets (or define your own), and record sessions as 1080p MP4/WebM videos — all entirely in the browser.

## Features

- **Real-time ASCII rendering**: Webcam or screen frames rendered in a `<pre>` as ASCII art.
- **Monochrome & Color modes**: Toggle between grayscale or colorized ASCII.
- **Invert mode**: Flip the light–dark mapping of the character scale.
- **Character set selection**: Choose between multiple character ranges (Simple, Standard, Pixel, etc.) or define a **Custom** set.
- **Adjustable Width**: Dynamically change horizontal resolution.
- **Contrast control**: Brightness scaling centered around mid-gray.
- **Live Preview Toggle**: Hide/show the preview area for performance.
- **Camera/Screen switch**: Select webcam input or screen capture.
- **Snapshot**: Save the current ASCII frame as a PNG image.
- **Recording**: Export ASCII rendering at 1080p as MP4/WebM.
- **Responsive Controls**: Reset all settings or dynamically switch modes mid-session.

## Getting Started

1. **Download** `index.html` (this file contains all code).
2. **Open** it in a modern browser (Chrome, Firefox, Edge, Safari).
3. **Allow** camera/screen access when prompted.
4. The ASCII art will start rendering automatically.

No installation or server is required — everything runs locally in-browser.

## Controls

| Control                  | Description                                                                 |
| ------------------------ | --------------------------------------------------------------------------- |
| **Width** slider         | Number of ASCII columns in the output.                                      |
| **Contrast** slider      | Adjusts brightness scaling (0.5× to 2.0×).                                   |
| **Color** toggle         | Renders using grayscale or per-character RGB color.                         |
| **Invert** toggle        | Reverses the brightness → ASCII mapping.                                    |
| **Chars** dropdown       | Choose character set (Simple, Standard, Pixel, etc.)                        |
| **Custom Chars** input   | Type your own characters if “Custom” is selected.                           |
| **Source** selector      | Choose between **Camera** or **Screen** as video input.                     |
| **Save PNG**             | Exports current frame as a PNG file.                                        |
| **Start/Stop Recording** | Captures 1080p ASCII video; saved as `ascii-<timestamp>.mp4` or `.webm`.   |
| **Reset Config**         | Restores Width = 150, Contrast = 1.0, Color = off.                          |
| **Hide/Show Preview**    | Temporarily disables preview pane (helpful on low-end devices).             |
| **FPS Indicator**        | Displays current rendering framerate.                                       |

## Tips & Troubleshooting

- **Recording Compatibility**: Most browsers support MP4 or WebM recording. Safari prefers MP4.
- **Performance**: Lower width and disabling color improves speed on slower machines.
- **Screen Sharing**: Screen recording auto-reverts to webcam if screen sharing is stopped.
- **Permissions**: Check your browser permissions if webcam/screen capture fails to start.

## Related Projects

If you’re looking for ASCII image converters, feel free to check out the companion project: [RJTPP/ascii-pic](https://github.com/rjtpp/ascii-pic)

## License

This project is released under the [MIT License](LICENSE).

You are free to use, modify, and distribute this software under the terms of the MIT License. See the LICENSE file for detailed terms and conditions.
