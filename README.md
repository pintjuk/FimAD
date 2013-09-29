# What is this
This is a little experiment to hide comments on fimfiction and only set you friends see them, with some tinkering it should work with other sites. The concept is simple it encrypts your comment, posts the cipher inside a spoiler tag, and decrypts all comments in the comment list that contain ciphers for you.

This project is quick and dirty many improvements could be made. For instance it would be better to post the secret comments to a remote server and retrieve other users secret comments from that server and then injecting them into the regular comment lists. This would make the secret comments truly invisible to regular users and website staff.


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
