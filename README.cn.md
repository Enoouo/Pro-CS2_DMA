<div align="center">

<img src="https://github.com/user-attachments/assets/b17feaa3-f724-479a-8d21-e27706c387ed" width="1080" alt="Pro CS2 DMA Banner"/>

<h1>🌌 <b>Pro CS2 DMA</b></h1>

**[English](https://github.com/Enoouo/Pro-CS2_DMA/blob/main/README.md) | 简体中文**

> 「Pro CS2 DMA」 是一个以热爱为驱动的项目，核心使用 **C++** 与 **JavaScript/HTML** 编写。  
> 追求极致的性能、精准的逻辑与清晰的视觉表现。  
> 你的灵感，或许能成为下一次重大改进的关键。  

---

[![GitHub Stars](https://img.shields.io/github/stars/Enoouo/Pro-CS2_DMA?color=ffcc00&style=for-the-badge&logo=github)](https://github.com/Enoouo/Pro-CS2_DMA/stargazers)
[![GitHub Release](https://img.shields.io/github/v/release/Enoouo/Pro-CS2_DMA?color=1e88e5&style=for-the-badge&logo=rocket)](https://github.com/Enoouo/Pro-CS2_DMA/releases)
[![Downloads](https://img.shields.io/github/downloads/Enoouo/Pro-CS2_DMA/total?color=26a69a&style=for-the-badge&logo=github)](https://github.com/Enoouo/Pro-CS2_DMA/releases)

</div>

---

## ✨ 功能展示

| 功能 | 预览图 |
| :-- | :-- |
| 🎯 **瞄准** | ![aim](https://github.com/user-attachments/assets/2956b210-3e9b-4cf7-8136-693174c2ce5f) |
| 👁 **视觉** | ![esp](https://github.com/user-attachments/assets/85b5939d-9b2d-4b72-b8cc-a7b340d6b34f) |
| ⚙ **杂项** | ![misc](https://github.com/user-attachments/assets/d79b55cc-2045-42e3-9ba0-479e391fca84) |
| 🧩 **其他** | 平台加密解密 · 通过 VPK 解析实现可见性检测 |

---

## 📸 功能演示

> **ESP 功能演示**
>
> ![esp](https://github.com/user-attachments/assets/76f2fe8f-c0d5-4852-97cd-a5b98f7bd548)
>
> **可见性检测与动态 FOV**
>
> ![IMG_0098 mov_20240820_010313_compressed](https://github.com/user-attachments/assets/54c6202b-45c7-40da-a8a5-36d68993c030)

---

<div align="center">

<h2>🧭 Web 雷达</h2>

<p>简洁易读 · 无限缩放 · 实时同步</p>
<p>支持 <b>静态模式</b> 与 <b>旋转模式</b>，可随视角自动旋转。</p>

<img src="https://github.com/user-attachments/assets/30b4b6c6-2239-435d-bd4c-f6f26f656e8a" width="750" alt="Radar"/>

</div>

---

## 🗺 雷达标识说明

| 图标 | 类型 | 说明 |
| :--: | :--: | :-- |
| ![player](https://github.com/user-attachments/assets/b41a9cdc-6461-47e9-a2c8-860e13e1f260) | 默认 | 显示所有玩家、武器及昵称 |
| ![host_dot](https://github.com/user-attachments/assets/98a2df8b-3722-49b0-b36d-c5a38267a245) | 主视角玩家 | 当前选中的主视角目标 |
| ![low hp](https://github.com/user-attachments/assets/101e1743-abca-4cf3-a6c8-f2dbe81ca284) | 血量指示 | 血环颜色随生命值动态变化 |
| ![boom player](https://github.com/user-attachments/assets/44848735-f3ee-4c59-9d8e-a6476ef302e7) | 携带 C4 玩家 | 显示携带炸弹的玩家 |
| ![dead](https://github.com/user-attachments/assets/16de6160-cb20-4273-b4ef-7e255db29bff) | 死亡状态 | 被击杀的玩家会以淡十字显示 |
| ![f1](https://github.com/user-attachments/assets/e6e2fcf2-d29a-4c14-bbb6-da1b9a845ce0) | 开火状态 | 显示正在射击的玩家 |
| ![Hurt](https://github.com/user-attachments/assets/8207e985-e6f9-49ff-ac47-776c3e7abf0d) | 受伤 | 显示玩家受到伤害的状态 |
| ![shan](https://github.com/user-attachments/assets/7a4edc95-f4bf-4323-8833-485db1b82173) | 致盲 | 玩家被闪光弹致盲时显示 |
| ![smoke](https://github.com/user-attachments/assets/e0287184-10de-47f0-8cf9-9e3ed3697d86) | 烟雾 | 显示 CT/T 双方的烟雾弹 |
| ![huo](https://github.com/user-attachments/assets/354542b5-0c90-46f2-8f46-ae2b1a0905dd) | 火焰 | 显示燃烧弹与燃烧区域 |
| ![zhayan](https://github.com/user-attachments/assets/09937762-0e49-46f2-ac1e-bd0bf7fd0547) | 爆炸 | 显示爆炸类物体的触发点 |

---

### 🎥 自动聚焦（Autozoom）

当存活玩家较少时，雷达上会出现大量空白区域。  
**Autozoom 自动缩放功能** 可智能聚焦战斗区域，并随战况平滑移动。

<div align="center">
<img src="https://github.com/user-attachments/assets/28a271a4-d1ce-4516-ac13-740db8efcab0" width="520" alt="Autozoom"/>
</div>

---

### ⚠️ 事件提示（Advisories）

系统会自动检测关键事件，帮助观战者快速响应。

| 图标 | 事件 | 说明 |
| :--: | :--: | :-- |
| ![no](https://github.com/user-attachments/assets/285a2d04-5001-4a59-ac1f-b954e4c15fc1) | 默认 | 当前无特殊事件 |
| ![plant](https://github.com/user-attachments/assets/af6671fc-581c-4858-af52-b39487e2d625) | 已安装炸弹 | 显示倒计时与爆炸时间 |
| ![chai](https://github.com/user-attachments/assets/8b698bfc-623b-4d75-b6a9-5334384db852) | 正在拆弹 | CT 正在进行拆除操作 |

---

### 💡 其他特性
- 烟雾、燃烧弹、闪光弹均显示在地图上  
- Nuke / Vertigo 地图支持上下层分层显示  
- 玩家高度差以颜色或比例标识  
- 可自定义任意雷达背景颜色（含全透明）  
- 支持玩家选择与队友隐藏  

---

## 🚀 使用说明

1. 📦 下载最新版本 [**Release**](https://github.com/Enoouo/Pro-CS2_DMA/releases)  
2. ▶ 运行 `radar.exe`（如需使用雷达功能）  
3. 🎮 运行 `Pro CS2.exe`  
4. ✅ 享受增强的 CS2 游戏体验！  

---

> [!NOTE]
> 源码将在整理完毕后发布。  
> 当前提供可执行版本用于测试。

💬 有任何建议或问题？请通过 [**Issues**](https://github.com/Enoouo/Pro-CS2_DMA/issues) 告诉我！  
⭐ 如果本项目对你有帮助，请点亮一个 **Star** 支持后续更新！

---

<div align="center">

**Made with ❤️ by [Enoooo](https://github.com/Enoouo)**  

<img src="https://img.shields.io/github/stars/Enoouo/Pro-CS2_DMA?style=for-the-badge&color=ffcc00" />
<img src="https://img.shields.io/github/v/release/Enoouo/Pro-CS2_DMA?style=for-the-badge&color=1e88e5" />
<img src="https://img.shields.io/github/downloads/Enoouo/Pro-CS2_DMA/total?style=for-the-badge&color=26a69a" />

</div>
