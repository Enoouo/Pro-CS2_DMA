![cs2-2024](https://github.com/user-attachments/assets/afbeb13e-1f2f-4a98-a77a-fb0f42a3ecf7)
# <p align="center">Pro CS2 DMA</p>

**<p align="center">English | [简体中文](https://github.com/Enoouo/Pro-CS2_DMA/blob/main/README.cn.md)</p>**


<p align="center">「Pro CS2 DMA」 is a passion project, and I will do my best to optimize the user experience. I hope everyone can offer good suggestions for improvement. The project itself is in C++, with the radar based on JavaScript and HTML. Suggestions can be related to technical skills or even natural language logic. Everyone is smart, and maybe your inspiration can bring significant improvements to the project.</p>

## ✨Features 
+ Aimbot🔫
  - Aimbot
  - Magnet triggerbot
  - Triggerbot
  - Recoil with smoothing
  - Dynamic FOV
  - Weapon group: rifle, sniper, smg, shotgun...

+ Visuals👀
  - Esp Box
  - Esp Bones
  - Esp Joints 
  - Player name                            
  - Weapon
  - Health
 
+ Misc
  - Visible check via VPK parsing
  - Decrypt platform encryption
 
## 🧩 Screenshots
> Esp feature demonstration.
> 
> ![esp](https://github.com/user-attachments/assets/e6df2d18-6c16-411c-8d72-a9578cb7be73)
> 
> Visible check and dynamic FOV feature demonstration.
> ![IMG_0098 mov_20240820_010313_compressed](https://github.com/user-attachments/assets/54c6202b-45c7-40da-a8a5-36d68993c030)



                              

 

# <p align="center">Web Radar🧭</p>
<p align="center">Easy to read, infinitely resizeable.</p>
<p align="center">Two styles: static and centered, rotating with the view.</p>

**<p align="center">![test01](https://github.com/user-attachments/assets/3fddaf8a-29c0-4bdb-abe3-07eef1d42a88)      ![2024-08-19 21-57-16 mkv_20240820_003716_compressed](https://github.com/user-attachments/assets/16092ecd-3e24-45c0-9f0b-13dccefbc817)</p>**

## 🎉Radar Features
|     Dots    |   Type   |     Description     |
|  :---:       |   :---:  |         :---:       |
|  ![ct_or_t](https://github.com/user-attachments/assets/173d2ba2-eae1-4ba7-8e80-11e5d85e137b)| Default     | Both CT and T players are shown, along with the weapon they're holding and their nickname.    |
|  ![host_dot](https://github.com/user-attachments/assets/98a2df8b-3722-49b0-b36d-c5a38267a245)| Host       | The selected main view player is easy to distinguish.      |
|  ![hp_dot](https://github.com/user-attachments/assets/95df1103-a9cb-48ae-8eeb-f1e8cdea3132)| Health indicator  | When a player loses health, the color of the health ring will change accordingly.      |
|  ![boom](https://github.com/user-attachments/assets/718e966d-aaee-443e-bc70-05e1a18f0689)| Bomb carrier  | Shows the player that has the C4 with them. Easily spottable on the radar because of the color difference.      |
|  ![dead_dot](https://github.com/user-attachments/assets/fcaa4f10-0b0c-41db-bedb-9d9b2aca9869)| Dead  | Killed players are still faintly visible on the radar as a small cross.      |

### Follow the action  

When only a few players are alive most of the radar is just empty and only a very small part contains all the action. Boltobserv has an autozoom feature that fixes this. The radar image can automatically pan and zoom according to where the players are located, and smoothly follows the action.
  **<p align="center">![697](https://github.com/user-attachments/assets/28a271a4-d1ce-4516-ac13-740db8efcab0)</p>** 
Autozoom tries to keep the action in the middle, with a safe padding around any players so they can never accidentally run off the radar image. it also has a minimal zoom level, so that the radar only zooms in when the action is concentrated in a small part of the map.  

  


### Advisories

  Advisories are automatically detected events that the observer might want to switch to. To make switching to this event easier, the observer slot number is displayed next to an icon noting the type of advisory. The observer should still make his own judgment of the situation.  

|     Advisory    |   Type   |     Description     |
|  :---:       |   :---:  |         :---:       |
|  ![6877](https://github.com/user-attachments/assets/0ea14f54-aa51-40f4-8137-e03e4e9f22ce)| Default     | This is displayed when no other notable events are happening.    |
|  ![33a](https://github.com/user-attachments/assets/b733d1ea-91d3-46a4-acf3-715ed114b164)| Defusing      | A CT is defusing the bomb.      |  



### And much more
  + Smokes, molotovs and flashbangs shown on the map
  + Split maps for upper and lower on Nuke and Vertigo 
  + Player dot z-height indicators, either by color dot or scale
  + Any radar background color, including full transparency
  + Player selection, choose the main view
  + Hide teammates



# How to use ❓

  1. Download the latest [release](https://github.com/Enoouo/Pro-CS2_DMA/releases).
  2. Download the [map](https://github.com/Enoouo/Pro-CS2_DMA/tree/main/maps) files in the project's maps directory.
  3. After extracting, maintain the following directory structure.
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
  4. Run `radar.exe` (if using this feature).
  5. Run `Pro CS2.exe`
  6. Enjoy the game😀


# Planned tasks 📑  

  - [ ] Fix the slight delay in ESP display
  - [ ] Optimize aimbot movement trajectory to make it more human-like
  - [ ] Customize multiple bone selections for aimbot (currently: rifle: head, neck; pistol: head; sniper rifle: head, neck, upper torso, lower torso)
  - [ ] Add a dead zone to aimbot
  - [ ] Fix the performance of sniper rifles under the Magnet triggerbot function
  - [ ] Improve web radar functionality
  - [ ] Add item flight trajectory to web radar
  - [ ] Address issues related to C4, as traversing C4 consumes too much performance. It's currently disabled and will be improved once a solution is found
  - [ ] Optimize memory reading performance
  - [ ] Revise kmbox-related code

    

    

> [!IMPORTANT]
> There are still some features that need improvement, and I will update them as soon as possible. Once the code is organized, I will upload the source code. In the meantime, I will first release the packaged program. 

If you have any suggestions regarding the project and its features, you can use the Issues section to let me know. 

If the project has been helpful to you, please give it a ⭐star⭐.




