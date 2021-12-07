- 👋 Hi, I’m @ItsYoutubeHomey330sweet
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
ItsYoutubeHomey330sweet/ItsYoutubeHomey330sweet is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
Blink basically freezes your player for other people. You can do damage and build but others can not see. You will get kicked if you are in blink for longer than 10-15 seconds!
 
// ==UserScript==
// @name         1v1.LOL Blink Script (Release)
// @version      1.0
// @description  Press the blink key to enter/exit blink mode. You will appear like you teleported when you come out of blink. You will get kicked after about 10-15 seconds!
// @author       TDStuart
// @match        https://1v1.lol/
// @grant        none
// @require      https://pastebin.com/raw/PPBXMS89
// ==/UserScript==
 
(function() {
    'use strict';
 
    // Change this key to change the keybind (This is a javascript key code!)
    let toggleKey = "KeyT";
    // If true you will have god mode while in blink (Note : God Mode is VERRY Buggy and you may still die)
    let godInBlink = true;
    // Debug Mode (Check Console)
    let debugMode = false;
    //
    //
    // Code Below!
    initMod({toggleKey, godInBlink, debugMode});
})();
 Blink basically freezes your player for other people. You can do damage and build but others can not see. You will get kicked if you are in blink for longer than 10-15 seconds!

// ==UserScript==
// @name         1v1.LOL Blink Script (Release)
// @version      1.0
// @description  Press the blink key to enter/exit blink mode. You will appear like you teleported when you come out of blink. You will get kicked after about 10-15 seconds!
// @author       TDStuart
// @match        https://1v1.lol/
// @grant        none
// @require      https://pastebin.com/raw/PPBXMS89
// ==/UserScript==

(function() {
    'use strict';

    // Change this key to change the keybind (This is a javascript key code!)
    let toggleKey = "KeyT";
    // If true you will have god mode while in blink (Note : God Mode is VERRY Buggy and you may still die)
    let godInBlink = true;
    // Debug Mode (Check Console)
    let debugMode = false;
    //
    //
    // Code Below!
    initMod({toggleKey, godInBlink, debugMode});
})();
