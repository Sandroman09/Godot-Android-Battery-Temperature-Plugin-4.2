# Godot-Android-Battery-Temperature-Plugin-4.2
Android plugin for Godot used to access the battery temperature of android devices. It should work on Godot versions 4.2+ but it has only been tested in version 4.5.1

## How to use it
1) Copy the GDBatteryTemp folder into the addons folder of your Godot project.
  <img width="252" height="79" alt="image" src="https://github.com/user-attachments/assets/39bf26a5-d3f0-4324-b494-fc389e7ba7b6" />
  
2) Activate the plugin in the project settings.
  <img width="1919" height="1027" alt="Screenshot 2025-12-30 123201" src="https://github.com/user-attachments/assets/7de160e0-a811-4f51-9d32-63d30c911cb6" />

3) Add a new node and select GodotAndroidBatteryTemperature.
  <img width="891" height="721" alt="Screenshot 2025-12-28 232255" src="https://github.com/user-attachments/assets/7e6f3962-5c65-4034-8682-edb834ff725d" />
  
4) On the GodotAndroidBatteryTemperature node you will be able to call the get_battery_temperature() method, it will return the battery temperature
5) If you are exporting the project to android remember to enable gradle build otherwise the plugin won't work.
