# Godot-Android-Battery-Temperature-Plugin-4.2
Android plugin for Godot used to access the battery temperature of android devices. It should work on Godot versions 4.2+ but it has only been tested in version 4.5.1

## How to use it
1) Copy the GDBatteryTemp folder into the addons folder of your Godot project.
<img width="252" height="79" alt="image" src="https://github.com/user-attachments/assets/39bf26a5-d3f0-4324-b494-fc389e7ba7b6" />

3) Activate the plugin in the project settings.
4) Add a new node and select GodotAndroidBatteryTemperature.
5) On the GodotAndroidBatteryTemperature node you will be able to call the get_battery_temperature() method, it will return the battery temperature
6) If you are exporting the project to android remember to enable gradle build otherwise the plugin won't work.
