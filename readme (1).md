# SlugCord
A SlugTerra themed bot for discord. Play with your friends on your server together! Use "s!" as prefix. Here is the list of commands :- 
<br><br>
### General Commands
Find all the general commands below :-
<br><br>
#### catch :
Use this command to catch slugs. Can only be used when there's a wild slug around. The bot will send a message when a wild slug appears.
#### slugs `@user` :
Use this command to get the list of slugs owned by a particular user. leave `@user` empty to get a list of your own slugs.
#### stats `slug name` :
Use this command to get info about any slug from the bot's dictionary.
##
<br><br>
### Dueling Commands
Find all the commands associated with dueling below
<br><br>
#### challenge `@user` :
Use this command to challenge any user. The challenging system work on first-come, first-served basis hence, a particular user can challenge or be challenged by one user at a time. A user must reject previously given challenge to be able to challenge someone.
#### cancelChallenge :
Use this command to cancel the challenge given to any user.
#### accept :
Use this command to accept a challenge given by any player. Cannot be used during a duel or if the user is not challenged by anyone.
#### reject :
Use this command to reject a challenge given by a player.
#### shoot : 
Use this command to shoot slugs. Slugs are put on a one minute cooldown after being shot and have a 1 in 10 chance of getting injured after losing against another slug. While injured, a slug will always lose against other slugs.
##
<br><br>
### Trading Commands
Find all the commands associated with slug trading below.
<br><br>
#### trade `slug to be given` `slug to be taken`:
Use this command to offer trade for 2 slugs.
#### cancelTrade:
Use this command to remove the offer to trade for slugs.
#### acceptTrade:
Use this command to accept a trade offer.

## GUIDE TO ADD SLUGCORD TO YOUR SERVER:
### Step 1 : Go to https://discord.com/developers/applications, click on New Application and name it as SlugCord. After creating a new application, go to OAuth2 and select scope as bot. In bot permissions, check Send Messages. Now copy the link at the bottom of Scopes and copy and paste it into your browser follow the steps as shown on the webpage
### Step 2 : Go to Bot on Discord Developer Portal and click on the Copy button.
### Step 3 : Fork this project.
### Step 4 : Go to Secrets on the sidebar and create a new secret with its key as `TOKEN` and its value as the text you copied earlier. You're all set!