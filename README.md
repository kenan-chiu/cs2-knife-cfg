## how to use

### Step 1:
Download the .cfg files and move them to your game directory. Don't delete the custom folder, just leave it like that.  
**Make sure you go to ``game\core\cfg``, NOT ``game\csgo\cfg``**  
> For me this will be  
> ``C:\Program Files (x86)\Steam\steamapps\common\Counter-Strike Global Offensive\game\core\cfg``

### Step 2:
Join a custom server and type in console ``exec knife_binds``

### Step 3:
Drop your knife on the ground. Look at it and type in the console what knife you want.  
For example your console will look like this:

``> stiletto``  
``[InputService] execing custom/knives/stiletto``  
``[Console] subclass_change: Changed entity 498 from subclass 59 -> subclass 522``  

And now you can pick up your new knife.  

### Note:
You can spawn a new knife with this command:  
`give weapon_knife`  

The numpad on your keyboard will change the knife for you.  
This is optional, feel free to delete if you're already using the numpad for other binds.  
```
1 = M9 BAYONET  
2 = BUTTERFLY  
3 = SKELETON  
4 = KARAMBIT  
5 = BOWIE  
6 = BAYONET  
7 = STILETTO  
8 = FLIP  
9 = SURVIVAL  
0 = DEFAULT
```
If you want to change numpad 1 to spawn a karambit instead of an m9, edit in your cfg:  
`bind "KP_1" "m9bayonet;"` -> `bind "KP_1" "karambit;"`.  
Change this as well to remind yourself.  
`echo 1 = M9 BAYONET` -> `echo 1 = karambit`.
