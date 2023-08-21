<div align='center'>
<img src="https://github.com/DaBluLite/Cyan/blob/master/cyan-addon-banner.png?raw=true"/>
</div>

# Cyan - Clean and Customizable, with custom background support

[![BetterDiscord][bd-badge]][bd-link] [![Cyan Customizer][cc-badge]][cc-link] [![Cyan Addons][addon-badge]][addon-link] [![Cyan+][helper-badge]][helper-link]

[bd-link]: https://betterdiscord.app/theme/Cyan
[bd-badge]: https://img.shields.io/badge/Cyan-Download%20On%20BetterDiscord-3a71c1?labelColor=0c0d10&color=009f88&style=for-the-badge

[cc-link]: https://dablulite.github.io/Cyan
[cc-badge]: https://img.shields.io/badge/Customize%20With%20Cyan%20Customizer-3a71c1?labelColor=0c0d10&color=009f88&style=for-the-badge

[addon-link]: https://dablulite.github.io/Cyan/Addons
[addon-badge]: https://img.shields.io/badge/Addons%20For%20Cyan-Download-3a71c1?labelColor=0c0d10&color=009f88&style=for-the-badge

[helper-link]: https://dablulite.github.io/Cyan/CyanPlus.plugin.js
[helper-badge]: https://img.shields.io/badge/Cyan+-Download-3a71c1?labelColor=0c0d10&color=009f88&style=for-the-badge

# Special thanks to:
* [@ObjectiveSlayer](https://github.com/ObjectiveSlayer)/carrot#8812
* [@maenDisease](https://github.com/maenDisease)/Disease#3749 
* [@lucysim9](https://github.com/lucysim9)/lucism#3987

## [NEW] Cyan Rewrite is here! Faster and lighter than ever, Cyan is ready to be your next theme. Available only on [Vesktop](https://github.com/Vencord/Vesktop) for the time being.
### Installation:
* Donwload Cyan from any official source
* Open the `theme.css` file on any text editor
* Replace `import.css` with `remaster.css`
* In Vesktop, go to Settings > Vencord > Themes > Local Themes > Open themes folder
* Drag and drop the `theme.css` file from its current folder to Vesktop's themes folder
* Settings > Vencord > Themes > Local Themes > Load Missing Themes
* You're done! This can be done with any Cyan version, as the import fully supports *most* of Cyan's existing settings (Except text shadow, for now). This release also offers some remarkable new settings, such as:
	* `--cyan-channelbar-width`: the width of the channels/DMs list
	* `--cyan-glass-foreground`: any text in front of Cyan's glass material
 	* `--window-titlebar-size`: the extra space added at the top of the omnibar to account for the traffic lights
	* `--cyan-secondary-foreground`: any text in front of Cyan's secondary background

# Customizing:
[NEW] Presets are now in [DiscordColorways](https://raw.githubusercontent.com/DaBluLite/DiscordColorways/master/DiscordColorways.plugin.js)! Select the "Cyan" preset to easiy generate colors for Cyan.

Colors:
* Accent: `--cyan-accent-color`
* Primary: `--cyan-background-primary`
* Tertiary `--cyan-background-secondary`

Cyan uses the following values to change the way it looks:
```css
:root {
	--cyan-background-primary: hsla(0deg 0% var(--cyan-background-lightness) / 40%); /*The "glass" color*/
	--cyan-elevation-shadow: 0 0 0 1.5px var(--cyan-accent-color), 0 2px 10px 0 rgb(0 0 0 / 60%); /*The border/shadow*/
	--cyan-font: 'Montserrat', 'Open Sans'; /*The main fonts*/
	--cyan-background-img: url(https://dablulite.github.io/Cyan/cyan-waves.png); /*The Background image*/
	--cyan-accent-color: #009f88; /*The accent color for various UI elements*/
	--cyan-blur-radius: 10px; /*How blurry blurry surfaces should be*/
	--cyan-text-shadow: 1; /*If the test shadow should be on or off (1 or 0 is true or false)*/
	--window-margin: 8; /*The margins around the windows*/
	--window-border-radius: 8px; /*Their border radii*/
}
```

# Screenshots
<div align='center'>
<img src="https://github.com/DaBluLite/Cyan/blob/master/screenshots/cyan-screenshot-1.png?raw=true"/>
</div>
<div align='center'>
<img src="https://github.com/DaBluLite/Cyan/blob/master/screenshots/cyan-screenshot-2.png?raw=true"/>
</div>
<div align='center'>
<img src="https://github.com/DaBluLite/Cyan/blob/master/screenshots/cyan-screenshot-3.png?raw=true"/>
</div>
<div align='center'>
<img src="https://github.com/DaBluLite/Cyan/blob/master/screenshots/cyan-screenshot-4.png?raw=true"/>
</div>
