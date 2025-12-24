# 🎄 Gesture Christmas Tree

一个基于手势识别的沉浸式 3D 圣诞树网页装置  
A gesture-driven interactive 3D Christmas Tree experience.

## ✨ 项目简介
本项目使用 **Three.js + WebGL + MediaPipe Hands** 构建一个
由粒子、几何体与照片云组成的 3D 圣诞树。

用户无需任何控制器，仅通过 **真实手势** 即可完成状态切换与空间交互，
探索数字装置中的「秩序 / 解构 / 凝视」。

## 🎮 交互方式（Gestures）
- ✊ **握拳**：圣诞树合拢（初始 / 回归态）
- 🖐 **张开五指**：元素散开，自由漂浮
- 🔄 **旋转手掌**：旋转视角（空间操控）
- 🤏 **抓取动作**：抓住照片并放大聚焦

## 🌲 系统状态
1. 合拢态（Tree Form）
2. 散开态（Exploded Space）
3. 照片放大态（Photo Focus）

状态之间通过平滑动画过渡。

## 🎨 视觉设计
- 主色系：哑光绿 / 金属金 / 圣诞红
- 电影感辉光（Bloom）
- 深色背景 + 空间雾化
- Instanced Mesh 高性能粒子系统

## 🛠 技术栈
- Three.js / WebGL
- InstancedMesh
- GLSL Shader
- MediaPipe Hands
- 原生 HTML / CSS / JavaScript

## ⚠️ 使用说明
- 推荐使用 **Chrome / Edge（桌面端）**
- 需允许摄像头权限
- iOS Safari 可能存在性能限制

## 🔗 在线体验
👉 https://jerry081118-hash.github.io

---

> 本项目为实验性创意编码作品，适用于互动装置、数字艺术与新媒体方向。
