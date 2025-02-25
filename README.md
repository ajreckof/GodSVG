# GodSVG

GodSVG is an application in extremely early development built with Godot for creating optimal Scalable Vector Graphics (SVG) files. It is specifically designed for programmers, allowing them to easily edit individual SVG elements and view the corresponding code in real-time.
GodSVG is inspired by the need for an editor for programmers that produces optimized SVG without using unnecessary attributes or metadata.

## Features

- Interactive SVG editing: Modify individual elements of an SVG file using a simple interface.
- Real-time code preview: Instantly view the SVG code as you make changes to the elements.
- Optimized SVG output: Generate clean and efficient SVG files.

| Name | Support level | Notes |
| --- | --- | --- |
| circle | Supported | |
| clipPath | Not yet supported | Probably never, will evaluate later |
| ellipse | Supported | |
| g | Not yet supported | |
| line | Not yet supported | May not support directly |
| linearGradient | Not yet supported | |
| mask | Not yet supported | |
| path | Supported | |
| polygon | Not yet supported | May not support directly |
| polyline | Not yet supported | May not support directly |
| radialGradient | Not yet supported | |
| rect | Supported | |
| stop | Not yet supported | |

All other elements are currently not planned.

## Installation

Currently, there are no pre-built binaries available for GodSVG. However, you can still run it by following these steps:

1. Clone the repository: `git clone https://github.com/mew-pur-pur/GodSVG.git`
2. Open the project in the Godot Engine.
3. Build and run the project within the Godot Engine editor.

## Contributing

Contributions to GodSVG are very welcome! To do so, do the following:

1. Fork the repository.
2. Create a new branch: `git checkout -b implement-gradients`
3. Make your modifications.
4. Commit your changes: `git commit -m "Implement linear gradients"`
5. Push to the branch: `git push origin implement-gradients`
6. Create a new pull request and describe your changes in detail.

Since the app is in early development, tidiness is not of utmost importance, so feel free to use a different PR workflow (but the above is still preferable).
To report bugs, use Github's issue form. If features are proposed, please provide a mock-up UI or implementation details.

## License

GodSVG is licensed under the MIT License.
