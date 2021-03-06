<!-- markdown-toc start - Don't edit this section. Run M-x markdown-toc-refresh-toc -->
**Table of Contents**

- [Plasma UX.](#plasma-ux)
    - [Apply.](#apply)
    - [Features.](#features)
        - [Taskbar and Window Icons.](#taskbar-and-window-icons)
        - [Panel Icons.](#panel-icons)
        - [Active Screen Corners and Edge.](#active-screen-corners-and-edge)
        - [Swipe Touch Screen.](#swipe-touch-screen)
        - [Application Improved.](#application-improved)

<!-- markdown-toc end -->

# Plasma UX.

This files are [KDE Plasma](https://www.kde.org/plasma-desktop)'s improved setting.

based on Kubuntu 18.04.


* Original

![Original](resource/Original.jpg)

[Original Image from [MT Software's Youtube](https://youtu.be/oxHz1kp4JmY?t=724)]

* Plasma UX Preview

![Plasma1](resource/KDE-Desktop1.png)

![Plasma2](resource/KDE-Desktop2.png)

## Apply.

1. Download files and cd.

    `git clone https://github.com/black7375/plasma-ux.git && cd plasma-ux`

2. Copy & Paste.

    `cp -rfv config/* ~/.config && cp -rfv local/* ~/.local`

Now Apply!!

## Features.

### Taskbar and Window Icons.

New Feature.

1. Only icons taskbar.  
Space utilization is better than the original taskbar.
![Taskbar](resource/IconOnlyTaskBar.png)

2. Always on Top Button.  
You can always on top some windows.
![AlwaysToTop](resource/WindowAlwaysTop.png)

### Panel Icons.

![Feature2](resource/Feature2.png)

1. Add Virtual Desktop(Original is one) && Icons.
2. Some Application Icon.
3. Program Dashboard.
4. Show Desktop.

* Program Dashboard.
![Dashboard](resource/Dashboard.png)

* Show Desktop.
![ShowDesktop](resource/ShowDesktop.png)

### Active Screen Corners and Edge.

![ActiveScreen](resource/ActiveScreen.png)

1. Left Top: Show Virtual Desktop.
2. Right Top: Show all program windows in this Desktop.
3. Left Bottom: Command Run(like Spotlight)
4. Right Bottom: Show Desktop.

* Show Virtual Desktop.
![VirtualDesktop](resource/VirtualDesktop.png)

* Show all program windows in this Desktop.
![ShowAll](resource/ShowAll.png)

* Command Run(Plasma Search)
![CommandRun](resource/CommandRun.png)
  * Search Program, Files, Directory, Windows, Program Session, Bookmarks, Setting..etc
  * And can Run Commands, Simple Calculate.
  * Action like spotlight

* Show Desktop.
![ShowDesktop](resource/ShowDesktop.png)


### Swipe Touch Screen.

1. Left: Run Program(Start Button)
2. Right: Show Virtual Desktop.
3. Top: Show all program windows in All Desktop.
4. Bottom: Show Desktop.

### Application Improved.

![Application](resource/KDE-Desktop1.png)
* Set Theme to Breeze: Unified form to Users.
* Set Application's Function(Somthing)
* Applied Program: Dolphin(File Manager), Kate(Text Editor), Konsole(Terminal).
  * Dolphin - Show with Terminal, Preview.
  * Kate - Set Theme, Show Line number Word wrap mark(Print Margin, 80 columns), Auto Bracket..etc
  * Konsole - Set Theme(using BlaCk-Void Profile).
