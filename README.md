# Tag Navigator - Obsidian Plugin

[English](README.md) | [中文](README_zh-CN.md)

This tools allows you to <u>**easily and quickly**</u> navigate to your note through tags 

Do you feel it hassle to search tags? The original searching  process of a tag would be like this: **open** the left bar -> **choose** the global search -> **choose** "tag" -> type your tag -> **choose** you tag in a small list -> see the results <u>all squeezed in the sidebar</u>

How inefficient and inconvenient! Let's reduce the process to 1 step, and get a more comfortable view of your results!

# Quick Start

After installing the plugin, you can bind the only command of this plugin ("open tag search") to a hotkey, for example, `alt+t`.

Press your hotkey or callout the <u>tag-navigator palette</u> through Command Palette.

Input the tag you want to navigate to, and `Enter`

- If a tag note exists (matched via frontmatter aliases), directly open that note
- If only one note contains the tag, directly open that note
- If multiple notes contain the tag, display a selection list for user choice
  - The selection palette will offer you a icon to fill the tag search expression into the global search inbox


 <img src="assets/image-20251126183819305.png" alt="image-20251126183819305" style="zoom:50%;" />

<img src="assets/image-20251126183919515.png" alt="image-20251126183919515" style="zoom:50%;" />

# Feature

### 🚀 Smart Tag Navigation
- **Frequency-based sorting**: Tags are sorted by usage frequency in descending order, making it easy to find commonly used tags
- Allows fuzzy search

### 🔍 Convenient Search Integration
- Provides a search button in the tag file chooser to quickly insert tags into global search



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

# Configuration
Currently, the plugin requires no additional configuration and works out of the box.
### Tag Notes Feature
To use the tag notes feature, create a note and add aliases in the frontmatter:

```yaml
---
aliases: ["#tagname", "abc","hahaha"]
---
```
When searching for this tag, the plugin will prioritize opening this tag note.

# Development Information
This plugin is based on the original work by R. W. Blickhan and has been modified and enhanced by Tiancheng Tan.
### Tech Stack
- JavaScript/TypeScript
- Obsidian API
### Contributing
Issues and Pull Requests are welcome!
### License
MIT License - See [LICENSE](LICENSE) file for details
### Support
If you encounter issues or have suggestions, please contact via:
- Submit an [Issue](https://github.com/EarthTan/tag-navigator/issues) on GitHub repository
- Email the author
***
**Enjoy a smarter tag navigation experience!** 🎉


## Changelog
### v1.0.0
- Initial release
- Basic tag navigation functionality
- Intelligent navigation logic
- Search integration feature

