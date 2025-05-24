Astc OpenGL3  
4x4 - low quality  
8x8 - best mix  
16x16 - highest  

name.hd.astc.pvr textures - single resolution  
name.astc.pvr - same res + full mip mapping  

linear - non pbr  
srgb(name_BC) - pbr  

-----------------------------  

BC - convert in Paint.Net or Nvidia Texture Tools to TGA then in PVRTexTool to astc srgb  
Astc to BC - ABGG  

-----------------------------  

PvrTexTool channel editor ![image](https://github.com/user-attachments/assets/77df45b8-8ead-4d62-ab2c-e1874d0b6760)  

ANM/NM/MISC/RM/MASK/CM  

With Alpha:  
Channels RGBA to A-A-A-G  

Without Alpha(its content in RED):  
Channels RGBA to R-R-R-G  

No Alpha at all:  
Channels RGBA to G-G-G-G  

-----------------------------
-----------------------------

Purple or green(pbr) squares(missing textures)? Probably name issue  
Very dark unlike pc? Check alpha  
