# Tag Navigator - Obsidian Plugin

[English](README.md) | [中文](README_zh-CN.md)

An enhanced tag navigation and search utility for Obsidian, providing smarter tag management experience.

## Features

### 🚀 Smart Tag Navigation
- **Frequency-based sorting**: Tags are sorted by usage frequency in descending order, making it easy to find commonly used tags
- **Intelligent navigation**: 
  - If a tag note exists (matched via frontmatter aliases), directly open that note
  - If only one note contains the tag, directly open that note
  - If multiple notes contain the tag, display a selection list for user choice

### 🔍 Convenient Search Integration
- Provides a search button in the tag file chooser to quickly insert tags into global search
- Supports keyboard shortcuts (Ctrl/Cmd + Enter or Shift + Enter)

### 🎯 User-Friendly Interface
- Fuzzy search suggestion mode
- Responsive design that adapts to different screen sizes
- Intuitive icons and tooltips

## Installation

### Via Obsidian Community Plugins
1. Open Obsidian Settings
2. Go to "Community plugins" tab
3. Click "Browse" and search for "Tag Navigator"
4. Click "Install" when you find the plugin
5. Enable the plugin after installation

### Manual Installation
1. Download the latest version from Releases page
2. Extract the files to your Obsidian vault's `.obsidian/plugins/tag-navigator/` directory
3. Reload Obsidian and enable Tag Navigator in community plugins

## Usage

### Basic Usage
1. Open tag search using keyboard shortcut or command palette
2. Enter tag name to search
3. After selecting a tag:
   - If a corresponding tag note exists, it opens directly
   - If only one matching note exists, it opens directly
   - If multiple matching notes exist, a selection list is displayed

### Keyboard Shortcuts
- **Ctrl/Cmd + Enter** or **Shift + Enter**: Quickly select the first suggestion

### Command Palette
- Type "Open tag search" to open the tag search interface

## Configuration

Currently, the plugin requires no additional configuration and works out of the box.

## Tag Notes Feature

To use the tag notes feature, create a note and add aliases in the frontmatter:

```yaml
---
aliases: ["#yourtag", "yourtag"]
---
```

When searching for this tag, the plugin will prioritize opening this tag note.

## Development Information

### Tech Stack
- TypeScript
- Obsidian API

### Build
```bash
npm install
npm run build
```

### Contributing
Issues and Pull Requests are welcome!

## License

MIT License - See [LICENSE](LICENSE) file for details

## Changelog

### v1.0.0
- Initial release
- Basic tag navigation functionality
- Intelligent navigation logic
- Search integration feature

## Support

If you encounter issues or have suggestions, please contact via:
- Submit an [Issue](https://github.com/EarthTan/tag-navigator/issues) on GitHub repository
- Email the author

---

**Enjoy a smarter tag navigation experience!** 🎉
