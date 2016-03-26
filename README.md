### Map edit by 50k
This is ETS2 map mod created by 50k, which will include rework of base map with various new prefabs etc.
This repository is a bit different than other 50k-customs repositories, as it features multiple targets/mods.

![](/preview/release_1_0.png?raw=true "Promo 1.0")


### CONTENTS
1. **"base"** folder where all existing ETS2 resources are saved only for proper loading in BT and 
thus don't need to be packed into final mod at all;
2. **"mod_map"** folder used as mod base of ETS2-MapEdit
2. **"mod_small_market"** folder used as additional mod base of "Small Market" prefab which has only 1 unloading point, moreover
it's layout matches boundaries of vanilla "Sellplan" prefab from ETS2 and can be packed into a mod separately.


### USAGE

Most recent direct ETS2-MapEdit mod download and all needed info can be found here 
**[@LATEST VERSION](../../releases/latest)**

***For advanced usage, step by step:***

1. Download [Conversion Tools](http://modding.scssoft.com/wiki/Documentation/Tools/Conversion_Tools) and unpack them to **\<folder_tools>**
2. Download this repository by clicking Download ZIP on the right/top site of web page and unpack it to **\<map_edit_folder>**
3. Open file **\<folder_tools>/conversion_tools/extra_mount.txt** and add paths depending on your needs:
  
  1. Convert map with all dependencies:
  
    ```
    <map_edit_folder>/mod_map
    <map_edit_folder>/mod_small_market
    ```
  2. Convert only Small Market prefab:
  
    ```
    <map_edit_folder>/mod_small_market
    ```
4. Go to **\<folder_tools>/conversion_tools/rsrc** and delete any content inside this folder
5. Go to **\<folder_tools>/conversion_tools** and run **convert.cmd**
6. Go to **\<folder_tools>/conversion_tools/rsrc** again and pack it's content as zip
7. Use zipped file as regular mod.
