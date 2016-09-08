# Yandere Rules

**Yandere** is an IRC group game similar to Mafia or Werewolf. It is part strategy, part deception, and part luck.
Games take place in [#yandere on freenode](irc://chat.freenode.net/yandere).

## Overview
Each player gets assigned a role. The roles are randomly chosen but certain roles are weighted more heavily so they are chosen more often. Each role has a place in the game, whether it's of innocent bystander, killer, spy, or other power. Each role also can have good, evil, or neutral alignment. See **YandereRoles** for a comprehensive list. Some roles can even upgrade other roles, so the game can "evolve" as it goes. There will always be at least one "yandere" that the game revolves around.

The object of the game is for one side to outwit the other by attempting to reveal who the yandere players are. Then each morning, the group votes who they think the evil yandere is. The game ends when all remaining players left alive are good or evil.

## Time
The game runs in two phases, DAY and NIGHT.

Each DAY all players vote who they think is a yandere. Special things can also happen during the day, some roles have powers that can only be exercised during the DAY. The player with the most yandere votes against them each DAY will be lynched, and then it will be revealed if they were a yandere or not.

Each NIGHT, the yandere vote which player they want to kill. Other night roles also take place, including spying and alignment checking.

Some games START AT NIGHT which makes the pace of the game faster.

## Roles
During the start of the game, **ljrbot** will send you a message explaining your secret role.
The bot will also explain any special commands that you can send in PM to the bot.
The bot will also tell you when the special commands can be used. Some roles don't have special commands.

You should read and understand EACH ROLE then carefully consider the consequences of each and how they interact. That is the best place to start to becoming a more powerful player. Don't forget that some roles can fake their alignment!

When you are 100% sure that a player is not the yandere you can VOUCH them. This signifies that you ensure they are not the yandere. Once someone is vouched (by another player, or by revealing) they may request CLAIMs from the remaining players. Each player should then send the vouched player their role in a private message (Hint: Yandere should lie), which the vouched player may then use to strategically plan out a course of action to find the yandere.

## Etiquette
* WHEN YOU ARE DEAD, YOU ARE NO LONGER PERMITTED TO GIVE INFORMATION. Doing so compromises the game at play.
* USE /NOTICE instead of /MSG for communications. This way it will all appear in the server window. Instead of creating dozens of windows in the recipient's irc client.
* Pasting private messages, including those from the game bot, is strictly forbidden. Fabricating messages that look like pastes, whether true or false, is also prohibited.
* No hurrying the join phase.
* Please don't spam the nick command.
* Do not force anyone who didn't explicitly state that they should be forced.
** If anyone is afk, ]yh instead of forcing them to abstain.

## Commands
When speaking to the bot in the channel you can use ]y instead of ]yandere to indicate a yandere command.

These are the commands recognized in the channel:
* ]yandere join (Joins the current game if it is still in pre-game)
* ]yandere extend (Makes the bot wait an additional 60 seconds for more players to join)
* ]yandere hurry (Forces the group to make a decision within 1 minute if a majority of players vote to hurry)
* ]yandere Little_Death (During the day, accuse Little_Death of being a Yandere. If Little_Death gets a majority vote, she is lynched.)
* ]yandere abstain (During the day, you say you do not want to vote for the Yandere. At night it says that you refuse to use your night power.)
* ]yandere force user command (An idle user can be forced to execute a command by ops)
* ]yandere end (Forces the game to end if it was compromised)

Each command also has a short form, given as ]y+first letter of the command. (e.g. ]ye will do the same thing as ]yandere extend )

# Private commands
Commands that are related to your role should only be sent privately to the bot.
Private commands start with '/msg ljrbot yandere'.
