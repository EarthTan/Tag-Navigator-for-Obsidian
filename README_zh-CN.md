# Tag Navigator - Obsidian 标签导航器

[English](README.md) | [中文](README_zh-CN.md)

一个增强的标签导航和搜索工具，为 Obsidian 提供更智能的标签管理体验。

## 功能特性

### 🚀 智能标签导航
- **按频率排序**: 标签按使用频率降序排列，快速找到常用标签
- **智能跳转**: 
  - 如果存在标签笔记（通过 frontmatter aliases 匹配），直接打开该笔记
  - 如果只有一个笔记包含该标签，直接打开该笔记
  - 如果多个笔记包含该标签，显示选择列表供用户选择

### 🔍 便捷搜索集成
- 在标签文件选择器中提供搜索按钮，可将标签快速填入全局搜索
- 支持快捷键操作（Ctrl/Cmd + Enter 或 Shift + Enter）

### 🎯 用户友好界面
- 模糊搜索建议模式
- 响应式设计，适配不同屏幕尺寸
- 直观的图标和提示

## 安装方法

### 通过 Obsidian 社区插件市场
1. 打开 Obsidian 设置
2. 进入「第三方插件」选项卡
3. 点击「浏览」并搜索 "Tag Navigator"
4. 找到插件后点击「安装」
5. 安装完成后启用插件

### 手动安装
1. 从 Releases 页面下载最新版本
2. 将文件解压到你的 Obsidian 库的 `.obsidian/plugins/tag-navigator/` 目录
3. 重新加载 Obsidian 并在第三方插件中启用 Tag Navigator

## 使用方法

### 基本使用
1. 使用快捷键或命令面板打开标签搜索
2. 输入标签名称进行搜索
3. 选择标签后：
   - 如果存在对应的标签笔记，直接打开
   - 如果只有一个匹配的笔记，直接打开
   - 如果有多个匹配的笔记，显示选择列表

### 快捷键
- **Ctrl/Cmd + Enter** 或 **Shift + Enter**: 快速选择第一个建议项

### 命令面板
- 输入 "Open tag search" 打开标签搜索界面

## 配置

目前插件无需额外配置，开箱即用。

## 标签笔记功能

要使用标签笔记功能，请创建一个笔记并在 frontmatter 中添加 aliases：

```yaml
---
aliases: ["#你的标签", "你的标签"]
---
```

这样当搜索该标签时，插件会优先打开这个标签笔记。

## 开发信息

### 技术栈
- TypeScript
- Obsidian API

### 构建
```bash
npm install
npm run build
```

### 贡献
欢迎提交 Issue 和 Pull Request！

## 许可证

MIT License - 详见 [LICENSE](LICENSE) 文件

## 更新日志

### v1.0.0
- 初始版本发布
- 基础标签导航功能
- 智能跳转逻辑
- 搜索集成功能

## 支持

如果您遇到问题或有建议，请通过以下方式联系：
- 在 GitHub 仓库提交 [Issue](https://github.com/EarthTan/tag-navigator/issues)
- 发送邮件至作者

---

**享受更智能的标签导航体验！** 🎉
