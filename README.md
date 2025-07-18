# Kali Linux Session Startup Commands
Set of commands to avoid kali gui from crashing


1. The default icons to be there on the home screen of kali linux not there.
just blank wallpaper no icons on the top left corner.

```bash
xfdesktop --daemon
```
or 
```bash
xfdesktop &
```

2. Xfce panel (the top bar) and your window manager (which draws the title‑bar buttons) have stopped running.
```bash
xfce4-panel --restart
```
or
```bash
xfce4-panel &
```

3. Your window borders and buttons (minimize/maximize/close) are drawn by xfwm4. To reload it, in the same terminal run:
```bash
xfwm4 --replace &
```
5. thermald : CPU temperature regulation
```bash
sudo systemctl start thermald
```
6. tlp : battery-saver
```bash
sudo tlp start
```
7. xfce4 panel - taskbar disappears
```bash
xfce4-panel &
```
8. xfce desktop - wallpaper & icons
```bash
xfdesktop &
```
9. XFCE panel - for top bar to not vanish
```bash
xfce4-panel --restart
```
10. Xfce Window manger - window borders and buttons
```bash
xfwm4 --replace
```
11. for XFCE to draw desktop layer
```bash
xfdesktop --daemon
```
