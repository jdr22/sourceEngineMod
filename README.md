sourceEngineMod
===============

HL2 multiplayer / HL2DM mod

So we talked about me doing three things for my mod:
#1 Adding extreme and over powered weapons
#2 Items giving booster back
#3 Gore themed scoring

I feel I did #1 faithfully.
For #2 I implemented it using healthkits and batteries. You have a random chance to either get 
an awesome boost or a possible penalty each time you touch a healthkit or battery.
I changed the logic on the dispensers so it forces players to press their luck with the random booster items.
Instead of simply turning off dispensers, I implemented aggressive damage penalty for negative reinforcement :^)
For #3 HL2:DM doesn't have support for BOTs. So for testing purposes I could never see if it was possible to get this working.
So instead of adding the gore element from hitting players, I added the gore element to my mod through impact calls via player weapon use 
and world entities. 

I may have missed a few things but I am pretty sure I listed the majority of the changes I made in the MOTD.
I have it copy and pasted here for your convience:

<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN" "http://www.w3.org/TR/1999/REC-html401-19991224/loose.dtd">
<html>
<head>
<title>EGPDM MOTD</title>
You are playing Extreme Powerup Gore Deathmatch<br>
Visit the official EPGDM web site @ https://github.com/jdr22/sourceEngineMod.git<br>
Changelog:<br>
-Added AK-47 (for assignment)<br>
-Added extremely slow RPG speed (for assignment)<br>
-Removed startup video<br>
-Added custom Message Of The Day that you are currently reading.<br>
-Added gore hits to stunstick, extreme range, and weapon script mods<br>
-Added gore hits to pistol, extreme auto-fire rate and weapon script mods<br>
-Added gore hits to SMG, extreme fire rate, and weapon script mods<br>
-Added gore hits to physcannon and weapon script mods<br>
-Added gore hits to .357, increased percieved recoil, and weapon script mods<br>
-Added gore hits to shotgun, increased percieved recoil, increased pellets, and weapon script mods<br>
-Endless grenades, throw two on primary attack, and weapon script mods<br>
-Weapons leave behind green blood instead of bulletholes<br>
-Glass and some other objects do additional blood FX when hit<br>
-Health kits give random effect. Either 2x default health or 0.5x default health<br>
-Wall mounted health dispenser is trap, will set player health to 1<br>
-Batteries give random effect. Either 2x default armor or set player 0 armor<br>
-Wall mounted armor dispenser is trap, will set player health to 1 and armor to 0<br>
-Citadel recharge station is trap, will set player health to 1 and armor to 0<br>
</body>
</html>

INSTALLING / PLAYING THE GAME:
Yeah I accidently gave the actual game contents a crappy directory location on github, but my upload speed sucks so I don't
want to delete and reupload.
-Navigate inside the src folder. there should be a folder called INSTALL. inside there should be a folder called
Deathmatch Mod 2013. Thats the actual folder you are going to want to copy and paste into your sourcemods folder
in your steam directory.

My mod is based on Source SDK Base 2013 Multiplayer and HL2:DM which I believe you need to have both installed.
Steam should hopefully auto prompt you for any downloads you need.

The game should start up to the main menu, click create server, and I included dm_lockdown as a map for you to play.
After that you should spawn and be greeted by my MOTD. After that you can run around and test out the changes I made.

Have fun. :D
