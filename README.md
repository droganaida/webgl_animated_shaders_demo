# WebGL Shaders Demo

## Overview
This demo showcases a dynamic visual effect using native JavaScript and WebGL without any external libraries. It features multiple shaders and framebuffers to create an animated effect and integrate an image from external source. The demo is designed to be a practical example for those interested in learning about WebGL shaders.
Live preview: https://droganaida.github.io/webgl_animated_shaders_demo/

## Features
- Pure JavaScript and WebGL implementation.
- No external libraries used.
- Multiple framebuffers for complex effects.
- Image integration.
- Dynamic resizing to fit the browser window.
- Animated shader effects.

## Running the Demo
To run this demo, you can clone the repository and open the HTML file in a browser. However, due to browser security restrictions, you might encounter a security error (`Uncaught DOMException: The operation is insecure.`) if you open the HTML file directly from the file system.

To avoid this issue, you can use a local server. Here's how you can do it using Python:

1. Navigate to the directory containing your project files.
2. Run a local server:
   - If you have Python 3.x installed, use: `python -m http.server`
   - If you have Python 2.x installed, use: `python -m SimpleHTTPServer`
3. Open your browser and go to `http://localhost:8000`.
4. Open the HTML file from the list of files served by the local server.

## Inspiration
This demo is inspired by the fascinating world of shaders and is a great starting point for those who are curious about creating their own. If you're interested in more intricate shader effects, check out my own texture generator - the "Magic Kaleidoscope" available on Steam. It comes with a free demo and is a fantastic resource for shader enthusiasts. [Magic Kaleidoscope on Steam](https://store.steampowered.com/app/2449130/Magic_Kaleidoscope/)

## Contributing
Feel free to fork this repository and experiment with the shaders. Contributions, suggestions, and improvements are welcome.

## License
This project is open source and available under the [MIT License](LICENSE).
