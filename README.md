# GameHub PRIME Render Offload Tweak
Tweak for GameHub that allow to use discrete Nvidia graphics card  
  
## How To Use  
Copy [prime.json](https://github.com/demonich/GameHub-prime-render-offload-tweak/blob/main/prime.json) to tweaks folder.  
To find out the location of this folder, go to the GameHub settings. Then check out the "Tweaks" tab.  
After copying enable tweak in GameHub settings. 
  
## Issues  
Perhaps steam games will not be able to work with this tweak. In this case, you need to add the required properties for each game manually.  
go to the library > right click on the game > properties. Click "set launch options" and past this:  
```
__NV_PRIME_RENDER_OFFLOAD=1 __GLX_VENDOR_LIBRARY_NAME=nvidia __VK_LAYER_NV_optimus=NVIDIA_only %command%
```
## Warning  
**This tweak only works if your system supports nvidia on-demand.**  

### [GameHub](https://github.com/tkashkin/GameHub)  
### [PRIME Render Offload](https://download.nvidia.com/XFree86/Linux-x86_64/435.21/README/primerenderoffload.html)  
