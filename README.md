---

<hr>

<div align="center">

<h1 align="center">Tabla Drop Beat Visualization</h1>

</div>

<pre align="center">A visualization of tabla beats using HTML5 Canvas in English and Hindi.</pre>

[![Best Practices](https://img.shields.io/badge/Best%20Practices%20from-SLIM-blue)](https://nasa-ammos.github.io/slim/)

![Sample](sample-vid.gif)

This project provides a simple visualization of tabla beats that flow like raindrops across the screen. Designed for music enthusiasts and creative coders, this visualization is fully customizable and easy to set up.

## Features

- Visual representation of tabla beats
- Customizable tabla characters, font size, and colors
- Responsive full-screen visualization
- Dynamic color changes for each beat
- Logo that randomly appears and fades away
- Lightweight and no extra JS frameworks involved - single HTML page app with a CSS file

## Contents

- [Quick Start](#quick-start)
- [Changelog](#changelog)
- [FAQ](#frequently-asked-questions-faq)
- [Contributing Guide](#contributing)
- [License](#license)
- [Support](#support)

## Quick Start

This guide provides a quick way to get started with the Tabla Drop Beat Visualization.

### Requirements

1. A modern web browser (e.g., Chrome, Firefox, Edge, Safari)
2. Basic HTML and CSS files (included in this repository)

### Setup Instructions

1. Clone or download this repository to your local machine.
2. Ensure the HTML file and CSS file are in the same directory.
3. Place your desired logo image in the same directory and update the HTML to point to its path.
4. Open the `index.html` file in your web browser.

### Run Instructions

1. Double-click the `index.html` file to open it in your browser.
2. The visualization will start immediately.
3. Enjoy the flowing tabla beat visuals and watch the logo randomly appear and fade.

### Usage Examples

- Replace the `tabla_boles` configuration in the HTML file to display different characters.
- Adjust the `font_size` variable to change the size of the tabla characters.
- Modify the CSS file to customize the background color and other styling.
- Update the `logo.png` path to use a custom logo image.

### Build Instructions (if applicable)

No build process is required. This project is ready to use out-of-the-box.

### Test Instructions (if applicable)

1. Verify that the `index.html` file opens correctly in a browser.
2. Customize the configuration variables in the HTML file and reload the page to see the changes.
3. Test the logo visibility by observing its appearance every 10 seconds.
4. Test on multiple browsers to ensure compatibility.

## Frequently Asked Questions (FAQ)

1. **How do I change the tabla characters?**
   - Open the HTML file and update the `tabla_boles` variable in the JavaScript section.
2. **How do I adjust the speed of the animation?**
   - Modify the `setInterval` function controlling the `draw` method. Lower values increase speed.
3. **How do I replace the logo?**
   - Place your logo image in the project directory and update the `<img>` tag's `src` attribute to the correct path.
4. **How do I change the logo fade duration?**
   - Update the `setTimeout` function inside the `randomPositionLogo` method to modify the fade-out time.

## Contributing

1. Fork this repository.
2. Create a new branch for your changes.
3. Submit a pull request with your modifications.

## License

See our [LICENSE](LICENSE) for license information.

## Support

For questions or support, contact the maintainers:

- [@riverma](https://github.com/riverma)
