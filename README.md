![1](https://github.com/Gamelover7825/BRVM/blob/main/resources/brvm_250502.png)

## How to install

1. Install the provided versions of _Termux_, _Termux-x11_ and _InputBridge_
2. Put the _BRVM.tar.gz_ file into the _Download_ folder
3. Run the following commands in _Termux_:

`termux-setup-storage`

`tar -zxf /sdcard/Download/BRVM.tar.gz -C /data/data/com.termux/files --recursive-unlink --preserve-permissions`

4. Restart _Termux_ when a new line appears, then run the virtual machine using the `brvm` command
5. Wait until the desktop is completely set up. Every time you restart _Termux_, run the virtual machine using the `brvm` command

### System requirements 
**OS:** 64-bit Android 10.0+

**GPU:** Adreno 610+ _(Mali and PowerVR not supported)_

**RAM:** minimum 6, 8 or 12 GB _(depending on game)_

### Recommended Termux-x11 settings

***Display Resolution Mode** = exact*

***Display Resolution** = 800x600*

***Show Additional Keyboard** = disabled*

***Fullscreen on Device Display** = enabled* 


## How to get games

You can find here some games pre-configured for minimal memory usage: https://github.com/piman-dev/BRVM-PreconfiguredGames/releases

You can find here some controls profiles for the _InputBridge_ app: https://github.com/piman-dev/BRVM-PreconfiguredGames/releases/tag/controls_ib


## How to run the pre-configured games directly from the homescreen


1. Make sure that a supported BRVM version is installed and completely set up, Termux allows _notifications_ and _drawing over other apps_
2. Install the provided utilities, _Activity Launcher_ and _Termux Widget_
3. Inside the virtual machine, create a folder _.shortcuts_ in _Z:\home_ if not exist, place there the shortcut script file for your game and BRVM version
4. Using _Activity Launcher_, run the _Termux Shortcut_ activity of the _Termux Widget_ app, and tap on the shortcut script file to add it to the homescreen
5. The game may be run minimized, tap _Termux_ in the notification panel to open it. If you have done everything correctly, your game will be run instead of the file manager
6. If the game does not run directly from the shortcut, enable _Force Landscape Orientation_ in _Termux-x11_ settings
7. Some games may require a specific action to be successfully run from shortcut



## Development builds

You can find here some development builds of the project and experimental pre-configured games: https://github.com/piman-dev/BRVM-Development



## Special thanks to

**alexvorxx:** Turnip + Zink libraries for Direct3D support in the project

**Alpyne Dreams:** D8VK libraries, used by Direct3D 8 games

**doitsujin:** DXVK libraries, used by Direct3D 9-12 games

**DotNetBurst:** InputBridge controls overlay

**DreamWorks Animation LLC:** the 2 women on the project logo

**Fredrick Fornwall:** Termux

**Ilya114:** Box64Droid, one of the emulators which the project is built on the top of

**JeezDisReez:** glibc prefix for Termux

**olegos2:** Mobox, one of the emulators which the project is built on the top of

**ptitSeb:** Box64 and Box86 compatibility layers

**Rob Clark:** Freedreno Turnip drivers for Qualcomm Snapdragon chips

**WineHQ:** Wine compatibility layer
