# Zia Media Player

Standalone extraction from [Zia](https://github.com/z1n-k/zia), MIT licensed.

Play media in a tab, then hover the player to reveal the timeline and additional controls. Artwork, metadata, seeking and picture-in-picture depend on the site and Zen support.

## Install

Requires Zen Browser and [Sine](https://github.com/CosmoCreeper/Sine). This includes JavaScript and cannot run as a CSS-only Zen store mod.

1. In Zen Settings → Sine Mods, enable installing JavaScript from unofficial sources.
2. Enter `natsufatsu/zia-media-player` in Sine's install box.
3. Disable the original full Zia mod, then restart Zen. The two extracted mods can run together or separately.

Restart after enabling, disabling or updating these JavaScript mods. If necessary, clear the startup cache in `about:support`.

The ZIP is a repository-ready package; it is not a Firefox extension/XPI. Repository: https://github.com/natsufatsu/zia-media-player

## 1.0.6

Open Zen Settings → Sine Mods → Zia Media Player's settings button to adjust collapsed and expanded background opacity independently from 0 to 100. Changes apply immediately, with defaults of 40% collapsed and 90% expanded. Empty or invalid values use the default; out-of-range values are clamped. Zen's native mute indicator is preserved. Player backgrounds follow the media tab's workspace color and fade smoothly over 300 ms. Bright colors are darkened for readable controls. Background opacity is 40% collapsed and 90% expanded, without fading the text or controls. Artwork glow is preserved and reduced-motion preferences are respected.

Update the mod in Sine and restart Zen to apply this version.

## Validation

JavaScript syntax and package dependencies checked locally. Live Zen interaction and visual checks are still required, especially on Windows and Linux.
