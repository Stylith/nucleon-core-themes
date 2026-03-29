# Nucleon Core Themes

Community and first-party theme components for [nucleon-core](https://github.com/Stylith/nucleon-core).

## Directory Structure

```
packs/              Global theme packs (bundle all components)
desktop/            Desktop styles (DesktopStyleManifest)
terminal/           Terminal themes (TerminalThemeManifest)
colors/             Color themes (ColorThemeManifest)
icons/              Icon packs (IconPackManifest)
sounds/             Sound packs (SoundPackManifest)
cursors/            Cursor packs (CursorPackManifest)
fonts/              Font packs (FontPackManifest)
```

Each component lives in its own subdirectory with a `manifest.json`.

## Installation

Components can be installed through the Addons app in Nucleon, or manually by copying the component directory into `{state_dir}/themes/{type}/`.
