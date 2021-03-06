<p align="center">  
    <img alt="" src="/images/surface_preview.gif" />
</p>
<p align="center">
    <img alt="" src="https://img.shields.io/badge/platform-Windows-blue?style=flat-square" />
    <img alt="" src="https://img.shields.io/github/last-commit/OrangeJedi/Aerial?style=flat-square" />
    <img alt="" src="https://img.shields.io/github/v/release/OrangeJedi/Aerial?style=flat-square" />
    <img alt="" src="https://img.shields.io/github/downloads/OrangeJedi/Aerial/total?style=flat-square" />
</p>

# Aerial - Apple TV Screen Saver for Windows
 
Aerial is a Windows screen saver that mimics the Apple TV screen saver that displays the videos Apple shot over New York, San Francisco, Hawaii, China, etc. as well as from the ISS and various underwater locations.

Aerial is inspired by [Mac Aerial Screen Saver](https://github.com/JohnCoates/Aerial) and [Aerial for Windows](https://github.com/cDima/Aerial).

[Complete list of available videos.](https://aerial-screensavers.netlify.com)

###### Mac user? Try [JohnCoates/Aerial](https://github.com/JohnCoates/Aerial). Linux user? Try [graysky2/xscreensaver-aerial](https://github.com/graysky2/xscreensaver-aerial/).

Aerial is open source so feel free to contribute.

## Installing
>🚧 This project is still in beta. It might not always work or behave as expected. 🚧

Download the latest release from [here](https://github.com/OrangeJedi/Aerial/releases). Follow the instructions to install Aerial.

##### [Version History](https://github.com/OrangeJedi/Aerial/wiki/Version-History)

## Features
* Cycles through randomly selected Apple TV videos
* Easily select only the video you want to play
  * Select by video type (aerial, space, and underwater)
  * Save various profiles of selected videos
* Control video playback settings (speed, brightness, contrast, hue, saturation, etc.)
* Skip videos with the right arrow key
* Simple dip to black transition between each video
* Multi-Screen Support
    * Play a different video on each screen
    * Play the same video on each screen
    * Play videos on only the primary screen
* Display text
  * Static text
  * Date and time
  * Display the location/description of the video
* Change the font, size, and color of text
* Sync to the time of day (mostly - not all videos have a 'day' or 'night' attribute yet)
* Cache videos
    * Downloads videos in the background
    * Chose which video to download
* Import your own videos

## To-Do
* Full Multi-Screen Support
* Display text
  * Sunrise & sunset
  * Custom image
  * Weather
  * Calendar and events?
* More advanced video transitions
* Video preview in Window's screensaver settings
* Auto update

## Want to Contribute?

Check out our [guide to contributing](https://github.com/OrangeJedi/Aerial/wiki/Contributing-Guide). It includes information on how to set up Aerial, launch flags, and other developer information.

## About
This is a [Node.JS](https://nodejs.org)/[Electron](https://www.electronjs.org/) based implementation of [Mac Aerial Screen Saver](https://github.com/JohnCoates/Aerial) for Windows. I was using cDima's [Aerial for Windows](https://github.com/cDima/Aerial) on my computer but wished it had more of the features found in the MacOS version, as well as being less buggy and having better 4K support. Not knowing much about C# and with the project seemingly dead I researched Windows screensavers and found I could make a screen saver with Node.JS and Electron – both of which I am very familiar with. Hopefully I’ll be able build on this implementation and it get it to near where the MacOS version is.

## License
[MIT License](https://github.com/OrangeJedi/Aerial/blob/master/LICENSE)
