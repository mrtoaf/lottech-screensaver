# Lottech Screensaver

A simple, customizable website that simulates the classic DVD screensaver bounce effect using your own logo. Built with plain HTML, CSS, and JavaScript.

## What is this?

Inspired by the classic DVD Video logo screensaver that bounces around the screen and changes coloe. The LotTech logo bounces around the screen, changing direction and optionally color when it hits the edges.

### Local Development

To run locally:
1. Clone this repository
2. Open the directory in a terminal
3. Start a local server (e.g., `python -m http.server`)
4. Open `http://localhost:8000` in your browser

## URL Parameters

Customize the screensaver with these URL parameters:
* `logo` - Link to a custom logo in SVG format
* `initialColor` - Starting color of the logo (default: white)
* `randomizeColor` - Set to "false" or "0" to keep a constant color
* `speed` - Movement speed of the logo (default: 0.8)

Example: `?logo=./logos/custom.svg&initialColor=red&speed=1.2`

## Using as an Actual Screensaver

### macOS
Use WebViewScreenSaver, SaverLab, or another tool that can display web content as a screensaver.

## License
This project is licensed under the MIT License - see the [`LICENSE.txt`](LICENSE.txt) file for details.