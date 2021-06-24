# [MobileIconChanger](https://github.com/programminghoch10/MobileIconChanger)
Change your mobile data icons! For example you can change the 3G/4G icons into 5G!

This module enables you to replace any of the mobile data icons with any other mobile data icon.

## Compatibility

Since you're probably reading this within `LSPosed Manager` your device should be compatible.
[Read more about compatiblity here](https://github.com/programminghoch10/MobileIconChanger#compatibility).

## Installation

1. Install the module on a system with a running XPosed framework with API version `>=93`.
1. Activate the resource hooks within your XPosed framework manager.
1. Activate the module. The package `SystemUI` should automatically be selected.
1. Restart your phone.
1. You are now ready to use the module. You will need to open the [Configuration](#configuration) screen to set it all up, as the module won't do anything yet.

## Configuration

_I don't like it when every XPosed module adds yet another app icon to the launcher. This is why this modules settings are hidden within the App-Info screen._

Here is how to open the settings:

- Route 1:
    - Go to the module list within your XPosed manager
    - Long press on `CameraControl` and select App Info
    - On the bottom, click on `Advanced`
    - Click on `Additional settings in the app`
- Route 2:
    - Go into device settings
    - Click on apps
    - Somehow tell the device to show all apps
    - Select `CameraControl`
    - On the bottom, click on `Advanced`
    - Click on `Additional settings in the app`
- Route 3:
    - Open up an ADB shell
    - Run command `am start-activity com.programminghoch10.mobileiconchanger/.SettingsActivity`

## More resources

I don't want to keep 4 different places up to date.

If you want to read more about 
[why this module exists](https://github.com/programminghoch10/MobileIconChanger#inspiration)
or [additional info about the configuration interface](https://github.com/programminghoch10/MobileIconChanger#configuration)
or [you just want to see some screenshots first](https://github.com/programminghoch10/MobileIconChanger)
head over to [the GitHub Repo](https://github.com/programminghoch10/MobileIconChanger).
