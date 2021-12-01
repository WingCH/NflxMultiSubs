<p align="center"><a href="README.md">English</a>, <a href="README_cn.md">中文</a></p>

<img src="docs/icon.png?raw=true" height="48"> NflxMultiSubs
============================================================
![Chrome users](https://img.shields.io/chrome-web-store/users/jepfhfjlkgobooomdgpcjikalfpcldmm?label=Chrome%20users)
![Firefox users](https://img.shields.io/amo/users/nflxmultisubs-2021?label=Firefox%20users)
[![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://www.paypal.com/donate?business=5GY9A82PFY38W&no_recurring=1&currency_code=EUR)

The best ever Chrome/Firefox extension to unleash bilingual subtitles on Netflix! 

This repository is updated for 2021 with a fix for the Netflix redesign and other bug fixes and improvements.

[<img src="https://user-images.githubusercontent.com/13658335/138092194-303708fb-9a4e-4e3f-a1dc-74baff1e45c9.png" height="59"/>](https://chrome.google.com/webstore/detail/jepfhfjlkgobooomdgpcjikalfpcldmm)
[<img src="https://user-images.githubusercontent.com/13658335/138086366-8deee659-16c3-4621-b3f0-eaf4cb6ed9ba.png" height="60"/>](https://addons.mozilla.org/firefox/addon/nflxmultisubs-2021)
[<img src="https://developer.apple.com/app-store/marketing/guidelines/images/badge-download-on-the-mac-app-store.svg" height="60"/>](https://apps.apple.com/app/nflxmultisubs/id1594059167)

#### We are now on the Chrome and Firefox stores under the name NflxMultiSubs 2021 🥳🥳🥳 <br /> An Apple Mac version for Safari with basic functionality is also available. Click on the badge to install.

**If you installed the extension from the zip before, please remove it and reinstall from the store.**

Features
--------
- Enable secondary subtitles in all languages (incl. image-based subtitles like Japanese, Chinese, Russian, …)
- Smart selection on secondary subtitles. Choose between 3 subtitle activation modes: disabled; automatically match subtitle language to audio language; or remember the last selected language.
- Seamless integration with native Netflix player UI -- switch languages in place
- Adjust playback speed (pressing key `[` and `]`)
- Open source!!

Installation
-----
Chrome: https://chrome.google.com/webstore/detail/jepfhfjlkgobooomdgpcjikalfpcldmm </br>
Firefox: https://addons.mozilla.org/firefox/addon/nflxmultisubs-2021 </br>

Safari Mac port maintained by [WingCH](https://github.com/WingCH) (without customisable settings for now): </br> https://apps.apple.com/app/nflxmultisubs/id1594059167

See it in Action
----------------
![Bilingual Subtitles with zh-cn/en](docs/2021_zh-en.jpg?raw=true)
![Intergrated in original menu](docs/2021_popup-menu.jpg?raw=true)
![Settings menu](docs/2021_settings.jpg?raw=true)

Build
-----
Requires Node.js. Build directories are `build/chrome` and `build/firefox`.
```
git clone https://github.com/gmertes/NflxMultiSubs.git
cd NflxMultiSubs
npm install
npm run build
```

Known Issues
-------------------------
- Wait for the Netflix home page to finish loading completely before starting a show/movie.
- Refresh the page if the secondary sub list is empty.
- This extension could conflict with other Netflix-related extensions (but not [NflxIntroSkip](https://github.com/gmertes/NflxIntroSkip)! :D). If you encounter any problem, try to disable some of them
- RTL (right-to-left) text-based subtitles are not ready yet
- This extension and the developers are not affiliated with Netflix, Inc; All rights belong to their owners


Problems?
---------
### The secondary subtitles list is empty or subs aren't showing up
- Subs will show up after a Refresh (F5).

### Large gap between main subtitle and secondary subtitle
- This happens only when the controls bar is active -- just wait until the controls hide

### Only available in Chrome/Firefox for desktop?
- Yup -- mobile devices, smart TVs, Apple TV, Chromecast, … are not supported

### Could I load subtitles from other country?
- This extension respects Netflix rules, hence we only support all official subtitles available in your country

### Feature request: __________ ?
- This extension does one thing and does it well -- great experience with bilingual subtitles support
- If you have a request you can open an issue for consideration (please put [Feature Request] in the title)

Donate
----
The extension is and will remain free. If you like and want to support my work, donations are welcome.

[![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://www.paypal.com/donate?business=5GY9A82PFY38W&no_recurring=1&currency_code=EUR)

BTC: `bc1qx8duq3526zhc2md724ym70qgd4wgadj5dqfuvr`

ETH: `0x02635a2ef80887B0AEBa5a8282AeFAEA401DFCf9`

XLM: `GB5Y7TVH7OBI7MFAT26RZ4TCZRDMVNWXLQH3LPTI2RRB22PRHSDR25BH`

License
--------
MIT. Original by [Dan Chen](https://github.com/dannvix), forked and maintained by [Gert Mertes](https://github.com/gmertes).
