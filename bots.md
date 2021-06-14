This page describes the bots that are officially recognized by the #anime ops.

# ljrbot
This is luke-jr's bot.

## Commands
* **!addquote _<ins>nick</ins>_ _<ins>quote</ins>_** : Record a funny or memorable quote the person said. Whenever the person rejoins the channel, they will be welcomed with one of these quotes. Examples: "!addquote <pyon> A fleshlight is still a 3D object, and thus inherently disgusting." or "!addquote beaky what anime has the most barefoot women"
* **!delquote _<ins>nick</ins>_ _<ins>number</ins>_** : Remove a quote from a user's list. Use this ONLY with consent from the user, or to correct a mistaken !addquote. The number refers to its position within the user's quote list. Note that removing quote 2 causes the previous quote 3 to become the new quote 2, etc. Example: "!delquote mathu 3"
* **!quote _<ins>nick</ins>_ _<ins>number?</ins>_** : Display a quote in a user's list. If a number is provided, it will show the quote in that position within the user's quote list. If no number is provided, it will instead select a random quote from the user. Examples: "!quote Nanobot 4" or "!quote davic"
* **!seen _<ins>nick</ins>_** : Displays the time and message of the last thing the user said in the channel. Example: "!seen warsh"
* **!later tell _<ins>nick</ins>_ _<ins>message</ins>_** : Leave a message for someone. The next time they are active in the channel, ljrbot will privately tell them the message you left, and how long ago it was. Example: "!later tell amigojapan I need help deciphering some moon runes!"

## Passive Services
* Welcomes users with quotes when they join.
* Delivers memos.
