# VS Code Configuration
This repository contains my current settings and configuration for Visual Studio Code.

## Settings
All the settings I have changed are present in the `settings.json` file. These include native VS Code settings as well as settings for the extensions I have installed.

## Extensions
I use several extensions to boost productivity and improve aesthetics. A list of all these extensions (with links) is present inside `Extensions.md`.

## Images
I use a VS Code extension to change the background image of the editor (the background changes every 5 minutes). All background images I use are in the `backgrounds` folder.
These images were taken from [this](https://www.addictivetips.com/windows-tips/50-minimalist-desktop-wallpapers-and-backgrounds/) website.

<br>

## Setup
The following instructions will explain to you how to apply the *exact* same settings and configurations that I use. Of course, you can make as many changes as desired.

* Install all extensions listed in `Extensions.md` either via the [Visual Studio Marketplace](https://marketplace.visualstudio.com) or by using VS Code's built-in Extensions tab 
* Clone this repo to your machine
* Open `settings.json` in VS Code and copy the content of this repo's `settings.json` into your own `settings.json` file. <br>
   Alternatively, navigate to the location of VS Code's `settings.json` file, and replace it with this repo's `settings.json` file
* (Optional) Move all images from the `background` folder to a suitable location
* In `settings.json`, navigate to the following piece of code: 
```
 "background.fullscreen": {
    "images": [
        //Images Here
    ],
    "opacity": 0.1,
    "size": "cover",
    "position": "center",
    "interval": 300,
    "random": true
  },
```
* Replace `//Images Here` with a list of the file locations of each background image, in `file` or `html` format <br>
For example,
```
  "background.fullscreen": {
    "images": [
        "file:///C:/Path/To/Background/Images/autumnForest.png",
        "file:///C:/Path/To/Background/Images/redSunset.png",
        "file:///C:/Path/To/Background/Images/shootingStars.jpg",
        "file:///C:/Path/To/Background/Images/blueIsland.jpg",
        "file:///C:/Path/To/Background/Images/bridgeMoon.jpg",
        "file:///C:/Path/To/Background/Images/greenLandscape.jpg",
        "file:///C:/Path/To/Background/Images/nightCity.jpg",
        "file:///C:/Path/To/Background/Images/orangeLake.jpg",
        "file:///C:/Path/To/Background/Images/pinkMountains.png",
        "file:///C:/Path/To/Background/Images/redderSunset.png"
    ],
    "opacity": 0.1,
    "size": "cover",
    "position": "center",
    "interval": 300,
    "random": true
  },
```
And that's it! You have successfully applied this exact configuration to your own VS Code Editor :)
