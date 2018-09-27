# Wp HyperMD

[![GitHub issues](https://img.shields.io/github/issues/jack9603301/Wp-Next-MD.Editor.svg)](https://github.com/JaxsonWang/Wp-Next-MD.Editor/issues)
[![GitHub forks](https://img.shields.io/github/forks/jack9603301/Wp-Next-MD.Editor.svg)](https://github.com/JaxsonWang/Wp-Next-MD.Editor/network)
[![GitHub stars](https://img.shields.io/github/stars/jack9603301/Wp-Next-MD.Editor.svg)](https://github.com/JaxsonWang/Wp-Next-MD.Editor/stargazers)
[![GitHub license](https://img.shields.io/github/license/jack9603301/Wp-Next-MD.Editor.svg)](https://github.com/JaxsonWang/Wp-Next-MD.Editor/blob/V5.0/LICENSE)
[![Latest Unstable Version](https://poser.pugx.org/jaxsonwang/wp-hypermd/v/unstable)](https://packagist.org/packages/jaxsonwang/wp-hypermd)
[![composer.lock](https://poser.pugx.org/jaxsonwang/wp-hypermd/composerlock)](https://packagist.org/packages/jaxsonwang/wp-hypermd)

### 说明 Description

该插件还处于开发中，部分功能还未完善，如果你有特殊需求请使用[WP-Editor.md](https://github.com/JaxsonWang/WP-Editor.md)插件

WP HyperMD是一个漂亮又实用的在线Markdown文档编辑器。

WP HyperMD is a beautiful and practical Markdown document editor.

基于[HyperMD](https://github.com/laobubu/hypermd/)构建对WordPress平台的支持。

Build support for the WordPress on [HyperMD](https://github.com/laobubu/hypermd/).

使用WordPress [Jetpack](http://jetpack.me) 的Markdown模块来解析和保存内容。

The plugin uses the Markdown module from WordPress [Jetpack](http://jetpack.me) for parsing and saving content.

WordPress Plugins [Download](https://wordpress.org/plugins/wp-hypermd/)

WordPress 插件库[下载](https://wordpress.org/plugins/wp-hypermd/)

注意：原作者停止更新，这是一个原插件WP-HyperMD的分支实现，继续维护。

### 特征 Feature

 - [x] 支持实时预览/语法高亮等功能；
 - [x] 支持 [Emoji 表情](http://www.emoji-cheat-sheet.com/)
 - [x] 支持WordPress的多媒体插入
 - [ ] 支持Toc文章目录显示
 - [x] 支持GFM Task lists
 - [x] 支持[KaTeX科学公式](https://khan.github.io/KaTeX/)或者[MathJAX科学公式](https://www.mathjax.org/)
 - [x] 支持[Mermaid](https://mermaidjs.github.io/)
 - [x] 支持图像粘贴

 ---

 - [x] Real-time Preview, Code syntax highlighting;
 - [x] Support [Emoji](http://www.emoji-cheat-sheet.com/)
 - [x] Support WordPress multimedia insertion
 - [ ] Support Toc
 - [x] Support GFM Task lists
 - [x] Support [KaTeX](https://khan.github.io/KaTeX/) Or [MathJAX](https://www.mathjax.org/)
 - [x] Support [Mermaid](https://mermaidjs.github.io/)
 - [x] Support Image Paste

### 使用说明 ReadMe

[Doc en-US](https://github.com/JaxsonWang/WP-HyperMD/blob/doc/en-US/synopsis.md)

[Doc zh-CN](https://github.com/JaxsonWang/WP-HyperMD/blob/doc/zh-CN/synopsis.md)

[Markdown](https://raw.githubusercontent.com/JaxsonWang/WP-HyperMD/doc/Example/Markdown.md)

~~[KaTeX](https://raw.githubusercontent.com/JaxsonWang/WP-HyperMD/doc/Example/KaTeX.md)~~

~~[Mermaid](https://raw.githubusercontent.com/JaxsonWang/WP-HyperMD/doc/Example/Mermaid.md)~~

~~[MindMap](https://raw.githubusercontent.com/JaxsonWang/WP-HyperMD/doc/Example/MindMap.md)~~
 
### 开发 Development

使用[npm](https://bower.io/)安装静态资源依赖文件：

```bash
npm install # 安装依赖文件
npm minify # 压缩assets/src/* 目录下配置文件
npm watch # 监视项目并且执行编译任务
```

其它命令：

```bash
npm postinstall # 复制依赖文件到assets/
npm clean assets # 清理assets/目录下文件
```

### 安装 Installation

1. 上传 `WP-HyperMD`目录 到 `/wp-content/plugins/` 目录;

1. 在后台插件菜单激活该插件;

---

- Upload the `WP-HyperMD` directory to the `/wp-content/plugins/` directory;

- Enable the WordPress Plugins

### 截图 Screenshots

![](https://raw.githubusercontent.com/JaxsonWang/Wp-HyperMD/doc/screenshots/Interface-wp-editor.png)

### 更新日志 ChangeLog

请见[更新日志](./CHANGELOG.md)

### License

![GPLv3](https://www.gnu.org/graphics/gplv3-127x51.png)

WP-HyperMD is licensed under [GNU General Public License](https://www.gnu.org/licenses/gpl.html) Version 3 or later.

```
WP-HyperMD is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

WP-HyperMD is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with WP-HyperMD.  If not, see <http://www.gnu.org/licenses/>.
```
