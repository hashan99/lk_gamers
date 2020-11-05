HOW TO INSTALL

-> EXTRACT THE FOLDER smv_promod165a IN MODS FOLDER IN YOUR COD4 SERVER DIRECTORY
-> EDIT THE +SET fs_game "" PARAMETER AS +set fs_game "mods\smv_promod166a" IN YOUR SERVER COMMANDLINE

IT IS RECOMMENDED TO CHANGE THE MOD FOLDER NAME TO SOMETHING OTHER THAN  smv_promod166a
 

HOW TO BECOME ADMIN & USE ADMIN MENU  

-> FIRST START SERVER AND ENTER THE SERVER.
-> PRESS P , ADMIN MENU WILL OPENUP. YOU CAN VIEW YOUR GUID BY SELECTING YOUR PLAYER NAME
-> NOTE DOWN YOUR GUID
-> ADD THE LAST 8 CHARACTERS OF YOUR GUID IN  server.cfg AT SECTION "MENU PERMISSIONS & MENU ADMiNs" and also set permissions.  
-> Restart server 
-> Enter Server and Press P to open menu. If everything good, You can use the  

HOW TO SET SOUNDS FOR Killcam :

You can open z_snd.iwd with any zip tool. 
Replace the sound files inside it with your sound files and edit smvsounds.cfg . 
Refer smvsounds.cfg for more details and references

 
HOW TO ENABLE MAP PREVIEW and MAP NAMES of CUSTOM MAPS at the END VoteMAP ? 

If you are using a Custom Map on your Server, Its preview image and Name might not Shown properly on Votemap (till version smv_promod164a.2)
From smv_promod165a, there are some dummy image files which are unused and which can be used by replacing it with the custom preview image . 
Dummy image files are  image0.iwi,image1.iwi, ...image9.iwi  (located inside pml220.iwd)     

-> Open your <Custom MAPname>.iwd file at usermaps folder with zip   For example :  mp_nuketown.iwd
-> Inside images folder there will be loadscreen_<Custom MAPname>.iwi , extract it.   For example: Extract loadscreen_mp_nuketown.iwi
-> Rename it to image<number>.iwi  (number should be less than 10)  Eg: image0.iwi
-> Replace the image<number>.iwi with the dummy image inside 'images' folder of pml220.iwd of the smv promod 
-> Then Edit set vote_mapinfo at server.cfg



SERVER COMPATIBILITY

COD4 VERSION 1.7, 1.7a, 1.8 - 17.2


PLUGIN SUPPORT

We have added PLUGIN FACILITY from Version LV 1.5.4  .. You can add custom gsc plugins like in deathrun servers..(Note that deathrun plugins might not work with promod)
(If you are not a Modder and you need customized scripts, contact any modder/gsc developer)  
Developer note: Plugins will be threaded at each game start as Level

ADDITIONAL NOTES

-> SEE SERVER.CFG FILE AND CUSTOMIZE "ADDITIONAL FEATURES" SECTION AS YOUR NEED 
-> YOU CAN DISABLE ANY ADDITIONAL FEATURE IF YOU DONT LIKE IT OR IF YOU FOUND ANY BUG ON IT...
-> YOU ARE FREE TO DELETE ADDITIONAL IWD FILES SUCH AS smv.iwd, skins.iwd , IF YOU DONT LIKE OUR WEAPON SKINS OR OTHER CUSTOMIZED IMAGE FILES :P
-> ALSO YOU CAN ADD YOUR CUSTOM SOUND FILES IN z_snd.iwd FOR FINAL KILLCAM MUSIC AND GAMEEND MUSIC....
-> THERE ARE STILL BUGS AND MINOR ERRORS... :p

======================================================================================================================================
-> NO WARRANTY .. USE THIS MOD AT YOUR OWN RISK.. C-BIN or SMVHOST WILL NOT BE RESPONSIBLE FOR ANY DAMAGES OR ANY OTHER LOSES DUE TO MOD 
======================================================================================================================================



 ______________________________________________________________
|                                                              |
|  CREDITS AND THANKS TO ALL WHO SUPPORTED IN CREATING THE MOD |
|                                                              |
|______________________________________________________________|
---------------------
SPECIAL CREDITS 
---------------------
OFFICIAL PROMOD TEAM, INGRAM, BRAXI, DUFFMAN, CRAZY, |UzD|GaZa AND WHOEVER THE REAL CONTRIBUTORS OF SCRIPT MODULES & FILES.
I USED MANY IMAGE FILES & SKIN FILES FROM CFG FACTORY..THANKS TO THOSE ARTISTS & DEVELOPERS WHO MADE THEM ..


SOURCE REFERENCE SITES
-------
GITHUB
CFGFACTORY
MODDB.COM
ZEROY.COM
COD4X.ME


FOR IMPROVED CUSTOM VERSION OR PLUGINS OF THIS MOD (with more features) CONTACT US AT smvgamehosting@gmail.com






