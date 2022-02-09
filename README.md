# 🔧FiveM-SteeringWheel-Compatible

## ⭐CREDITS / ❗COPYRIGHT
**I am not the owner. I don't know who is the owner, because my friend used this plugin 1 year ago and it was free. Maybe it was removed maybe, maybe not.
If you are the creator and don't want this resource to be here on GitHub, just create an issue and pull request. It was a very good plugin, so I reuploaded it on GitHub.**

## 📺Preview / Settings
[Video](https://youtu.be/FqN7JuryX4A)

## 📗Installation
1. Rightclick:  FiveM
2. Click: Open file path
3. Go into the `FiveM ApplicationData`
4. Create a `plugins` folder, maybe you already have the folder
5. Put the `ManualTransmission` and the `Gears.asi` inside the `/plugins` folder.
- _Steps to be taken by developers:_
6. Open the `server.cfg`
7. Navigate to:
```
# This allows players to use scripthook-based plugins such as the legacy Lambda Menu.
# Set this to 1 to allow scripthook. Do note that this does _not_ guarantee players won't be able to use external plugins.
sv_scriptHookAllowed 0
````
8. Change
```sv_scriptHookAllowed 0``` to ```sv_scriptHookAllowed 1```
**⚠️Be careful! This allows Modmenus on the server and more plugins!**

### ⚙️Setings
All Settings can be found in the `ManualTransmission`.