# 333voidGirl's TF2 config
Should reproduce my exact TF2 settings (give or take things like volume, if I have chat, etc. as I change those often). Anything I cannot directly distribute (I.E. mods) should be linked below. I run the game using Vulkan on Arch Linux x86_64 [tkg kernel](https://github.com/Frogging-Family/linux-tkg). 

## Launch Options
gamemoderun %command% -enablefakeip -precachefontchars -particles 1 -no_texture_stream -nosteamcontroller -novid -nojoy -noff -nosteamcontroller -nohltv -w 1280 -h 960 -freq 165 -fullscreen -displayindex 0

## Hud
[m0rehud Linux branch](https://github.com/Hypnootize/m0rehud/tree/linux). 

## Graphics Mods
I use [mastercomfig](https://comfig.app/) (originally the medium low preset but I've tweaked it a lot in modules.cfg) in addition to a couple of their mods which you can install from the "app" section--namely the "No Footsteps" and "No Soundscapes" VPKs. I'm also using [https://github.com/JarateKing/CleanTF2plus](CleanTF2Plus) to get rid of bullet dust, generate flat textures, etc. If you're on Linux you might have to disable the checks to see if the folder is in the right place as the Linux version of TF2 doesn't have what CTF2+ is looking for and won't run otherwise (simply comment out the lines doing the checking and you should be fine lol). I also have renamed the folder "verycleantf2plus-linux64" to ensure it runs after my hud as renaming m0rehud breaks it and I was experiencing issues before doing this.

For reduced/no explosion smoke I use [Pyro Pool](https://drive.google.com/file/d/0B_loCHMSRedyc2ZqVWZGVXVFWGs/view?resourcekey=0-kLQ4d6BeqOGqIFEwHEjvug). You can read more and pick out your favorite effect [here](https://www.teamfortress.tv/25647).

I also use [No-Smoke Rocket Launcher Particles](https://gamebanana.com/mods/12418) and [ClearWater](https://gamebanana.com/mods/199840) although they don't work in casual. The [Modern Casual Preloader](https://gamebanana.com/wips/79779) may help you but it breaks my computer bc I run the game in 4:3 on Linux which is abnormal lol. I've not tried [Casual Particle Preloader](https://gamebanana.com/tools/19049) but it's recommended for particle mods. You could also use [EZ Casual Conversion Helper](https://gamebanana.com/tools/18215) to convert them if they don't work by default but I've not gotten the tool to work on Linux.

## Other Mods

[No After-Match Music](https://gamebanana.com/sounds/33479).

[Custom Pyrovision Goggles (fr0vision Animated Rainbow Gradient)](https://gamebanana.com/mods/547776). 

My hit and kill sounds are hardstyle kicks from the various Reddit Hardstyle Packs on /r/Hardstyle, the killsound being overlaid with the Quake "Holy Shit" sfx. 

