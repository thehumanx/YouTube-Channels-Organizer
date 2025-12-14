![YT Organizer](https://github.com/user-attachments/assets/215bb2a1-5748-43a2-b2ba-3add74f17d31)



# YouTube Channels Organizer
A simple extension for Chromium and Firefox-based browsers to organize your favorite channels into the categories you prefer. 
I created this extension because I wanted to view view latest videos of my fav creators in one place without having to go to each's profile or subscribe them. 

#### Notes and features:
- It fetches the latest 5 videos of each creator and shows them.
- It uses YT RSS to fetch the videos so might be slow and not updated.
- Since YT restricted the embed video being played (especially from extension), the video now opens in the new tab instead of the same tab.
- You can edit/delete/order categories you created or remove the channels from the category. 
- You can also import and export your categories in json.


> Disclaimer: Due to YT's restriction, the video plays in a new tab instead.


## Installation guidelines

### Chromium-based browsers
1. Go to the Extension page `chrome:extensions`
2. Enable "Developer mode"
3. Click on "Load unpacked" and upload the downloaded folder

### Firefox-based browsers
> FF users can install the extension from [here](https://addons.mozilla.org/en-US/firefox/addon/youtube-channels-organizer) or if you want to install manually:
1. Type `about:config` in the address bar and press Enter. Click on "Accept Risk and continue".
2. Search for `xpinstall.signatures.required` and set it to "False" by dounle-clicking on the row
3. Open Add-ons Manager page `about:addons`
4. From gear icon, select "Install add-on from file" and select the downloaded xpi file.
