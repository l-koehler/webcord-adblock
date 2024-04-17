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
If you want a stricter filter (notably removing user activity), repeat these  
steps with the `add-strict.theme.css` (in addition to adblock, not replacing)  

#### Effects
This CSS Theme hides:
* Discords Nitro Ads  
* Emojis/Stickers you can't use without Nitro  
* The option to boost Servers  
* HypeSquad/Nitro Badges in User Profiles  
* Custom Avatar Decorations (these mildly obnoxious profile animations)  
* the "Send Gift" button  

If you additionally use the `add-strict.theme.css` file, it will also  
hide "User Activity", which is mostly advertising spotify or some game,  
and hide nitro users profile gradients*.  
*: It still shows the profile theme as light mode  
if the users profile page has a light theme.  
#### Remove
If you want to remove the theme, open `~/.config/WebCord/Themes` and delete  
the respective `*.theme` file. If you aren't on Linux,  
the .theme files will be somewhere else, idk.  
