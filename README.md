# wow-3.3.5-dxvk
pre-configured build and config of DXVK for wow 3.3.5 clients

The purpose of this is to **increase FPS** in most cases, as well as potentially fix some (gpu) issues and allow for some extra configuration.

I've tested this build and config for a very long time with very little crashes or problems on my AMD gpu, and some other people used the same files successfully.

## How to install
Download by clicking on 'Code' -> Download zip. 

Then simply copy d3d9.dll and dxvk.conf to your wow folder, not a subfolder. They need to be in the same folder as your wow.exe

If you already have one of these files, you have a conflicting mod of some sort. (ENBSeries or another dxvk build most likely) Remove it if you want to use this DXVK version.
Do not try to install another mod that replaces d3d9.dll such as ENBSeries, this does not work!

## Credit
I did NOT compile this binary, nor write this config, it originated from a [post on the Warmane forums](https://forum.warmane.com/showthread.php?t=440657). The binary is from [this release of DXVK](https://github.com/Sporif/dxvk-async/releases/tag/2.0). 

I do not take any credit for any of this as a result. I am offering this here to simplify setup for people who want to use this, nothing more.
