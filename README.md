<h1 align="center">AnuPpuccin</h1>
<h3 align="center">Personal theme for <a href="https://obsidian.md">Obsidian</a> :3</h3><br>

<p align="center"> <img src="assets/gh-preview.webp"> </p>

## Preface
Please do note that I've made this theme for myself, and it may not fit your use cases. However, I've made most of the configuration completely optional so that the experience remains as close to vanilla if you choose to do so. Most of the in-application variables are recolored so that your custom snippets can be used easily with the theme.

<details>
<summary><h2>Installation</h2></summary>
- Grab the latest release from the <a href="https://github.com/AnubisNekhet/AnuPpuccin/releases/tag/Release">releases</a> page. <br>
- For latest commits, clone the repo to your obsidian/themes folder. <br>
<code>
git clone https://github.com/AnubisNekhet/AnuPpuccin.git
</code>
</details>

## Features

### Custom palette
<p align="center"> <img src="assets/gh-colorscheme-preview.webp"> </p>
The theme supports various palettes (5 in the base theme and even more if you use the <a href="https://github.com/AnubisNekhet/AnuPpuccin">extended colorschemes</a> snippet) which include many popular colorschemes such as Catppuccin and Dracula. These are heavily integrated into the theme as they are directly used to stylize various UI elements.

### Callouts
Anuppuccin currently supports 2 layout variants.
<p align="center"> <img src="assets/gh-layout-preview.webp"> </p>

### Rainbow folders
The theme comes with a toggleable rainbow folder snippet which color-codes your folders as per their order in the filesystem.<br>
It's great if you need to easily distinguish between folders or if you want to make your vault look a bit prettier (Both in my case :P)<br>
<p align="center"> <img src="assets/gh-rainbow-preview.webp"> </p>

#### Full rainbow theme
This snippet makes the rainbow theme apply to the first layer of the root directory, aka only direct children.<br>
You can choose if it applies to root files as well and customise the indentation border color.<br>

#### Simple rainbow theme
This snippet makes the rainbow theme apply to every folder in your filesystem, and the order is determined by the children's place in the parent folder.<br>
You can toggle if the recolor applies to the title, the collapse border, the collapse icon and you can append a small icon to the folder title as well.<br>

### Alternate tabs

<p align="center"> <img src="assets/gh-preview-tabs.webp"> </p>

### Callouts
The theme comes with a custom callout style (which can be toggled so it doesn't interfere with your own callout snippet).<br>
The snippet also includes support for using the colors of your selected palette which means that the callouts don't ever look out of place :)<br>
If you use the admonition plugin/have custom callout colors, they won't be affected by the recolor as it only targets vanilla callouts. However, you can make them use AnuPpuccin's palette to support dynamic per-palette theming.<br>
<p align="center"> <img src="assets/callout.png" style="width: 60%;"> </p>

### Simplified markdown embeds
Markdown embeds have an alternate styling with an animated variant which can be toggled globally using style settings or individually using alt names for embeds, for example: `![[embed|alt-name]]`

| Embed style | Alt name |
| ----------- | -------- |
| Static | anp-embed |
| Animated | anp-embed-animated |

<p align="center"> <img src="assets/markdown-embed.png" style="width: 60%;"> </p>

## Colorschemes used
**Note**: Colorschemes that aren't in the base theme can be used through the [extended colorschemes](https://github.com/AnubisNekhet/AnuPpuccin/blob/main/snippets/extended-colorschemes.css) snippet. <br>

| Theme | Light Mode | Dark Mode | Extra Notes |
| ----- | ---------- | --------- | ----------- |
| [Catppuccin](https://github.com/catppuccin/catppuccin) | Yes| Yes | There are 4 variants of the dark theme, namely: Frappe, Macchiato, Mocha and Mocha Old.<br>The light theme is called Latte. |
| Coffee | No | Yes | Custom colorscheme |
| [Dracula](https://github.com/dracula/dracula-theme) | No | Yes | - |
| [Gruvbox](https://github.com/morhetz/gruvbox) | Yes | Yes | - |
| [Nord](https://github.com/arcticicestudio/nord) | Yes | Yes | A custom darker variant of the dark theme is included as well. |
| [Rosé Pine](https://github.com/rose-pine/rose-pine-theme) | Yes | Yes | The second variant of the dark theme, namely Rosé Pine dawn hasn't been implemented yet. |
| [Rosebox](https://github.com/KraXen72/rosebox) | No | Yes | - |
| [Solarized](https://github.com/altercation/solarized) | Yes | Yes | - |

<details>
<summary><h3>Previews</h3></summary>
<details>
<summary><h4>Generic</h4></summary>
<h4 align="center">Dark</h4>
<img src="assets/colorschemes/generic-dark.webp"/>
<h4 align="center">AMOLED Dark</h4>
<img src="assets/colorschemes/amoled-dark.webp"/>
</details>
<summary><h4>Catppuccin</h4></summary>
<h4 align="center">Latte</h4>
<img src="assets/colorschemes/catppuccin-latte.webp"/>
<h4 align="center">Frappe</h4>
<img src="assets/colorschemes/catppuccin-frappe.webp"/>
<h4 align="center">Macchiato</h4>
<img src="assets/colorschemes/catppuccin-macchiato.webp"/>
<h4 align="center">Mocha</h4>
<img src="assets/colorschemes/catppuccin-mocha.webp"/>
<h4 align="center">Mocha Old</h4>
<img src="assets/colorschemes/catppuccin-mocha-old.webp"/>
</details>
<details>
<summary><h4>Coffee</h4></summary>
<img src="assets/colorschemes/coffee-dark.webp"/>
</details>
<details>
<summary><h4>Dracula</h4></summary>
<img src="assets/colorschemes/dracula-dark.webp"/>
</details>
<details>
<summary><h4>Gruvbox</h4></summary>
<img src="assets/colorschemes/gruvbox-light.webp"/>
<img src="assets/colorschemes/gruvbox-dark.webp"/>
</details>
<details>
<summary><h4>Nord</h4></summary>
<h4 align="center">Nord Light</h4>
<img src="assets/colorschemes/nord-light-original.webp"/>
<h4 align="center">Nord Dark</h4>
<img src="assets/colorschemes/nord-dark.webp"/>
<h4 align="center">Nord Darker (Custom Palette)</h4>
<img src="assets/colorschemes/nord-darker.webp"/>
</details>
<details>
<summary><h4>Rosebox</h4></summary>
<img src="assets/colorschemes/rosebox-dark.webp"/>
</details>
<details>
<summary><h4>Rosé Pine</h4></summary>
<h4 align="center">Rosé Pine Dawn</h4>
<img src="assets/colorschemes/rosepine-light.webp"/>
<h4 align="center">Rosé Pine</h4>
<img src="assets/colorschemes/rosepine-dark.webp"/>
</details>
<details>
<summary><h4>Solarized</h4></summary>
<img src="assets/colorschemes/solarized-light.webp"/>
<img src="assets/colorschemes/solarized-dark.webp"/>
</details>
</details>

Note: Themes are toggled via style settings, the default themes are **Latte** for light mode and **Mocha** for dark mode.

### Integrations
- Excalidraw
- Kanban
- Style Settings

### Special thanks to:
- [Chuck Harmston](https://github.com/chuckharmston) for his amazing alternate tabs snippet.

### If you like my theme:
I've made this theme primarily for my own purposes and it's completely free, but if you do like it enough to consider throwing a few coins in my hat, here's a ko-fi link.
<br>
<br>
<a href="https://ko-fi.com/AnubisNekhet">
    <img height="40px" src="https://cdn.ko-fi.com/cdn/kofi3.png?v=2" />
</a>
