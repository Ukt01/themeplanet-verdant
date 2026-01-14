# ThemePlanet - Verdant

A nature-inspired VS Code theme that brings the calming essence of forests and oceans to your coding environment. ThemePlanet - Verdant offers excellent readability with carefully crafted color palettes designed to reduce eye strain during long coding sessions.

## Features

- **Forest Night**: A dark theme inspired by deep pine forests and ocean depths
- **Morning Mist**: A light theme evoking fresh morning mist over evergreen landscapes
- **Nature-Inspired Palette**: Greens, teals, and earth tones for a soothing experience
- **Excellent Readability**: High contrast ratios and semantic color consistency
- **Comprehensive Language Support**: Optimized for TypeScript, JavaScript, JSX, JSON, Markdown, and more
- **Accessibility Focused**: Meets WCAG guidelines with distinguishable error/warning colors

## Installation

### Option 1: VS Code Marketplace (Recommended)

1. Open VS Code
2. Go to Extensions (Ctrl+Shift+X / Cmd+Shift+X)
3. Search for "Verdant"
4. Click Install

### Option 2: Manual Installation

1. Download the `.vsix` file from the [releases page](https://github.com/your-username/verdant-theme/releases)
2. In VS Code, go to Extensions (Ctrl+Shift+X / Cmd+Shift+X)
3. Click the "..." menu and select "Install from VSIX"
4. Select the downloaded `.vsix` file

## Usage

1. After installation, open the Command Palette (Ctrl+Shift+P / Cmd+Shift+P)
2. Type "Color Theme" and select "Preferences: Color Theme"
3. Choose either "Forest Night" or "Morning Mist"

## Recommended Settings

For the best experience, consider these optional settings:

```json
{
  "editor.fontLigatures": true,
  "editor.bracketPairColorization.enabled": true,
  "editor.semanticHighlighting.enabled": true,
  "workbench.iconTheme": "vs-minimal"
}
```

## Color Palette

### Forest Night (Dark)
- Background: Deep pine green (#1a2b1f)
- Foreground: Soft off-white (#e8f5e8)
- Keywords: Moss green (#6b8e6b)
- Strings: Ocean teal (#2d5a47)
- Comments: Muted green-gray (#5a7a5a)

### Morning Mist (Light)
- Background: Warm fog (#f5f7f2)
- Foreground: Deep slate (#2d3748)
- Keywords: Evergreen (#4a7c59)
- Strings: Deep teal (#1a3d2d)
- Comments: Slate gray (#718096)

## Screenshots

### Forest Night Theme
![Forest Night Theme](screenshots/forest-night.png)

*TypeScript code with Forest Night theme showing excellent syntax highlighting*

### Morning Mist Theme
![Morning Mist Theme](screenshots/morning-mist.png)

*JavaScript and JSX code with Morning Mist theme demonstrating clean readability*

### Markdown Support
![Markdown Support](screenshots/markdown.png)

*Markdown rendering with proper heading and code block styling*

## Language Support

Verdant provides optimized syntax highlighting for:

- **Web Technologies**: TypeScript, JavaScript, JSX, TSX, HTML, CSS
- **Data Formats**: JSON, XML
- **Documentation**: Markdown
- **Backend Languages**: Python, Go, C#, SQL (reasonable defaults)
- **Configuration**: YAML, TOML

## Accessibility

- All text maintains sufficient contrast ratios
- Error and warning colors are clearly distinguishable
- Comments remain readable without being too faint
- Selection and cursor are highly visible

## Contributing

Found a bug or have a suggestion? Please [open an issue](https://github.com/your-username/verdant-theme/issues) on GitHub.

### Development

1. Clone the repository
2. Make changes to the theme files in `/themes/`
3. Test locally: `code --install-extension verdant-theme-1.0.0.vsix`
4. Submit a pull request

## Changelog

### v1.0.0
- Initial release with Forest Night and Morning Mist themes
- Comprehensive syntax highlighting for major languages
- Terminal ANSI color support
- Git decoration colors

## License

MIT License - see [LICENSE](LICENSE) file for details.

## Credits

Inspired by the calming beauty of nature and designed for developers who value both aesthetics and functionality.

---

**Enjoy coding in harmony with nature! 🌲🌊**
