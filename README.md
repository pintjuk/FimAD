# What is this
This is a little experiment to hide comments on fimfiction and only let you friends see them, with some tinkering it should work with other sites. The concept is simple it encrypts your comment, posts the cipher inside a spoiler tag, and decrypts all comments in the comment list that contain ciphers for you.

This project is quick and dirty many improvements could be made. For instance it would be better to post the secret comments to a remote server and retrieve other users secret comments from that server and then injecting them into the regular comment lists. This would make the secret comments truly invisible to regular users and website staff.


## Istall
### for fast and easy install:
1. Install greasemonkey ( if you are using chrome then you have it already ) https://addons.mozilla.org/en-US/firefox/addon/greasemonkey/
2. Install the Single file version of this script from this link http://userscripts.org/scripts/source/178853.user.js
3. Profit
4. By more ponies

## What will this script alter
* Adds a "Dark" button, click this button to post a secret comment.
* Adds a "spoiler" button.
* Decrypts all comments that have been encrypted with this script.
* Remove edit buttons on all your comments, this will not be necessary in future versions.

## Where is the eddit button
This is a simple demo does and does not feature editing, attempting to edit an encrypted comment is bad. Therefore this script removes all comment edit buttons. This will be fixed soon. 

## sjcl.js 
Stanford Javascript Crypto Library is not my code, cheak it out @ https://github.com/bitwiseshiftleft/sjcl
