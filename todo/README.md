# 待办清单 - 前端学习项目

一个面向纯新手的 **HTML + CSS + JavaScript** 练手项目，已部署到 GitHub Pages：

**https://0001uw.github.io/my-css-dai/todo/**

---

## 项目简介

这是一个功能完整的待办清单（To-Do List）网页，从零开始手写每一行代码，边学边做：

- 用 **HTML** 搭页面结构
- 用 **CSS** 画样式、布局、动画效果
- 用 **JavaScript** 实现交互逻辑（添加 / 完成 / 删除任务 + 实时时钟）

---

## 功能

- 添加新任务（点「添加」按钮或按 Enter）
- 点击 ✅ 标记完成 / 取消完成
- 点击 ❌ 删除任务
- 实时数字时钟（显示当前年月日时分秒）
- 防 XSS 攻击：用户输入自动转义

---

## 本地运行

直接用浏览器打开 `index.html` 即可（file:// 协议），无需安装任何环境。

---

## 部署方式

项目托管在 GitHub Pages。每次修改后执行：

```
git add .
git commit -m "更新内容"
git push
```

GitHub Pages 会自动重新部署，稍等几十秒刷新页面就能看到最新版。

---

## 学习路线参考

本项目涉及的前端知识点：

- HTML 基础标签 — `index.html`
- CSS 选择器、盒模型 — `style.css`
- Flexbox 布局 — `.input-area`、`.task-list li`
- CSS 渐变背景 — `body`
- CSS 过渡动画 — `transition` 属性
- DOM 操作 — `<script>` 中的 JavaScript
- 事件监听 & 事件委托 — `addEventListener`
- 模板字符串 — `innerHTML` 拼接
- 防 XSS 安全处理 — `escapeHtml` 函数
- setInterval 定时器 — `updateClock`
- GitHub Pages 部署 — 仓库 Settings → Pages

---

写得不好或不完善的地方，边学边改 🚀
