<div align="center">

<img src="glasshome/logo.png" alt="GlassHome" width="360">

### A beautiful, local-first dashboard for Home Assistant

No YAML. No cloud relay. No clutter. Just your home, room by room.

[**Website**](https://glasshome.app) · [**Live Demo**](https://demo.glasshome.app) · [**Docs**](https://glasshome.app/docs) · [**Discord**](https://discord.gg/FJYdeDmrzv)

[![Add repository to my Home Assistant](https://my.home-assistant.io/badges/supervisor_add_addon_repository.svg)](https://my.home-assistant.io/redirect/supervisor_add_addon_repository/?repository_url=https%3A%2F%2Fgithub.com%2Fglasshome%2Fhomeassistant-addon)

</div>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://glasshome.app/assets/screenshots/home-midnight-glass-dark-desktop.webp">
  <img alt="GlassHome dashboard, Midnight Glass theme" src="https://glasshome.app/assets/screenshots/home-midnight-glass-light-desktop.webp">
</picture>

## What is GlassHome?

GlassHome is a modern dashboard that sits in front of your Home Assistant. It connects directly to your HA instance over WebSocket and runs entirely on your own hardware.

- **Feels like a premium app, not a config panel.** Rounded, layered, touch-first design that anyone in the household can use.
- **Drag, drop, resize.** Build your dashboard in the UI. No YAML, no restart-to-apply.
- **Room by room.** Widgets organize around your areas: lights, climate, sensors, cameras, weather, scenes, and more.
- **Make it yours.** Seven built-in themes with full light and dark modes, plus a custom theme editor.
- **Community widgets.** Install widgets built by others, or build your own with the [Widget SDK](https://glasshome.app/docs/widget-development).
- **Private by design.** No cloud relay, no telemetry. Your Home Assistant data never leaves your network.

Want to see it first? Open the [live demo](https://demo.glasshome.app) in your browser, no install needed.

## See it in action

Build your dashboard by dragging, dropping, and resizing widgets, straight from the UI:

![Dragging and rearranging widgets](https://glasshome.app/assets/screenshots/widget-drag-dark.gif)

Pick from seven built-in themes, each with light and dark modes:

| Coral Reef | Forest Zen | Lavender Dreams |
| --- | --- | --- |
| ![Coral Reef theme](https://glasshome.app/assets/screenshots/home-coral-reef-dark-desktop.webp) | ![Forest Zen theme](https://glasshome.app/assets/screenshots/home-forest-zen-dark-desktop.webp) | ![Lavender Dreams theme](https://glasshome.app/assets/screenshots/home-lavender-dreams-dark-desktop.webp) |

Made for the wall tablet as much as the desktop:

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://glasshome.app/assets/screenshots/tablet-wall-midnight-glass-dark.webp">
  <img alt="GlassHome on a wall-mounted tablet" src="https://glasshome.app/assets/screenshots/tablet-wall-midnight-glass-light.webp">
</picture>

## Add-ons in this repository

| Add-on | Channel | Port | Who it's for |
| --- | --- | --- | --- |
| [GlassHome Dashboard](./glasshome/) | Stable | 3123 | Daily use. Install this one. |
| [GlassHome Dashboard (Edge)](./glasshome-edge/) | Edge | 3124 | Early builds for testing. Requires Advanced Mode. Runs side by side with stable. |

## Installation

1. Click the button above, or add this repository manually in Home Assistant:
   **Settings → Add-ons → Add-on Store → ⋮ → Repositories** and paste:

   ```
   https://github.com/glasshome/homeassistant-addon
   ```

2. Install **GlassHome Dashboard** from the store and start it.

3. Open `http://homeassistant.local:3123` (or `http://YOUR_HA_IP:3123`) and follow the [quickstart](https://glasshome.app/docs/quickstart).

Not on the Home Assistant OS? GlassHome also runs as a [standalone Docker container](https://glasshome.app/docs/docker).

## What GlassHome is not

- **Not a replacement for Home Assistant.** HA still runs your automations, integrations, and devices. GlassHome is the UI layer in front of it.
- **Not a cloud service.** GlassHome runs on your hardware and talks to HA locally.

## Community and support

- [Discord](https://discord.gg/FJYdeDmrzv): live help, feature requests, and bug reports.
- [Documentation](https://glasshome.app/docs): quickstart, concepts, troubleshooting.
- [Changelog](https://glasshome.app/docs/changelog): what's new in each release.

GlassHome is built by [GlassHome Labs](https://glasshome.app). The dashboard source lives at [glasshome/dash](https://github.com/glasshome/dash).
