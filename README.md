# Lilinyang Portfolio 2026

![Portfolio Preview](p1-111.png) 


> 🎨 一个基于 HTML5 Canvas 和 Tailwind CSS 构建的沉浸式个人作品集网站。
> A immersive portfolio website built with HTML5 Canvas and Tailwind CSS.

## ✨ 核心特性 (Features)

### 1. 视觉体验
- **动态极光背景 (Aurora Canvas)**: 
  - 纯原生 JavaScript 编写的粒子系统。
  - 包含“呼吸感”动态大小变化与随机漂浮算法。
  - `globalCompositeOperation = 'screen'` 混合模式模拟真实光感。
- **玻璃拟态 (Glassmorphism)**: 全站采用磨砂玻璃质感 UI，配合半透明边框与光影。
- **超大排版**: 响应式 `vw` 单位实现的巨型 Portfolio 标题。

### 2. 交互细节
- **平滑滚动**: 全局 Scroll-smooth 体验。
- **灯箱预览 (Lightbox)**: 点击作品卡片可呼出无滚动条的沉浸式大图预览。
- **智能回顶**: 页面滚动超过 300px 后自动浮现的玻璃态“回到顶部”按钮。

### 3. 性能优化 (Performance)
- **国内极速访问**: 全站静态资源 (AOS, Phosphor Icons) 已替换为 BootCDN 国内镜像源，解决内地访问慢的问题。
- **智能渲染**: 使用 `IntersectionObserver` API 监控视口，当首屏不可见时自动暂停 Canvas 动画渲染，极大节省设备电量与 CPU 占用。
- **防抖处理**: 窗口 Resize 事件添加防抖 (Debounce) 逻辑，防止频繁重绘。

## 🛠️ 技术栈 (Tech Stack)

- **核心**: HTML5, CSS3, Vanilla JavaScript (ES6+)
- **样式**: [Tailwind CSS](https://tailwindcss.com/) (CDN版)
- **动画**: [AOS.js](https://michalsnik.github.io/aos/) (滚动视差), HTML5 Canvas
- **图标**: Phosphor Icons

## 🚀 如何运行 (How to Run)

这是一个纯静态网页项目，无需安装 Node.js 环境。

1. 克隆或下载本仓库。
2. 直接双击 `index.html` 在浏览器中打开即可。
3. (可选) 使用 VS Code 的 "Live Server" 插件预览效果更佳。

## 📬 联系 (Contact)

- **Designer**: 李林阳 (Lilinyang)
- **Email**: 940213696@qq.com
- **Year**: 2026

---
*Created with ❤️ by Lilinyang*
