<p align="center"><img src="https://raw.githubusercontent.com/Vioneta/vioneta-graphite-theme/main/docs/logo_s.svg" width="240" alt="Logo Graphite Theme"/></p>
<h3 align="center">Graphite Theme for Vioneta</h3>
<p align="center">
	<img src="https://img.shields.io/badge/VPS-default-blue?colorA=1F2229&colorB=5c5e70&style=for-the-badge">
	<a href="https://github.com/Vioneta/vioneta-graphite-theme/stargazers"><img src="https://img.shields.io/github/stars/Vioneta/vioneta-graphite-theme?colorA=1F2229&colorB=5c5e70&style=for-the-badge"></a>
	<a href="https://github.com/Vioneta/vioneta-graphite-theme/issues"><img src="https://img.shields.io/github/issues/Vioneta/vioneta-graphite-theme?colorA=1F2229&colorB=5c5e70&style=for-the-badge"></a>
</p>

<p align="center"><img src="https://raw.githubusercontent.com/Vioneta/vioneta-graphite-theme/main/docs/screenshots/main.png"/><br/></p>

**Graphite** is a contemporary theme that features both a calming dark color scheme and a bright, clean light theme. It features native device fonts and a cohesive design language across all Vioneta interfaces, including the administration interface and code editors.

## Installation

<details>
<summary>Vioneta Plugins Store Guide</summary>

### Installation

The [Vioneta Plugins Store](https://vps.vioneta.com), or VPS, is the most convenient and efficient way to install the Graphite theme. VPS acts as a one-stop shop for community-developed extensions for Vioneta, similar to the Apple App Store or Google Play Store. With just a few clicks, you can easily find and install the Graphite theme within VPS.

### Guideline

1. Ensure you have [VPS installed](https://vps.vioneta.com/docs/setup/download).
1. Open the Vioneta Plugins Store (VPS) by clicking on the `VPS` tab in the side menu.
1. In the VPS store, click on the `Frontend` tab.
1. On the bottom right, click on `Explore & Download Repositories` and use the search bar to search for `Graphite`.
1. Click on the `Graphite` theme in the search results to open the theme's page.
1. On the theme's page, click on the `Download` button.
1. Wait for the installation to complete. This may take a few seconds.
1. Once the installation is complete, open your profile and select `Graphite` in your `Theme` dropdown menu.

That's it! The Graphite theme has been successfully installed and applied to your Vioneta instance. You will receive notifications in the Vioneta Plugins Store (VPS) whenever an update is available for the theme, so you can keep it up to date with the latest improvements and tweaks.

</details>

<details>
<summary>Manual Guide</summary>

### Manual Guide

1. Copy the `themes` folder into your home-assistant config folder
1. Set the theme folder in you `configuration.yaml`

```yaml
frontend:
  themes: !include_dir_merge_named themes
```

3. Restart Vioneta
4. Select the `Graphite` theme in your profile
</details>

## Examples

If you're curious about the cards from screenshot, you can [check out examples](https://github.com/Vioneta/vioneta-graphite-theme/blob/main/examples/README.md).

## Updating the theme

I've developed a small token abstraction and a script to maintain Graphite's integrity across theme variants and streamline updates. The source components are located in the `src` folder. After making modifications, run the `theme_assembler` Python 3 script found in the `tools` directory to update theme files. Please do not modify the artifacts in the `themes` directory manually. Feel free to use this as a foundation for crafting your own themes in minutes.
