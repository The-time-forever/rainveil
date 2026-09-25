# Rainveil — development notes

## Official references

- [Submit your theme](https://docs.obsidian.md/themes/app-themes/submit-theme)
- [Manifest](https://docs.obsidian.md/Reference/Manifest)
- [Set up and claim](https://docs.obsidian.md/community-directory/set-up-and-claim)
- [Developer policies](https://docs.obsidian.md/community-directory/developer-policies)
- [Theme self-critique](https://docs.obsidian.md/oo/theme)

## Release preparation

- Theme name: Rainveil.
- Author: YiXuan Xu (from the authenticated GitHub profile).
- License: MIT.
- Version: 1.0.0.
- Supported mode: Light.
- Screenshot: deferred as requested; recommended size is 512 × 288 px.
- Obsidian UI testing: deferred as requested.
- Minimum app version: 1.0.0 in this draft; confirm against the oldest supported Obsidian version before a directory submission.

## CSS review notes

- CSS braces are balanced (51 opening and 51 closing).
- No `!important` declarations or remote asset URLs found.
- Two `:has()` selectors remain. The official self-critique recommends avoiding `:has()` unless necessary because it can affect performance, especially in Canvas.
- The stylesheet includes `backdrop-filter` and a `prefers-reduced-transparency` fallback.
- This is a light-only theme; submit with Light mode selected.

## Before submitting to the Community Directory

1. Add a current screenshot from Obsidian.
2. Test Reading view, Live Preview, Canvas, menus, modals, settings, narrow layouts, and mobile behavior.
3. Confirm the minimum app version.
4. Update the version and create a matching GitHub Release, attaching `manifest.json` and `theme.css`.
5. Connect the GitHub account on the Community Directory, submit the repository and screenshot path, then address automated review feedback.
