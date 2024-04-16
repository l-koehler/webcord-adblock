#### Usage
To be used with [webcord](https://github.com/SpacingBat3/WebCord).  
Download the `adblock.theme.css` file to somewhere (you can delete it later).  
Ensure webcord is closed (not in the system tray).  
On Linux:
Run `webcord --add-css-theme` and select the file you just downloaded  
or run `webcord --add-css-theme "~/path/to/adblock.theme.css"`  
On Windows:  
Run `C:\path\to\webcord.exe --add-css-theme "C:\path\to\adblock.theme.css"`  
Start Webcord, Ads should now be gone.  

#### Effects
This CSS Theme hides:
* Discords Nitro Ads  
* Emojis/Stickers you can't use without Nitro  
* The option to boost Servers  
* HypeSquad/Nitro Badges in User Profiles  
* Custom Avatar Decorations (these mildly obnoxious profile animations)  
* the "Send Gift" button  

If you instead use the `adblock_with_useractivity.theme.css` file, it will also  
hide "User Activity", which is mostly advertising spotify or some game.  

#### Remove
If you want to remove the theme, open `~/.config/WebCord/Themes` and delete  
the respective `adblock.theme` or `adblock_with_useractivity.theme` file.  
If you aren't on Linux, the .theme files will be somewhere else, idk.  
