# Automatic-Wallpaper
Downloads wallpapers from the internet and changes your wallpaper periodically.

The Source Code is shown above, however if you just want to run the program an executable is provided:

[Click here to download [Win10]](https://github.com/gtyson/Automatic-Wallpaper/releases)

The wallpaper images will be stored in the folder called images, feel free to add or delete wallpapers to your preference

A settings file as well as an images folder will be generated in the first run.
The settings file contains the value for the time intervals between the wallpaper changes and startup options.
```python
{
  "time": 60
}
```
Set the value in minutes to your preference.

### AutoStart at Boot:
If you want the program to launch automatically at the start of your device

**Win10**
In the settings file change ```"starup" : false``` to ```True```.
