# 减脂餐 · 京东科技大厦

**在线访问 → [zc-ruc.github.io/jianzhi-meals/](https://zc-ruc.github.io/jianzhi-meals/)**

![screenshot](./screenshot.jpg)

单文件减脂餐管理小站（移动端优先）：一周餐单 + 商家比价 + 记账 + 体重趋势 + 周报，数据本地存储 + 云端同步。

## 功能

- **一周餐单**：午/晚餐搭配（含热量与实测价），围绕 1900–2100 kcal/日、120–140g 蛋白质目标设计，≈0.5kg/周减重节奏
- **商家比价**：周边轻食商家评分 / 人均 / 距离 / 代表价一览
- **日历 + 记一笔**：按日记录餐饮花费，¥60 餐补额度当日清零提醒
- **体重趋势**：体重曲线（88kg → 75kg 目标）
- **周报**：每周花销与减重进度回顾
- **云端同步**：多端数据合并（Cloudflare Worker 后端）
- **深色模式**：跟随系统 / 手动切换

## 使用

单文件应用，无需构建：直接打开 `index.html`。线上版由 GitHub Pages 托管（main 分支根目录）。

数据默认存浏览器 localStorage；云端同步依赖配套的 Cloudflare Worker 端点（`jianzhi-sync.*.workers.dev`，为作者私有配置，复用时请替换为你自己的同步服务）。

## 技术

纯原生 HTML/CSS/JS，零依赖零构建。
