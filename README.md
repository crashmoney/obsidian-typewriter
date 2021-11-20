# Obsidian Typewriter

Typewriter is an [Obsidian](https://www.obsidian.md) theme designed for a focused writing experience.

![cover](cover.jpg)

## Features
- Careful choice in fonts; monospace in the editor and semi-proportional in preview and UI
- Fonts have been base64 encoded, meaning you don't need to install them to use Typewriter
  - This also means that the fonts used here are available on mobile
- Vim cursor support
- Cool dark mode and warm light mode
- Compatibility with community plugins (see [Plugin Compatibility](https://github.com/crashmoney/obsidian-typewriter/new/main?readme=1#recommended-plugins))
- Compatibility with Obsidian Hub
- Multicolored highlights support (achieved through the use of inline color classes)
  - To use the multicolored highlights, use `<text class=orange>This is some orange text</text>`
  - *Current colors supported: green, orange*
- Clean PDF export without link colors (achieved through YAML header `cssclass: nolink`)
- Focus on the active line

## Recommended Plugins
- [Typewriter Scroll by @death_au](https://github.com/deathau/cm-typewriter-scroll-obsidian) for the full typewriter experience
  - This plugin comes also with a focus mode, which dims every line except the active one

## Plugin Compatability
*This list is non-exhaustive; other plugins I haven't tested yet may work. The plugins on this list are plugins I've tested or added specific support for.*

- [Calendar by @liamcain](https://github.com/liamcain/obsidian-calendar-plugin)
- [Sliding Panes (Andy's Mode) by @death_au](https://github.com/deathau/sliding-panes-obsidian)
- [Kanban by @mgmeyers](https://github.com/mgmeyers/obsidian-kanban)

## Development
This theme is currently under development. Issues and pull requests are welcome.

Please see [CHANGELOG.md](CHANGELOG.md) for new features. Descriptions are also available under Releases.

## Installation

### Recommended
> Typewriter is not yet available on the Obsidian theme store.

Installing from the Obsidian theme store, found in `Settings > Appearance > Themes > Manage`.

### Manual
You can also manually install this theme.

1. Download `obsidian.css`
2. Rename the file to `Typewriter.css`
3. Move the file to your vault's theme directory
	- Navigate to your vault's hidden `.obsidian/themes` folder
	- Place `Typewriter.css` inside that folder

## Credits
Inspiration and some code were taken from the following themes:

- [Minimal by @kepano](https://github.com/kepano/obsidian-minimal)
- [Yin and Yang by @chetachiezikeuzor](https://github.com/chetachiezikeuzor/Yin-and-Yang-Theme)
- [Deep Work by @nikbrunner](https://github.com/nikbrunner/obsidian-deep-work-theme)
- the Scrivener theme A Midsummer Night for the colors behind Typewriter's dark mode

### Fonts
This theme uses the fonts iA Writer Mono V, iA Writer Quattro V and JetBrains Mono. These fonts have been base64 encoded into the theme CSS, meaning that you don't have to install them and that they are available on mobile. If you want to, however, the links are below:

- [iA Writer Fonts (GitHub)](https://github.com/iaolo/iA-Fonts)
- [JetBrains Mono (Google Fonts)](https://fonts.google.com/specimen/JetBrains+Mono#standard-styles)
