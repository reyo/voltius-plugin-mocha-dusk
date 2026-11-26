# Mocha Dusk

A community port of Catppuccin Mocha for Voltius. Mauve highlights the active tab and controls, while Rosewater marks the terminal cursor and selection. The terminal includes all 16 normal and bright ANSI colours from [Catppuccin for Alacritty](https://github.com/catppuccin/alacritty/blob/main/catppuccin-mocha.toml).

## Install from a release

1. Download `manifest.json` and `index.js` from the [latest release](https://github.com/reyo/voltius-plugin-mocha-dusk/releases/latest).
2. Place both files in a folder named `mocha-dusk` inside the Voltius app data directory's `plugins` folder.
3. In **Settings → Plugins → Installed**, select **Scan for local plugins**.
4. Open **Settings → Appearance → Color Theme** and select **Mocha Dusk**.

See the [Voltius local plugin guide](https://docs.voltius.app/plugins/developing/#local-development) for the app data directory on your platform.

## Source and permissions

The release bundle is the repository's single ES module, `index.js`. It uses the `themes` permission to register the palette when enabled and remove it when disabled. The upstream palette is distributed under the [MIT license](LICENSE).
