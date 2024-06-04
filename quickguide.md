# Quick guide

- Install Steam Tinker Launch using "ProtonUp-Qt"
- Install VC++ runtime by adding to steam as game and running using proton
- Find prefix created by proton and add your duckstation, client and game somewhere in this location eg. documents
- Add duckstation's executable to steam as a game/change the target for the VC++ runtime to the duckstation executable
- Setup duckstation, including your bios and the required settings as defined via OnlineCTR instructions
- Additionally in duckstation, make sure you configure your controller settings and check the steam deck APU as the graphics adaptor
- Change the compatibility option from proton to Steam Tinker Launch
- Run the game in steam and select main menu on the Steam Tinker Launch menu
- Select the following options:
    - select "use custom command" - then in custom command, add client.exe
    - select "fork custom command"
    - select "force Proton with custom command"
    - (optional) in "Game command arguments" add arguments for launching duckstation. Would recommend at least using 
  "-bigpicture" or "-boot </path/to/onlinectr>"
- Save your settings and test it in desktop mode. Duckstation and the client should both run when you press play.
- If all is working try it in game mode!
    - Note: You may need to enable dev mode in the steam settings so that you can switch windows in game mode. You'll need 
  this so you can switch between duckstation and the client, mainly needed so you can type your name in
    - To update, you will simply need to replace the client and patched version of your game in the location you have 
  placed them in