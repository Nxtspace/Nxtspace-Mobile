<p align="center">
  <a href="#" target="_blank" rel="noopener noreferrer">
    <img width="100" src="https://raw.githubusercontent.com/Nxtspace/Nxtspace-Web/main/icon.ico" alt="Nxtspace logo">
  </a>
</p>

<h2 align="center">Nxtspace Mobile</h2>

<p align="center">
  🚀 React Native Cross-platform Mobile App
</p>

---

![React Native](https://img.shields.io/badge/React%20Native-v0.83.6-61DAFB?logo=react&logoColor=white&style=flat-square) ![React](https://img.shields.io/badge/React-v19.2.5-61DAFB?logo=react&logoColor=white&style=flat-square) ![TypeScript](https://img.shields.io/badge/TypeScript-5.x-3178C6?logo=typescript&logoColor=white&style=flat-square) ![Gluestack](https://img.shields.io/badge/Gluestack-UI-00C7B7?style=flat-square)

<details open>
<summary><strong>中文 / Chinese</strong></summary>

### 简介

---

Nxtspace Mobile 是一款基于 React Native 构建的建筑 3D 场景搭建移动端应用，专为建筑行业打造。

无论您是否有模型基础，都能轻松上手。通过 Nxtspace Mobile 您可以快速实现 3D 建筑场景搭建的需求，轻松创建专属 Demo。

Nxtspace Mobile 支持 Android、iOS 等移动平台运行，结合 React Native 提供跨平台能力，并通过 Gluestack UI 提供统一的移动端交互体验。

### 模型

---

Nxtspace Mobile 支持导入和管理 3D 模型资源，为建筑场景搭建提供丰富的模型库。

目前支持使用 Sweet Home 3D 免费模型资源，包括：

- 家具模型
- 室内装饰模型
- 灯具模型
- 植物模型
- 厨房模型
- 卫浴模型
- 门窗模型
- 建筑组件模型

模型来源：

- Sweet Home 3D 官方免费模型库
- 用户自定义 3D 模型

Sweet Home 3D 免费模型：

https://www.sweethome3d.com/freeModels.jsp

### 平台

---

- 🟢 Android
- 🟢 iOS

### 功能/计划

---

Tips: ⚪ 筹备中 🟡 进行中 🟢 已完成

- 🟢 编辑器核心
  - 🟢 二维平面图
    - 🟢 墙体绘制（直线 / 弧墙一键转换，正交 / 夹角画墙，内 / 外 / 中三种定位线，绘制中可取消）
    - 🟢 门洞与窗户（插入墙体自动开洞，含单开门 / 双开门 / 门洞 / 多款式）
    - 🟢 门窗跨墙移动（拖到相邻墙直接落成，链式标尺实时反馈落点距离，绘制时幽灵预览跟随光标）
    - 🟢 区域绘制（闭合房间自动计算面积，多边形区域支持）
    - 🟢 家具摆放（拖拽模型进场景 + 实时吸附对齐 + 落点预览）
    - 🟢 顶点编辑（墙体端点 / 拐点拖拽微调，墙体自动重算）
    - 🟢 尺寸标注（墙体长度 / 角度实时显示，独立开关切换显隐，绘制中标尺长度可输入直接落成）
    - 🟢 净距标尺（拖动时实时显示与墙体 / 相邻物体的四向最近净距）
    - 🟢 参考线（水平 / 垂直 / 圆形辅助线，颜色自定义，按层管理，圆形随画布缩放平移）
    - 🟢 参考图（CAD / 平面图 / 任意图片作为底图描边，可缩放/平移/透明度调整）
    - 🟢 网格与标尺（网格开关 + 吸附，横纵标尺随缩放/平移同步）
    - 🟢 右键菜单（上下文快捷操作：复制/粘贴/删除/分组/锁定/属性/重命名）
    - 🟢 可交互小地图缩略图（拖动聚焦框平移主场景，滚轮以光标为锚点缩放）
  - 🟢 三维可视化
    - 🟢 2D / 3D 视图一键切换
    - 🟢 正交 / 透视投影切换
    - 🟢 多种视角快速切换（正视 / 侧视 / 俯视 / 仰视 / 左视 / 右视 / 等轴测）
    - 🟢 视角辅助球（右下角立方体，点击面/边/角即切换视角）
    - 🟢 娃娃屋模式（按相机位置实时背面剔除墙体，俯视时自动看到室内）
    - 🟢 漫游模式
      - 🟢 第一人称（鼠标锁定 + WASD 移动 / Shift 奔跑 / 空格跳跃，接入物理碰撞阻挡）
      - 🟢 第三人称（轨道相机环绕）
    - 🟢 风格渲染
      - 🟢 材质（PBR 材质贴图 + 灯光）
      - 🟢 材质与轮廓（材质 + 轮廓线叠加）
      - 🟢 轮廓（纯轮廓线模式）
    - 🟢 渲染画质三档（高 / 均衡 / 性能，按设备性能切换）
    - 🟢 二三维视觉反馈统一（悬停轮廓、选中包围盒、选中着色、吸附标记常驻置顶）
    - 🟢 天空与地面（纯色 / 贴图两种模式，50+ 纹理可选）
    - 🟢 右侧栏 3D 实时预览
    - 🟢 3D 场景缩略图

- 🟢 元件库与素材库
  - 🟢 结构元件
    - 🟢 墙体（厚度 / 高度 / 材质默认设置）
    - 🟢 门洞（单开门 / 双开门 / 无门）
    - 🟢 窗户（尺寸 / 窗台 / 样式可调）
    - 🟢 区域（房间参数化默认设置）
  - 🟢 室内模型库
    - 🟢 分类浏览（客厅 / 卧室 / 厨房 / 卫浴 / 办公 / 其他，搜索时无结果分类自动隐藏）
    - 🟢 搜索过滤（按名称快速检索元件）
    - 🟢 自定义模型导入（上传 GLB / ZIP 包，填写尺寸、分类、名称；单个弹窗支持开合类型选择与压缩包模板下载）
    - 🟢 批量导入（下载模板 ZIP，批量上传模型 + 封面，生成结果报表）

- 🟢 材质与贴图
  - 🟢 素材库材质页签（基于 SweetHome3D 材质库，按分类聚合展示，真实尺寸平铺，中英文名称齐全）
  - 🟢 材质选择器（缩略图预览 + 悬浮放大 + 搜索 + 分类分组）
  - 🟢 拖拽铺贴（拖动材质更换区域面与墙体 A/B 面，贴图与纯色通用）
  - 🟢 洪泛铺贴（按住修饰键沿物理相邻面传播材质，连续墙面一次铺满，一次操作仅一条撤销）
  - 🟢 材质刷（吸管吸取区域面 / 墙面材质后直接涂刷到目标，二三维通用，Esc 退出并恢复进入前视图）

- 🟢 编辑与操作
  - 🟢 基础操作
    - 🟢 指针工具（切换回选择态，退出绘制模式）
    - 🟢 选择（多选 / 框选 / 点选 / 反选）
    - 🟢 移动、旋转、��放（三轴 Gizmo 手柄）
    - 🟢 删除
    - 🟢 元素锁定（锁定后可选中但禁止移动 / 缩放 / 旋转 / 删除，混选锁定元素整批拦截）
    - 🟢 复制、剪切、粘贴（含落点预览，粘贴项独立偏移防重叠）
    - 🟢 撤销 / 重做（最大 50 步历史栈）
    - 🟢 全局元件搜索（弹窗搜索所有楼层的墙/洞/家具/区域，定位 + 自动选中 + 聚焦）
    - 🟢 楼层快速切换（下拉选择器 + 搜索过滤，跨楼层跳层编辑）

- 🟢 场景与属性
  - 🟢 右侧栏快捷工具
    - 🟢 放大 / 缩小按钮
    - 🟢 聚焦选区 / 聚焦全局按钮
    - 🟢 吸附分项弹出面板（点/线/线段/网格/参考线 5 项独立勾选）
  - 🟢 属性面板
    - 🟢 墙体属性（厚度 / 高度 / 弧墙细分 / 颜色 / 材质）
    - 🟢 门窗属性（尺寸 / 开启方向 / 样式 / 离地高度）
    - 🟢 家具属性（尺寸 / 旋转 / 位置 / 替换模型）
    - 🟢 区域属性（名称 / 颜色 / 材质）
    - 🟢 分组属性（整体缩放 / 重命名）
  - 🟢 场景设置
    - 🟢 场景尺寸（长 / 宽）
    - 🟢 天空（颜色 / 贴图 2 种模式，7+ 天空纹理）
    - 🟢 地面（颜色 / 贴图 2 种模式，60+ 地面 / 墙面 / 地板纹理）

- 🟢 文件与数据
  - 🟢 导入
    - 🟢 NXTS 格式（项目文件）
  - 🟢 导出
    - 🟢 NXTS 格式（完整项目 JSON，全量场景下载）
    - 🟢 GLTF 格式（三维场景直出，JSON 结构 + 贴图分离，含一键外景）
    - 🟢 GLB 格式（二进制单文件，贴图嵌入，含一键外景）
    - 🟢 OBJ 格式（纯几何体导出，含一键外景）
    - 🟢 SVG 格式（二维矢量图纸导出，含一键外景）
    - 🟢 2D / 3D 截图（PNG 格式，自动命名下载）

- 🟢 偏好设置
  - 🟢 外观
    - 🟢 浅色 / 深色主题（跟随系统 + 手动切换）
    - 🟢 界面语言（简体中文 / English，下拉切换即时生效）
  - 🟢 2D / 3D 视图设置
    - 🟢 缩放速度、平移速度、旋转速度、惯性开关
  - 🟢 单位
    - 🟢 公制单位（厘米 / 米），属性面板统一换算

- 🟢 快捷键
  - 🟢 项目操作
    - 🟢 新建项目（⌘/Ctrl + ⌥/Alt + N）
    - 🟢 保存（⌘/Ctrl + S）
    - 🟢 重命名（⌘/Ctrl + R）
    - 🟢 撤销（⌘/Ctrl + Z）
    - 🟢 重做（⌘/Ctrl + Y）

### 免责声明

---

本项目处于持续开发与迭代阶段，功能与界面可能随版本更新而调整，具体以实际发布内容为准。

</details>

<details>
<summary><strong>English / 英文</strong></summary>

### Introduction

---

Nxtspace Mobile is a 3D architectural scene-building mobile application built with React Native, designed specifically for the architecture and construction industry.

Whether you have prior experience with 3D modeling or are completely new to it, you can get started quickly. With Nxtspace Mobile, you can rapidly build 3D architectural scenes and create your own demo projects with ease.

Nxtspace Mobile supports Android and iOS, offering cross-platform performance through React Native and a unified mobile interaction experience via Gluestack UI.

### Models

---

Nxtspace Mobile supports importing and managing 3D model resources, giving users a rich library for architectural scene creation.

It supports free model assets from Sweet Home 3D, including:

- Furniture models
- Interior decoration models
- Lighting models
- Plant models
- Kitchen models
- Bathroom models
- Door and window models
- Architectural component models

Model sources:

- Sweet Home 3D official free model library
- User-customized 3D models

Sweet Home 3D free models:

https://www.sweethome3d.com/freeModels.jsp

### Platforms

---

- 🟢 Android
- 🟢 iOS

### Features & Roadmap

---

Legend: ⚪ Planned 🟡 In Progress 🟢 Completed

- 🟢 Editor Core
  - 🟢 2D Floor Plan
    - 🟢 Wall drawing (straight lines / arc walls, orthogonal / angle-based wall drawing, inner / outer / center alignment guides, cancel during drawing)
    - 🟢 Openings and windows (auto-cut openings when walls are inserted, single / double door / opening / multiple styles)
    - 🟢 Wall-to-window movement (drag to adjacent wall to create a seamless connection, dynamic measurement feedback, ghost preview during drawing)
    - 🟢 Area drawing (automatic area calculation for enclosed rooms, polygon support)
    - 🟢 Furniture placement (drag model into scene + real-time snap + placement preview)
    - 🟢 Vertex editing (drag endpoints / corners to refine wall geometry)
    - 🟢 Dimension annotation (real-time wall length / angle display, toggling visibility, direct input while drawing)
    - 🟢 Clearance ruler (real-time shortest distance to walls or nearby objects)
    - 🟢 Reference guides (horizontal / vertical / circular guides, color customization, layer-based management)
    - 🟢 Reference images (CAD / floor plans / any image as base tracing layer, scalable / movable / opacity adjustable)
    - 🟢 Grid and ruler system
    - 🟢 Context menu (copy / paste / delete / group / lock / properties / rename)
    - 🟢 Interactive mini-map
  - 🟢 3D Visualization
    - 🟢 2D / 3D view switching
    - 🟢 Orthographic / perspective projection switching
    - 🟢 Multiple camera views (front / side / top / bottom / left / right / isometric)
    - 🟢 View helper sphere
    - 🟢 Dollhouse mode
    - 🟢 Walkthrough mode
      - 🟢 First-person mode (WASD movement / Shift sprint / Space jump)
      - 🟢 Third-person orbit camera
    - 🟢 Stylized rendering modes (material / material + outline / outline only)
    - 🟢 Three rendering quality levels (high / balanced / performance)
    - 🟢 2D / 3D visual consistency
    - 🟢 Sky and ground system
    - 🟢 Right-side 3D live preview
    - 🟢 3D scene thumbnails

- 🟢 Asset Library
  - 🟢 Structural components
    - 🟢 Walls (thickness / height / material defaults)
    - 🟢 Openings (single door / double door / no door)
    - 🟢 Windows (size / sill / style)
    - 🟢 Areas (room parameter presets)
  - 🟢 Interior model library
    - 🟢 Category browsing (living room / bedroom / kitchen / bathroom / office / other)
    - 🟢 Search and filtering
    - 🟢 Custom model import (GLB / ZIP)
    - 🟢 Batch import

- 🟢 Material & Texture
  - 🟢 Material library tabs
  - 🟢 Material selector
  - 🟢 Drag-and-drop tiling
  - 🟢 Flood-fill material application
  - 🟢 Material brush tool

- 🟢 Editing & Operations
  - 🟢 Basic operations
    - 🟢 Pointer tool
    - 🟢 Selection (multi-select / box select / click select / inverse select)
    - 🟢 Move / rotate / scale (3-axis gizmo)
    - 🟢 Delete
    - 🟢 Element locking
    - 🟢 Copy / cut / paste
    - 🟢 Undo / redo
    - 🟢 Global component search
    - 🟢 Floor quick switching

- 🟢 Scene & Properties
  - 🟢 Shortcut tools panel
  - 🟢 Property panel
  - 🟢 Scene settings
  - 🟢 Wall default settings
  - 🟢 Area default settings

- 🟢 File & Data
  - 🟢 Import
    - 🟢 NXTS format
  - 🟢 Export
    - 🟢 NXTS
    - 🟢 GLTF
    - 🟢 GLB
    - 🟢 OBJ
    - 🟢 SVG
    - 🟢 2D / 3D screenshots

- 🟢 Preferences
  - 🟢 Appearance
    - 🟢 Light / dark theme
    - 🟢 UI language (Simplified Chinese / English)
  - 🟢 2D / 3D view tuning
  - 🟢 Unit conversion

- 🟢 Shortcuts
  - 🟢 Project actions
    - 🟢 New project
    - 🟢 Save
    - 🟢 Rename
    - 🟢 Undo
    - 🟢 Redo

### Disclaimer

---

This project is under active development. Features and interfaces may change as updates are released. Please refer to the actual published version for the latest details.

</details>

---

<p align="center">
  <sub>Built for architecture, interior planning, and 3D design workflows.</sub>
</p>
