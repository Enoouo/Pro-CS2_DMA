![cs2-2024](https://github.com/user-attachments/assets/afbeb13e-1f2f-4a98-a77a-fb0f42a3ecf7)
# <p align="center">Pro CS2 DMA</p>

**<p align="center">[English](https://github.com/Enoouo/Pro-CS2_DMA/blob/main/README.md) | 简体中文</p>**


<p align="center">「Pro CS2 DMA」是一个兴趣项目，我会尽力去优化使用体验，希望大家可以提出好的改进建议，项目本身是C++，雷达基于JavaScript和HTML，建议可以是专业技能相关的，也可以是自然语言逻辑表达，每个人都很聪明，也许你的灵感可以给项目带来很大帮助。</p>

## ✨功能 
+ 瞄准🔫
  - 自瞄
  - 磁性扳机
  - 扳机
  - 反后坐力
  - 动态 FOV
  - 武器分组设置: 步枪, 狙击枪, 微冲, 霰弹枪...

+ 视觉👀
  - 方框显示
  - 骨骼显示
  - 关节显示
  - 玩家昵称显示                          
  - 武器显示
  - 血量显示
 
+ 其他
  - 基于解析地图文件的掩体检测
  - 解密平台的加密
 
## 🧩 截图
> 视觉效果演示
> 
> ![esp](https://github.com/user-attachments/assets/e6df2d18-6c16-411c-8d72-a9578cb7be73)
> 
> 掩体检测和动态FOV演示  
> ![IMG_0098 mov_20240820_010313_compressed](https://github.com/user-attachments/assets/54c6202b-45c7-40da-a8a5-36d68993c030)



                              

 

# <p align="center">网页雷达🧭</p>
<p align="center">易于阅读, 可调整大小，支持移动端观看</p>
<p align="center">两种样式: 静态和动态, 雷达跟随主视角移动和旋转</p>

**<p align="center">![test01](https://github.com/user-attachments/assets/3fddaf8a-29c0-4bdb-abe3-07eef1d42a88)      ![2024-08-19 21-57-16 mkv_20240820_003716_compressed](https://github.com/user-attachments/assets/16092ecd-3e24-45c0-9f0b-13dccefbc817)</p>**

## 🎉雷达功能
|     标记    |   类型   |     描述     |
|  :---:       |   :---:  |         :---:       |
|  ![ct_or_t](https://github.com/user-attachments/assets/173d2ba2-eae1-4ba7-8e80-11e5d85e137b)| 默认     | 区分CT和T阵营玩家，同时显示玩家所持的武器和玩家昵称    |
|  ![host_dot](https://github.com/user-attachments/assets/98a2df8b-3722-49b0-b36d-c5a38267a245)| 高亮玩家    | 高亮显示选择的玩家，由于颜色差异，容易区分      |
|  ![hp_dot](https://github.com/user-attachments/assets/95df1103-a9cb-48ae-8eeb-f1e8cdea3132)| 血量环  | 当玩家损失血量后，血量环的颜色会随之变化      |
|  ![boom](https://github.com/user-attachments/assets/718e966d-aaee-443e-bc70-05e1a18f0689)| 炸弹  | 显示携带C4的玩家，由于颜色差异，很容易在雷达上发现      |
|  ![dead_dot](https://github.com/user-attachments/assets/fcaa4f10-0b0c-41db-bedb-9d9b2aca9869)| 死亡  | 被击杀的玩家在雷达上仍会隐约显示小十字      |

### 战斗动态

当仅有少数玩家存活时，大部分雷达显示区域都是空的，只有很小的一部分包含所有的战斗，自动缩放功能解决了这个问题。雷达图像可以根据玩家所在位置自动平移和缩放，并且平滑地跟随战斗动态。
  **<p align="center">![697](https://github.com/user-attachments/assets/28a271a4-d1ce-4516-ac13-740db8efcab0)</p>** 
自动缩放功能试图将战斗保持在雷达的中央，周围留有一定的安全间隔，以确保玩家不会意外地跑出雷达图像。它还具有一个最小缩放级别，因此只有当战斗集中在地图的一小部分时，雷达才会放大显示 

  


### 提示

  提示是自动检测到的事件，观察者可能会希望了解到这些事件。 

|     Advisory    |   Type   |     Description     |
|  :---:       |   :---:  |         :---:       |
|  ![6877](https://github.com/user-attachments/assets/0ea14f54-aa51-40f4-8137-e03e4e9f22ce)| Default     | This is displayed when no other notable events are happening.    |
|  ![33a](https://github.com/user-attachments/assets/b733d1ea-91d3-46a4-acf3-715ed114b164)| Defusing      | A CT is defusing the bomb.      |  



### 更多
  + 在地图上显示烟雾弹、燃烧弹和闪光弹
  + 为Nuke和Vertigo的上下层地图提供分离显示
  + 玩家标记的Z轴高度指示器，可以通过颜色点或比例尺显示
  + 支持任意雷达背景颜色，包括完全透明
  + 玩家选择，选择主视角
  + 隐藏队友



# 怎么使用 ❓

  1. 下载最新[发布](https://github.com/Enoouo/Pro-CS2_DMA/releases)的版本。
  2. 下载项目中 'maps' 目录下的 [地图](https://github.com/Enoouo/Pro-CS2_DMA/tree/main/maps) 文件。
  3. 解压后确保目录结构正常
     - 📁web radar
       - radar.exe
       - ...
       - ...
     - 📁maps
        - de_mirage
        - de_inferno
        - de_dust2
        - ...
        - ...
     - Pro CS2.exe
     - config.cfg
     - offsets
     - leechcore.dll
     - ...
     - ...
  4. 运行 `radar.exe` (如果使用此功能)
  5. 运行 `Pro CS2.exe`
  6. 享受游戏😀


# 计划任务 📑  

  - [ ] 修复 Esp 显示有点延迟的问题
  - [ ] 优化 aimbot 移动轨迹更像人类
  - [ ] aimbot 骨骼自定义多选(目前步枪:头, 颈部; 手枪:头，狙击枪:头， 颈部，上躯干， 下躯干)
  - [ ] aimbot 增加死区
  - [ ] 修复 Magnet triggerbot 功能下 狙击枪的表现
  - [ ] 完善网页雷达功能
  - [ ] 网页雷达增加道具飞行轨迹
  - [ ] 处理关于C4的问题，遍历C4过于消耗性能，现在关闭了，等找到解决方案再完善
  - [ ] 优化内存读取性能
  - [ ] 重新修改kmbox相关代码

    

    

> [!IMPORTANT]
> 还有些功能需要完善，我会尽快更新，等代码整理完善好后上传源码，在此之前先发布打包好的程序。 

对于项目您有什么建议，请使用 'Issues' 告诉我 

如果项目给您提供了帮助，请为我点一个⭐star⭐




