This page describes the bots that are officially recognized by the #anime ops.

# ImoutoBot
This is Nanobot's bot. It was entirely custom-written in PHP (and yet somehow the world hasn't ended) and has direct access to Nanobot's personal anime database, which it uses for the anime lookups.

## Commands
* **!a _<ins>anime title</ins>_** : Look up information about a particular anime, including when the next episode is expected. Example: "!a re zero"
* **!addquote _<ins>nick</ins>_ _<ins>quote</ins>_** : Record a funny or memorable quote the person said. Whenever the person rejoins the channel, they will be welcomed with one of these quotes. Examples: "!addquote <pyon> A fleshlight is still a 3D object, and thus inherently disgusting." or "!addquote beaky what anime has the most barefoot women"
* **!delquote _<ins>nick</ins>_ _<ins>number</ins>_** : Remove a quote from a user's list. Use this ONLY with consent from the user, or to correct a mistaken !addquote. The number refers to its position within the user's quote list. Note that removing quote 2 causes the previous quote 3 to become the new quote 2, etc. Example: "!delquote mathu 3"
* **!quote _<ins>nick</ins>_ _<ins>number?</ins>_** : Display a quote in a user's list. If a number is provided, it will show the quote in that position within the user's quote list. If no number is provided, it will instead select a random quote from the user. Examples: "!quote Nanobot 4" or "!quote davic"
* **!aotw _<ins>anime title</ins>_** : Set your choice for anime of the week. Every week, the channel topic is updated to the choice of the next active user alphabetically. Your choice MUST be a legitimate non-hentai anime or else you will be skipped over. Try to pick something you like that most people haven't seen. Example: "!aotw Asatte no Houkou"
* **!motw _<ins>manga title</ins>_** : Same as !aotw, but for manga of the week. Example: "!motw Unbalance School Life"
* **!seen _<ins>nick</ins>_** : Displays the time and message of the last thing the user said in the channel. Example: "!seen warsh"
* **!memo _<ins>nick</ins>_ _<ins>message</ins>_** : Leave a message for someone. The next time they are active in the channel, ImoutoBot will privately tell them the message you left, and how long ago it was. Example: "!memo amigojapan I need help deciphering some moon runes!"

## Passive Services
* Welcomes users with quotes when they join.
* Announces new episodes for currently-airing anime series.
* Delivers memos.
* Updates the topic on a weekly basis to rotate the AOTW and MOTW selections.

# Suzuka
This is davic's bot. It provides ops with tools to moderate the channel, along with other features.

## Passive Services
* Automatically quiets users who appear to be spamming/flooding.
* Automatically directs people to ##anime-jail if they are repeatedly joining/leaving #anime, as may happen with faulty Internet connections.

# Enju
This is davic's bot. 

## Commands
* **\_g _<ins>search terms</ins>_** : Search for websites using searx (which means multiple search engines). Example: "\_g light novel title generator"
* **\_c _<ins>amount</ins>_ _<ins>currency</ins>_ in _<ins>currency</ins>_** : Converts amount into another currency. Example: "\_c 10 USD in SEK"

## Passive Services
* Posts titles of URLs people link the channel.
* Emphasizes NSFW labels.
