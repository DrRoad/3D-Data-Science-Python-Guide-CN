# 3D Data Science with Python - 中文指南 🚀
![License](https://img.shields.io/badge/License-CC%20BY--NC--ND%204.0-lightgrey)
![Python](https://img.shields.io/badge/Python-3.9+-blue)
![Platform](https://img.shields.io/badge/Platform-WSL2%20%7C%20Linux%20%7C%20CUDA-green)

本项目致力于为 O'Reilly 2024 年重磅新书 **《3D Data Science with Python》** 提供中文语境下的深度技术支持与实践参考。

> **📢 出版合作声明：**
> 本人已完成全书中文初稿翻译，并对书中所有代码进行了 2026 年最新库版本的兼容性修复。目前正在积极寻找国内出版社（如：图灵教育、博文视点、异步社区等）进行商业化引进合作。
> 📬 **联系方式：** clw1031@gmail.com | **WeChat:** [你的微信]

---

## 🌟 为什么关注本书？

在**具身智能 (Embodied AI)**、**自动驾驶**与**低空经济**爆发的今天，3D 数据处理已成为 AI 工程师的必备技能。本书填补了从 2D 数据科学到 3D 空间计算的断层，涵盖：
- **点云（Point Clouds）** 的大规模处理与过滤。
- **几何深度学习** 的数学基础与实战。
- **Open3D & PyTorch3D** 在工业级场景下的应用。

## 🛠️ 本项目的增值价值 (Value-Add)

1. **WSL2 + CUDA 全流程跑通**：针对国内开发者常用的 Windows 子系统环境，提供了完整的 GPU 加速避坑指南。
2. **2026 兼容性修复**：原书代码基于较早版本的 Open3D。本项目修复了由于接口变更导致的渲染 Bug。
3. **中文体系化导航**：完整呈现中文目录及核心概念索引，助力快速评估内容深度。

## 📊 效果展示 (Visualizations)

| 原始点云数据 | 曲面重建与渲染 | 体素化处理 |
| :--- | :--- | :--- |
| ![点云图](assets/pc.png) | ![重建图](assets/mesh.png) | ![体素图](assets/voxel.png) |

## 📂 仓库结构

- `/notebooks`: 经过验证的 Jupyter Notebook 示例代码。
- `/environment`: 针对 WSL2/Ubuntu 的 `requirements.txt` 和配置脚本。
- `/docs`: 中文详细目录与样章片段。

---

## 🤝 致出版社编辑

如果您是技术出版领域的策划编辑，正在寻找高质量的 AI/数据科学选题，本项目已具备以下“快车道”条件：
- **翻译进度：100%**
- **代码校验：100% (基于最新 Python 环境)**
- **译者背景：** 土木工程博士，深耕 Agentic AI 与 3D ML 领域，具备社区推广能力。

我们诚挚邀请您进行版权确认与合作洽谈。
