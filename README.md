# Baixi520.github.io

> 白汐ex (Furry_白汐ex) 的个人主页 —— 赛博朋克风格的 Furry 个人展示页

## 项目简介

这是一个基于 TailwindCSS 4.x + Alpine.js + Particles.js 构建的个人主页网站，采用赛博朋克/工业美学设计风格，包含粒子特效背景、CRT 屏幕闪烁动画、HUD 装饰元素和加载动画等视觉效果。

## 功能特性

- **赛博朋克视觉风格** — CRT 屏幕闪烁、HUD 动态装饰线、科幻字体 (Orbitron + Rajdhani)
- **粒子特效背景** — 基于 Particles.js 的动态粒子系统
- **响应式布局** — 基于 TailwindCSS 的移动端优先响应式设计
- **动态交互** — 使用 Alpine.js 实现响应式数据交互
- **加载动画** — 进度条滑入 + 容器淡入缩放动画
- **GitHub Pages 部署** — 自动通过 GitHub Pages 提供访问

## 技术栈

| 技术 | 说明 |
|------|------|
| TailwindCSS 4.x | CSS 框架（浏览器 CDN 引入） |
| Alpine.js 3.x | 轻量级响应式框架 |
| Particles.js | 粒子特效背景库 |
| Google Fonts | Orbitron + Rajdhani 科幻字体 |

## 在线预览

[https://baixi520.github.io](https://baixi520.github.io)

## 本地运行

由于项目为纯静态 HTML 页面，直接用浏览器打开 `index.html` 即可。也可使用本地服务器：

```bash
# 使用 Python 内置服务器
python -m http.server 8000

# 或使用 Node.js 的 serve
npx serve
```

然后访问 `http://localhost:8000`。

## 项目结构

```
Baixi520.github.io/
├── index.html      # 主页面
├── images/         # 图片资源
└── README.md       # 项目说明
```

## License

[MIT](./LICENSE)
