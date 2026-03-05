# 《Real-Time Rendering》第4版 读书笔记

> Real-Time Rendering, Fourth Edition
> 作者：Tomas Akenine-Möller, Eric Haines, Naty Hoffman

---

## 📚 笔记概览

这是《Real-Time Rendering》第4版（RTR4）的完整读书笔记，涵盖：
- **26章核心内容**：从渲染管线到实时光线追踪
- **在线附录**：线性代数、三角学
- **总行数**：6635行

---

## 🎯 核心内容

### 基础架构（Ch1-4）
- 图形渲染管线
- GPU架构
- 变换系统
- 数学基础

### 着色与材质（Ch5-9）
- 着色基础
- 纹理技术
- 阴影系统
- 物理着色（PBR）

### 光照（Ch10-11）
- 局部光照
- 全局光照

### 特效与高级技术（Ch12-17）
- 图像空间特效
- 体积与半透明渲染
- 非真实感渲染（NPR）
- 多边形技术
- 曲线与曲面

### 优化（Ch18-20）
- 管线优化
- 加速算法
- 高效着色

### 专题（Ch21-26）
- VR/AR技术
- 相交测试
- 图形硬件
- 未来展望
- 碰撞检测
- 实时光线追踪 ⭐⭐⭐

---

## 💡 核心价值

### 与PBRT4的互补

| 维度 | **RTR4**（本书） | **PBRT4** |
|------|-----------------|----------|
| **主题** | 实时渲染 | 离线光线追踪 |
| **帧率** | 60-144fps | 秒级到小时级 |
| **方式** | 光栅化 + 混合光追 | 路径追踪 |
| **代码** | 理论+伪代码 | 完整C++17实现 |
| **应用** | 游戏、VR、交互 | 电影、建筑可视化 |

### 学习亮点

- ✅ **行业标准教材**：实时渲染领域最权威的参考书
- ✅ **技术全面**：覆盖现代GPU管线的所有方面
- ✅ **实战导向**：大量真实游戏案例和优化技巧
- ✅ **与时俱进**：第4版新增实时光线追踪、VR等内容

---

## 📖 章节结构

### 基础篇（Ch1-4）
1. Introduction
2. The Graphics Rendering Pipeline
3. The Graphics Processing Unit
4. Transform

### 着色篇（Ch5-9）
5. Shading Basics
6. Texturing
7. Shadows
8. Light and Color
9. Physically Based Shading ⭐⭐⭐

### 光照篇（Ch10-11）
10. Local Illumination ⭐⭐
11. Global Illumination ⭐⭐⭐

### 特效篇（Ch12-17）
12. Image-Space Effects ⭐⭐
13. Beyond Polygons
14. Volumetric and Translucency Rendering
15. Non-Photorealistic Rendering
16. Polygonal Techniques
17. Curves and Curved Surfaces

### 优化篇（Ch18-20）
18. Pipeline Optimization ⭐⭐
19. Acceleration Algorithms ⭐⭐
20. Efficient Shading

### 专题篇（Ch21-26）
21. Virtual and Augmented Reality
22. Intersection Test Methods
23. Graphics Hardware
24. The Future
25. Collision Detection
26. Real-Time Ray Tracing ⭐⭐⭐

**⭐ 标记重要程度**

---

## 🔗 相关资源

### 官方资源
- 📘 书籍官网：http://www.realtimerendering.com/
- 💻 在线资源：交互式demo、补充材料
- 📚 在线附录：线性代数、三角学

### 相关笔记
- [PBRT4读书笔记](https://github.com/WhiteLeer/PBRT4-Reading-Notes) - 离线渲染
- 图形渲染知识总结（本地）

---

## 🎓 学习建议

### 前置知识
- 基础图形学概念
- 线性代数
- 基础编程经验
- OpenGL/DirectX了解（可选）

### 阅读路径

**路径1：完整学习（推荐）**
```
Ch1-4（基础）→ Ch5-9（着色）→ Ch10-11（光照）→ Ch12-20（特效+优化）→ Ch21-26（专题）
```

**路径2：快速上手（游戏开发）**
```
Ch2-3（管线+GPU）→ Ch5-6（着色+纹理）→ Ch7（阴影）→ Ch9（PBR）→ Ch18（优化）
```

**路径3：现代管线（光追）**
```
Ch1-4（基础）→ Ch9（PBR）→ Ch11（全局光照）→ Ch26（实时光追）
```

**路径4：特效艺术家**
```
Ch5-7（着色+纹理+阴影）→ Ch12（图像特效）→ Ch14（体积渲染）→ Ch15（NPR）
```

### 实践建议
1. ✅ 结合Unity/Unreal实践
2. ✅ 实现Ch9的PBR管线
3. ✅ 研究Ch26的实时光追
4. ✅ 对比Ch11传统全局光照与现代光追
5. ✅ 配合PBRT4学习离线渲染

---

## 📊 笔记统计

- **总行数**：6635行
- **完成日期**：2026-03-05
- **阅读耗时**：约3天
- **笔记质量**：⭐⭐⭐⭐⭐

---

## 📝 笔记特点

- **逐章总结**：每章提炼核心要点
- **技术对比**：不同方法的优劣分析
- **公式整理**：关键数学推导
- **实现细节**：GPU优化技巧
- **案例分析**：真实游戏实践
- **互补体系**：与PBRT4形成离线+实时双覆盖

---

## ⚠️ 版权声明

本笔记仅包含技术要点总结和概念提取，不含原书的完整内容。
完整内容请访问书籍官网或购买正版书籍。

**原书版权**：© 1999-2018 Tomas Akenine-Möller, Eric Haines, and Naty Hoffman

---

## 🤝 贡献

欢迎提出改进建议！

---

*笔记整理：Master + Claude*
*最后更新：2026-03-05*
