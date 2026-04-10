# 🎨 PicTool Pro

> 免费在线AI图片处理工具箱 - 压缩、转换、裁剪、水印、滤镜、拼图、增强一站式解决

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/LINEXIANSEN/LPicTool?style=social)](https://github.com/LINEXIANSEN/LPicTool/stargazers)

[🖥️ 在线访问](https://LINEXIANSEN.github.io/LPicTool/) | [📖 文档](https://github.com/LINEXIANSEN/LPicTool/blob/main/SPEC.md) | [🚀 v3.0 新版](https://LINEXIANSEN.github.io/LPicTool/pictool-pro.html)

---

## ✨ 功能特色

### v3.0 新版功能
| 功能 | 描述 | 状态 |
|------|------|------|
| ↻ 旋转翻转 | 90°/180°/270° 旋转 + 水平/垂直翻转 | 🆕 |
| ✨ 图片增强 | 亮度、对比度、饱和度、锐化调节 | 🆕 |
| 🖼️ 边框圆角 | 自定义圆角大小和边框样式 | 🆕 |
| 📱 PWA 支持 | 可安装到桌面，离线使用 | 🆕 |

### 基础功能
| 功能 | 描述 | 状态 |
|------|------|------|
| 🗜️ 图片压缩 | 智能压缩，保持画质 | ✅ |
| 🔄 格式转换 | JPG/PNG/WEBP/GIF/HEIC 互转 | ✅ |
| 📐 尺寸调整 | 自定义尺寸，保持比例 | ✅ |
| ✂️ 智能裁剪 | 多种社交媒体预设比例 | ✅ |
| 💧 添加水印 | 文字水印，保护版权 | ✅ |
| 📝 添加文字 | 图片添加文字标注 | ✅ |
| 🎨 滤镜效果 | 10种预设滤镜一键美化 | ✅ |
| 🖼️ 图片拼图 | 多图拼接成一张 | ✅ |
| 📦 批量处理 | 一次性处理多张图片 | ✅ |

---

## 🚀 快速开始

### 在线使用（推荐）

👉 **[PicTool Pro v3.0](https://LINEXIANSEN.github.io/LPicTool/pictool-pro.html)** - 最新版本，支持 PWA

👉 **[PicTool v2.0](https://LINEXIANSEN.github.io/LPicTool/pictool-v2.html)** - 稳定版本

### 本地运行

1. 克隆仓库：
   ```bash
   git clone https://github.com/LINEXIANSEN/LPicTool.git
   ```

2. 直接用浏览器打开 `pictool-pro.html` 或 `index.html` 文件

3. 无需安装任何依赖，无需服务器

### 安装为桌面应用

1. 使用 Chrome/Edge 打开 [v3.0](https://LINEXIANSEN.github.io/LPicTool/pictool-pro.html)
2. 点击地址栏右侧的安装图标
3. 即可像桌面应用一样使用！

---

## 📁 项目结构

```
LPicTool/
├── index.html          # 入口首页（版本选择）
├── pictool-pro.html     # PicTool Pro v3.0（最新功能版）⭐推荐
├── pictool-v2.html     # PicTool v2.0（稳定版）
├── pic-tool.html       # PicTool Classic v1.0（经典版）
├── manifest.json       # PWA 清单
├── sw.js              # Service Worker（离线缓存）
├── SPEC.md            # 项目规范文档
├── 运营指南.md         # 产品运营指南
├── 上线步骤.md         # 网站上线教程
├── 零成本部署教程.md    # 免费部署指南
├── 部署常见问题.md      # 部署问题解答
├── LICENSE            # MIT 许可证
└── README.md          # 项目说明文档
```

---

## 🎯 核心优势

- 🆓 **完全免费** - 所有功能免费使用，无隐藏收费
- 🔒 **隐私保护** - 所有处理在本地完成，图片不会上传服务器
- ⚡ **即用即走** - 无需注册、无需安装，打开浏览器即可使用
- 📱 **响应式设计** - 完美适配电脑和手机设备
- 🌐 **跨平台** - 支持所有主流浏览器
- 💾 **PWA 支持** - 可安装到桌面，离线也能用

---

## 🛠️ 技术栈

- **前端**: HTML5 + CSS3 + Vanilla JavaScript
- **图片处理**: Canvas API
- **离线支持**: Service Worker + Cache API
- **PWA**: Web App Manifest
- **无需后端**: 纯前端实现，保护用户隐私
- **无外部依赖**: 不使用任何外部库

---

## 📊 版本对比

| 功能 | v1.0 | v2.0 | v3.0 ⭐ |
|------|:----:|:----:|:-------:|
| 图片压缩 | ✅ | ✅ | ✅ |
| 格式转换 | ✅ | ✅ | ✅ |
| 尺寸调整 | ✅ | ✅ | ✅ |
| 智能裁剪 | ✅ | ✅ | ✅ |
| 添加水印 | - | ✅ | ✅ |
| 添加文字 | - | ✅ | ✅ |
| 滤镜效果 | - | ✅ | ✅ |
| 图片拼图 | - | ✅ | ✅ |
| 批量处理 | - | ✅ | ✅ |
| 旋转翻转 | - | - | ✅ |
| 图片增强 | - | - | ✅ |
| 边框圆角 | - | - | ✅ |
| PWA 支持 | - | - | ✅ |

---

## 📄 许可证

本项目基于 [MIT License](LICENSE) 开源。

---

## 👤 作者

**LINEXIANSEN**

- GitHub: [@LINEXIANSEN](https://github.com/LINEXIANSEN)
- 项目地址: [LPicTool](https://github.com/LINEXIANSEN/LPicTool)

---

## 🙏 致谢

- 图标来自 emoji 🎨
- 设计参考了现代 UI 趋势
- 感谢所有开源社区的贡献者

---

<p align="center">
  Made with ❤️ by <a href="https://github.com/LINEXIANSEN">LINEXIANSEN</a>
</p>
