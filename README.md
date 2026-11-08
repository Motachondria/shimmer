# Shimmer Tab for Firefox

**A beautiful, customizable new-tab experience for Mozilla Firefox.**

An unofficial Firefox adaptation of [Shimmer Tab](https://github.com/dmitthedazed/shimmer-tab), originally developed by **[@dmitthedazed](https://github.com/dmitthedazed)** for the Helium browser.

This repository contains a Firefox-compatible adaptation of the original browser extension, with changes intended to make it work with Mozilla Firefox.

## Features

Shimmer Tab transforms your new-tab page into a customizable starting point with wallpapers, shortcuts, search and useful widgets.

Features inherited from the original project include:

### Wallpapers and Appearance
- Animated Shimmer wallpapers.
- Starfield backgrounds with cursor parallax.
- Live sky wallpapers that respond to weather and time of day.
- Use your own pictures and GIFs.
- Automatically rotate wallpapers on each new tab, hourly, daily or never.
- Adjust wallpaper blur, dimming and appearance.

### Search and Navigation
- Search bangs with autocomplete.
- Search shortcuts such as `!yt`, `!w` and more.
- Start searching directly from the new-tab page.

### Custom Shortcuts
- High-quality vector logos for hundreds of services.
- Automatic website icons where available.
- Organize shortcuts into containers.
- Drag and reorder shortcuts.
- Customize shortcut names and colours.

### Widgets
- Most visited websites.
- Recently closed tabs.
- Date and time.
- Weather information.
- Quick mathematical answers and unit conversions through the search bar.

### Personalization
- Time-based greetings.
- Focus mode.
- Left, center and right layouts.
- Light and dark appearance.
- Customizable browser-inspired colours.
- Performance settings: Speed, Balanced and Beauty.
- Simple and advanced settings.
- Undo removed wallpapers, shortcuts, folders and resets.
- Settings export and import.

**Note:** These features originate from the upstream project. Their availability and behaviour may vary in this Firefox adaptation, particularly where the original implementation depends on Helium or Chromium-specific APIs.

## Installation

### Mozilla Firefox

1. Download the firefox zip from the Releases section and extract it to your desired location.
2. Go to `about:config`, paste this in the search bar: `xpinstall.signatures.required`, and toggle it to "false"
3. Go to `about:addons` and click on the **gear** icon and click `Install Add-on from file`
4. Navigate to the extracted folder directory.
5. Select the extracted folder.


## Original Project

This project is based on:

**Shimmer Tab**

Original developer: [@dmitthedazed](https://github.com/dmitthedazed)

Original repository: https://github.com/dmitthedazed/shimmer-tab

Original project documentation: https://github.com/dmitthedazed/shimmer-tab#readme

This repository is an unofficial Firefox adaptation. It is not the original project and is not affiliated with the original developer or the Helium browser project.

## Credits and Acknowledgements

Full credit goes to the original developer and the projects that made Shimmer Tab possible.

The original project acknowledges:

- **[@dmitthedazed](https://github.com/dmitthedazed)** — Original Shimmer Tab project.
- **[Helium Prism](https://github.com/)** — UI components used by the original project.
- **[ErrorZeros' Helium New Tab](https://github.com/ErrorZeros)** — Inspiration for the starfield.
- **[exsesx/helium-new-tab](https://github.com/exsesx/helium-new-tab)** — Bang resolver.
- **Kagi Search and imput** — Bang catalog.
- **[svgl](https://svgl.app/)** — Vector service logos.
- **[Open-Meteo](https://open-meteo.com/)** — Weather data.
- **Atmosphere** — Sky rendering.

Additional third-party license notices are preserved in the project's `LICENSE` and `licenses/` files.

## Privacy

The original Shimmer Tab project states that it does not use accounts, analytics, advertisements or its own server.

Its documented third-party connections include weather services, logo providers and search/suggestion services.

This Firefox adaptation should be evaluated using its own source code, manifest permissions and network requests. Refer to the [original privacy policy](https://github.com/dmitthedazed/shimmer-tab/blob/main/PRIVACY.md) for the upstream project's documented data practices.

## Contributions and modifications:-

Contributions and modifications should comply with the project's GPL-3.0 license.


## License

This project is distributed under the **GNU General Public License v3.0 (GPL-3.0)**, following the original Shimmer Tab project.

See the `LICENSE` file and `licenses/` directory for the full license texts and third-party notices.

---

**Original project:** [dmitthedazed/shimmer-tab](https://github.com/dmitthedazed/shimmer-tab)

**Firefox adaptation:** [@Motachondria](https://github.com/Motachondria)

**License:** GNU GPL-3.0
