# YouTube-Thumbnails-with-FUWAMOCO
Adds "with FUWAMOCO" to YouTube thumbnails via user styles. "with FUWAMOCO" will appear below "LIVE" and video timestamps

## Prerequisites
You will need
1. A userstyles manager (e.g. [Stylus](https://github.com/openstyles/stylus))
1. Appreciation for Laplus Darknesss' thumbnail on her [public humiliation stream](https://www.youtube.com/watch?v=_1ffz3ADSNI)

## Installation
1. Install Stylus (or some other userstyles manager)
1. Add the userstyle from [Userstyles.world](https://userstyles.world/style/23517/fuwamoco-everywhere) or from [this repository](/with-fwmc-yt.css)
1. ???
1. <del>PROFIT!!!</del>BAU BAU!!!

## Screenshots
![Sample screenshot on Marine's channel](/with-fwmc-preview.jpg)

## Customization
### Size
- To change FWMC's size, play around with the ```background-size``` value to another percentage. FWMC grows with the value.
- If you want them to occupy the entire frame, use ```background-size: contain;```.
### Shorts
- If you do not want to see FWMC on shorts thumbnails, remove ```.shortsLockupViewModelHostThumbnailContainer::after``` and the preceding comma.
### Image
- If you want to replace FWMC with your own image, host your image somewhere (e.g. Catbox) and change the URL inside the ```background-image``` value.

## Credits
Inspired by [@paramedsz](https://x.com/paramedsz/status/1951152462393450518).
Borrowed with-fwmc.png from [@arashari0](https://github.com/arashari/chrome-ext-with-fwmc).
