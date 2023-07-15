# Chronometer_FreeCAD
A macro to run a chronometer in FreeCAD and record 3D modeling times of different parts

It is designed for all those FreeCAD users who want to practice for the 3D CAD SpeedModeling World Championship.
https://tootalltoby.com/leaderboard/

![capture](https://github.com/andesfreedesign/Chronometer_FreeCAD/blob/main/chronometer.png)

### Installation on Debian-based distributions

- Open a terminal
- Download the digital font used by the chronometer
```
wget https://github.com/andesfreedesign/Chronometer_FreeCAD/raw/main/digital-7.zip
```
- Unzip the file digital-7.zip
```
unzip digital-7.zip
```
- Copy the unzipped folder
```
sudo cp -r digital-7/ /usr/share/fonts/truetype/digital-7
```
- Update the fonts of the operating system
```
sudo fc-cache -f -v
```
- Download the macro
```
wget https://github.com/andesfreedesign/Chronometer_FreeCAD/raw/main/chronometer.FCMacro
```
- Copy the macro
```
sudo cp chronometer.FCMacro /home/your_user/.local/share/FreeCAD/Macro/
```
