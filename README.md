# Live ASCII Webcam

🎥 [▶ Try the Live Demo](https://rjtpp.github.io/ascii-cam/)

A self-contained HTML application that captures your webcam, converts each frame into real-time ASCII art (monochrome or color), and displays it in the browser. You can adjust width and contrast, toggle color mode, save snapshots as PNG, record sessions as MP4/WebM, and toggle the camera on/off while preserving your settings.

## Features

- **Real-time ASCII rendering**: Webcam frames are rendered as ASCII art in a `<pre>` element.
- **Monochrome & Color modes**: Toggle between pure grayscale ASCII or full-color ASCII.
- **Adjustable Width**: Control the number of ASCII columns (default 150).
- **Contrast control**: Stretch or compress brightness around mid-gray.
- **Camera toggle**: Turn the webcam off/on without losing your configuration.
- **Snapshot**: Save the current ASCII frame as a PNG image.
- **Recording**: Start/stop recording of the ASCII canvas to an MP4 or WebM video.
- **Settings reset**: Quickly restore width, contrast, and color to defaults.

## Getting Started

1. **Download** `index.html` (this file contains all code).
2. **Open** it in a modern browser (Chrome, Firefox, Edge, Safari).
3. **Allow** camera access when prompted.
4. The ASCII art will start rendering automatically.

_No installation or server is required — the app runs entirely in-browser._

## Controls

| Control                 | Description                                                                 |
| ----------------------- | --------------------------------------------------------------------------- |
| **Width** slider        | Sets the ASCII output width (columns).                                      |
| **Contrast** slider     | Adjusts brightness contrast (0.5× to 2.0×).                                  |
| **Color** checkbox      | Toggles between monochrome and full-color ASCII.                            |
| **Save PNG** button     | Downloads the current ASCII frame as `ascii-<timestamp>.png`.               |
| **Start Recording**     | Begins video recording of the ASCII canvas.                        |
| **Stop Recording**      | Stops recording and downloads `ascii-<timestamp>.mp4` or `.webm`.           |
| **Turn Camera Off/On**  | Pauses or resumes the webcam feed; settings persist across toggles.         |
| **Reset Config** button | Restores default Width (150), Contrast (1.0), and Color (off).             |

## Tips & Troubleshooting

- **Performance**: Higher widths and color mode increase CPU usage. For smoother performance, reduce the width or disable color.
- **Recording Format**: Browsers may fallback to WebM if MP4 is not supported.
- **Permission Denied**: If the camera doesn’t start, check browser privacy settings to allow camera access.


## Related Projects

If you’re looking for ASCII image converters, feel free to check out the companion project: [RJTPP/ascii-pic](https://github.com/rjtpp/ascii-pic)

## License

This project is released under the [MIT License](LICENSE).

You are free to use, modify, and distribute this software under the terms of the MIT License. See the LICENSE file for detailed terms and conditions.



