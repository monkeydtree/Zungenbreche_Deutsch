# Zungenbreche_Deutsch

这是一个专为12-13岁德语学习者设计的交互式绕口令练习网页。该网页提供了丰富的德语绕口令集合，支持语音朗读功能，让学习者能够更好地练习德语发音，提高语言学习兴趣。

Eine interaktive Webseite zum Üben deutscher Zungenbrecher, speziell für 12-13-jährige Deutschlernende entwickelt. Die Webseite bietet eine umfangreiche Sammlung deutscher Zungenbrecher mit Sprachausgabefunktion, um das Üben der deutschen Aussprache zu erleichtern und das Interesse am Sprachenlernen zu fördern.

## ✨ 功能特点 | Funktionen

### 🎯 主要功能 | Hauptfunktionen

- 📝 **精选绕口令集合** - 18个精选德语绕口令，涵盖不同难度
- 🎯 **智能难度分级** - 简单、中等、困难三个等级，适合不同水平学习者
- 🔍 **搜索筛选功能** - 实时搜索，快速找到想要的绕口令
- 🔊 **语音朗读功能** - 使用Web Speech API实现德语语音朗读
- ⚡ **语速调节** - 支持慢速、正常、快速三种语速
- 📱 **响应式设计** - 完美适配桌面、平板和手机设备
- ✍️ **自定义练习** - 支持输入自定义文本进行练习
- 🎨 **现代化UI** - 活泼的界面设计，适合青少年用户

### 🔧 技术特点 | Technische Merkmale

- **纯前端实现** - 无需后端支持，可直接在浏览器中运行
- **Web Speech API** - 原生浏览器语音合成技术
- **响应式网格布局** - CSS Grid实现的自适应卡片布局
- **实时搜索筛选** - JavaScript实现的即时搜索和分类筛选
- **Font Awesome图标** - 丰富的图标库，提升用户体验
- **渐进式增强** - 优雅降级，兼容不同浏览器

## 🚀 使用方法 | Anleitung

### 基本使用 | Grundlegende Nutzung

1. **打开网页** - 在浏览器中打开 `Zungenbreche.html` 文件
2. **浏览绕口令** - 查看所有可用的德语绕口令
3. **选择难度** - 使用顶部的分类按钮筛选不同难度级别
4. **搜索内容** - 在搜索框中输入关键词快速查找
5. **听取发音** - 点击播放按钮听取标准德语发音
6. **调节语速** - 使用语速控制选择适合的朗读速度
7. **自定义练习** - 在底部练习区域输入自己的文本

### 高级功能 | Erweiterte Funktionen

- **组合筛选** - 搜索和分类可以同时使用
- **播放控制** - 支持停止当前播放，开始新的朗读
- **视觉反馈** - 播放时按钮会有动画效果
- **无结果提示** - 搜索无结果时显示友好提示

## 🛠️ 技术栈 | Technologie-Stack

### 前端技术 | Frontend-Technologien

- **HTML5** - 语义化标记，无障碍访问支持
- **CSS3** - 现代样式，动画效果，响应式设计
- **JavaScript (ES6+)** - 交互逻辑，语音API调用
- **Web Speech API** - 浏览器原生语音合成
- **Font Awesome 6.4.0** - 图标库

### 设计原则 | Design-Prinzipien

- **移动优先** - 响应式设计，优先考虑移动设备
- **用户友好** - 简洁直观的界面，适合青少年用户
- **性能优化** - 轻量级实现，快速加载
- **可访问性** - 支持键盘导航，屏幕阅读器友好

## 🌐 浏览器支持 | Browser-Unterstützung

| 浏览器 | 支持状态 | 备注 |
|--------|----------|------|
| Chrome | ✅ 完全支持 | 推荐使用，语音功能最佳 |
| Firefox | ✅ 完全支持 | 良好支持 |
| Edge | ✅ 完全支持 | 基于Chromium，功能完整 |
| Safari | ⚠️ 部分支持 | 语音功能可能有限制 |
| Opera | ✅ 完全支持 | 基于Chromium |

### 系统要求 | Systemanforderungen

- 现代浏览器（支持ES6+）
- 网络连接（用于加载Font Awesome图标）
- 音频输出设备（用于语音播放）

## 📁 项目结构 | Projektstruktur

```
Deutsche-Zungenbrecher/
├── Zungenbreche.html          # 主页面文件
├── README.md                  # 项目说明文档
└── assets/                    # 资源文件夹（可选）
    ├── images/               # 图片资源
    └── sounds/               # 音频资源
```

### 文件说明 | Dateibeschreibung

- **Zungenbreche.html** - 完整的单页面应用，包含所有功能
- **README.md** - 项目文档，包含使用说明和技术细节

## 🚀 本地运行 | Lokale Ausführung

### 快速开始 | Schnellstart

1. **克隆仓库**：
```bash
git clone [repository-url]
cd Deutsche-Zungenbrecher
```

2. **直接运行**：
```bash
# 方法1：直接打开HTML文件
open Zungenbreche.html

# 方法2：使用本地服务器（推荐）
python -m http.server 8000
# 然后在浏览器中访问 http://localhost:8000
```

### 开发环境 | Entwicklungsumgebung

```bash
# 使用Node.js的http-server
npm install -g http-server
http-server

# 使用Python的SimpleHTTPServer
python -m http.server 8000

# 使用PHP的内置服务器
php -S localhost:8000
```

## 📋 功能清单 | Funktionsliste

### ✅ 已实现功能

- [x] 18个德语绕口令内容
- [x] 难度分类系统（简单/中等/困难）
- [x] 实时搜索功能
- [x] 语音朗读功能
- [x] 语速调节（0.7x, 1x, 1.3x）
- [x] 响应式设计
- [x] 自定义练习区域
- [x] 播放状态动画
- [x] 无结果提示
- [x] 移动端优化

### 🔮 计划功能

- [ ] 用户进度追踪
- [ ] 收藏夹功能
- [ ] 分享功能
- [ ] 更多绕口令内容
- [ ] 发音评分系统
- [ ] 游戏化元素

## ⚠️ 注意事项 | Hinweise

### 使用限制 | Nutzungsbeschränkungen

- **语音功能** - 需要浏览器支持Web Speech API
- **网络连接** - 需要网络连接加载Font Awesome图标
- **浏览器版本** - 建议使用最新版本的现代浏览器
- **音频设备** - 需要音频输出设备听取语音

### 兼容性说明 | Kompatibilitätshinweise

- **语音合成** - 不同浏览器的语音质量可能不同
- **移动设备** - 某些移动浏览器可能限制自动播放
- **离线使用** - 可以下载Font Awesome图标到本地使用

## 🤝 贡献指南 | Beitragsrichtlinien

### 如何贡献 | Wie man beiträgt

1. **Fork项目** - 在GitHub上fork本项目
2. **创建分支** - 创建功能分支进行开发
3. **提交代码** - 提交您的更改
4. **发起PR** - 创建Pull Request

### 开发规范 | Entwicklungsrichtlinien

- **代码风格** - 遵循现有的代码风格和注释规范
- **功能测试** - 确保新功能在不同浏览器中正常工作
- **文档更新** - 更新相关文档和注释
- **性能考虑** - 注意代码性能和用户体验

### 提交规范 | Commit-Richtlinien

```
feat: 添加新功能
fix: 修复bug
docs: 更新文档
style: 代码格式调整
refactor: 代码重构
test: 添加测试
chore: 构建过程或辅助工具的变动
```

## 📄 许可证 | Lizenz

本项目采用 **MIT License** 开源许可证。

```
MIT License

Copyright (c) 2023 Project2501

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## 👨‍💻 作者 | Autor

**Project2501**

- 📧 邮箱：[your-email@example.com]
- 🌐 网站：[your-website.com]
- 💼 GitHub：[github.com/your-username]

## 📈 版本历史 | Versionsgeschichte

### v2.0.0 (2023-12-XX)
- ✨ 新增搜索筛选功能
- ✨ 优化卡片网格布局
- ✨ 添加10个新绕口令
- ✨ 改进用户界面设计
- ✨ 增强响应式支持
- 🐛 修复播放按钮交互问题
- 📝 完善代码注释和文档

### v1.0.0 (2023-XX-XX)
- 🎉 初始版本发布
- ✨ 实现基本语音朗读功能
- ✨ 添加难度分类系统
- ✨ 实现响应式设计
- ✨ 添加自定义练习区域

## 🙏 致谢 | Danksagung

感谢以下开源项目和服务：

- [Font Awesome](https://fontawesome.com/) - 图标库
- [Web Speech API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Speech_API) - 语音合成技术
- [GitHub](https://github.com/) - 代码托管平台

## 📞 联系方式 | Kontakt

如果您有任何问题、建议或反馈，欢迎通过以下方式联系：

- 📧 邮箱：[your-email@example.com]
- 🐛 问题反馈：[GitHub Issues](https://github.com/your-username/your-repo/issues)
- 💬 讨论：[GitHub Discussions](https://github.com/your-username/your-repo/discussions)

---

⭐ 如果这个项目对您有帮助，请给我们一个星标！ 
