# UnturnedServerConfigs
This is written in 2 languagens, English and Portuguese, for read in portuguese please jump untill you see -----PORTUGUESE------
###############################################################################################################################

I recommend see in Raw.

First, to create your server you will follow this steps: https://github.com/SmartlyDressedGames/U3-Docs/blob/master/ServerHosting.md#Server-Hosting
After that, you will have a vanilla server without any plugin or customization. To fix that you will download uEssentials: https://imperialplugins.com/Uncategorized/Products/uEssentials
After download, extract and save in Plugins folder. Servers\ServerName\Rocket\Plugins
After that, you have to configurate uEssentials according to your goals. First, we will start from permissions. The permissions are divided in 2 first and essential types: default and vip, you can change this and create the ammout of vips or groups you want. To give permissions to use a kit for example, you will use: 

<Permission Cooldown="0">essentials.kit</Permission>
<Permission Cooldown="0">kit</Permission>
<Permission Cooldown="0">essentials.kits</Permission>
<Permission Cooldown="0">kits</Permission>

These are essential and you use only once, after that, you create a kit inside the game with de command /creakit name_kit time(time in seconds).
Then you do this:

<Permission Cooldown="0">essentials.kit.name_of_the_kit</Permission>

You will do this to every single kit you create. "But man, i want to create some kits that use xp." I got you, to do that you to the uEssentials folder-kits.
You will see all kits you have created, every kit has a "cost", choose how much xp you want to the kit. Then you go to the config file, also in the uEssentials folder. 
Go to this part:
 "Economy": {
    "UseXp": true,
    "XpCurrency": "Xp",
    "UconomyCurrency": "$"
    
  As you can see, the currency is the xp, put "UseXP: true" and its done.
  
  To give tpa and home permissions this are the codes:
  
  <Permission Cooldown="0">home</Permission>
  <Permission Cooldown="0">essentials.command.home</Permission>
  <Permission Cooldown="0">essentials.command.tpa</Permission>
  <Permission Cooldown="0">essentials.command.tpa.send</Permission>
  <Permission Cooldown="0">essentials.command.tpa.accept</Permission>
  <Permission Cooldown="0">essentials.command.tpa.deny</Permission>
  <Permission Cooldown="0">essentials.command.tpa.cancel</Permission>
  <Permission Cooldown="0">tpa</Permission>
  <Permission Cooldown="0">home</Permission>
  
  Warp permissions:
  
   <Permission Cooldown="0">warp</Permission>
   <Permission Cooldown="0">warps</Permission>
   <Permission Cooldown="0">essentials.warps</Permission>
   <Permission Cooldown="0">essentials.warp</Permission>
   <Permission Cooldown="0">essentials.warp.warp_name</Permission>
   <Permission Cooldown="0">warp.warp_name</Permission>
   
   To set warp use /setwarp name time
   
   
   Text command like /rules  /vip  /discord
   
   <Permission Cooldown="0">essentials.rules</Permission>
   <Permission Cooldown="0">essentials.vip</Permission>
   <Permission Cooldown="0">essentials.discord</Permission>
   <Permission Cooldown="0">rules</Permission>
   <Permission Cooldown="0">discord</Permission>
   <Permission Cooldown="0">vip</Permission>
   
   To set map, number of player, etc, go to commands file.
   
   welcome 
   owner 
   name 
   mode 
   perspective 
   map 
   cheats 
   maxplayers
   port 
   
   Example:
   
   welcome Welcome, have fun xD
   owner (your steam id)
   name SurvivalServer
   mode normal
   perspective both
   map russia
   cheats on
   maxplayers 24
   port 2700
   
   
   To add workshop go to the file WorkshopDownloadConfig.
   
   {
  "File_IDs": [
    636256489,
    2389824620,
    2445362554,
    2447885812,
    2549159109
  ],
  
  Here in file ids you will put the ids of the workshops you want. To get the ids you go to Unturned Local files in steam, Bundles-Workshop-Content.
  You just need the id, copy the ids and put there.
  
  
  If you have any doubt or something to add, talk to me.
  
  By the way, join my server. BR SOBREVIVENCIA.
  
  
  
  
  
  
   
   
   
   
   
   
   

   
   
   
   
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  

