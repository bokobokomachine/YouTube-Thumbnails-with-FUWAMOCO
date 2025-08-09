# YouTube Thumbnails with hololive
Adds some of Laplus Darknesss' masterpieces to YouTube thumbnails via userstyles. These additions will appear below "LIVE" and video timestamps.

## Prerequisites
You will need
1. A userstyles manager (e.g. [Stylus](https://github.com/openstyles/stylus))
1. Appreciation for Laplus Darknesss' thumbnails on her public humiliation streams

## Installation
1. Install Stylus (or some other userstyles manager)
1. Add the userstyle you want from the below section  or from 
1. ???
1. <del>PROFIT!!!</del>BAU BAU NYE!!!

| Name | Links | Preview | Original |
| --- | --- | --- | --- |
| with hololive | [Userstyles](https://userstyles.world/style/23626/)<br>[GitHub](/with-hololive.css) | !["with hololive" Preview](/docs/preview-with-hololive.jpg) ||
| with FUWAMOCO | [Userstyles](https://userstyles.world/style/23517)<br>[GitHub](/with-fwmc.css) | !["with FUWAMOCO" Preview](/docs/preview-with-fwmc.jpg) | [![【ご褒美】待望のネリッサお姉様オフコラボ🤓汚い言葉を言ってもらう♡ ASMR KU100 withFUWAMOCO 【ラプラス・ダークネス/ホロライブ】](https://i.ytimg.com/vi/_1ffz3ADSNI/mqdefault.jpg)](https://www.youtube.com/watch?v=_1ffz3ADSNI) |
| with Sakura Miko | [Userstyles](https://userstyles.world/style/23625)<br>[GitHub](/with-miko.css) | !["with Sakura Miko" Preview](/docs/preview-with-miko.jpg) | [![【㊗】罵倒の日にAZKiさんがASMR⁉さすがにみこさんと同時視聴な件🤓☝️【ラプラス・ダークネス/ホロライブ】](https://i.ytimg.com/vi/zSyGu0kC4dc/mqdefault.jpg)](https://www.youtube.com/watch?v=zSyGu0kC4dc) |

## Customization
### Size
- To change their size, play around with the `background-size` value to another percentage.
- If you want them to occupy the entire frame, use `background-size: contain;`.
### Shorts
- If you do not want to see them on shorts' thumbnails, remove `content: '';` under the `/* Shorts Thumbnails */` section.
- If you're using the `with hololive` userstyle and just want to remove one image, change their `background-size` value to `0`.
### Image
- If you want to replace the girls with your own image, host your image somewhere (e.g. Catbox) and change the URL inside the `background-image` value.

## Credits
Inspired by [@paramedsz](https://x.com/paramedsz/status/1951152462393450518) and [@arashari0](https://x.com/arashari0/status/1951186868621721693).
Borrowed with-fwmc.png from [@arashari0](https://github.com/arashari/chrome-ext-with-fwmc).
