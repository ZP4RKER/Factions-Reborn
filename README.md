# Factions Reborn

Factions Reborn, formerly known as zNexusFactions, is a variation of Factions, the idea was suggested on the Bukkit 
forums by @LeCastlecrafter.

## How it works

Basically, it has almost all the features of the original Factions plugin and also with a twist! Factions can not 
only be raided but they can be destroyed, not just the base but the whole Faction! Faction bases are also quite 
different, there is no claiming rather the size of the base depends on Faction experience points and player counts. A
base also consists of a vault with a nexus located in the middle of it.

#### The Vault

The vault is a 5x5x3 enclosed area which has the Nexus in the middle of it, the vault is the most secure location in 
a faction base especially when the offline-defence is active. By default the vault is located in the middle of the 
base when a new faction is created, however a vault can be moved around.

#### The Nexus

The Nexus is the heart of a faction, if destroyed the faction will be destroyed as well with the exception of the 
grace period. The Nexus is what stores the faction experience points and also the only place you can use the points. 
Upgrades such as harder blocks (takes longer to mine), bigger base and more features in the future.

#### The Grace Period

The grace period is in place to give defending factions a better chance at keeping their faction alive. This period 
is only initiated when the faction owner is not online. Essentially it gives the faction owner a period of time to 
login and save the faction from being destroyed after the Nexus has been destroyed. Although the owner will be able 
to save the faction, he/she will not be able to save the base and everything inside it, the only thing that will 
remain are the upgrades and experience points.


## Commands

**/fr create {NAME} {TAG}** Creates a faction with the name: {NAME} and the tag: {TAG} <br>
**/fr join {NAME}** Joins the faction {NAME} <br>
**/fr leave** Leaves your faction <br>
**/fr disband** Disbands & Destroys the faction <br>
**/fr invite {PLAYER}** Invites {PLAYER} to your faction (Faction ADMIN/OWNER only) <br>
**/fr accept {NAME}** Accepts invite from faction {NAME} <br>
**/fr open** Toggles whether the faction is public or not <br>
**/fr info {NAME}** Displays information about a faction <br>
**/fr list** Displays a list of all factions <br>
 <br>
**/fr promote {PLAYER}** Promotes {PLAYER} in the faction (Faction OWNER only) <br>
**/fr demote {PLAYER}** Demotes {PLAYER} in the faction (Faction OWNER only) <br>
**/fr kick {PLAYER}** Kicks {PLAYER} from the faction (Faction ADMIN/OWNER only) <br>
**/fr chat** Toggles faction chat <br>
**/fr broadcast {MESSAGE}** Send message to all faction members even if faction chat is off <br>
**/fr near** Displays nearby faction bases, tells you how many blocks away and if they are online or offline <br>
 <br>
**/fr destroy {NAME}** Destroys and Disbands a faction (Server Staff only) <br>
**/fr reload** Reloads the plugin (Server Staff only)

## Updates