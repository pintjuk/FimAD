# What is this
This is a little experement to hide coments on fim fiction, and with some twiking other sites.
The consept is simple it encrypts your coment, posts the cipher inside a spoiler tag, and decrypts all coments in the coment list that contain ciphers for you.


This project is quik and dirty many improvments could be made.
Fore inctance it would be better to post the sicret coments to a remote serve and retrive sicret coments of other users form this server and injecting them into the regular coment lists. 
This would make the sicret coments fully invisible to regular users and website staff. 

## Istall
If you are using muzzila then you should install greasmonky if you havn't don so already.
click on the monky and click ad new script and paste the FimAD.user.js script into the into the greasmonkie script edditor.
The last thing to do is to find your greasmonkie folder in thet you will find the folder for userscript you created, past sjcl.js into that folder.

## What will this script alter
* ads a "Dark" button, click this button to post a sikret comment
* ads a "spoiler" button, dont know why, remove the script that does it if you dont like it
* dicrypts all coments that have been encrypted with this script
* romevs eddit buttons on all your comments, this will not be nesasary in future versions. 

## Where is the eddit button
this simple demo does not fiture edditing, attempting to eddit an encrypted comment is bad. therefore this script removes all comment eddit buttons.

## sjcl.js 
Stanford Javascript Crypto Library is not my code, cheak it out @ https://github.com/bitwiseshiftleft/sjcl
