# wow-3.3.5-dxvk
pre-configured build and config of DXVK for wow 3.3.5 clients

The purpose of this is to **increase FPS** in most cases, as well as potentially fix some (gpu) issues and allow for some extra configuration.

I've tested this build and config for a very long time with very little crashes or problems on my AMD gpu, and some other people used the same files successfully. 
However I do not offer any support if anyone is having problems with it.

## How to install
[Download zip file](https://github.com/Satela-wow/wow-3.3.5-dxvk/archive/refs/heads/main.zip).

Then simply copy d3d9.dll and dxvk.conf to your wow folder, not a subfolder. They need to be in the same folder as your wow.exe

If you already have one of these files, you have a conflicting mod of some sort. (ENBSeries or another dxvk build most likely) Remove it if you want to use this DXVK version.
Do not try to install another mod that replaces d3d9.dll such as ENBSeries, this does not work!

#### Uninstall / disable
Simply delete or rename at least the d3d9.dll file, this prevents it from loading in.

## Credit
I did NOT compile this binary, nor write this config, it originated from a [post on the Warmane forums](https://forum.warmane.com/showthread.php?t=440657). The binary is from [this release of DXVK](https://github.com/Sporif/dxvk-async/releases/tag/2.0). 

I do not take any credit for any of this as a result. I am offering this here to simplify setup for people who want to use this, nothing more.
