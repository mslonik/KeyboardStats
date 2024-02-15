# KeyboardStats.ahk

Simple monitoring of pressed keys with heat map displayed in a form of GUI.
Microsoft Windows only.
Statistics is saved in a log file every hour since the application starts.
Written in [AutoHotkey][] language.

## Screen shots

The default GUI, when some keyboard keys are already pressed:
![GUI 1](/pictures/GUI01.png) 

After pressing Ctrl key you get statistics about specific keys:
![GUI 1](/pictures/GUI02.png)

After clicking of a key with left mouse button the tooltip is displayed for 5 s:
![GUI 1](/pictures/GUI03.png)

## Activation

Click in system tray, next in icon of **KeyboardStats**, left mouse click. The GUI will be displayed in the front of your default monitor.

Left mouse click brings tiny menu:
![GUI 1](/pictures/Tray01.png)

## Hotkeys

Hotkeys are active only when GUI window is active.

| hotkey | meaning | comment |
| :---         |     :---:      |          ---: |
| Control      | to display individual values for pressed keys     | left or right    |
| F1 or ?      | to display this info       | _        |
| F2           | to copy current results to Clipboard | | 	
| F3			| to copy heatmap scale to Clipboard | |
| F4			| to save current results to log | |
	
If you click with left mouse button in key name, then current value is displayed for 5 s in form of a tooltip.

[AutoHotkey]: https://www.autohotkey.com/