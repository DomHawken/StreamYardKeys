# StreamYardKeys
Automate switching camera angles and video/audio mute on the Streamyard video streaming service

Based on this [original script](https://gist.github.com/rothgar/92e69d5bdcf80ea23f065bb6db03f7cd) by [rothgar](https://github.com/rothgar).

- Use [Chrome](https://www.google.co.uk/chrome/).
- Install the [TamperMonkey](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo) Chrome extension.
- Open the [StreamYard](https://streamyard.com/) website, log into your StreamYard account and open a new broadcast. There is no need to go live.
- Select TamperMonkey from the extension menu top right on Chrome.  
  
![TemperMonkey Menu](assets/screenshot_01.png)
  
- Select 'Create New Script' from the TamperMonkey menu.  
  
![TamperMonkey New Script Menu](assets/screenshot_02.png)
   
- replace the template script by pasting in the TamperMonkey script from this repository.
- Save the TamperMonkey cript (File->Save).
- Reload the StreamYard page and enter the studio
  
The script implements the following keys:

- SHIFT CTRL COMMAND Q - switches the microphone mute on and off
- SHIFT CTRL COMMAND W - switches the camera on and off
- SHIFT CTRL COMMAND E - switches to the comments
- SHIFT CTRL COMMAND R - switches to the banners
- SHIFT CTRL COMMAND T - switches to the brand
- SHIFT CTRL COMMAND Y - switches to the private chat

Should be self explanatory in the code how to change the keys and modifiers.