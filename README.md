# Overlay Terminal
- ![#1589F0]tested only on arch linux with i3-wm
# Description
this is a simple python program that will create terminal window (kinda), that will run one command (for example you can use it to make twitch chat overlay on your screen, by running some twitch chat client in it)
the window won't react to any input, and can't be focused - because it is overlay. So the only way to kill the program is by tray icon (or cancelling it from terminal)
# Installation and Dependencies
you need to install python and PyQt5 library, then just download the overterm file, and that's all. So basically:
ArchLinux:
```bash
sudo pacman -S python
sudo pacman -S python-pyqt5
git clone https://github.com/tohyneylfd/overlay-terminal
```
# Usage
first, you need to make the program executable by doing this:
```bash
sudo chmod +x overterm
```
then you can run it:
```bash
./overterm
```
![Screenshot]()
